---
title: "Practical Bitcoin Guides: Wallets, Applications, and Development"
description: This page is for collecting and organizing information related to using Bitcoin in one way shape or form.
toc_sticky: false
excerpt: Links to code, howtos, and other resources related to practical use of Bitcoin.
permalink: blog/Bitcoin/
published: false
header:
  image: "https://imgur.com/QjmwITb.png"
categories: ["crypto"]
tags: ["bitcoin"]
last_modified_at: 2019-07-16T11:22:33-23:00

---

Please note, some of the resources provided may be out of date. For a first run I'm including everything I can find, and will archive depreciated guides, later.


## [lopp.net/bitcoin.html](https://lopp.net/bitcoin.html)

**Bitcoin Information & Resources**
  >Bitcoin is a revolutionary system that is quite complex and has a steep learning curve. Below you'll find curated educational resources and information about Bitcoin. You could spend months sifting through them all. Make sure you have a decent grasp of the system before you store a significant amount of value in it! The same aspects of Bitcoin that make it so valuable also make it unforgiving to those who make mistakes.
  * [githbu.com/jlopp/jopp.net](https://github.com/jlopp/lopp.net)



## [Bitcoin.org](https://bitcoin.org)

**How it works for:**
  * [Individuals](https://bitcoin.org/en/bitcoin-for-individuals)
  * [Businesses](https://bitcoin.org/en/bitcoin-for-businesses)
  * [Developers](https://bitcoin.org/en/bitcoin-for-developers)
    * [Developers Guide](https://bitcoin.org/en/developer-guide)
  * [Getting started](https://bitcoin.org/en/getting-started)
  * [How it works](https://bitcoin.org/en/how-it-works)

## Fee Calculators
[transactionfee.info](https://transactionfee.info)
* [When Segwit?](https://whensegwit.com/)
* [The relation between Segwit and AsicBoost, covert and overt](https://bitslog.wordpress.com/2017/04/10/the-relation-between-segwit-and-asicboost-covert-and-overt/)
  >I will try to explain the relation between Segwit and AsicBoost, in both the covert and overt forms, in certain detail. I will also try to explain why a method was recently proposed to reduce the i…

### Nodes
* [Bitseed Core - Bitcoin full node](https://bitseed.org/product/bitseed-3/)
  > Bitseed Core comes preconfigured as a Bitcoin full node, allowing you to keep bitcoin running 24/7 without slowing your PC.
* [A complete beginners guide to installing a Bitcoin Full Node on Linux (2018 Edition)](https://hackernoon.com/a-complete-beginners-guide-to-installing-a-bitcoin-full-node-on-linux-2018-edition-cb8e384479ea)
  >How to compile a Bitcoin Full Node on a fresh installation of Kubuntu 18.04 without any Linux experience whatsoever.
  ![](https://imgur.com/hhN0o3F.png)
* [What Comprises a Bitcoin Fullnode Implementation? – Amentum](https://medium.com/amentum/what-comprises-a-bitcoin-fullnode-implementation-df27989e673a)
  >Often times in the press I see a lot of confusion around what a fullnode implementation of bitcoin actually *is*. I saw this as a great…

### Scripting

* [Bitcoin Covenants](http://fc16.ifca.ai/bitcoin/papers/MES16.pdf)
  >Abstract.This paper presents an extension to Bitcoin’s script language enabling covenants, a primitive that allows transactions to restrict howthe value they transfer is used in the future. Covenants expand the set offinancial instruments expressible in Bitcoin, and enable new powerful andnovel use cases. We illustrate two novel security constructs built usingcovenants.
* [Yes, Bitcoin Can Do Smart Contracts and Particl Demonstrates How](https://bitcoinmagazine.com/articles/yes-bitcoin-can-do-smart-contracts-and-particl-demonstrates-how/)
  >The Bitcoin blockchain is not known for its ability to enable smart contracts. In fact, most developers creating smart contracts use a different blockchain, like Ethereum. But the truth is that the Bitcoin protocol can be used to create smart contracts. Particl.io, the blockc...
* [Bitcoin Magazine - Scriptless Scripts: How Bitcoin Can Support Smart Contracts](https://bitcoinmagazine.com/articles/scriptless-scripts-how-bitcoin-can-support-smart-contracts-without-smart-contracts/)
  >Bitcoin’s capacity is limited. Meanwhile, smart contracts can be resource intensive. So even though Bitcoin has always supported basic smart contract functionality, the two have never been a natural match.But a recent topic of research spearheaded by Blockstream mathematici...
* [Jameson Lopp (@lopp)](https://twitter.com/lopp/status/1072156493116518400)
  >https://t.co/etW1yP65Zr has a neat animated Bitcoin script interpreter and debugger for those who want to better understand script execution. https://t.co/5TAkdoPU7b https://t.co/6UkzUGu4dK
  * [liuhongchao/bitcoin4s](https://github.com/liuhongchao/bitcoin4s)

  

## Development

* [Teach Bitcoin](https://teachbitcoin.io/)
  >Teach Bitcoin protocol training is an in-depth program that was inspired from the study of several hundred thousand lines of implementation code. It teaches you both the high and low-level designs of the Bitcoin Protocol, so you can greatly accelerate your journey to becoming a Bitcoin implementation developer or protocol researcher.
  * [Jameson Lopp (@lopp)](https://twitter.com/lopp/status/1032985874361974784?s=19)
    >teachbitcoin.io is a work in progress, but already very slick-looking technical education site for developers who want to understand how wallets and transactions are constructed. Adding this to my resources list!
* [Bitcoin toolchain, unit testing & deterministic builds](http://diyhpl.us/wiki/transcripts/scalingbitcoin/tokyo-2018/edgedevplusplus/bitcoin-toolchain-unit-testing-and-deterministic-builds/)
  >The build system is based on autotools, so it should just work anywhere where autotools runs. Just run ./autogen.sh ./configure and then make, that's it.
  >
  >We recently added support for MSVC for Windows developers in the build system.
  >
  >For release builds, we use cross-compilation which is currently only supported on Ubuntu.



### 101

* [ChristopherA/Learning-Bitcoin-from-the-Command-Line](https://github.com/ChristopherA/Learning-Bitcoin-from-the-Command-Line)


## Application

### Rootstock

* [www.rootstock.io](http://www.rootstock.io/) - RSK, bitcoin´s smart contract platform.


### BTCPay Server

* [A Year After Launch, BTCPay Has Grown Larger Than Its Creator Expected](https://bitcoinmagazine.com/articles/year-after-launch-btcpay-has-grown-larger-its-creator-expected/)
  >BTCPay has become a meteoric success. But for what started out as a hobbyist’s side project, this success has, in some respects, become unwieldy.

### Lightning
* [Pierre Rochard [⚡️] (@pierre_rochard)](https://twitter.com/pierre_rochard/status/1055159992733626368)
  >The LND node software now runs from within the Excel plugin. With neutrino, that means that a Windows + Excel user can be making and receiving LN payments with a few clicks. https://t.co/qeP2dCJSqp
* [Will O'Beirne (@wbobeirne)](https://twitter.com/wbobeirne/status/1131989707389329408?s=12)
  >Need plans for the long weekend? Why not get started on making your own Lightning App! Over the next couple of weeks I'll be posting a 5 part series on building a modern web app that takes lightning payments, and how to host it securely. https://t.co/gDsAAUKrnj
* [Fulmo ⚡ @fulmolightning](https://twitter.com/fulmolightning/status/1035183579196743680)
  >Get ready to rumble! The latest batch of 20 #RaspiBlitz, a full #Bitcoin and #LightningNetwork node running on a Raspberry Pi, is ready to be picked up and plugged in at the #LightningHackday! If you can't attend in person, you can build one yourself: 
  - https://github.com/rootzoll/raspiblitz
  ![](https://imgur.com/edaW3pO.png)

### Mining




### Books

* [bitcoinbook/bitcoinbook](https://github.com/aantonop/bitcoinbook) - Mastering Bitcoin 2nd Edition - Programming the Open Blockchain


## Assorted


* [bitdb.network](https://bitdb.network/) - The Random Access Memory for Bitcoin
* [Mapping out bitcoin's supply chain - The Block](https://www.theblockcrypto.com/2018/11/01/mapping-out-bitcoins-supply-chain/)
  >The Block complements our writings and analyses with charts, graphs, and maps is to give our readers a comprehensive look at the complex crypto ecosystem. Even the veteran Bitcoiner can get lost in the twist and turns that is the bitcoin labyrinth. Here, we take a high-level...
  >![](https://imgur.com/1XOFJBx.png)

* [BestMixer.io’s Bitcoin Blender Aims to Bring Anonymity Back to C...](https://thebitcoinnews.com/bestmixer-ios-bitcoin-blender-aims-to-bring-anonymity-back-to-crypto/)
  >The BestMixer.io development team has introduced their next generation bitcoin blender in an effort aimed at disrupting the quickening pace of blockchain analysis firms such as Chainalysis. The reason behind the move is simple: cryptocurrency is not anonymous but it pretends ...
* [The Business of Bitcoin Cold Storage – Nik Bhatia](https://medium.com/@timevalueofbtc/the-business-of-bitcoin-cold-storage-148fba7f1255)
  >Bitcoin is digital gold, and this continues to be its most appropriate and concise metaphor. I recently discussed some parallels between…
* [How to Create and Verify a Chainpoint Proof – Tierion](https://medium.com/tierion/how-to-create-and-verify-a-chainpoint-proof-eba52a7700e3)
  >This guide shows how developers can use a Chainpoint Node to create and verify a Chainpoint proof. Chainpoint is an open standard for…

* [The Evolution of Bitcoin Key Management](https://medium.com/casa/the-evolution-of-bitcoin-key-management-c2fd29ba35d6)
  >Let’s revisit important milestones in how we experienced Bitcoin HODLing over the past 10 years, and what we can expect from 2019.
  >
  >In this post, I’m not talking about custodial “vaults” — exchanges and wallets that hold crypto on the customer’s behalf — nor all the security faux-pas and breaches that happened in custody. This is merely my appreciation for the development of the sovereign Bitcoiner.


## BTC Layer 2

* [P.Miller (@patmillertime)](https://twitter.com/patmillertime/status/1020742512112095233)
  >Are you looking for more #LightningNetwork resources and information? Check out: https://t.co/m9aRwlno69 https://t.co/BqXexWLHCa https://t.co/hAvtZyBdtc https://t.co/PaeCg5f6Um https://t.co/2ykoLIrzFp


* [Nick Szabo⚡️ (@NickSzabo4)](https://twitter.com/NickSzabo4/status/846492284036145152)
  >"Bitcoin .. needs .. a secondary level of payment[s] which is lighter weight." -- Hal Finney 2010 https://t.co/tIbkVF2ezc ht @rextar4444


* [The Code for an Anonymous Lightning Network is Now Live](https://www.coindesk.com/the-code-for-an-anonymous-lightning-network-is-now-live/)
  >A private version of the crypto protocol lightning network is headed to zcash, with the potential it could be added for other blockchains soon.
 
* [The Lightning Network: How to install and (hopefully) make money -Ronald Mannak](https://medium.com/coinmonks/the-lightning-network-how-to-install-and-hopefully-make-money-6e3058e3fa7c)
  >Note: This document was written in July 2018. Lightning is new and improving fast. If you find any out-of-date information or omissions, please leave a comment.

* [The perfect Bitcoin ⚡️Lightning️⚡ node – Stadicus](https://medium.com/@stadicus/perfect-low-cost-%EF%B8%8Flightning%EF%B8%8F-node-4c2f42a4ff7b) -This page is no longer maintained. Please check out the latest and enhanced version of this guide on Github:
 
* [The Bitcoin Second Layer – Nik Bhatia – Medium
The Lightning Network Reference Rate](https://medium.com/@timevalueofbtc/the-bitcoin-second-layer-d503949d0a06), Part 1 of 4
 
* [lightningnetworkstores.com](http://lightningnetworkstores.com/)
* [bcongdon/awesome-lightning-network](https://github.com/bcongdon/awesome-lightning-network) ⚡ awesome-lightning-network ⚡ A curated list of awesome Lightning Network projects for developers and crypto enthusiasts
 
* [dev.lightning.community/resources/](https://dev.lightning.community/resources/) - Lightning Resources - Developer resources and documentation for the Lightning Network Daemon.


* [Making sense of Lightning network nodes and money transmission licensing](https://coincenter.org/entry/making-sense-of-lightning-network-nodes-and-money-transmission-licensing) -An update on Coin Center’s work to avoid unnecessary regulatory burdens on technologists.
 
* [Dan Hedl (@danheld)](https://twitter.com/danheld/status/1033044447842336768)
  >1/ A complete debunking of top Lightning FUD claims:

* [The Lightning Times - Issue #2](https://the-lightning-times.ongoodbits.com/2018/08/27/issue-2)

* [Fulmo ⚡ (@fulmolightning)](https://twitter.com/fulmolightning/status/1035183579196743680) - [rootzoll/raspiblitz](https://github.com/rootzoll/raspiblitz)
  >Get ready to rumble! The latest batch of 20 #RaspiBlitz, a full #Bitcoin and #LightningNetwork node running on a Raspberry Pi, is ready to be picked up and plugged in at the #LightningHackday! If you can't attend in person, you can build one yourself: 

* [Casa Lightning Node](https://store.casa/lightning-node/) - Simple, easy to use Lightning Network node
 
* [Exploring Lightning Network Routing](https://blog.lightning.engineering/posts/2018/05/30/routing.html)
  >When we last left our hero Carol, she had successfully joined the Lightning Network and started making Lightning transactions. As she’s become familiar with the user experience side of Lightning, she’s also started to become more interested in Lightning from a technical standpoint. She’s even thinking about running a Lightning routing node herself, with the goal of earning enough in routing fees to pay for her monthly BitFlix subscription. 
  
* [Stephan Livera (@stephanlivera)](https://twitter.com/stephanlivera/status/1028079725460111360) -([spotify](https://open.spotify.com/episode/7eq7H9t54IvnLo4QKA9rrb))
  >SLP9 - Lightning UX and Routing, with @bvu VP, Product of @lightning We discuss: - Lightning User Experience - Lightning Routing - Benefits for users, merchants and exchanges - Autopilot, watchtowers, AMP, splicing listen, subscribe, share! 
* [Announcing the Casa Lightning Node – Casa Blog – Medium](https://medium.com/casa/announcing-the-casa-lightning-node-596df7a7427) -The easiest way to use Lightning available today.
 


* [𝑅𝑎𝑔𝑛𝑎𝑟 𝐿𝑖𝑓𝑡ℎ𝑟𝑎𝑠𝑖𝑟 🏴 (@Ragnarly)](https://twitter.com/Ragnarly/status/1039113181023490050) -Some of the best tools in bitcoin have been built by without raising capital from VCs: @BtcpayServer, @SamouraiWallet, @OPENDIME and @COLDCARDwallet, and most software wallets. Did I miss any?

* [ZigZag](https://zigzag.io/#/) - lightning enabled crypto exchange

* [BTCPayServer](https://nbitstack.com/c/btcpayserver)
  >Anything related to the free, open-source .NET cryptocurrency payment processor BTCPayServer.
 
* [Stadicus/guides](https://github.com/Stadicus/guides/blob/master/raspibolt/README.md) -Cryptocurrency guides by Stadicus. Contribute to Stadicus/guides development by creating an account on GitHub.
 


* [Blockstream's New Solution To Bitcoin's Liquidity Problem Looks Od...
](https://www.forbes.com/sites/francescoppola/2018/10/11/blockstreams-new-solution-to-bitcoins-liquidity-problem-looks-oddly-familiar/#3484b491e51a) -Blockstream's Liquid sidechain purports to be an innovative solution to Bitcoin's chronic illiquidity. But it inadvertently replicates something with which we are all too familiar.
 
* [Blockstream’s Liquid Network for “High Value” Bitcoin](https://bitcoinmagazine.com/articles/blockstreams-liquid-network-high-value-bitcoin-payments-live/)
  >Blockstream’s COO Samson Mow explains how “Liquid is designed to facilitate fast and reliable high value transfers” of bitcoin (and other cryptocurrencies -- eventually.)
 
* [Beautyon (@Beautyon_)](https://twitter.com/Beautyon_/status/1062100915925213185) -SUPER INTERESTING: "The 8333.io platform provides tooling, apps & services on top of any bip32 compatible Bitcoin wallet. It's a service layer on top of the Bitcoin network, offering powerful utilities for users and/or developpers." https://8333.io/
* [Lightning in 2018](https://shea.io/lightning-in-2018)
  -Below is an archived and reformatted tweetstorm from Nov 29, 2018. Enjoy! #1 Lightning Network is on fire lately 12500 channels (up 3…
* [JW Weatherman | mathbot.com (@JWWeatherman_)](https://twitter.com/JWWeatherman_/status/1069232488604729344)
  >#rsk #rootstock https://t.co/dmwA7j7U3K Is still planning to introduce a security flaw they call “drive chains” If they get enough fools to put bitcoin on this flawed side chain it will resulting a massive theft of #bitcoin Defend bitcoin by alerting people of the ...
* [SLP37 Rene Pickhardt – Bitcoin Lightning Education & Lightning S...](https://stephanlivera.com/episode/37)
  >Rene Pickhardt, a Bitcoin/Lightning educator, and rising star in the world of Lightning joins me to talk about the Lightning Network. We discuss: How he got into Lightning Involvement in the Pirate…
 

* [How to Create an Online Store & Accept Bitcoin](https://bitcoinshirt.co/how-to-create-store-accept-bitcoin)
  >Learn how to build an online e-commerce store and accept Bitcoin payments with no coding or web-designing skills required. Using free and open-source software: WordPress, WooCommerce and BTCPay. No steps skipped and video tutorials.
 
* [Blockstream Boosts Bitcoin Satellite Service With Lightning Payments](https://www.coindesk.com/blockstream-boosts-bitcoin-satellite-service-with-lightning-payments)


* [Lightning Network enables Unicast Transactions in Bitcoin.](https://medium.com/@melik_87377/lightning-network-enables-unicast-transactions-in-bitcoin-lightning-is-bitcoins-tcp-ip-stack-8ec1d42c14f5)
  >It has recently come to my attention that there is a great deal of confusion revolving around the Lightning Network within the Bitcoin and…
 
* [Melik Manukyan ⚡️ ludvigart.com (@realLudvigArt)](https://twitter.com/realLudvigArt/status/1037592389529919488)
  >1)I am seeing an increasing number of people under the impression that #lightning as an overlay bridge network for #blockchains (via atomic swaps) is a great thing for alts. And they can not be more wrong. In reality, Lightning is where #altcoins will come in droves only...

* [Sergio Demian Lerner 'not giving away Eth' (@SDLerner)](https://twitter.com/sdlerner/status/1075506026114371584?s=12)
  >After reading @AaronvanW 's excellent review of Bitcoin and @RSKSmart growth in 2018, I decided do provide actual statistics of RSK growth in 2018 .. so here is the tweet thread !

* [Bitcoin Lightning Joule Chrome Extension](https://medium.com/lightning-power-users/bitcoin-lightning-joule-chrome-extension-ac149bb05cb9)
  >Lightning Joule is an awesome Chrome plugin being developed by William O'Beirne, check out his presentation at the Chaincode Labs…
 
* [Is the Lightning network ready for commerce?](https://www.scipioerp.com/2018/12/12/is-lightning-ready-for-commerce/)
  >We have been experimenting with Lightning (Bitcoin) payments. But is it ready for commerce applications? Here's what we think...
 


* [Alex Bosworth ☇ (@alexbosworth)](https://twitter.com/alexbosworth/status/1078353292768403456)
  - Ways I can tell LN routing is not a mature market yet: - I’m charging 25x more than anyone and routing more than ever before - The largest capacity owner assigns capacity at random - Almost no one charges any fees at all for routing - Most public nodes aren’t even reli...

* [Nik Bhatia (@timevalueofbtc)](https://twitter.com/timevalueofbtc/status/1078337607493332992) 
  >Recent interviews given by @roasbeef @bitconner and tweets by @alexbosworth confirm my initial theory about the potential for operating a profitable Lightning node: payment channel management skill is the primary driver of profits. Merely staking capital ensures nothing.

* [[Lightning-dev] An Argument For Single-Asset Lightning Network](https://lists.linuxfoundation.org/pipermail/lightning-dev/2018-December/001752.html)
  >In theory, the Lightning Network could potentially perform "seamless" currency conversions, allowing a payer to spend one currency to pay a payee requesting for another currency.
  >
  >However, a significant technical barrier prevents implementation of such feature as of current designs (late 2018) for Lightning.

* [Jeff Vandrew Jr Attorney+CPA (@vandrewattycpa)](https://twitter.com/vandrewattycpa/status/1079471260978040833)
  >Today I released LibrePatron, an alternative to Partreon backed by @BtcpayServer. Most Patreon alternatives don't implement the full Patreon feature set. This seeks to change that. Sample site (alpha not mobile responsive, mobile coming soon!): 
  * [JeffVandrewJr/patron](https://github.com/JeffVandrewJr/patron)

* [lightninglayer.com](https://lightninglayer.com/)
* [Andreas Brekken (@abrkn)](https://twitter.com/abrkn/status/1079116127542726656)
  >Explained why I took my LN hub down. Every maximalist attacked me, without reading my review Asked how to add LN as a payment option for my startup. No one replied This is why https://www.shitcoin.com/ exists. We prove that no one is using what they shill. But I do. https:...

* [Blockstream/liquid](https://github.com/Blockstream/liquid) -Liquid daemon and cli. Contribute to Blockstream/liquid development by creating an account on GitHub.
 

* [Easiest #Bitcoin Lightning Guide!](https://medium.com/lightning-power-users/windows-macos-lightning-network-284bd5034340)
