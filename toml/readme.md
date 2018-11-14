# TOML formatting
### The Problem and our Process

The problem is that developers don't have much to build until there is a database. In order to create the database to power a dynamic web-portal, we are using the TOML format to organize the information and describe it and tag it. TOML is a simple format that we are using to prepare our information to be transformed into a mongo database. By labeling each link with a Title, Description, and Tags we will have made it easy   to be used for a web directory. Of course all of that takes a lot of work. Its easy, relaxing, and a wonderful educational opportunity, but time consuming.

We used a discord server history scraper https://dht.chylex.com/ to create '[crypt0library_history.txt](https://raw.githubusercontent.com/infominer33/Crypto-library/master/toml/crypt0library_history.txt)' which can be viewed with https://dht.chylex.com/build/viewer.html

The first step is to use that viewer app to copy\paste channel histories for channels that have not had files made for them yet. The best thing would be if someone could make files for all of the channels not done yet, so we could remove one more step from our process. It's fine to copy paste each channel into an individual file with the same filename as channel name.

[note: this is an ugly step, I don't want to look at it anymore. as soon as I get to a good stopping point with the identity toml I'm going to move all of that stuff over here.]

Those files can be added to https://github.com/infominer33/crypto-library/

The next step is transforming each file of resources into toml format.  (https://github.com/toml-lang/toml)
  
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


### Our current plan for completing population of toml files is broken down as follows:

\* note: if you're volunteering to help I will be happy even if you follow your own system for completing the work. This is the best system that I could to come up with.

1. First get the history of every channel into individual files here in this repository.
   - simply copy\paste 
2. Clean up each of those files and begin creating the toml format like above, except only with the link field filled out, leaving the rest blank, but ready to be filled out (for the whole server).
   - a script could probably assist in this matter, but that's not my specialty
4. then filling out the description and tags and title for each, manually.
5. While the database is being prepared, developers are working on the web-application and a discord bot but there isn't much for them to work on without a sufficiently populated database.

The work was ordered in those steps both to get the easiest most time consuming tasks out of the way first, and to give librarians more time to come up with a proceedure and organizaed thought around how they should be tagged. If you want to help by automating any part of that process would, it would be appreciated.

* BTC 1GvkjHtiy9LUjVkStnEAXxjhcoS56aCokY



**Thanks for all the help!!!**

I will happily compensate anyone who makes significant contributions. —@infominer

---
## TOML'd Channels:
#101 #satoshi #history #cypherpunks #distributed-systems #consensus #pow #pos #decentralization #smart-contracts #decentralized-id #id-dev
