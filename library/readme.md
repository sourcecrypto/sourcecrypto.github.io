Final outcome for this library is to create a dynamic web directory for every type of crypto knowledge.

This won't have anything to do with ICOs (except for how to evaluate them) or brand new things that aren't developed.

**This plan will genereally progress in the following stages:**
1. Fill Discord Library with curated crypto resources (very good progress already)
2. Place crypt0library server history in machine readable format<br/>
     —`[html](https://github.com/infominer33/Crypto-library/tree/master/library/html)` folder is for special projects outside the scope of this readme<br/>
     —`toml` folder (coming soon) for finished toml files
3. Work on automating database population <br/>
     —One part of this is the discord bot<br/>
     —Another part is the database workings that the discord bot talks to
4. A dynamic front end where each item can have multiple tags and you can filter content with the tagging system

-----

**1. Discord Library**  [http://crypt0library.net]
This involves curating crypto knowledge and placing source material in the appropriate channels of the crypt0library.net discord server. Source material means that it is a primary source of information, or is filled with references from a bunch of primary sources. Sometimes just super good content... basically it's all content that is the best place to learn about a particular subject (that we've found so far) or something I referenced in an article sometime and could be useful again in the future for anyone trying to learn in depth on a given topic.

Personally, I re-tweet a dozen or so informational links every day, and then go through them all on a weekly basis; continually adding to the server.  I follow a curated collection of crypto enthusiasts, lawyers, cryptographers, academics, developers, thought leaders, influencers, etc. Also, I'm creating content, and doing freelance research... I find a lot of valuable information... and am trying to collect for display with top notch UX

What would be helpful here is to find the channels that don't have a ton of information already and look for amazing resources on those subjects to fill out the under-represented areas of the library.

**2. Place crypt0library server history in machine readable format**
I used this discord server history scraper https://dht.chylex.com/ to create '[crypt0library_history.txt](https://github.com/infominer33/crypto-library/blob/master/library/crypt0library_history.txt)' which can be viewed in https://dht.chylex.com/build/viewer.html

It's much easier to transfer the information from discord to github using this method. To begin with we are doing minimal formatting, removing extraneous data, and begin creating files in this directory with the links in them. This is the grunt work part, and then these will all be cleaned and made machine readable to turn into a database later. 

We'll use toml format for the library entries:
https://github.com/toml-lang/toml#user-content-example

Example:

[Title] <br/>
Link = "Blah.com"<br/>
Author = "blah"<br/>
Source = "blah blah"<br/>
Description = "Blah blah \n blah blah"<br/>
Tags = ["Blah", "Blah-blah"]<br/>

The entry name can be short and to the point subject related and a nubmer if many entries are for similar content.
Description can be whatever text is valuable to communicate, and sometimes requires creativity. You can leave out title or author labels if they don't apply to a particular resource.

Here is an example of a "Crypto Library—Super Source" toml file, currently in progress:

https://github.com/infominer33/Crypto-library/blob/master/library/general_knowledge/101.toml

These files will have the same name as the discord channel `channel_name.toml

The short list of directories that I personally would prioritize for this (but if you're volunteering, by all means, go ahead and work on whatever you like):

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


There is some progress going for 3 and 4, but those aren't my specialties. Let me know if you'd like to get involved on that end of things and I'll connect you with some other folk.

—ThankYou
