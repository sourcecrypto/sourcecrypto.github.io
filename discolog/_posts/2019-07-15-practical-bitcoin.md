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

I'll try to order this content as a user might progress naturally through the Bitcoin software ecosystem.

1. Wallets
2. Nodes
4. Layer 1 Apps
4. Lightning
5. Lightning Apps
7. Pi
8. Sattelite

For the purposes of the Bitcoin Takeover iteration, I don't expect I'll stray into exchanges or mining, simply for the reduced complexity. 

I plan to keep my commentary as brief as possible, and add guides where they will provide the most value.


## You MUST Do Your Own Research

This is intended to be a starting point for anyone who is interested in using Bitcoin code \ hardware. These guides and tutorials are a great jumping off point, from which you can explore a variety of technologies you may not even have known were available.

Please. Do your own research.

There may be newer materials or advisaries for any of the following projects. Be sure to have a look around for additional information, rather than relying entirely upon this research.

## Primary Sources

* [lopp.net/bitcoin.html](https://lopp.net/bitcoin.html)

**Bitcoin Information & Resources**
  >Bitcoin is a revolutionary system that is quite complex and has a steep learning curve. Below you'll find curated educational resources and information about Bitcoin. You could spend months sifting through them all. Make sure you have a decent grasp of the system before you store a significant amount of value in it! The same aspects of Bitcoin that make it so valuable also make it unforgiving to those who make mistakes.
  * [githbu.com/jlopp/jopp.net](https://github.com/jlopp/lopp.net)

* [bitcoin-only.com](https://bitcoin-only.com)

>For a project to be listed on bitcoin-only it must simply meet the following two requirements;
>1.	Support bitcoin.
>2.	Reject ever supporting altcoins.

## Buying Bitcoin

//Add localbitcoins and bitcoin atms... double check your article about this and add whatever 

* [Bitcoin Savings Plan](https://jlopp.github.io/bitcoin-savings-plan/)
* [bitcoin-only.com/#get-bitcoin](https://bitcoin-only.com/#get-bitcoin)
  * [FastBitcoins](https://fastbitcoins.com/) Buy and Sell Bitcoin	Canada & UK
  * [Cash App](https://cash.app/)	Buy bitcoin with debit card	USA
  * [BullBitcoin](https://bullbitcoin.com/) Non-Custodial Bitcoin Services	Canada
  * [Bittr](https://www.getbittr.com/)	Regular Automated Buying	Europe
  * [Bitonic](https://bitonic.nl/) Buy and Sell Bitcoin	Netherlands
  * [Amber](https://getamber.io/)	Regular Automated Buying (Beta)	Australia

## Earn Bitcoin
* [bitcoin-only.com/#get-bitcoin](https://bitcoin-only.com/#get-bitcoin)
  * [TallyCoin](https://tallyco.in/) [[*](https://bitcoin-only.com/#get-bitcoin)]	Bitcoin Fundraising
  * [jfgi](https://www.jfgi.cc/) [[*](https://bitcoin-only.com/#get-bitcoin)]	Bitcoin Fundraising
  * [LNDwork](https://www.lndwork.com/)	Micro-Freelancing
  * [MicroLancer](https://microlancer.io/) Micro-Freelancing

## Privacy

* [Bitcoin Anonymity Guide 2019: How to use BTC like a straight up G](https://www.coincache.net/2019/01/02/bitcoin-anonymity-guide-2019-how-to-use-btc-like-a-straight-up-g/?v=3e8d115eb4b3)
* [Jolly Roger’s Security Guide for Beginners](https://gir.pub/deepdotweb/jolly-rogers-security-guide-for-beginners/) (oldie but a goodie)
* [Buying and Using Bitcoin Anonymously / Without ID](https://99bitcoins.com/buy-bitcoin/anonymously-without-id/)


## Wallets

[Choose your wallet here](https://btcinformation.org/en/choose-your-wallet) (traditional bitcoinorg style 'choose your wallet')

> * Do not use wallets that don't give you recovery data; these wallets are likely controlling your keys.
> * Do not use paper wallets unless you're an advanced user who understands all the risks.
> * Do not store large amounts of value in single signature wallets.
> * Make sure your heirs know how to recover your wallets without you!
>
>Note that it is NOT recommended that novices use the Bitcoin Core wallet. If you want to use a wallet backed by a fully validating node you run, read [Securing Your Financial Sovereignty](https://blog.lopp.net/securing-your-financial-sovereignty/).

* [https://en.bitcoin.it/wiki/How_to_set_up_a_secure_offline_savings_wallet](https://en.bitcoin.it/wiki/How_to_set_up_a_secure_offline_savings_wallet)


[**bitcoin-only.com - Wallets**](https://bitcoin-only.com/#wallets)

* [Bitcoin Core](https://bitcoincore.org/)	Full node & Bitcoin wallet.	Desktop
* [Samourai Wallet](https://samouraiwallet.com/)	The most feature rich and advanced bitcoin wallet available on Android today.	Android
* [Wasabi Wallet](https://wasabiwallet.io/) 	Privacy focused Bitcoin wallet, that implements trustless coin shuffling	Desktop
* [Electrum](https://electrum.org/#home)	The most feature rich bitcoin desktop wallet available today. 	Desktop & Android
* [Blockstream Green](https://blockstream.com/green/)	Easy to use wallet. Use Google Authentication not Email/Phone.	iOS & Android
* [GreenAddress](https://github.com/greenaddress/WalletElectron/releases/tag/v0.1.04)	Desktop companion to Blockstream Green mobile wallet.	Deskop
* [Muun Wallet](https://muun.com/)	Relatively new wallet with novel multi-sig 2-of-2 spending. 	Android
* [Hodl Wallet](https://hodlwallet.co/)	Relatively new wallet with simple UI.	iOS & Android
* [Armory](https://www.bitcoinarmory.com/)	Cold Storage & Multisig 	Desktop
* [ABCore](http://abco.re/en/releases/)	Bitcoin Core Full Node for Android	Android

[**bitcoin-only.com - Other Hardware**](https://bitcoin-only.com/#hardware)
* [revealer](https://revealer.cc/)	Optical Seed Encryption Tool
* [ColdCard](https://coldcardwallet.com/) Hardware Wallet 
* [Opendime](https://opendime.com/) Bitcoin Bearer Bond
* [Bitpiggys](https://www.bitpiggys.com/)	Piggybank + Opendime

[**lopp.net - Recommended Wallets**](https://www.lopp.net/bitcoin-information/recommended-wallets.html)

A couple wallets which are not *only* used for bitcoin are worth noting, here.

>* Hardware: [Trezor](https://shop.trezor.io/) or [Ledger Nano X](https://shop.ledger.com/pages/ledger-nano-x)
>* Web: [BitGo](https://www.bitgo.com/)
>* Extreme Privacy: [Wasabi](https://wasabiwallet.io/)
>* Extreme Security: [Casa Keymaster](https://keys.casa/keymaster/)

Some of these wallets are very simple to use, however, I will list here the best guides I can find for each of them. Even simple to use wallets can have additional features available to the technically empowered.

### Wallet Guides\Tutorials

[**Electrum**](https://electrum.org/)
  * [Welcome to the Electrum Documentation!](http://docs.electrum.org/en/latest/)
  * [Unofficial guides for Electrum](https://bitcoinelectrum.com)
  * [[Guide] How to Create a Watch-only Wallet (for Electrum)](https://bitcointalk.org/index.php?topic=4573616.0) - great way to safely "watch" the status of your (offline) cold-storage wallet.

[**Paper Wallets**](https://en.bitcoin.it/wiki/Paper_wallet)
  * [p4fg/secure-paper-wallet](https://github.com/p4fg/secure-paper-wallet) (fork of [pointbiz/bitaddress.org](https://github.com/pointbiz/bitaddress.org))
  * [dbasch/bitcoin-paper-wallet](https://github.com/dbasch/bitcoin-paper-wallet)
  * [nurupo/paper-store](https://github.com/nurupo/paper-store) - Cold store small files on paper as QR

[**Samourai Wallet**](https://play.google.com/store/apps/details?id=com.samourai.wallet)

* [Samoria Wallet - Youtube Channel](https://www.youtube.com/channel/UCb4Y89L9Bokuo6OWqjAhMoA)

[**Blockstream Green**](https://blockstream.com/green/) 
* [docs.blockstream.com - Getting Started](https://docs.blockstream.com/green/getting-started/getting-started-index.html)

[**BitGo**](https://www.bitgo.com/)
* [bitgo.github.io/bitgo-docs/](https://bitgo.github.io/bitgo-docs/)
* [Bitgo User Guide](https://static1.squarespace.com/static/5956707b6b49988d1df0001a/t/5ae161608a922d28394af452/1524719979322/BitGo+User+Guide042518.pdf)

>This document provides step-by-step details about how to use the non-custodial BitGo servicethrough the Web interface as well as how to administer the service and configure policies.

[**Wasabi**](https://wasabiwallet.io/)

* [MIT Bitcoin Expo 2019 - Wasabi Wallet: Unfairly Private](https://www.youtube.com/watch?v=JtDY7Gb-L5s)
* [zkSNACKs/WalletWasabi](https://github.com/zkSNACKs/WalletWasabi)
  * [FAQ](https://github.com/zkSNACKs/WalletWasabi/blob/master/WalletWasabi.Documentation/FAQ.md)
  * [DOJO](https://github.com/zkSNACKs/WalletWasabi/blob/master/WalletWasabi.Community/Dojo.md) - Community contributions: Guides, Reviews, Etc.
* [402 Payment Required - Wasabi wallet Youtube Playlist](https://www.youtube.com/watch?v=zPKpC9cRcZo&list=PLmoQ11MXEmahCG1nkbKK6DiAwVx9giJCi)

[**Casa Keymaster**](https://keys.casa/keymaster/)

* [Casa Keymaster Security: Mobile Key Overview](https://blog.keys.casa/casa-keymaster-security-mobile-key-overview/)
* [Setting up Keymaster by Casa (basic multisig)](https://www.youtube.com/watch?v=B-JpOC1Knx8)

[**Trezor**](https://shop.trezor.io/) 
  * [Trezor Wiki / User/ User manual](https://wiki.trezor.io/User_manual)
  * [How to transfer bitcoin from Coinbase to Trezor hardware wallet](https://youtu.be/K7fqbNGgTXU)
  * [[TUTORIAL] Send Bitcoin to Multiple Addresses in One Transaction Only - TREZOR](https://bitcointalk.org/index.php?topic=5136349.0)
  * [NEW 2019 TREZOR model T - Complete Setup, Backup and Restore Tutorial](https://www.youtube.com/watch?v=lab9_L61ZY0)
  * [romanz/trezor-agent](https://github.com/romanz/trezor-agent) -Hardware-based SSH/PGP agent

[**Ledger Nano X**](https://shop.ledger.com/pages/ledger-nano-x)
  * [LEDGER NANO X BEST SET-UP GUIDE, UNBOXING AND STEP BY STEP TUTORIAL 2019](https://www.youtube.com/watch?v=lHzFY4ucTYQ)

[**Cold Card**](https://coldcardwallet.com)
  * [Official getting started with your new Coldcard guide](https://coldcardwallet.com/docs/quick)
  * [coldcardwallet.com/docs/#guides-by-others](https://coldcardwallet.com/docs/#guides-by-others)
  * [402 Payment Required ColdCard Walkthrus](https://www.youtube.com/watch?v=f8dBNrlwJ0k&list=PLmoQ11MXEmahiHdXhOIUM0ja3Hzf_hVvc&index=2)
  
## Fee Calculators

[transactionfee.info](https://transactionfee.info)
  
## Escrow

Escrow Agents are impartial and trusted intermediaries who hold custody of buyer's funds until pre-defined conditions are met. They allow parties who don't know or trust each-other to engage in commerce, online.

* [Bitrated.com](https://www.bitrated.com/) 
* [jobs4btc-escrow.appspot.com](http://jobs4btc-escrow.appspot.com/)
* [Bitcoin Escrow and Key Signatures](https://web-work.tools/practical-public-key-crypto/)

### [Running a Bitcoin Full Node](https://www.lopp.net/bitcoin-information/full-node.html)

>While managing your own keys ensures that you can't lose your money due to the negligence or maliciousness of a custodian, running a full node ensures that you can't be tricked into accepting invalid bitcoin payments. Running and using your own node gives you the strongest security model Bitcoin has to offer.

![](https://raw.githubusercontent.com/PierreRochard/node-launcher/master/macos.png)
*[*lightning-power-users/node-launcher*](https://github.com/lightning-power-users/node-launcher)

* [bitcoin/bitcoin](https://github.com/bitcoin/bitcoin)
* [Why Run a Full Node?](https://blog.lopp.net/securing-your-financial-sovereignty/)
* [bitcoin.org - How to Run a Full Node](https://bitcoin.org/en/full-node)
* [Bitcoin Core Config File Generator](https://github.com/jlopp/bitcoin-core-config-generator)
* [Node Launcher](https://github.com/lightning-power-users/node-launcher)
* [Raspberry Pi Node Guide](https://medium.com/@meeDamian/bitcoin-full-node-on-rbp3-revised-88bb7c8ef1d1)
* [RaspPiBolt Guide](https://stadicus.github.io/RaspiBolt/)
* [Startnode](https://startnode.org/)
* [A complete beginners guide to installing a Bitcoin Full Node on Linux (2018 Edition)](https://hackernoon.com/a-complete-beginners-guide-to-installing-a-bitcoin-full-node-on-linux-2018-edition-cb8e384479ea)
  >How to compile a Bitcoin Full Node on a fresh installation of Kubuntu 18.04 without any Linux experience whatsoever.
  ![](https://imgur.com/hhN0o3F.png)
* [What Comprises a Bitcoin Fullnode Implementation? – Amentum](https://medium.com/amentum/what-comprises-a-bitcoin-fullnode-implementation-df27989e673a)
  >Often times in the press I see a lot of confusion around what a fullnode implementation of bitcoin actually *is*. I saw this as a great…
* [402 Payment Required Youtube Playlist - The Bitcoin Core Client](https://www.youtube.com/watch?v=q0Uen8p4feM&list=PLmoQ11MXEmag9I2ibHnubzJdjDqypujCk)



<blockquote class="twitter-tweet"><p lang="en" dir="ltr">Other full node options:<br>* <a href="https://twitter.com/CasaHODL?ref_src=twsrc%5Etfw">@CasaHODL</a>: <a href="https://t.co/JqpJeMGZVU">https://t.co/JqpJeMGZVU</a><br>* <a href="https://twitter.com/nodl_it?ref_src=twsrc%5Etfw">@nodl_it</a>: <a href="https://t.co/QyzOK9leWO">https://t.co/QyzOK9leWO</a><br>* Cyphernode: <a href="https://t.co/tMXS1kCgHW">https://t.co/tMXS1kCgHW</a><br><br>And of course, just running Bitcoin Core directly:<br>* &quot;Running a Full Node&quot;: <a href="https://t.co/D6Fs5WlZE9">https://t.co/D6Fs5WlZE9</a><br>* Bitcoin Core: <a href="https://t.co/OHW7H8oRzM">https://t.co/OHW7H8oRzM</a></p>&mdash; Michael Goldstein (@bitstein) <a href="https://twitter.com/bitstein/status/1091334121274646528?ref_src=twsrc%5Etfw">February 1, 2019</a></blockquote> <script async src="https://platform.twitter.com/widgets.js" charset="utf-8"></script> 


[**Full Node Software**](https://www.lopp.net/bitcoin-information/full-node.html#node_software):

* [bitcoin.org/en/download](https://bitcoin.org/en/download)
  >Bitcoin Core initial synchronization will take time and download a lot of data. You should make sure that you have enough bandwidth and storage for the full block chain size (over 200GB). If you have a good Internet connection, you can help strengthen the network by keeping your PC running with Bitcoin Core and port 8333 open. Read the full node guide for details.
* [Bcoin](https://github.com/bcoin-org/bcoin/releases) 
  - Javascript bitcoin library for node.js and browsers http://bcoin.io
* [BTCD](https://github.com/btcsuite/btcd) - An alternative full node bitcoin implementation written in Go (golang) 
  - https://github.com/btcsuite/btcd/tree/master/docs
* [Gocoin](https://gocoin.pl/) - Gocoin is a full Bitcoin solution written in Go language (golang). + tools 
* [Libbitcoin Node](https://github.com/libbitcoin/libbitcoin-node/releases)
  >These binaries require no installation, simply download and run the single file. Mainnet and testnet are supported based on configuration differences. You can verify the downloads using the signed SHA256 hashes below.

[**Plug & Play Node Hardware**](https://www.lopp.net/bitcoin-information/full-node.html#node_hardware):

* [Casa](https://keys.casa/lightning-bitcoin-node/#node-plans)
  * [Setting up your Casa Node](https://www.youtube.com/watch?v=C0FirXi_d0I)
* [Fulmo](https://shop.fulmo.org/?product=raspiblitz-lightning-node-1-tb)
* [NODL](https://shop.nodl.it/en/)
* [Startnode](http://startnode.org/PreBuilt/)
* [Bitseed Core - Bitcoin full node](https://bitseed.org/product/bitseed-3/)
  > Bitseed Core comes preconfigured as a Bitcoin full node, allowing you to keep bitcoin running 24/7 without slowing your PC.



## Development

* [ChristopherA/Learning-Bitcoin-from-the-Command-Line](https://github.com/ChristopherA/Learning-Bitcoin-from-the-Command-Line)
  >Programming with Bitcoin Core and Lightning (Or: Programming Bitcoind and Lightningd)
* [Bitcoin.org - Developer Guide](https://bitcoin.org/en/developer-guide)
* [A Gentle Introduction to Bitcoin Core Development](https://bitcointechtalk.com/a-gentle-introduction-to-bitcoin-core-development-fdc95eaee6b8)
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
* [bitcointechtalk.com](https://bitcointechtalk.com/)
* [jimmysong/programmingbitcoin](https://github.com/jimmysong/programmingbitcoin)
* [Why I decided to Build Bitcoin from scratch](https://hackernoon.com/why-i-decided-to-build-bitcoin-from-scratch-d2ca7526d0ee)

### Scripts

* [Programming Bitcoin Script Transaction (Crypto) Contracts Step-by-Step ( Beta / Rough Draft ) by Gerald Bauer et al, 2019 - FREE (Online Version)](https://github.com/openblockchains/programming-bitcoin-script)
* [Jameson Lopp (@lopp)](https://twitter.com/lopp/status/1072156493116518400)
  >https://t.co/etW1yP65Zr has a neat animated Bitcoin script interpreter and debugger for those who want to better understand script execution. https://t.co/5TAkdoPU7b https://t.co/6UkzUGu4dK
  * [liuhongchao/bitcoin4s](https://github.com/liuhongchao/bitcoin4s)

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


### Books

* [bitcoinbook/bitcoinbook](https://github.com/aantonop/bitcoinbook) - Mastering Bitcoin 2nd Edition - Programming the Open Blockchain
* [kallerosenbaum/grokkingbitcoin](https://github.com/kallerosenbaum/grokkingbitcoin) - Source repository for Grokking Bitcoin
  - [Manning - Grokking Bitcoin](https://www.manning.com/books/grokking-bitcoin)

## Assorted


* [bitdb.network](https://bitdb.network/) - The Random Access Memory for Bitcoin
* [BestMixer.io’s Bitcoin Blender Aims to Bring Anonymity Back to C...](https://thebitcoinnews.com/bestmixer-ios-bitcoin-blender-aims-to-bring-anonymity-back-to-crypto/)
  >The BestMixer.io development team has introduced their next generation bitcoin blender in an effort aimed at disrupting the quickening pace of blockchain analysis firms such as Chainalysis. The reason behind the move is simple: cryptocurrency is not anonymous but it pretends ...
* [The Business of Bitcoin Cold Storage – Nik Bhatia](https://medium.com/@timevalueofbtc/the-business-of-bitcoin-cold-storage-148fba7f1255)
  >Bitcoin is digital gold, and this continues to be its most appropriate and concise metaphor. I recently discussed some parallels between…
* [How to Create and Verify a Chainpoint Proof – Tierion](https://medium.com/tierion/how-to-create-and-verify-a-chainpoint-proof-eba52a7700e3)
  >This guide shows how developers can use a Chainpoint Node to create and verify a Chainpoint proof. Chainpoint is an open standard for…


* [a Ƀitcoin service provider :)](https://8333.io/)
  >The 8333.io platform provides tooling, apps & services on top of any bip32 compatible Bitcoin wallet. It's a service layer on top of the Bitcoin network, offering powerful utilities for users and/or developpers.

## BTC Layer 2


* [How to Create an Online Store & Accept Bitcoin](https://bitcoinshirt.co/how-to-create-store-accept-bitcoin)
  >Learn how to build an online e-commerce store and accept Bitcoin payments with no coding or web-designing skills required. Using free and open-source software: WordPress, WooCommerce and BTCPay. No steps skipped and video tutorials.
* [Bitcoin Lightning Joule Chrome Extension](https://medium.com/lightning-power-users/bitcoin-lightning-joule-chrome-extension-ac149bb05cb9)
  >Lightning Joule is an awesome Chrome plugin being developed by William O'Beirne, check out his presentation at the Chaincode Labs…
 

 * [JeffVandrewJr/patron](https://github.com/JeffVandrewJr/patron)

* [lightninglayer.com](https://lightninglayer.com/)
* [Andreas Brekken (@abrkn)](https://twitter.com/abrkn/status/1079116127542726656)
  >Explained why I took my LN hub down. Every maximalist attacked me, without reading my review Asked how to add LN as a payment option for my startup. No one replied This is why https://www.shitcoin.com/ exists. We prove that no one is using what they shill. But I do. https:...

* [Blockstream/liquid](https://github.com/Blockstream/liquid) -Liquid daemon and cli. Contribute to Blockstream/liquid development by creating an account on GitHub.
 

* [Easiest #Bitcoin Lightning Guide!](https://medium.com/lightning-power-users/windows-macos-lightning-network-284bd5034340)
