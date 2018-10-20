Final outcome for this library is to create a dynamic web directory for every type of crypto knowledge.

This won't have anything to do with ICOs (except for how to evaluate them) or brand new things that aren't developed.

**This plan should progress generally in the following stages:**
1. Discord Library
2. Github Barebones Webpages designed to be easily machine readable for future transformation to a database
     —I'm considering #2 to be like the MVP (minimumm viable product)
     —html folder is for special projects outside the scope of this readme
3. Work on automating database population 
     —One part of this is the discord bot
     —Another part is the database workings that the discord bot talks to
4. A dynamic front end where each item can have multiple tags and you can filter content with the tagging system

-----

**1. Discord Library**  [http://crypt0library.net]
This involves curating crypto knowledge and placing links in the appropriate channels of the crypt0library.net discord server. 

Personally, I re-tweet a dozen or so informational links every day, and then go through them all on a weekly basis; continually adding to the server.  I follow a curated collection of crypto enthusiasts, lawyers, cryptographers, academics, developers, thought leaders, influencers, etc.

What would be helpful here is to find the channels that don't have a ton of information already and look for amazing resources on those subjects to fill out the under-represented areas of the library.

**2. Github Barebones Webpage**
I used this discord server history scraper https://dht.chylex.com/ to create '[crypt0library_history.txt](https://github.com/infominer33/crypto-library/blob/master/library/crypt0library_history.txt)' which can be viewed in https://dht.chylex.com/build/viewer.html

It's much easier to transfer the information from discord to github using this method. To begin with we are doing minimal formatting, removing extraneous data, and begin creating files in this directory with the links in them. This is the grunt work part, and then these will all be cleaned and made machine readable to turn into a database later. 

We'll use toml format for the library entries:
https://github.com/toml-lang/toml#user-content-example

Example:

[Entry] Entry names can be numbered starting with [0001] (unless you have a better idea)
Link = "Blah.com"
Description = "Blah blah"
Tags = ["Blah", "Blah blah"]

These files will have the same name as the discord channel `channel_name.toml

The short list of directories that I would prioritize for this:

#evaluation 
#economics 
#governance 
#decentralization 
#smart-contracts 
#privacy 
#trading 
#regulation 
#pow 
#pos 
#consensus-etc 
#security 
#cryptography 
#research-papers 
#blockchain-developing 
#bitcoin-dev 
#ethereum-dev 
#hyperledger-dev

---

This are a bit far ahead for my thoughts right now, but I'm open to suggestions \ help on these matters for sure.

3. Work on automating database population <br/>
     —One part of this is a discord bot that knows the whole directory and can help with tagging and searching and all of the things.</br>
     —Another part is the database workings that the discord bot talks to
4. A dynamic front end where each item can have multiple tags and you can filter content with the tagging system


