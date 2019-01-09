# The Crypto Library — Super Source
Creating a collaborative web-directory of "source-grade" content, searchable and manually navigable — perhaps with chat bot search engines, to make it portable. For writers, students, and research nerds to easily find information on the topics we're studying at any given moment. 

Originally organized in the channels of a discord server, this is a landing pad in the process of making a machine readable repository of information on every subject in crypto.

<center><img src="http://i.imgur.com/HxFqaQg.png" /></center>

## [crypt0library.net](http://crypt0library.net)

In order to create the database to power our dynamic web-portal, I'm using the TOML format to organize the information and describe it and tag it. TOML is a simple format that we are using to prepare our information to be transformed into a mongo database. By labeling each link with a Title, Description, and Tags we will have made it easy   to be used for a web directory. Of course all of that takes a lot of work. Its easy, relaxing, and a wonderful educational opportunity, but time consuming.

I'm using a discord server history scraper https://dht.chylex.com/ to create '[crypt0library_history.txt](https://raw.githubusercontent.com/infominer33/Crypto-library/master/toml/crypt0library_history.txt)' which can be viewed with https://dht.chylex.com/build/viewer.html

I've moved the most important information over already, but there's still a bit to go through, yet. A little confusing, because I don't always notice if the scraper has gotten each channel completely until I'm copying the info over.

The next step is more straightforward: transforming each file of links into toml format.  (https://github.com/toml-lang/toml). basically every file without the ".toml" needs transformation.
  
### The Format

```
["The **Title** of the entry and must always be different from previous entries"] 
Link = ["https://Blah.com"]
Description = "Description can be whatever text is valuable to communicate.\nTypically copied directly from the source; sometimes requiring creativity. "
Tags = ["blah", "blah-blah"]
```

>* **For any label that can potentially have multiple values it must always be ["bracketed"] even though sometimes there is only one value.**
>* **I made "Link" a bracketed ["array"] so that sometimes a supporting link can be included. occasionally this will be helpful.**
>* **Also, all entries have to have the same fields and format**
>* **If you use \n for a newline, you can't actually use a newline, the open " and closing " must be on the same line**
>* **Be careful of quotation marks in text copied descriptions. Change to ' or use an escape character \\" in front of the quotation mark**
>* **TOML is Case Sensitive. All the tags should be lower case. All the value names must always begin with a capital and be identical**

<img src="http://i.imgur.com/1nmrAAu.png"/></br>
The result of this process, once it's landed on github ^^^

### Tagging

Tagging is a complex topic. We need enough unique tags to make this directory ideally navigable, and to use a consistent schema for tagging over the course of this project. 

Using a consistent tagging schema will be nearly impossible in the long run. We are just doing the best that we can. Once this project is living in a web app it will become a more streamlined collaborative process: so that tags can be suggested and also flagged as unhelpful.

See "[tag-definitions.md](https://github.com/infominer33/Crypto-library/blob/master/toml/tag-definitions.md)" for more information. Feel free to join in on the fun :)


### Brought to you by: [The Crypto Library—Super Source](https://github.com/infominer33/Crypto-library)

BTC— 1GvkjHtiy9LUjVkStnEAXxjhcoS56aCokY

![](http://imgur.com/yXLLm9Bl.png) 

DOGE— DSzMxfABB8EwKiumzV7YHhS7HTvWAyM7QF

![](https://i.imgur.com/0zBLoUP.png) [<img src="https://i.imgur.com/zeYCNMS.jpg" align="right" width="150" height="140">](https://github.com/infominer33/Crypto-library)
