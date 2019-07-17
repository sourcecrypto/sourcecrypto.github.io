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

## Lightning

* [Bitcoin Lightning Network:Resource and Information Guide](https://lnroute.com)

[**Setup and Tutorials**](https://lnroute.com/setup-tutorials/)
  * [Pierre Rochard’s Bitcoin and Lightning Node Launchers](https://github.com/PierreRochard/node-launcher) - Windows /macOS Bitcoin / Lightning executables.
  * [Beginner’s Guide to Lightning️ on a Raspberry Pi](https://github.com/Stadicus/guides/blob/master/raspibolt/README.md)
  * [Setup Tutorial for Windows](https://medium.com/@jadmubaslat/bitcoin-lightning-network-node-easy-setup-tutorial-for-windows-desktop-users-a-how-to-guide-9937b5a8a669)
  * [ZAP Wallet setup for Windows (video)](https://www.youtube.com/watch?v=w3PGlgiM0ZQ)
  * [Run your own Lightning Node](https://medium.com/@dougvk/run-your-own-mainnet-lightning-node-2d2eab628a8b)
  * [Beginners Guide to Lightning on Raspberry Pi](https://github.com/Stadicus/guides/blob/master/raspibolt/README.md)
  * [Setup LND 0.4 beta and bitcoind on Ubuntu 16.04](https://gist.github.com/bretton/0b22a0503a9eba09df86a23f3d625c13)
  * [setup C-lightning on Debian, with or without TOR (french)](https://www.crypto-lyon.fr/setup-lightning-node-bitcoin.html)
  * [Bitcoin Core + LND 0.4 Beta (mainnet) Installer for Raspberry](https://github.com/jochemin/raspnode)
  * [Setting up an LTC lightning node on MAC](https://gist.github.com/ecurrencyhodler/f6da7f26110c875e7fa41a91c66b72a1)
  * [How to build your own portable plug-in Lightning node!](https://blockstream.com/2018/04/21/portable-lightning-node-tutorial.html)

[**Explorers and Statistics**](https://lnroute.com/explorers-and-statistics/)  ([Forget Statistics, Reality is Better](https://lnroute.com/2018/09/forget-lightning-statistics-reality-is-even-better/))

Lightning Node Match – maximize te number of nodes reached in a minimum number of hops.
  * [www.moneni.com/mcb/nodematch](https://www.moneni.com/mcb/nodematch)

**Lightning Stats**
  * [p2sh.info/dashboard/db/lightning-network](https://p2sh.info/dashboard/db/lightning-network)
  * [lightningpeach.com/ln-monitor](https://lightningpeach.com/ln-monitor)
  * [bitcoinvisuals.com/lightning](https://bitcoinvisuals.com/lightning)
**Testnet Explorers**
  * [1ml.com/testnet/](https://1ml.com/testnet/)
**Mainnet Explorers**
  * [explorer.acinq.co/](https://explorer.acinq.co/)
  * [explore.casa/](https://explore.casa/)
  * [graph.lndexplorer.com/](https://graph.lndexplorer.com/)
  * [lightning.chaintools.io/](https://lightning.chaintools.io/)
  * [bitcoinvisuals.com/lightning](https://bitcoinvisuals.com/lightning)
  * [www.robtex.com/lightning/node/](https://www.robtex.com/lightning/node/)
  * [lnmainnet.rompert.com/](https://lnmainnet.rompert.com/)
  * [bitcoinexchangerate.org/lightning](https://bitcoinexchangerate.org/lightning)
  * [1ml.com/](https://1ml.com/)
  * [lightblock.me](http://lightblock.me)

[**Implementations**](https://lnroute.com/category/implementations/)

* [lightning-space.com/get-space/](https://lightning-space.com/get-space/)
  >Buy webspace with Bitcoin Lightning. You will receive the specified amount of SSD-webspace for the specified amount of days. Included is PHP 7.2, a MySQL (MariaDB) database, SSH and FTP access and an email address (username@lightning-space.com)
* [www.lightningduel.com/](https://www.lightningduel.com/)
  >Provably fair gamble game with instant deposits and withdrawals. A good showcase of the power of the Lightning network.
* [thundersats.com/](https://thundersats.com/)
  >Miniature Roulette Game on top of the Bitcoin Lightning Network.
Oc2 (Off chain On chain https://oc2realm.com/) - India’s first Decentralised Exchange, 0x Relayer and early adopters of Lightning. 
* [lightning.oc2realm.com/](https://lightning.oc2realm.com/)
  >To support their vision, they have created a Slot Machine on top of Lightning Network. 
* [unlock.lngames.net/](https://unlock.lngames.net/)
  >Open the correct lock and get satoshis
* [bottle.li](https://bottle.li)
  >Bottle uses the Lightning Network andSocial networks to help make Bitcoin accessible for everyone.
* [github.com/lightningd/plugins/tree/master/autopilot](https://github.com/lightningd/plugins/tree/master/autopilot)
  >The C-Lightning plugin repository received an autopilot plugin that can help users choose one or more channels to open to start sending LN payments. The plugin is based on an earlier PR to the main C-Lightning codebase.
* [cryptoally.io/](https://cryptoally.io/)
  >CryptoAlly.io is a place to discover quotes of Satoshis and Bitcoin in 100+ currencies at real time. The value transfer of Satoshis is powered by Lightning Network.
* [cryptochill.com/](https://cryptochill.com/)
  >Bitcoin and Lightning Network payment gateway focused on security, customizability and simple integration.
* [nayuta.co/](https://nayuta.co/) - [github.com/nayutaco](https://github.com/nayutaco)
  >Ptarmigan by Nayuta Co is a 4th Lightning implementation,
   focused on the Internet of Things.
* [funraiden.com/](https://funraiden.com/)
  >Funraiden offers cool and geeky products from collectibles to stickers and merch, payed with Bitcoin/Lightning.
* [crypto-coffee.org](http://crypto-coffee.org)
  >Buy coffee and stickers with Lightning
* [lightningflip.xyz](http://lightningflip.xyz)
  >LN coinflipping game
* [crypto.slamtrade.com/](https://crypto.slamtrade.com/)
  >24/7 streaming of high-performance Crypto-Currency trading signals presented in a single view for professional trading. Find out where to buy/sell or when to buy/sell at any point in time in seconds. Also discover liquidity, market making, and arbitraging opportunities.
* [bitcoinvisuals.com/lightning](https://bitcoinvisuals.com/lightning)
  >Bitcoin Visuals Lightning Statistics
* [github.com/janoside/lnd-admin](https://github.com/janoside/lnd-admin)
  >Admin UI for LND. See * [lnd-admin.chaintools.io/ for an example.](https://lnd-admin.chaintools.io/ for an example.)
* [rgbslot.lngames.net/](https://rgbslot.lngames.net/)
  >Three colors and  three wheels. Simple and different slot machine game.
* [poke.lightningwiki.net/](https://poke.lightningwiki.net/)
  >Play Pokémon with your fellow bitcoiners a collaborative gameboy powered by Lightning
* [github.com/bitromortac/lndmanage](https://github.com/bitromortac/lndmanage)
  >Control tool for lightning network daemon (lnd) node operators, optimized for remote control.
* [boltz.exchange/](https://boltz.exchange/) ([*](https://medium.com/boltzhq/announcing-the-first-boltz-release-6cb630701432))
  >An instant, account free, and non-custodial digital asset exchange built on top of the lightning network.
* [www.zebpay.com/](https://www.zebpay.com/)
  >App-enabled cryptocurrency exchange and wallet provider, Zebpay, has announced that it is enabling Lightning Network payments for all its users. Zebpay claim that it will even pay the fees for Lightning transactions made through its wallet.
* [trustedcoins.co.uk/sweetsugarleaf/](https://trustedcoins.co.uk/sweetsugarleaf/)
  >Cute Cannabis themed artwork by a Medical Marijuana advocate in the UK
* [blockclock.live/](https://blockclock.live/)
  >A Block Clock powered by the Lightning Network. You can send a lightning payment to write a message on the BlockClock that is being live streamed on Twitch!
* [limichat.herokuapp.com/](https://limichat.herokuapp.com/)
  >Limichat is a chat application that limits messages based on payment via Lightning. Sending a message gets cheaper over time, but doubles when someone pays, resulting in one message per ~10 min!
* [mailchi.mp/cf60f9bb7278/opennode-can-now-be-used-on-shopify](https://mailchi.mp/cf60f9bb7278/opennode-can-now-be-used-on-shopify)
  >Opennode released a plugin for Shopify that allows you to accept Bitcoin and Bitcoin Lightning payments.
* [wordpress.org/plugins/btcpay-for-woocommerce/](https://wordpress.org/plugins/btcpay-for-woocommerce/)
  >BTCPay Server is a free and open-source cryptocurrency payment processor which allows you to receive payments in Bitcoin and altcoins directly, with no fees, transaction cost or a middleman.
* [wordpress.org/plugins/opennode-for-woocommerce/](https://wordpress.org/plugins/opennode-for-woocommerce/)
  >This plugin allows stores that use WordPress WooCommerce shopping cart system to accept Bitcoin and Bitcoin through Lightning Network via OpenNode.
* [wordpress.org/plugins/lightning-publisher/#description](https://wordpress.org/plugins/lightning-publisher/#description)
  * [github.com/ElementsProject/wordpress-lightning-publisher](https://github.com/ElementsProject/wordpress-lightning-publisher)
    >Lightning Publisher for WordPress is developed by Blockstream and allows you to offer previews of your blog posts and require a Lightning Network payment to release the rest.
* [www.travelbybit.com](https://www.travelbybit.com)
  >We help travellers explore the world using cryptocurrency. Lightning payments are accepted.
* [satoshis.pictures/](https://satoshis.pictures/)
  >Experience the power of the lightning network by advertising your products and solutions in satoshis.pictures
* [whereisnakamoto.lngames.net/](https://whereisnakamoto.lngames.net/) -The player that finds Nakamoto is awarded 50% of the jackpot.
  >Satoshi Nakamoto is hidden in one of 256 cards of the board. At the beginning of each game, all cards are closed. When Nakamoto is found, the game ends and another begins with all the cards closed again.
* [www.satoshibet.io/](https://www.satoshibet.io/)
  >Satoshibet is a provably fair roulette with a trollbox and a tipping bot. Play roulette while talking with fellow players in the chat.
* [satoshi-go-bet.alhur.es/](https://satoshi-go-bet.alhur.es/)
  >Satoshi Go Bet is a betting platform for online Go games. Choose any of the live Go games and make bets on the player you think will win.
* [lnsh.pw/](https://lnsh.pw/)
  >Lightning Shell allows you to get root access to a Docker container for just 42 satoshis per hour . Pay with Lightning and get access to a shell with 200MB RAM, 0.5 CPU and up to 200MBit/s network connection!
* [kriptode.com/satsforlikes/index.html](https://kriptode.com/satsforlikes/index.html)
  >Pay people to like your tweets or follow you.
* [lightningscratchcard.io/](https://lightningscratchcard.io/)
  >Pay Satoshis with Lightning Network to scratch letters and help reveal a hidden message. Or post a message yourself and make it attractive so people want to discover.

* [buyabeerwithlightning.com](http://www.buyabeerwithlightning.com/)
Zap is developing Point of Sale solutions for the Lightning Network. Check out this site for a demonstration.
zap POS implementation



LuckyThunder Slot Machine

* [www.luckythunder.com/#/](https://www.luckythunder.com/#/)
  >LuckyThunder is a slot machine built on top of the bitcoin lightning network. No login required, provably fair, high win percentage.

Casa Lightning Explorer

* [explore.casa/](https://explore.casa/)
  >A fast explorer that allows you to query nodes and channels. Node details include a starmap and a list of channels.

Suredbits NFL, NBA and Crypto API’s

Suredbits’ Lightning App API allows you to query NFL, NBA and Crypto Exchange data. Their NFL and NBA APIs offer multiple channels including teams, players, games, scores, and statistics. Their Crypto Exchange API allows you to stream data on Trades, Tickers and Order Books.

* [suredbits.com](https://suredbits.com)
  >Usage of the API is charged over Lightning Network per call or per streaming data period.

Acinq Lightning Mainnet Explorer

* [explorer.acinq.co/](https://explorer.acinq.co/)
  >A world map Lightning Explorer for mainnet.

WordPress plugin for managing & using your LND node

* [github.com/rstmsn/lnd-for-wp](https://github.com/rstmsn/lnd-for-wp)
  >LND For WP is a WordPress plugin that allows you to manage and use your LND node, right from your WordPress administration panel. It provides a fully functional wallet interface, allowing you to send and recieve funds across the Lightning Network with ease. The user interface is responsive and will adapt to fit any web enabled desktop, tablet or mobile device. You can search the Lightning Network graph, manage peer connections and open & close channels with ease. The plugin has QR support, enabling basic encoding & decoding of QR codes. LND For WP also adds a number of WordPress ‘shortcodes’, allowing you to embed LND functionality directly in your website pages and posts. New Shortcodes will be added with future versions, as needs & use cases arise.

LN Payment Gateway for OpenCart

* [www.opencart.com/](https://www.opencart.com/)
  >A free payment gateway for Bitcoin Lightning Network for store owners who use OpenCart and have their own LN node.

Internet Superstore

* [internetsuper.store](https://internetsuper.store)
  >Bitcoin online store that accepts Lightning payments


The Lightning Wall

Post public messages on the wall and receive satoshis from people who like your message.

http://lightningwall.tips

BC.Game

* [bc.game](https://bc.game)
  >BC.Game is a BlockChain Game platform with provably fair, fast payouts, a free faucet and Lightning Network support. Some of the games available are Crash, Dice and Blackjack.


Lightning Memory Game

* [memory.lngames.net/](https://memory.lngames.net/)
  >Classical memory game on Lightning. Pair up the 8 different images and if you beat the highscore, you win the jackpot.

Lightning Mainnet Faucet

* [light.yuyaogawa.com/faucet/](https://light.yuyaogawa.com/faucet/)
  >A lightning faucet where you can claim an invoice of 200 sats. Maximum one claim per day.

* [fortune.lngames.net/](https://fortune.lngames.net/)
  >Lightning Wheel of Fortune

Moifay

* [moifay.online/](https://moifay.online/)
  >Official release of first ever Music Album of Moifay, sold online for #Lightning $BTC. Each song is $1 only.

Bitlum Chrome Extension Wallet

Bitlum is a Lightning Network mainnet web wallet. Fast, easy, and without the need to install a node. Setting up only takes 5 minute access.

* [t.co/o6KyypNuYL](https://t.co/o6KyypNuYL)
  >The wallet referral system will allow you to onboard new people in Lightning within 3 minutes, by giving them a free $0.1 bonus on registration, so that they can try the Lightning Network even without having Bitcoin.

Bitcoin Tunnels

* [www.bitcointunnels.com/](https://www.bitcointunnels.com/)
  >Bitcoin and Lightning merchandise

Canadian Cannabis Company to accept Lightning

Bosstalgia Medicinals (@bosstalgia) is the first Canadian Company to accept payments on the Bitcoin Lightning network.

* [bosstalgia.com](https://bosstalgia.com)
  >Canadians can now order their award winning cannabis extract using bitcoin. You need to be over 19 years of age and sign up to access the site.


Mini Casino Roulette

* [miniroulette.lngames.net/](https://miniroulette.lngames.net/)
  >Lightning Network simple casino roulette game

ln.pizza

* [ln.pizza/](https://ln.pizza/)
  >Order Domino’s Pizza via the Lightning Network from anywhere in the US. Get 5% off when paying with Lightning!

Vape Crypto

* [vapecrypto.com/shop](https://vapecrypto.com/shop)
  >Providing the best prices on authentic Vape Gear, Juices and Accessories. We’re your one stop shop for vape gear

Hipptee

* [hipptee.com/](https://hipptee.com/)
  >Bitcoin T-shirt

* [neverfiat.com/](https://neverfiat.com/)
  >NeverFiat Crypto Marketplace

* [joltfun.com/](https://joltfun.com/)
  >Joltfun

* [thecryptocloak.com/](https://thecryptocloak.com/)
  >CryptoCloaks

* [www.moonstuff.co/](https://www.moonstuff.co/)
  >moonstuff

Hammerland

* [playhammerland.com/](https://playhammerland.com/)
  >A role-playing game using Lightning for in-game payments

CoinTippy

* [cointippy.com/](https://cointippy.com/)
  >CoinTippy helps you reward content on Reddit, Twitter, Telegram and Twitch with cryptocurrencies

LNCast

* [lncast.com/#!/](https://lncast.com/#!/)
  >Lightning Network Podcasts

Lightning Payment Request Decoder

* [lndecode.com/](https://lndecode.com/)
  >For decoding lightning network payment requests as defined in BOLT #11

* [lnroute.com/shop/](https://lnroute.com/shop/)
  >Testnet LNROUTE Tea Store

* [lnd-testnet-2.mably.com/](https://lnd-testnet-2.mably.com/)
  >Testnet Slack Tipping Bot

* [testnet.satoshis.place/](https://testnet.satoshis.place/)
  >Testnet Satoshi’s Place

* [testnet.lightninggem.com/](https://testnet.lightninggem.com/)
  >Testnet Lightning Gem Game

* [starblocks.acinq.co/#/](https://starblocks.acinq.co/#/)
  >Testnet Starblocks Coffee Shop

Microlancer.io

* [microlancer.io/](https://microlancer.io/)
  >Earn bitcoin with microtasks

* [proofofplays.hopto.org/](https://proofofplays.hopto.org/)
  >Proof of Plays

LightTube

A platform for content creators to showcase their videos and get paid satoshis.

http://light-tube.surge.sh/

Tallycoin

* [tallyco.in/](https://tallyco.in/)
  >Bitcoin and Lightning fundraising platform. Create crowdfunding campaigns for your project and get funded by fellow bitcoiners!

Salttie

* [salttie.com/](https://salttie.com/)
  >Micro Blogging Platform

* [tippin.me](https://tippin.me)
  >tippin.me

* [singles.shock.network/](https://singles.shock.network/)
  >Lightning Singles

* [shop.energy-kitchen.ch/#/shop](https://shop.energy-kitchen.ch/#/shop)
  >energyKitchen

* [www.lndwork.com/](https://www.lndwork.com/)
  >Lightning Tasks

* [www.mocacinno.com/lightning/](https://www.mocacinno.com/lightning/)
  >Image Unblurrer

* [www.btcduke.com/](https://www.btcduke.com/)
  >BtcDuke

* [zigzag.bitlum.io](https://zigzag.bitlum.io)
  >Zig Zag

* [ludvigart.com/](https://ludvigart.com/)
  >Ludvig Bitcoin Art

Y’alls

* [mainnet.yalls.org/](https://mainnet.yalls.org/)
  >Read and write articles, with Lightning Network micropayments.

Bitrefill

* [www.bitrefill.com/](https://www.bitrefill.com/)
  >Buy 30+ Vouchers, refill your phone and pay your bills with Lightning.

Lightning Joule

Bring the power of lightning to the web with in-browser payments and identity, all with your own node. Available for Chrome, Firefox, Opera and Brave.

* [lightningjoule.com/](https://lightningjoule.com/)

lnwallet.io

* [lnwallet.io/](https://lnwallet.io/)

OpenNode

* [www.opennode.co/](https://www.opennode.co/)

Globee

* [globee.com/](https://globee.com/)

Coingate

* [coingate.com/lightning-network](https://coingate.com/lightning-network)

Strike by ACINQ

* [strike.acinq.co/](https://strike.acinq.co/)

BTCPay Server

* [github.com/btcpayserver](https://github.com/btcpayserver)

Lightning In a Box

* [lightninginabox.co/](https://lightninginabox.co/)

Casa Lightning Node

* [store.casa/lightning-node/](https://store.casa/lightning-node/)

Modular Synth Fun

Audo Samples

* [modularsynth.fun](https://modularsynth.fun)

BTCWonderland

* [btcwonderland.com](https://btcwonderland.com)

CryptoHO.ST

Bitcoin and LN powered Virtual Private Server (VPS) store

* [cryptoho.st/](https://cryptoho.st/)

Empower Your Life

* [www.empowermindbodylife.com/shop/](https://www.empowermindbodylife.com/shop/)

LNDlife

* [lndlife.com](https://lndlife.com)

---

## Wallets

* [www.cardwallet.com](https://www.cardwallet.com) -You get a 10% discount when paying with Lightning.
  >The Card Wallet is a co-production of Coinfinity and the Austrian State Printing House, and offers a simple way to securely store Bitcoin offline in form of a tamper-proof card. The Card Wallet is manufactured in the high-security room of the Austrian State Printing House in an isolated offline system, using Coinfinity’s Secure Entropy Technology. The private key is sealed tamper-proof before the card leaves the production machine, and immediately deleted after the process so that not even the staff at the high-security room can ever see the key. High-quality security materials and tamper-proof features prevent a manipulation of the card.


## BTC Layer 2

* [P.Miller (@patmillertime)](https://twitter.com/patmillertime/status/1020742512112095233)
  >Are you looking for more #LightningNetwork resources and information? Check out: https://t.co/m9aRwlno69 https://t.co/BqXexWLHCa https://t.co/hAvtZyBdtc https://t.co/PaeCg5f6Um https://t.co/2ykoLIrzFp
 Twitter
https://twitter.com/NickSzabo4/status/846492284036145152

Nick Szabo⚡️ (@NickSzabo4)
"Bitcoin .. needs .. a secondary level of payment[s] which is lighter weight." -- Hal Finney 2010 https://t.co/tIbkVF2ezc ht @rextar4444
Retweets
350
Likes
825
 Twitter
https://www.coindesk.com/the-code-for-an-anonymous-lightning-network-is-now-live/
The Code for an Anonymous Lightning Network is Now Live - CoinDesk
A private version of the crypto protocol lightning network is headed to zcash, with the potential it could be added for other blockchains soon.
 
__ https://medium.com/coinmonks/the-lightning-network-how-to-install-and-hopefully-make-money-6e3058e3fa categories: ["Crypto"] ----------------------------------------------- (edited)
https://medium.com/@stadicus/perfect-low-cost-%EF%B8%8Flightning%EF%B8%8F-node-4c2f42a4ff7b
The perfect Bitcoin ⚡️Lightning️⚡ node – Stadicus – Medium
This page is no longer maintained. Please check out the latest and enhanced version of this guide on Github:
 
https://medium.com/@timevalueofbtc/the-bitcoin-second-layer-d503949d0a06
The Bitcoin Second Layer – Nik Bhatia – Medium
The Lightning Network Reference Rate, Part 1 of 4
 
http://lightningnetworkstores.com/
https://github.com/bcongdon/awesome-lightning-network
bcongdon/awesome-lightning-network
awesome-lightning-network - ⚡ A curated list of awesome Lightning Network projects for developers and crypto enthusiasts
 
v
https://lnroute.com/ — Lightning Network resources(edited) https://dev.lightning.community/resources/
Lightning Resources
Developer resources and documentation for the Lightning Network Daemon.

⧉infominer 28-Aug-18 03:51 PM
https://coincenter.org/entry/making-sense-of-lightning-network-nodes-and-money-transmission-licensing
Making sense of Lightning network nodes and money transmission lic...
An update on Coin Center’s work to avoid unnecessary regulatory burdens on technologists.
 

⧉infominer 30-Aug-18 07:08 PM
https://twitter.com/danheld/status/1033044447842336768

Dan Hedl (@danheld)
1/ A complete debunking of top Lightning FUD claims:
Retweets
403
Likes
917
 Twitter

⧉infominer 30-Aug-18 07:46 PM
https://the-lightning-times.ongoodbits.com/2018/08/27/issue-2
The Lightning Times - Issue #2

⧉infominer 04-Sep-18 12:27 AM
https://twitter.com/fulmolightning/status/1035183579196743680

Fulmo ⚡ (@fulmolightning)
Get ready to rumble! The latest batch of 20 #RaspiBlitz, a full #Bitcoin and #LightningNetwork node running on a Raspberry Pi, is ready to be picked up and plugged in at the #LightningHackday! If you can't attend in person, you can build one yourself: https://t.co/b6GaqoPL...
Retweets
164
Likes
533
 
 Twitter

⧉infominer 04-Sep-18 09:28 PM
https://store.casa/lightning-node/
Casa Lightning Node
Simple, easy to use Lightning Network node
 

⧉infominer 13-Sep-18 09:10 AM
https://blog.lightning.engineering/posts/2018/05/30/routing.html

⧉infominer 17-Sep-18 12:07 AM
https://twitter.com/stephanlivera/status/1028079725460111360

Stephan Livera (@stephanlivera)
SLP9 - Lightning UX and Routing, with @bvu VP, Product of @lightning We discuss: - Lightning User Experience - Lightning Routing - Benefits for users, merchants and exchanges - Autopilot, watchtowers, AMP, splicing listen, subscribe, share! https://t.co/QJAIJezOks
Likes
138
 Twitter

⧉infominer 17-Sep-18 12:15 AM
https://medium.com/casa/announcing-the-casa-lightning-node-596df7a7427
Announcing the Casa Lightning Node – Casa Blog – Medium
The easiest way to use Lightning available today.
 

⧉infominer 23-Sep-18 12:47 AM
https://twitter.com/Ragnarly/status/1039113181023490050

𝑅𝑎𝑔𝑛𝑎𝑟 𝐿𝑖𝑓𝑡ℎ𝑟𝑎𝑠𝑖𝑟 🏴 (@Ragnarly)
Some of the best tools in bitcoin have been built by without raising capital from VCs: @BtcpayServer, @SamouraiWallet, @OPENDIME and @COLDCARDwallet, and most software wallets. Did I miss any?
Likes
189
 Twitter
https://zigzag.io/#/
ZigZag - lightning enabled crypto exchange
Exchange Top Cryptocurrencies in seconds with low fees
 

⧉infominer 30-Sep-18 11:25 PM
https://nbitstack.com/c/btcpayserver
BTCPayServer
Anything related to the free, open-source .NET cryptocurrency payment processor BTCPayServer.
 
https://github.com/Stadicus/guides/blob/master/raspibolt/README.md
Stadicus/guides
Cryptocurrency guides by Stadicus. Contribute to Stadicus/guides development by creating an account on GitHub.
 

⧉infominer 12-Oct-18 01:00 PM
https://www.forbes.com/sites/francescoppola/2018/10/11/blockstreams-new-solution-to-bitcoins-liquidity-problem-looks-oddly-familiar/#3484b491e51a
Blockstream's New Solution To Bitcoin's Liquidity Problem Looks Od...
Blockstream's Liquid sidechain purports to be an innovative solution to Bitcoin's chronic illiquidity. But it inadvertently replicates something with which we are all too familiar.
 

⧉infominer 04-Nov-18 01:32 PM
https://bitcoinmagazine.com/articles/blockstreams-liquid-network-high-value-bitcoin-payments-live/
Blockstream’s Liquid Network for “High Value” Bitcoin Paymen...
Blockstream’s COO Samson Mow explains how “Liquid is designed to facilitate fast and reliable high value transfers” of bitcoin (and other cryptocurrencies -- eventually.)
 

⧉infominer 09-Dec-18 03:28 AM
https://twitter.com/Beautyon_/status/1062100915925213185

Beautyon (@Beautyon_)
SUPER INTERESTING: "The https://t.co/yDMDqgCKyl platform provides tooling, apps & services on top of any bip32 compatible Bitcoin wallet. It's a service layer on top of the Bitcoin network, offering powerful utilities for users and/or developpers." https://t.co/uofRClqm4v
 Twitter

⧉infominer 23-Dec-18 01:55 AM
https://shea.io/lightning-in-2018
Lightning in 2018
Below is an archived and reformatted tweetstorm from Nov 29, 2018. Enjoy! #1 Lightning Network is on fire lately 12500 channels (up 3…
 

⧉infominer 23-Dec-18 02:56 AM
https://twitter.com/JWWeatherman_/status/1069232488604729344

JW Weatherman | mathbot.com (@JWWeatherman_)
#rsk #rootstock https://t.co/dmwA7j7U3K Is still planning to introduce a security flaw they call “drive chains” If they get enough fools to put bitcoin on this flawed side chain it will resulting a massive theft of #bitcoin Defend bitcoin by alerting people of the ...
 Twitter

⧉infominer 23-Dec-18 03:21 AM
https://stephanlivera.com/episode/37
Stephan
SLP37 Rene Pickhardt – Bitcoin Lightning Education & Lightning S...
Rene Pickhardt, a Bitcoin/Lightning educator, and rising star in the world of Lightning joins me to talk about the Lightning Network. We discuss: How he got into Lightning Involvement in the Pirate…
 

⧉infominer 23-Dec-18 06:00 AM
https://bitcoinshirt.co/how-to-create-store-accept-bitcoin
How to Create an Online Store & Accept Bitcoin - Step By Step Guid...
Learn how to build an online e-commerce store and accept Bitcoin payments with no coding or web-designing skills required. Using free and open-source software: WordPress, WooCommerce and BTCPay. No steps skipped and video tutorials.
 

⧉infominer 24-Dec-18 12:58 AM
https://www.coindesk.com/blockstream-boosts-bitcoin-satellite-service-with-lightning-payments

⧉infominer 24-Dec-18 01:14 AM
https://medium.com/@melik_87377/lightning-network-enables-unicast-transactions-in-bitcoin-lightning-is-bitcoins-tcp-ip-stack-8ec1d42c14f5
Lightning Network enables Unicast Transactions in Bitcoin. Lightni...
It has recently come to my attention that there is a great deal of confusion revolving around the Lightning Network within the Bitcoin and…
 
https://twitter.com/realLudvigArt/status/1037592389529919488

Melik Manukyan ⚡️ ludvigart.com (@realLudvigArt)
1)I am seeing an increasing number of people under the impression that #lightning as an overlay bridge network for #blockchains (via atomic swaps) is a great thing for alts. And they can not be more wrong. In reality, Lightning is where #altcoins will come in droves only...
Likes
244
 Twitter

⧉infominer 25-Dec-18 02:05 PM
https://twitter.com/sdlerner/status/1075506026114371584?s=12

Sergio Demian Lerner 'not giving away Eth' (@SDLerner)
After reading @AaronvanW 's excellent review of Bitcoin and @RSKSmart growth in 2018, I decided do provide actual statistics of RSK growth in 2018 .. so here is the tweet thread !
Likes
109
 Twitter

⧉infominer 23-Jan-19 12:36 AM
https://medium.com/lightning-power-users/bitcoin-lightning-joule-chrome-extension-ac149bb05cb9
Bitcoin Lightning Joule Chrome Extension – Lightning Power Users...
Lightning Joule is an awesome Chrome plugin being developed by William O'Beirne, check out his presentation at the Chaincode Labs…
 

⧉infominer 05-Feb-19 06:45 PM
https://www.scipioerp.com/2018/12/12/is-lightning-ready-for-commerce/
paul
Is the Lightning network ready for commerce?
We have been experimenting with Lightning (Bitcoin) payments. But is it ready for commerce applications? Here's what we think...
 

⧉infominer 12-Feb-19 04:29 PM
https://twitter.com/alexbosworth/status/1078353292768403456

Alex Bosworth ☇ (@alexbosworth)
Ways I can tell LN routing is not a mature market yet: - I’m charging 25x more than anyone and routing more than ever before - The largest capacity owner assigns capacity at random - Almost no one charges any fees at all for routing - Most public nodes aren’t even reli...
Likes
258
 Twitter
https://twitter.com/timevalueofbtc/status/1078337607493332992

Nik Bhatia (@timevalueofbtc)
Recent interviews given by @roasbeef @bitconner and tweets by @alexbosworth confirm my initial theory about the potential for operating a profitable Lightning node: payment channel management skill is the primary driver of profits. Merely staking capital ensures nothing.
 Twitter
https://lists.linuxfoundation.org/pipermail/lightning-dev/2018-December/001752.html

⧉infominer 12-Feb-19 05:22 PM
https://twitter.com/vandrewattycpa/status/1079471260978040833

Jeff Vandrew Jr Attorney+CPA (@vandrewattycpa)
Today I released LibrePatron, an alternative to Partreon backed by @BtcpayServer. Most Patreon alternatives don't implement the full Patreon feature set. This seeks to change that. Sample site (alpha not mobile responsive, mobile coming soon!): https://t.co/ZcHDjUfBfe T...
Retweets
245
Likes
633
 Twitter
https://lightninglayer.com/
https://twitter.com/abrkn/status/1079116127542726656

Andreas Brekken (@abrkn)
Explained why I took my LN hub down. Every maximalist attacked me, without reading my review Asked how to add LN as a payment option for my startup. No one replied This is why https://t.co/sSd1kvBX49 exists. We prove that no one is using what they shill. But I do. https:...
Likes
269
 Twitter

⧉infominer 16-Feb-19 08:07 PM
https://github.com/Blockstream/liquid
Blockstream/liquid
Liquid daemon and cli. Contribute to Blockstream/liquid development by creating an account on GitHub.
 

⧉infominer 21-Feb-19 06:00 PM
https://twitter.com/xentagz/status/1098702643969564672?s=12

Dennis Parker⚡️ (@Xentagz)
Easiest #Bitcoin Lightning Guide! https://t.co/TaSTxlsM2q
 Twitter