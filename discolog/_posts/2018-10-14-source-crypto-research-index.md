---
layout: single
title: SourceCrypto Research-Index
description: An Open-Source Index of Crypto Knowledge.
header:
  image: /images/source-crypto-disco.png
  og_image: /images/source-crypto-disco.png #/images/source-crypto-gh-og.png
  teaser: /images/source-crypto-disco.png
  caption: #"@Delpadschnick | [CryptoDesign.io](https://CryptoDesign.io)"
sidebar:
  nav: sourcedisco 
excerpt: "[Source Crypto Discord Chat](https://discord.gg/ahTuPMY) is a landing pad.. I drop links there on the fly, occasionaly exporting and publishing the [channels](/discolog/) here. The next step is to systematically build better, more organized resources with the server as a starting point."
toc: true
permalink: blog/research-index/
share: true
categories: [SourceCrypto, indroduction]
tags: [bitcoin, blockchain, development, cypherpunks, ethereum, enterrise, fintech, web3, defi, cryptography, distributed systems, cryptocurrencies, p2p]
last_modified_at: 2019-06-20T11:22:33-23:00

---

**A discord server and web-portal for creating an open-source, public-domain, index of Crypto Knowledge.**

[Source Crypto Discord Chat](https://discord.gg/ahTuPMY) is a landing pad.. I drop links there on the fly, occasionaly exporting and publishing the [channels](/discolog/) here. The next step is to systematically build better, more organized resources with the server as a starting point.

The aim is to generally map out the history and knowledge related to Bitcoin and blockchain in general.

There is so much to learn about, I mostly manage to avoid thinking about scammy stuff and icos, and really whatever you are hyped about, I probably don't care. So the application section is in rough shape.. I don't spend a lot of time there. Tech, History, Development, Webwork. I care about real web technologies.

So, little by little, those un-organized pages will grow to become each a formidible resource of its own.

{% include video id="bxUDZzUJk_A" provider="youtube" %}


While I do intend to build custom pages for most of these channels, being able to simply export the entire discord server and publish it is excellent.

## SourceCrypto

**[discord.gg/ahTuPMY](https://discord.gg/ahTuPMY)**
* [Discord Index](https://SourceCrypto.pub/discolog/)
  * [General](https://SourceCrypto.pub/discolog/general/)
  * [Resources](https://SourceCrypto.pub/discolog/resources/)
  * [Crypto](https://SourceCrypto.pub/discolog/crypto/)
  * [Blockchain-Tech](https://SourceCrypto.pub/discolog/blockchain-tech/)
  * [Tech](https://SourceCrypto.pub/discolog/tech/)
  * [Development](https://SourceCrypto.pub/discolog/development/)
  * [Enterprise](https://SourceCrypto.pub/discolog/enterprise/)
  * [Application](https://SourceCrypto.pub/discolog/application/)
  * [Web Work](https://SourceCrypto.pub/discolog/web-work/)

For now you can browse the entire index of channels at once, or one category at a time.

For those who would like to browse from GitHub, all the pages are in `_pages`, all the files that become (via jekyll collections) the pages of the discolog are in `discolog`, all the data is in `_data`.  

Everything else is `mmistakes/minimal-mistakes`. Pretty straightforward: its [open-source](https://github.com/mmistakes/minimal-mistakes), and [well-documented](https://mmistakes.github.io/minimal-mistakes/).


## A Machine Readable Repository on Every Subject In Crypto.


* [Source⧉Crypto](https://discord.gg/ahTuPMY) - I collect and categorize links in here, on the fly.
![](https://i.imgur.com/hLOk7yL.png)

Previously, I was putting information in TOML format. Then, after I started to learn GitHub pages, and working with some other people on a similar project for Decentralized Identity, I realized that GitHub Pages \ Jekyll have built-in support for yaml, csv, and json... so, yaml is nice and we'll go with that. 

Recently, I found [Tyrrrz/DiscordChatExporter](https://github.com/Tyrrrz/DiscordChatExporter/) which quickly turned the entire contents of Source Crypto Discord Server into 170+ html files. 

If you're using linux, like me... you just have to make it's .exe executable and run it from the terminal, like so: `./DiscordChatExporter.CLI.exe`.

I also used a bulk-renaming tool, and Regex.. those are both great tools, and Regex isn't limited to one particular app, but used all over.

Then, I used minimal-mistakes collections feature to quickly publish the lot of them, using VSCode to easily edit all of the files at the same time. 

I cut out the head of each of the files and injected the css to be applied to those pages.

[![](https://imgur.com/zLF17fAl.png)](https://imgur.com/zLF17fA.png)

That's super quick, and not so dirty, way to get all that content up here on the web where anyone can access it more easily.


* [sourcecrypto/sourcecrypto.github.io](https://github.com/sourcecrypto/sourcecrypto.github.io) -  Now I have a few complete and proper toml files converted to json that I can use to experiment with generating pages - listing by title, tag, and incorporating search functionality, or perhaps filter by user-input.

I'm looking into ways to take a list of links and pull title description image automatically into yaml or json, and pages can be generated with jekyll.

Further down the line, each subject area will become the focus of its own landing page with well researched information, building with and from the structured data. Compared to currently we've got whatever I've happened upon in my travels of the web, with some contributions from the community, with a focus on history and identity. 

* [GitHub Pages Starter Pack](https://web-work.tools/gh-pages-starter-pack/)
* [Minimal Mistakes Quickstart Guide](https://mmistakes.github.io/minimal-mistakes/docs/quick-start-guide/)


![](https://i.imgur.com/pYydLx7.png)

## [discord.gg/ahTuPMY](https://discord.gg/ahTuPMY)



![](https://SourceCrypto.pub/images/interlinked.png){: .align-center}


