# TOML formatting of crypto knowlege

I used this discord server history scraper https://dht.chylex.com/ to create '[crypt0library_history.txt](https://github.com/infominer33/crypto-library/blob/master/crypt0library_history.txt)' which can be viewed in https://dht.chylex.com/build/viewer.html

1. It's much easier to use the dht.chylex.com tool and copy paste channel history from the server into files here on the github than to copy paste directly from the discord channels. 

2. The next step is transforming each file of resources into toml format.  (https://github.com/toml-lang/toml)
  — I'm now using vscode to make the toml files, since it has a nice toml extension that helps make sure that you're formatting correctly

Example:

["The **Title** of the entry and must always be different from previous entries"] <br/>
Link = ["https://Blah.com"]<br/> 
Description = "Description can be whatever text is valuable to communicate.\nTypically copied directly from the source, and sometimes requires creativity. "<br/>
Tags = ["blah", "blah-blah"]<br/>

>* **For any label that can potentially have multiple values it must always be ["bracketed"] even though sometimes there is only one value.**
>* **I made "Link" a bracketed ["array"] so that sometimes a supporting link can be included. occasionally this will be helpful.**
>* **Also, all entries have to have the same fields and format**
>* **If you use \n for a newline, you can't actually use a newline, the open " and closing " must be on the same line**
>* **Be careful any text copied from another site for a description doesn't have a " quotation mark. Change to ' or use an escape character \" in front of the quotation mark**
>* **TOML is Case Sensitive. All the tags should be lower case. All the value names must always begin with a capital and be identical**


These files will have the same name as the discord channel `channel_name.toml

### I'd like to see this project progress in the following stages:

* note: if you're volunteering to help I won't try to micromanage you. progress is wonderful :)

1. It would be awesome to start by get the entire server history into individual files for each channel.
  - this could be a simple copy\paste affair
2. Clean up those files and begin creating the toml format like above, except only with the link and the rest blank, but ready to be filled out (for the whole server)
3. then filling out the rest of the informations

I put it in those steps because step 1 and 2 are the easiest, and if someone was willing to help they could do a great service by creating all of those files without dedicating a ridiculous amount of time on it.

Actually filling out the toml entries is tricky, and tagging is somewhat discressionary. I suppose I shall come up with more detailed instructions on tagging, eventually.  

**Thanks for all the help!!!**