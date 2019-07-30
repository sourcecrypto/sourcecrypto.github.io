---
layout: single
title: Tag Definitions - a draft
permalink: /posts/tag-definitions/
redirect_from:
  - blog/tag-definitions/
share: true
header: 
  image: "/images/author-centric-ranking-web.png"
  teaser: "/images/author-centric-ranking-web.png"
  caption: "[Enabling Author-Centric Ranking of Web Content](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.397.8960&rep=rep1&type=pdf)"
toc: false
classes: wide
last_modified_at: 2019-06-20T11:22:33-23:00
excerpt: "what's really missing is tagging all of these resources by authors, co-authors, references/citations once this is done, topical tags can be derived algorithmically- @MaciekLaskus"
categories: [SourceCrypto]
tags: [metadata, web-work, development, tags]

---


@MaciekLaskus suggests:
>this is very interesting, but I think you're making a fundamental mistake with tagging this by topics
>
>what's really missing is tagging all of these resources by authors, co-authors, references/citations once this is done, topical tags can be derived algorithmically
* [Enabling Author-Centric Ranking of Web Content](http://citeseerx.ist.psu.edu/viewdoc/download?doi=10.1.1.397.8960&rep=rep1&type=pdf)

The limitations of this theme have helped with my efforts for categorization. I can't publish more than 10 different types of collections, that also includes blog-posts.

Posts and Collections alike can be tagged and given categories within this Jekyll Theme, Minimal Mistakes. That's plenty to account for the variety, and futher tagging.

I've updated the categories on the discord server, so they should be arranged the same as this web-site.

* [Discord Index](https://SourceCrypto.pub/archive/)
  * [General](https://SourceCrypto.pub/archive/general/)
  * [Resources](https://SourceCrypto.pub/archive/resources/)
  * [Crypto](https://SourceCrypto.pub/archive/crypto/)
  * [Tech](https://SourceCrypto.pub/archive/tech/)
  * [Blockchain Tech](https://SourceCrypto.pub/archive/blockchain-tech/)
  * [Development](https://SourceCrypto.pub/archive/development/)
  * [Enterprise](https://SourceCrypto.pub/archive/enterprise/)
  * [Application](https://SourceCrypto.pub/archive/application/)
  * [Web-work](https://sourcecrypto.pub/archive/web-work/)

I'll be using a similar category structure for [DIDecentral](https://decentralized-id.com). You see, I can make as many posts\channels in each category as I like.

So it will be good to distill any topic to 9 categories or less, for publishing and organizing resources on Discord.

## Depreciated

It has become apparent that we need a key for tagging standards. ultimately each tag will have additional tags related to it for search purposes, but this document to define "top-level" tags (or tags that are visible to and navigable by the user) is in progress. 

All source items will be as inclusively tagged as possible. As many tags as applicable will be used for each item. For example, everything related to bitcoin will have the 'bitcoin' tag, while some will have additional bitcoin related tags, depending upon the content.

Tagging "Rules":
* Each company, organization, and project gets its own tag.
* More prominent projects get multiple tags to make their abundant resources easier to navigate.
Generally speaking tags should be used liberally, so that 'bitcoin', for example, will be used as a tag for anything related to bitcoin, and additional tags are used to define further.
* All tags are lower case

### General

The idea is to make a few top level tags that every SuperSource item must have.  

1.
* 'organization' 
* 'business'
* 'academic'
* 'state'  For state\federal govt based projects
* 'enterprise' For private and\or permissioned chains
2.
* 'platform'
* 'protocol' (for the main webpage, and\or github)
* 'app'
3.
* 'research-paper'
* 'documentation'
* 'blog'
* 'resources'
* 'presentation'
* 'podcast'
* 'video'
* 'image'
* 'whitepaper'
* 'press-release'

need some better way to organize these 'supertags' and probably have left out some important ones.

Any core blockchain or dlt protocol will be one of the three
* 'private' (these are always permissioned)
* 'public-permissioned'
* 'public' (these are typically permissionless)

### Bitcoin Related

* 'bitcoin' = Master tag, everything related
* 'btc-protocol' = anything pertaining to the protocol
* 'btc-lyr2' = protocols built onto bitcoin, such as lightning or liquid
* 'btc-app' = applications integrating bitcoin somehow
* 'btc-wallet'
* 'btc-fork' = any software based upon bitcoin


### Ethereum Related

* 'ethereum' = master tag for everything related
* 'eth-protocol' = anything pertaining to the protocol
* 'eth-lyr2' = eg. State Channels, Plasma, and Truebit
* 'eth-app' = applications integrating bitcoin somehow
* 'eth-wallet'
* 'eth-fork' = any software based upon bitcoin


### Identity Related
There are a lot more identity tags than this. but there are a few to keep in mind.

* 'blockchain-id'    \
* 'decentralized-id'  > These three are differentiated because many projects check all three, but some only check 1 or 2.
* 'self-sovereign'   /
* 'identification'  - Anything related to identification, but not specificly did or self sovereign related. For items that don't fit in other classifications

*'w3c' - this tag often accompanies
* 'did'
* 'verifiable-claims'
* 'credentials'

\* each item recieving a 'protocol' tag should also be tagged with the predecessor (the documentation for indy sovrin and evernym is intertwined.. must reflect that in the tagging)
* 'evernym' - originators of the codebase that was passed on to the sovrin foundation
* 'sovrin' - and further developed and deployed, passing forward the code to the hyperledger foundation
* 'indy' -  

