# The Crypto Library ⧉ Super Source
<a href="https://infominer.id"><img src="https://infominer.id/DIDecentralized/infominer.png" align="right" width="150"></a>

Creating a collaborative web-directory of "source-grade" content, searchable and manually navigable — perhaps with chat bot search engines, to make it portable. For writers, students, and research nerds to easily find information on the topics we're studying at any given moment. 

Originally organized in the channels of a [discord server](http://crypt0library.net), this is a landing pad in the process of making a machine readable repository of information on every subject in crypto.

<center><img src="http://i.imgur.com/HxFqaQg.png" /></center>

### [⧉ SuperSource](http://crypt0library.net) Directory [**^**](#research-index)

I'll share the server directory here, to give you an idea of what you're missing out on. It's quite navigable, using `ctrl+k` (in the discord app), or by using the channel directory I've made in-server.

**General Knowledge**

\#101, #history, #satoshi, #wallets, #exchanges, #cypherpunk, #icos, #evaluation, #economics, #governance, #trading, #mining, #regulation, #walstreet, #wallets, #growth-adoption, #traditional-finance, #classification, 

**Resources**

\#resources, #assorted-media, #twitter-follows, #communities, #news-sites, #swag, #women, #earn-crypto, #conferences, #books, #research-papers, #non-english, #data, #send-crypto

**Crypto**

\#gen-crypto, #bitcoin, #btc-layer2, #ethereum, #eth-layer2, #eth-consensus, #stable-coins, #doge, #zcash, #cardano, #stellar, #ripple, #tron, #bch, #dash, #litecoin, #monero, #iota, #neo, #etc, #steem, #eos, #bitshares, #nano, #hyperledger, #corda, #etcetera, #bytom, #tezos, #cosmos, #enterprise-dlt, #grin-mimblewimble, #blockstack, #central-bank-digital-currency

**Tech**

\#cryptography, #decentralization, #privacy, #security, #protocols, #hash-algos, #open-source, #forks, #smart-contracts, #dapps, #sidechains, #master-nodes, #databases, #ipfs, #tor, #pi-rasberry, #bittorrent, #oracles, #interoperability, #identification, #p2p, #drivechains, #internet-protocols 

**Distributed Consensus**

\#distributed-systems, #consensus, #pow, #pos, #tendermint, #hashgraph, Development, #discussion-dev, #hackathons, #gen-developing, #blockchain-developing, #forking, #bitcoin-dev, #ethereum-dev, #state-channels, #id-dev, #corda-dev, #steem-dev, #hyperledger-dev, #quant-trading, #nano-dev, #cardano-dev, #design

**Application**

\#security-tokens, #identity-did, #finance, #payment-processing, #institutional-derivitives, #prediction-markets, #dao, #fiat-onramp, #publishing, #united-nations, #government, #voting, #supplychain, #social-media, #music, #art-collectibles, #iot, #ai, #intellectual-propery, #games, #energy, #services, #marketplaces, #notary, #criminal, #bots, #utility, #china, #crypto-selfregulation

<b><a href="https://discord.gg/ahTuPMY" target="_blank">discord.gg/ahTuPMY</a></b>

## [crypt0library.net](http://crypt0library.net)

In order to create the database to power our dynamic web-portal, I'm using the [TOML format](https://github.com/toml-lang/toml) to organize the information and describe it and tag it. TOML is a simple format that we are using to prepare our information to be transformed into a mongo database. 

I've scraped the server, and copied all of its contents into files in this repository. Once transformed into TOML, many of them will be made into "[awesome lists](/projects.md)", which is part of my process in gathering more resources for the database. Of course, all of this research makes it easier to write articles on any of the subjects within the repo, which also leads to gathering more information.
  
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

Tagging is a complex topic. We need enough unique tags to make this directory ideally navigable, and to use a consistent schema for tagging over the course of this project. If you are jumping in and getting involved, just tag as best you can, I'll be going over the tagging many times.

Once this project is living in a web app it will become a more streamlined collaborative process: so that tags can be suggested and also flagged as unhelpful. 

To be clear these are app specific tags that users will be able to create and navigate via. Not every possible keyword, that will come later on another layer.

See "[tag-definitions.md](https://github.com/infominer33/Crypto-library/blob/master/toml/tag-definitions.md)" for more information. Feel free to join in on the fun :)

---
### Tips Jar 

BTC— 1GvkjHtiy9LUjVkStnEAXxjhcoS56aCokY

![](http://imgur.com/yXLLm9Bl.png) 

DOGE— DSzMxfABB8EwKiumzV7YHhS7HTvWAyM7QF

![](https://i.imgur.com/0zBLoUP.png) 
