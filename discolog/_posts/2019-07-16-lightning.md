---
title: "Practical Lightning: Wallets, Applications, Guides and Development"
description: This page is for collecting and organizing information related to using the Lightning Network.
toc_sticky: false
excerpt: Links to code, howtos, and other resources related to practical use of Lightning.
permalink: blog/Bitcoin/lightning/
published: false
header:
  image: "https://imgur.com/QjmwITb.png"
categories: ["crypto"]
tags: ["bitcoin","lightning"]
last_modified_at: 2019-07-16T11:22:33-23:00

---


* [Pierre Rochard [⚡️] (@pierre_rochard)](https://twitter.com/pierre_rochard/status/1055159992733626368)
  >The LND node software now runs from within the Excel plugin. With neutrino, that means that a Windows + Excel user can be making and receiving LN payments with a few clicks. https://t.co/qeP2dCJSqp
* [Will O'Beirne (@wbobeirne)](https://twitter.com/wbobeirne/status/1131989707389329408?s=12)
  >Need plans for the long weekend? Why not get started on making your own Lightning App! Over the next couple of weeks I'll be posting a 5 part series on building a modern web app that takes lightning payments, and how to host it securely. https://t.co/gDsAAUKrnj
* [Bitcoin Lightning Network:Resource and Information Guide](https://lnroute.com)

## [lopp.net - Lightning Network Resources](https://www.lopp.net/lightning-information.html) ([source](https://github.com/jlopp/lopp.net/blob/master/lightning-information.html))



## [**LNRoute -Setup and Tutorials**](https://lnroute.com/setup-tutorials/)
* [Pierre Rochard’s Bitcoin and Lightning Node Launchers](https://github.com/PierreRochard/node-launcher) - Windows /macOS Bitcoin / Lightning executables.
* [Setup Tutorial for Windows](https://medium.com/@jadmubaslat/bitcoin-lightning-network-node-easy-setup-tutorial-for-windows-desktop-users-a-how-to-guide-9937b5a8a669)
* [ZAP Wallet setup for Windows (video)](https://www.youtube.com/watch?v=w3PGlgiM0ZQ)
* [Run your own Lightning Node](https://medium.com/@dougvk/run-your-own-mainnet-lightning-node-2d2eab628a8b)
* [Setup LND 0.4 beta and bitcoind on Ubuntu 16.04](https://gist.github.com/bretton/0b22a0503a9eba09df86a23f3d625c13)
* [setup C-lightning on Debian, with or without TOR (french)](https://www.crypto-lyon.fr/setup-lightning-node-bitcoin.html)
* [Setting up an LTC lightning node on MAC](https://gist.github.com/ecurrencyhodler/f6da7f26110c875e7fa41a91c66b72a1)
* [How to build your own portable plug-in Lightning node!](https://blockstream.com/2018/04/21/portable-lightning-node-tutorial.html)

## [**LNRoute -Explorers and Statistics**](https://lnroute.com/explorers-and-statistics/)  ([Forget Statistics, Reality is Better](https://lnroute.com/2018/09/forget-lightning-statistics-reality-is-even-better/))

Lightning Node Match – maximize te number of nodes reached in a minimum number of hops.
* [www.moneni.com/mcb/nodematch](https://www.moneni.com/mcb/nodematch)

### Lightning Stats
* [p2sh.info/dashboard/db/lightning-network](https://p2sh.info/dashboard/db/lightning-network)
* [lightningpeach.com/ln-monitor](https://lightningpeach.com/ln-monitor)
* [bitcoinvisuals.com/lightning](https://bitcoinvisuals.com/lightning)



### Mainnet Explorers
* [explorer.acinq.co](https://explorer.acinq.co/)
* [explore.casa](https://explore.casa/)
* [graph.lndexplorer.com](https://graph.lndexplorer.com/)
* [lightning.chaintools.io](https://lightning.chaintools.io/)
* [bitcoinvisuals.com/lightning](https://bitcoinvisuals.com/lightning)
* [www.robtex.com/lightning/node](https://www.robtex.com/lightning/node/)
* [lnmainnet.rompert.com](https://lnmainnet.rompert.com/)
* [bitcoinexchangerate.org/lightning](https://bitcoinexchangerate.org/lightning)
* [1ml.com](https://1ml.com/)
* [lightblock.me](http://lightblock.me)

## Raspberry - SBCs

* [Beginner’s Guide to Lightning️ on a Raspberry Pi](https://github.com/Stadicus/guides/blob/master/raspibolt/README.md)
* [Fulmo ⚡ @fulmolightning](https://twitter.com/fulmolightning/status/1035183579196743680)
  >Get ready to rumble! The latest batch of 20 #RaspiBlitz, a full #Bitcoin and #LightningNetwork node running on a Raspberry Pi, is ready to be picked up and plugged in at the #LightningHackday! If you can't attend in person, you can build one yourself: 
  - https://github.com/rootzoll/raspiblitz
  ![](https://imgur.com/edaW3pO.png)
* [Bitcoin Core + LND 0.4 Beta (mainnet) Installer for Raspberry](https://github.com/jochemin/raspnode)


## LN Wallets

* [lnwallet.io](https://lnwallet.io/)
* [bitlum.io](https://bitlum.io/?utm_source=lnroute.com) - Bitlum Chrome Extension Wallet
  >The wallet referral system will allow you to onboard new people in Lightning within 3 minutes, by giving them a free $0.1 bonus on registration, so that they can try the Lightning Network even without having Bitcoin.

### [lnroute.com/desktop-wallets/](https://lnroute.com/desktop-wallets/)

**Lightning Desktop App** by [Lightning Labs](https://github.com/lightninglabs)
* [lightninglabs/lightning-app](https://github.com/lightninglabs/lightning-app)
* [The New Lightning App]https://blog.lightning.engineering/announcement/2018/09/10/lightning-app.html) -10 Sep 2018
  >Today we’re excited to announce the release of the new version of our Lightning desktop app. This release includes a complete redesign and optimized backend targeted toward light clients.
* [ZAP Wallet for Desktop and Mobile](https://zap.jackmallers.com/)
* [Spark GUI for c-lightning](https://medium.com/@notgrubles/spark-a-new-gui-for-c-lightning-2cf2f024500c) by Nadav Ivgi 
  * [shesek/spark-wallet](https://github.com/shesek/spark-wallet)
* [Eclair Wallet for Android](https://github.com/ACINQ/eclair-wallet) by ACINQ
Lightning MacOS GUI Wallet by Alex Bosworth
  * [alexbosworth/lnd-gui](https://github.com/alexbosworth/lnd-gui)
* [LightningPeach Wallet](https://lightningpeach.com/peach-wallet) by Lightning Peach
* [darosior/c-simple](https://github.com/darosior/c-simple)

### [LNRoute.com/mobile-wallets/](https://lnroute.com/mobile-wallets/)
 >Some wallets also require you to run your own lightning full-node.

* [ACINQ/eclair-wallet](https://github.com/ACINQ/eclair-wallet) Android
* [bitcoin lightning wallet](http://lightning-wallet.com/) Android
* [rawtx](https://rawtx.com/) Android iOS
* [swiftlightning.io](https://www.swiftlightning.io/) iOS
* [neogeno/shango-lightning-wallet](https://github.com/neogeno/shango-lightning-wallet) -Android iOS
* [Cipherbook](https://www.cryptotec.com/cipherbook/)
* [CoinOS](https://coinos.io/) Android
* [shocknet.github.io](https://shocknet.github.io/) -Own full-node
* [marzig76/fulmo](https://github.com/marzig76/fulmo) -Fulmo Own full-node
* [https://zap.jackmallers.com/](https://zap.jackmallers.com/) iOS Own full-node
* [bluewallet.io](https://bluewallet.io/) -iOS
* [shesek/spark-wallet](https://github.com/shesek/spark-wallet) -Android Own full-node
* [breez.technology](https://breez.technology/) -Android Neutrino
* [WalletOfSatoshi](https://www.walletofsatoshi.com/) - Android iOS
* [Hoo Wallet](https://hoo.com/)- Android iOS Own full-node
* [darosior/c-simple](https://github.com/darosior/c-simple)
c-simple Android
* [Mobile LN](https://play.google.com/store/apps/details?id=com.mobileln) Android
* [zeusln.app](https://zeusln.app/)
Zeus Android iOS Own full-node
* [muun.com](https://muun.com/)
Muun Wallet Android 

### [LNRoute.com/category/wallets/online-wallets](https://lnroute.com/category/wallets/online-wallets/)

* [Bottle](https://bottle.li) -Bottle uses the Lightning Network andSocial networks to help make Bitcoin accessible for everyone.
* [tippin.me](https://tippin.me)
* [lnwallet.io](https://lnwallet.io/)

### [LNRoute.com/category/wallets/wallet-tools/](https://lnroute.com/category/wallets/wallet-tools/)
	
* [Lightning Mainnet Faucet](https://light.yuyaogawa.com/faucet/) - A lightning faucet where you can claim an invoice of 200 sats. Maximum one claim per day.
* [Submarine Swap Tool](https://submarineswaps.org/)
* [Lightning Payment Request Decoder](https://lndecode.com/)
  >For decoding lightning network payment requests as defined in BOLT #11
* [Lightning Decoder](https://lightningdecoder.com/) - Another online tool to decode Lightning Network Invoice (BOLT11)
* [Lightning Singles](https://singles.shock.network/)


## [**LNRoute -Implementations**](https://lnroute.com/category/implementations/)

* [nayuta.co](https://nayuta.co/) - [github.com/nayutaco](https://github.com/nayutaco)
  >Ptarmigan by Nayuta Co is a 4th Lightning implementation,
   focused on the Internet of Things.
* [bitcoinvisuals.com/lightning](https://bitcoinvisuals.com/lightning) -Bitcoin Visuals Lightning Statistics
* [github.com/janoside/lnd-admin](https://github.com/janoside/lnd-admin)
  >Admin UI for LND. See https://lnd-admin.chaintools.io/ for an example.
* [github.com/bitromortac/lndmanage](https://github.com/bitromortac/lndmanage)
  >Control tool for lightning network daemon (lnd) node operators, optimized for remote control.
* [joltfun.com](https://joltfun.com/)
  >Joltfun
* [thecryptocloak.com](https://thecryptocloak.com/)
  >CryptoCloaks
* [www.moonstuff.co](https://www.moonstuff.co/)
  >moonstuff
* [singles.shock.network](https://singles.shock.network/)
  >Lightning Singles
* [www.mocacinno.com/lightning](https://www.mocacinno.com/lightning/)
  >Image Unblurrer
* [www.btcduke.com](https://www.btcduke.com/)
* [zigzag.bitlum.io](https://zigzag.bitlum.io)
* [www.opennode.co](https://www.opennode.co/)
* [globee.com](https://globee.com/)
* [coingate.com/lightning-network](https://coingate.com/lightning-network)
* [strike.acinq.co](https://strike.acinq.co/)
* [lightninginabox.co](https://lightninginabox.co/)
* [btcwonderland.com](https://btcwonderland.com)
* [lndlife.com](https://lndlife.com)
* [www.excellion.com](https://www.excellion.com)
* [bitcoin-lightning.de](https://bitcoin-lightning.de)
* [torguard.net](https://torguard.net/)
* [hodlmonkey.com](https://hodlmonkey.com/)
* [coincards.ca](https://coincards.ca)

## LN Payments

* [github.com/btcpayserver](https://github.com/btcpayserver)
* [github.com/lightningd/plugins/tree/master/autopilot](https://github.com/lightningd/plugins/tree/master/autopilot)
  >The C-Lightning plugin repository received an autopilot plugin that can help users choose one or more channels to open to start sending LN payments. The plugin is based on an earlier PR to the main C-Lightning codebase.
* [www.opencart.com](https://www.opencart.com/)
  >A free payment gateway for Bitcoin Lightning Network for store owners who use OpenCart and have their own LN node.
* [lndecode.com](https://lndecode.com/)
  >For decoding lightning network payment requests as defined in BOLT #11
* [www.bitrefill.com](https://www.bitrefill.com/)
  >Buy 30+ Vouchers, refill your phone and pay your bills with Lightning.
* [lightningjoule.com](https://lightningjoule.com/)
  >Bring the power of lightning to the web with in-browser payments and identity, all with your own node. Available for Chrome, Firefox, Opera and Brave.
* [cryptochill.com](https://cryptochill.com/)
  >Bitcoin and Lightning Network payment gateway focused on security, customizability and simple integration.
* [buyabeerwithlightning.com](http://www.buyabeerwithlightning.com/) - zap POS implementation
  >Zap is developing Point of Sale solutions for the Lightning Network. Check out this site for a demonstration.

### Merchant Tools


* [BTCPay (self hosted payment processor)](https://github.com/btcpayserver/btcpayserver)
* [CoinGate](https://coingate.com/)
* [CryptoChill](https://cryptochill.com/)
* [FileBazaar (sell digital files)](https://github.com/ElementsProject/filebazaar)
* [GloBee](https://globee.com/)
* [Lightning Charge](https://github.com/ElementsProject/lightning-charge) (merchant solution for c-lightning)
* [Lightning Collect](https://lightningcollect.com/) (payment processor)
* [LNWallet](https://lnwallet.io/)
* [Nano PoS](https://github.com/ElementsProject/nanopos) (for Lightning Charge)
* [OpenNode](https://www.opennode.co/)
* [Python Strike library](https://github.com/JASchilz/pystrike)
* [Strike](https://strike.acinq.co/) (Stripe-like API)
* [WooCommerce gateway](https://github.com/ElementsProject/woocommerce-gateway-lightning)
* [OpenCart Payment Gateway](https://www.opencart.com/index.php?route=marketplace/extension/info&extension_id=36414) (for LND node)



### Tips

* [BitPatron](https://bitpatron.co/)
* [Lightning Gifts](https://lightning.gifts/) (add tipping to web pages)
* [LNTipBot](https://www.reddit.com/r/lntipbot/wiki/index) (reddit)
* [nanotip](https://github.com/ElementsProject/nanotip) (for c-lightning)
* [Slack Tipbot](https://github.com/CryptoFR/ln-tip-slack)
* [tippin.me](https://tippin.me) (twitter tips)


## LN Marketplace

[Accept Lightning store list/map](https://acceptlightning.com/)
[Lightning Network Stores](http://lightningnetworkstores.com/)
[LNRoute store list](https://lnroute.com/category/implementations/stores/)
[Messari merchant list](https://messari.io/resource/lightning-network#heading-6)

* [store.casa/lightning-node](https://store.casa/lightning-node/) -Casa Lightning Node
* [funraiden.com](https://funraiden.com/)
  >Funraiden offers cool and geeky products from collectibles to stickers and merch, payed with Bitcoin/Lightning.
* [crypto-coffee.org](http://crypto-coffee.org)
  >Buy coffee and stickers with Lightning
* [bitcointunnels.com](https://www.bitcointunnels.com/)
  >Bitcoin and Lightning merchandise
* [shop.energy-kitchen.ch/#/shop](https://shop.energy-kitchen.ch/#/shop)
  >energyKitchen
* [www.empowermindbodylife.com/shop](https://www.empowermindbodylife.com/shop/)
* [store.blockstream.com/shop](https://store.blockstream.com/shop/) -Blockstream Lightning Store
* [www.cryptoidshop.com](https://www.cryptoidshop.com/)
* [vapecrypto.com/shop](https://vapecrypto.com/shop)
  >Providing the best prices on authentic Vape Gear, Juices and Accessories. We’re your one stop shop for vape gear
* [hipptee.com](https://hipptee.com/)
  >Bitcoin T-shirt
* [neverfiat.com](https://neverfiat.com/)
  >NeverFiat Crypto Marketplace
* [bitcoinshirt.co](https://bitcoinshirt.co/)
* [www.travelbybit.com](https://www.travelbybit.com)
  >We help travellers explore the world using cryptocurrency. Lightning payments are accepted.
* [internetsuper.store](https://internetsuper.store)
  >Bitcoin online store that accepts Lightning payments
* [satoshis.pictures](https://satoshis.pictures/)
  >Experience the power of the lightning network by advertising your products and solutions in satoshis.pictures
* [lnsh.pw](https://lnsh.pw/)
  >Lightning Shell allows you to get root access to a Docker container for just 42 satoshis per hour . Pay with Lightning and get access to a shell with 200MB RAM, 0.5 CPU and up to 200MBit/s network connection!
* [www.coinmall.com](https://www.coinmall.com/)
* [lightning-space.com/get-space](https://lightning-space.com/get-space/)
  >Buy webspace with Bitcoin Lightning. You will receive the specified amount of SSD-webspace for the specified amount of days. Included is PHP 7.2, a MySQL (MariaDB) database, SSH and FTP access and an email address (username@lightning-space.com)
* [cryptoho.st](https://cryptoho.st/)
  >Bitcoin and LN powered Virtual Private Server (VPS) store
* [bosstalgia.com](https://bosstalgia.com)
  >Bosstalgia Medicinals (@bosstalgia) is the first Canadian Company to accept payments on the Bitcoin Lightning network.
* [ln.pizza](https://ln.pizza/)
  >Order Domino’s Pizza via the Lightning Network from anywhere in the US. Get 5% off when paying with Lightning!
* [www.hodlgang.store](https://www.hodlgang.store/)

## LN Earn

* [www.lndwork.com](https://www.lndwork.com/)
  >Lightning Tasks
* [microlancer.io](https://microlancer.io/)
  >Earn bitcoin with microtasks
* [proofofplays.hopto.org](https://proofofplays.hopto.org/)
  >A platform for content creators to showcase their videos and get paid satoshis.
* http://light-tube.surge.sh/ - Videos w lightning rewards
* [tallyco.in](https://tallyco.in/)
  >Bitcoin and Lightning fundraising platform. Create crowdfunding campaigns for your project and get funded by fellow bitcoiners!

### LN Faucet
* [light.yuyaogawa.com/faucet](https://light.yuyaogawa.com/faucet/)
  >A lightning faucet where you can claim an invoice of 200 sats. Maximum one claim per day.

## Testnet

* [Bitcoin Testnet Lightning Network Faucet – Receive tBTC via Lightning](https://faucet.lightning.community/)
* [lnroute.com/shop](https://lnroute.com/shop/)
* [lnd-testnet-2.mably.com](https://lnd-testnet-2.mably.com/) -Testnet Slack Tipping Bot
* [testnet.lightninggem.com](https://testnet.lightninggem.com/)
  >Testnet Lightning Gem Game
* [1ml.com/testnet](https://1ml.com/testnet/) -Explorers
* [testnet.satoshis.place](https://testnet.satoshis.place/)
  >Testnet Satoshi’s Place
* [starblocks.acinq.co/#](https://starblocks.acinq.co/#/)
  >Testnet Starblocks Coffee Shop
* [lnroute.com/shop](https://lnroute.com/shop/)
  >Testnet LNROUTE Tea Store
* [CoinClip](https://itunes.apple.com/us/app/coinclip-testnet/id1372927440) iOS


### LN Exhange / Signals / API

* [cryptoally.io](https://cryptoally.io/)
  >CryptoAlly.io is a place to discover quotes of Satoshis and Bitcoin in 100+ currencies at real time. The value transfer of Satoshis is powered by Lightning Network.
* [crypto.slamtrade.com](https://crypto.slamtrade.com/)
  >24/7 streaming of high-performance Crypto-Currency trading signals presented in a single view for professional trading. Find out where to buy/sell or when to buy/sell at any point in time in seconds. Also discover liquidity, market making, and arbitraging opportunities.
* [boltz.exchange](https://boltz.exchange/) ([*](https://medium.com/boltzhq/announcing-the-first-boltz-release-6cb630701432))
  >An instant, account free, and non-custodial digital asset exchange built on top of the lightning network.
* [suredbits.com](https://suredbits.com) - NFL, NBA and Crypto API’s -Use of API charged via Lightning Network per call or streaming period.
  >Suredbits’ Lightning App API allows you to query NFL, NBA and Crypto Exchange data. Their NFL and NBA APIs offer multiple channels including teams, players, games, scores, and statistics. Their Crypto Exchange API allows you to stream data on Trades, Tickers and Order Books.
* [www.zebpay.com](https://www.zebpay.com/)
  >App-enabled cryptocurrency exchange and wallet provider, Zebpay, has announced that it is enabling Lightning Network payments for all its users. Zebpay claim that it will even pay the fees for Lightning transactions made through its wallet.


### LN Social

* [lightningwall.tips](http://lightningwall.tips)
  >Post public messages on the wall and receive satoshis from people who like your message.
* [salttie.com](https://salttie.com/)
  >Micro Blogging Platform
* [bottle.li](https://bottle.li)
  >Bottle uses the Lightning Network andSocial networks to help make Bitcoin accessible for everyone.
* [mainnet.yalls.org](https://mainnet.yalls.org/)
  >Read and write articles, with Lightning Network micropayments.
* [limichat.herokuapp.com](https://limichat.herokuapp.com/)
  >Limichat is a chat application that limits messages based on payment via Lightning. Sending a message gets cheaper over time, but doubles when someone pays, resulting in one message per ~10 min!
* [blockclock.live](https://blockclock.live/)
  >A Block Clock powered by the Lightning Network. You can send a lightning payment to write a message on the BlockClock that is being live streamed on Twitch!
* [kriptode.com/satsforlikes/index.html](https://kriptode.com/satsforlikes/index.html)
  >Pay people to like your tweets or follow you.
* [lncast.com](https://lncast.com/#!/)
  >Lightning Network Podcasts
* [cointippy.com](https://cointippy.com/)
  >CoinTippy helps you reward content on Reddit, Twitter, Telegram and Twitch with cryptocurrencies



### LN Art
* [satoshis.place](https://satoshis.place/)
  >collaborative artboard. Inspired by Reddit Place, and the Million Dollar Homepage. There are 1 million pixels on the canvas and each pixel costs 1 satoshi to paint. Pixels can be painted over indefinitely. Satoshi’s Place is a great way to experience the power of micro-transactions through the Bitcoin Lightning Network.
* [trustedcoins.co.uk/sweetsugarleaf](https://trustedcoins.co.uk/sweetsugarleaf/)
  >Cute Cannabis themed artwork by a Medical Marijuana advocate in the UK
* [ludvigart.com](https://ludvigart.com/) -Bitcoin Art



### LN Music

* [moifay.online](https://moifay.online/)
  >Official release of first ever Music Album of Moifay, sold online for #Lightning $BTC. Each song is $1 only.
* [modularsynth.fun](https://modularsynth.fun) -Audo Samples
* [sogbazaar.com](https://sogbazaar.com)

### LN WordPress

* [github.com/rstmsn/lnd-for-wp](https://github.com/rstmsn/lnd-for-wp) -WordPress plugin for managing & using your LND node
  - manage your LND node from your WordPress admin panel
  - fully functional wallet interface 
  - send / recieve funds with ease
  - responsive UI adapts to fit any web enabled desktop, tablet or mobile device. 
  - Search Lightning Network graph, manage peer connections, open & close channels with ease. 
  - QR support
  - WordPress ‘shortcodes’, embed LND functionality directly in your pages and posts.
* [wordpress.org/plugins/btcpay-for-woocommerce](https://wordpress.org/plugins/btcpay-for-woocommerce/)
  >BTCPay Server is a free and open-source cryptocurrency payment processor which allows you to receive payments in Bitcoin and altcoins directly, with no fees, transaction cost or a middleman.
* [wordpress.org/plugins/opennode-for-woocommerce](https://wordpress.org/plugins/opennode-for-woocommerce/)
  >This plugin allows stores that use WordPress WooCommerce shopping cart system to accept Bitcoin and Bitcoin through Lightning Network via OpenNode.
* [wordpress.org/plugins/lightning-publisher/#description](https://wordpress.org/plugins/lightning-publisher/#description)
  * [github.com/ElementsProject/wordpress-lightning-publisher](https://github.com/ElementsProject/wordpress-lightning-publisher)
    >Lightning Publisher for WordPress is developed by Blockstream and allows you to offer previews of your blog posts and require a Lightning Network payment to release the rest.

### LN Shopify

* [mailchi.mp/cf60f9bb7278/opennode-can-now-be-used-on-shopify](https://mailchi.mp/cf60f9bb7278/opennode-can-now-be-used-on-shopify)
  >Opennode released a plugin for Shopify that allows you to accept Bitcoin and Bitcoin Lightning payments.


### LN Games

* [www.luckythunder.com/#](https://www.luckythunder.com/#/)
  >LuckyThunder is a slot machine built on top of the bitcoin lightning network. No login required, provably fair, high win percentage.
* [medium.com/@BR_Robin/a-bitcoin-lightning-network-powered-rpg-penguinshooter-6d36cc34de0c](https://medium.com/@BR_Robin/a-bitcoin-lightning-network-powered-rpg-penguinshooter-6d36cc34de0c) - Penguin Shooter -A Bitcoin Lightning Network powered RPG
* [lightningscratchcard.io](https://lightningscratchcard.io/)
  >Pay Satoshis with Lightning Network to scratch letters and help reveal a hidden message. Or post a message yourself and make it attractive so people want to discover.
Oc2 (Off chain On chain https://oc2realm.com/) - India’s first Decentralised Exchange, 0x Relayer and early adopters of Lightning. 
* [lightning.oc2realm.com](https://lightning.oc2realm.com/)
  >To support their vision, they have created a Slot Machine on top of Lightning Network. 
* [miniroulette.lngames.net](https://miniroulette.lngames.net/) -Mini Casino Roulette
  >Lightning Network simple casino roulette game
* [playhammerland.com](https://playhammerland.com/)
  >A role-playing game using Lightning for in-game payments
* [koalastud.io](https://koalastud.io/) -Koala Studio’s first game is Lightning Powered online Chess
* [satoshis.games](https://satoshis.games/)
Another series of games that use the Lightning Network
* [lngames.net](https://lngames.net/) -Several games to experience the use of the Lightning Network.
* [kriptode.com](https://kriptode.com/) -A series of Lightning Apps and Games. Three Card Monte, Receive SMS, LN Hunt, MicroMine, Scratch and Win and Backgammon
* [lightning-casino.com](https://lightning-casino.com/) -Another Lightning Network powered Slot Machine
* [www.lightningslotmachine.com](https://www.lightningslotmachine.com/) -A Lightning Network powered Slot Machine
* [microbet.fun](https://microbet.fun/)
  - prediction and betting game
  - make a prediction about sports events or back/lay the others players bets
  - backers or layers get all satoshis divided equally amongst each participant.
* [www.lightningspin.com](https://www.lightningspin.com/)
  >Lightning Spin is a bitcoin gambling game that lives on top of the Lightning Network. It’s a simple yet exciting game – enter your wager, select a multiplier and spin the wheel. If the wheel lands on your target multiplier, you win!
* [lightninggem.com](https://lightninggem.com/)
  >The Lightning Gem is a fun game as well as an exercise in psychology. You can think of it as a series of speculative bubbles
* [lightning-roulette.com](https://lightning-roulette.com/)
  >Lightning Roulette is another Bitcoin Lightning Network powered online multiplayer game. This LApp uses a provably fair system that enables you to verify each spin result and make sure you are not being cheated.
* [lightningflip.xyz](http://lightningflip.xyz)
  >LN coinflipping game
* [www.lightningduel.com](https://www.lightningduel.com/)
  >Provably fair gamble game with instant deposits and withdrawals. A good showcase of the power of the Lightning network.
* [thundersats.com](https://thundersats.com/)
  >Miniature Roulette Game on top of the Bitcoin Lightning Network.
* [unlock.lngames.net](https://unlock.lngames.net/)
  >Open the correct lock and get satoshis
* [rgbslot.lngames.net](https://rgbslot.lngames.net/)
  >Three colors and  three wheels. Simple and different slot machine game.
* [poke.lightningwiki.net](https://poke.lightningwiki.net/)
  >Play Pokémon with your fellow bitcoiners a collaborative gameboy powered by Lightning
* [whereisnakamoto.lngames.net](https://whereisnakamoto.lngames.net/) -The player that finds Nakamoto is awarded 50% of the jackpot.
  >Satoshi Nakamoto is hidden in one of 256 cards of the board. At the beginning of each game, all cards are closed. When Nakamoto is found, the game ends and another begins with all the cards closed again.
* [www.satoshibet.io](https://www.satoshibet.io/)
  >Satoshibet is a provably fair roulette with a trollbox and a tipping bot. Play roulette while talking with fellow players in the chat.
* [satoshi-go-bet.alhur.es](https://satoshi-go-bet.alhur.es/)
  >Satoshi Go Bet is a betting platform for online Go games. Choose any of the live Go games and make bets on the player you think will win.
* [bc.game](https://bc.game)
  >BC.Game is a BlockChain Game platform with provably fair, fast payouts, a free faucet and Lightning Network support. Some of the games available are Crash, Dice and Blackjack.
* [memory.lngames.net](https://memory.lngames.net/)
  >Classical memory game on Lightning. Pair up the 8 different images and if you beat the highscore, you win the jackpot.
* [fortune.lngames.net](https://fortune.lngames.net/)
  >Lightning Wheel of Fortune
