---
title: Consensus Mechanisms Curated
redirect_from: 
  - /archive/layer1/consensus/
  - /archive/layer1/pow/
  - /archive/layer1/pos/
  - "/archive/layer1/tendermint/"
---

* [Emin Gün Sirer (@el33th4xor)](https://twitter.com/el33th4xor/status/1006931729679044608)
  > Proof-of-Work and Proof-of-Stake are **sybil control mechanisms**. PoS doesn't achieve consensus by itself. It has to be coupled with a protocol, such as PBFT, or Ben-Or, or Tendermint/Cosmos, or Avalanche, to make decisions.
* [PoW, PoS and DAGs are NOT consensus protocols – Coinmonks – Medium](https://medium.com/coinmonks/a-primer-on-blockchain-design-89605b287a5a)
  > The much hyped concepts of Proof-Of-Work, Proof-of-Stake and Directed Acyclic Graphs are often mistakenly advertised as “consensus…
* [Finality in Blockchain Consensus – Mechanism Labs – Medium](https://medium.com/mechanism-labs/finality-in-blockchain-consensus-d1f83c120a9a)
  > Today, with the swipe of a credit card, I purchased a delightful matcha green tea (shout out to Asha in Berkeley). Just moments after the…
* [Randomness in Blockchains (Part 1) – Mechanism Labs – Medium](https://medium.com/mechanism-labs/randomness-in-blockchains-part-1-79192b173816)
  > While randomness is important in the creation of secure channels of communication between two people, randomness can also play an important role in determining who is communicating with whom. If multiple people are trying to communicate with each other over a channel that has limited bandwidth, randomness can be used to determine a fair order in which the channel will carry the messages.
  > 
  > Randomness is also useful in helping a group of people or computers come to agreement, or consensus. Randomized consensus protocols are such an example. This post will explore the role of randomness in blockchains.
* [Bryan Bishop (@kanzure)](https://twitter.com/kanzure/status/1048039485550690304)
  > Transcript: "Abstract thinking about consensus systems" (@LukeDashjr) [https://t.co/xD3BLVcsT3](https://t.co/xD3BLVcsT3) #bitcoinedge2018 @TheBitcoinEdge
* [Let’s take a crack at understanding distributed “consensus”](https://medium.com/@preethikasireddy/lets-take-a-crack-at-understanding-distributed-consensus-dad23d0dc95)
  > Do you know how distributed systems work? It can be a tough topic to learn about, mainly because the knowledge surrounding it is…
* [How Unrealistic is Bribing Frequently Rotated Validators?](https://medium.com/nearprotocol/how-unrealistic-is-bribing-frequently-rotated-validators-d859adb464c8)
  > Many proposed blockchain protocols today use some sorts of committees to propose and validate blocks. The committees are at the core of…


![](https://i.imgur.com/Q98JZHP.jpg)

* [How Are Blockchain Transactions Validated? Consensus VS Validation](https://www.mangoresearch.co/blockchain-consensus-vs-validation/)
  > Blockchain Consensus vs Blockchain Validation - You've probably heard the terms "consesus" and "validation" being used frequently in blockchain blurb, sometimes even interchangeably. Issue is, the terms represent two very different functions in blockchain tech....
* [Explaining the liveness guarantee](https://ethresear.ch/t/explaining-the-liveness-guarantee/4228)
  > One of the aspects that seem to surprise many people that only casually follow the progress of Ethereum Serenity is the quadratic leak that is imposed upon validators for being offline and missing a slot. For those unwilling/unable to read the Casper FFG paper, I wrote up a ...
* [Study session: Distributed Systems and Consensus](https://www.youtube.com/watch?v=WndYl3wUzYM&feature=youtu.be)
  > Preethi talks about distributed systems, the difficulty with achieving consensus, and the Casper CBC debate. Join the TruStory Expert Community today https:/...

![](https://i.imgur.com/wRfL2nA.jpg)

* [Sarah Jamie Lewis (@SarahJamieLewis)](https://twitter.com/sarahjamielewis/status/1164613365747965952?s=12)
  > Seems a few communities are explicitly basing their consensus algorithms off of various insect models. Who wants a cryptocurrency thread that is actually a thread about ants? Let me tell you about alarm pheromones.
* [Chatting about consensus algorithms with Robert Habermeier](https://www.zeroknowledge.fm/15)
  > Fredrik has a chat about consensus algorithms with Parity Technologies in-house consensus expert Robert Habermeier. We cover what a consensus algorithm is and how they work. We try to explain some common terms like safety and liveness, what a fork choice rule is and how real-...

## Byzantine Fault Tolerance

* [Understanding Blockchain Fundamentals, Part 1: Byzantine Fault Tololerance](https://medium.com/loom-network/understanding-blockchain-fundamentals-part-1-byzantine-fault-tolerance-245f46fe8419)
* [Practical Byzantine Fault Tolerance - Miguel Castro and Barbara Liskov](http://pmg.csail.mit.edu/papers/osdi99.pdf) 
  > This paper describes a new replication algorithm that is able to tolerate Byzantine faults. We believe that Byzantinefault-tolerant algorithms will be increasingly important in the future because malicious attacks and software errors are increasingly common and can cause faulty nodes to exhibit arbitrary behavior. Whereas previous algorithms assumed a synchronous system or were too slow to be used in practice, the algorithm described in this paper is practical: it works in asynchronous environments like the Internet and incorporates several important optimizations that improve the response time of previous algorithms by more than an order of magnitude. We implemented a Byzantine-fault-tolerant NFS service using our algorithm and measured its performance. The results show that our service is only 3% slower than a standard unreplicated NFS.
* [Bitcoin Theory (Byzantine Generals and Beyond)](https://bitcointalk.org/index.php?topic=99631.0)
  > Bitcoin Theory (Byzantine Generals and Beyond)
* [Does Bitcoin Solve Byzantine Consensus?](https://brooker.co.za/blog/2015/02/28/bitcoin.html)
* [Most Cited Byzantine Consensus Publications](https://blockchainlibrary.org/2017/10/most-cited-byzantine-consensus-publications)
  > Last updated October 26th, 2017. “CONCURRENCY CONTROL AND RECOVERY IN DATABASE SYSTEMS”. PA Bernstein, V Hadzilacos, N Goodman. 1987. courses.cs.washington.edu . 5808 cites. “Dist…
* [Federated Byzantine Agreement – Towards Data Science](https://towardsdatascience.com/federated-byzantine-agreement-24ec57bf36e0)
  > The next generation in Byzantine Consensus.
* [Validated Asynchronous Byzantine Agreement with Optimal Resilience and Asymptotically Optimal Time and Word Communication](https://arxiv.org/pdf/1811.01332.pdf)


## Proof of Work - PoW

* [The Anatomy of Proof-of-Work – Bitcoin Tech Talk](https://bitcointechtalk.com/the-anatomy-of-proof-of-work-98c85b6f6667)
  > Proof-of-Work (PoW) was originally invented as a measure against email spams. Only later it was adapted to be used in digital cash [1].
* [Block Chain Mining — Proof Work & Stake – Venkatesh Narayanan](https://medium.com/@venkinarayanan/block-chain-mining-proof-work-stake-95345d8af443)
  > What does it takes to add a new transaction / record / block to the blockchain ?
* [Uneeb Agha (@uneeb123)](https://twitter.com/uneeb123/status/1042267905881190400)
  > 1/ Proof of work is still pretty poorly understood. I'll break it down in my own terms.
* [nic carter (@nic__carter)](https://twitter.com/nic__carter/status/1041659062855843840)
  > Between @danheld and @LaurentMT, PoW is in safe hands. Laurent's latest is bang on the money. PoW enforces churn in the validator set, PoS enables incumbents to maintain a costless advantage. [https://t.co/ipSScdMX9w](https://t.co/ipSScdMX9w)
* [Dan Hedl (@danheld)](https://twitter.com/danheld/status/1040621230691213314)
  > 1/ Most people think #Bitcoin’s PoW is "wasteful." I explore how everything is energy, money is energy, subjective use of energy, and PoW's costs relative to existing governance systems For a deeper dive, my Medium post: [https://t.co/a3wJW5Y1Ni](https://t.co/a3wJW5Y1Ni) TL;DR - check out this t...
* [Blockchain Proof-of-Work is a Decentralized Clock - Gregory Trubetskoy](https://grisha.org/blog/2018/01/23/explaining-proof-of-work/)
  > This is an explanation of the key function on Proof-of-Work in the Bitcoin blockchain. It focuses on the one feature of Proof-of-Work that is …
* [Jimmy Song (송재준) (@jimmysong)](https://twitter.com/jimmysong/status/1034051762393505793)
  > Why you need Proof of Work: [https://t.co/UyzAuw561O](https://t.co/UyzAuw561O) via @YouTube
* [Dan Hedl (@danheld)](https://twitter.com/danheld/status/1032322008854421504)
  > 1/ Most people have misconceptions about PoW being "wasteful." Because this narrative is so popular, I've spent some time collecting my thoughts on its utility, efficiency, and morality. A thread: [https://t.co/H8FsrqZFZ7](https://t.co/H8FsrqZFZ7)
* [PoW, PoS, & Hybrid protocols: A Matter of Complexity?](https://arxiv.org/pdf/1805.08674.pdf)
* [Hugo Nguyen (@hugohanoi)](https://twitter.com/hugohanoi/status/1046097559993880584)
  > 1/ Emin again with the BS that PoW’s role is merely a “Sybil-controlled mechanism”. (And therefore PoS is a reasonable drop-in replacement.) It’s the classic mistake domain experts make when analyzing systems purely from their Point-of-View. [https://t.co/6GLnPiGw](https://t.co/6GLnPiGw)...
* [Beyond the doomsday economics of “proof-ofwork” in cryptocurrencies](https://www.bis.org/publ/work765.pdf)
* [monospaced-out/bit-by-bitcoin](https://github.com/monospaced-out/bit-by-bitcoin)
  > An interactive tool for understanding how Bitcoin and proof-of-work blockchains work - monospaced-out/bit-by-bitcoin
* [Gravity – LaurentMT – Medium](https://medium.com/@laurentmt/gravity-10e1a25d2ab2)
  > “Law I: Every UTXO persists in its state, except insofar as it is compelled to change its state by force impressed.” — Isaac Newton…
* [Proof of Work vs Proof of Something else – Hacker Noon](https://hackernoon.com/proof-of-work-vs-proof-of-something-else-272d2f5cf20a)
  > Zoom out of time for a while and imagine how the antlers of a magnificent moose buck evolved into being.
* [On the security and performance of proof of work blockchains](https://eprint.iacr.org/2016/555.pdf)

## Proof of Stake - PoS

* [PoS, & Hybrid protocols: A Matter of Complexity?](https://arxiv.org/pdf/1805.08674.pdf)
* [Variations of Proof of Stake — Steemit](https://steemit.com/bitcoin/@funmemes/variations-of-proof-of-stake)
  > Variations of Proof of Stake Proof of Stake Anonymous (PoSA) First introduced by Cloakcoin , transactions… by funmemes
* [The Creator of Proof-of-Stake Thinks He Finally Figured It Out](https://www.coindesk.com/the-creator-of-proof-of-stake-thinks-he-finally-figured-it-out)
Pseudonymous developer Sunny King, the creator of proof-of-stake, has a new approach for the consensus mechanism – and it revolves around hardware.
* [Kyle Samani (@KyleSamani)](https://twitter.com/KyleSamani/status/1039822086808592384)
  > POW-maximalists fail to recognize that an attacker in a POS system can be forked out if caught. This can be implemented by default This *dramatically* changes the cost-benefit analysis for attacking. If u assign a 5% probability 2 being caught, it becomes *much* riskier 2...
* [Electric Money – LaurentMT – Medium](https://medium.com/@laurentmt/electric-money-e2cd34f78f56)
  > “Do states dream of electric money ?” — Philip K. Dick (Reloaded)
* [On Stake and Consensus Andrew Poelstra](https://download.wpsoftware.net/bitcoin/pos.pdf)
* [Block Chain Mining — Proof Work & Stake – Venkatesh Narayanan ...](https://medium.com/@venkinarayanan/block-chain-mining-proof-work-stake-95345d8af443)
  > What does it takes to add a new transaction / record / block to the blockchain ?
* [Proof-of-Stake & the Wrong Engineering Mindset – Hugo Nguyen](https://medium.com/@hugonguyen/proof-of-stake-the-wrong-engineering-mindset-15e641ab65a2)
  > Proof-of-Stake (PoS) is all the rage these days. Ethereum Casper, Cardano Ouroboros, etc.
* [Proof-of-Stake, Private Keys Attacks and Unforgeable Costliness th...](https://medium.com/@hugonguyen/proof-of-stake-private-keys-attacks-and-unforgeable-costliness-the-unsung-hero-5caca70b01cb)
  > In my previous article, I discussed how PoS is less resilient than PoW in dealing with worst-case scenarios.
* [Blockchain Without Waste: Proof-of-Stake](https://pdfs.semanticscholar.org/d873/a75502e45e1791cd6fc8d1ce670e1337063a.pdf)
* [Formal Barriers to Longest-Chain Proof-of-Stake Protocols](https://ethresear.ch/t/formal-barriers-to-longest-chain-proof-of-stake-protocols/3509)
  > New paper Formal Barriers to Longest-Chain Proof-of-Stake Protocols from Arvind Narayanan of Princeton. Not sure if these papers should be posted to this forum (my instinct is that they should!), but trying it as an experiment (instead of just discussing on Twitter). Key id...
* [https://cyber.stanford.edu/sites/default/files/formal_barriers_to_proof-of-stake_protocols.pdf](https://cyber.stanford.edu/sites/default/files/formal_barriers_to_proof-of-stake_protocols.pdf)
* [Proof of Stake is Still Pointless](http://www.truthcoin.info/blog/pos-still-pointless/) - 07 Jul 2017
  > I go line-by-line against Vitalik’s Proof of Stake FAQ. PoS is still just as expensive as PoW (but it may have different security features).
* [Eric Lombrozo (@eric_lombrozo)](https://twitter.com/eric_lombrozo/status/1045916707821408256)
PoS is the cryptoeconomic equivalent of a perpetual motion machine. Moreover, if it were really possible to get it to work, PoW would have probably never been invented in the first place. [https://t.co/2f6R1QqjZb](https://t.co/2f6R1QqjZb)
* [nic carter (@nic__carter)](https://twitter.com/nic__carter/status/1041844862612590593)
  > PoS is a cheaper and more efficient alternative to proof of w– [https://t.co/Vv9xmmXAby](https://t.co/Vv9xmmXAby)
* [Brave New Coin (@bravenewcoin)](https://twitter.com/bravenewcoin/status/891070977714663425)
  > Based on a 2012 paper, @PeercoinPPC is similar to #Bitcoin, but more energy efficient & no hard limit on coin number [https://t.co/NjX8APKy9I](https://t.co/NjX8APKy9I)
* [scott lewis🌾 (@scott_lew_is)](https://twitter.com/scott_lew_is/status/1042043969348284417)
  > David Chaum proposed ecash in 1982. A full 6 years later, it was 1988. and an additional full 20 years after that Satoshi Nakamoto solved it. [https://t.co/0tfWWcRgD3](https://t.co/0tfWWcRgD3)
* [Classifying Staking Implementations: A Framework](https://blog.chorus.one/classifying-staking-implementations-a-framework)
  > There is a lot of confusion around Proof-of-Stake and staking cryptoassets in general. This post introduces a framework for classifying implementations and goes into detail distinguishing between DPoS and PoS, as well as delegation in the projects Cosmos, Cardano, Ethereum an...
* [Understanding the Basics of a Proof-of-Stake Security Model](https://blog.cosmos.network/understanding-the-basics-of-a-proof-of-stake-security-model-de3b3e160710)
  > Devcon3 is fully underway, and despite the development-focused agenda at the conference, a majority of the audience is still befuddled…
* [How Unrealistic is Bribing Frequently Rotated Validators?](https://medium.com/nearprotocol/how-unrealistic-is-bribing-frequently-rotated-validators-d859adb464c8)
  > Many proposed blockchain protocols today use some sorts of committees to propose and validate blocks. The committees are at the core of…
* [Understanding Proof of Stake through it’s Flaws. Part 3](https://medium.com/@abhisharm/understanding-proof-of-stake-through-its-flaws-part-3-long-range-attacks-672a3d413501)
  > Note: This is the final part in a series in which I investigate the major problems with Proof of Stake currencies in an attempt at gaining…
* [#5: The Stakes Are High – Staking Economy – Medium](https://medium.com/staking-economy/5-the-stakes-are-high-cd9dbc72f777)
  > Proof-of-Work vs. Proof-of-Stake, DPoS vs. PoS, Cosmos validators vs. each other and secret contracts vs. smart contracts.
* [cbc-casper/cbc-casper-paper](https://github.com/cbc-casper/cbc-casper-paper/blob/master/cbc-casper-paper-draft.pdf)
  > The paper for Correct-By-Construction Casper consenus protocols - cbc-casper/cbc-casper-paper
* [Validator Ordering and Randomness in PoS](http://web.archive.org/web/20180725200558/https://vitalik.ca/files/randomness.html) - Vitalik
* [Eric Conner (@econoar)](https://twitter.com/econoar/status/1053311930885197825)
  > 0/ I see a lot of discussion about the technicals of Ethereum’s Casper PoS but not much discussion around the economics. I’ve been giving a lot of thought to the current incentive structure and here are my thoughts. SPOILER: I think we need more discussion around the e...
* [Security flaws found in 26 low-end cryptocurrencies - ZDNet](https://www.zdnet.com/article/security-flaws-found-in-26-low-end-cryptocurrencies/)
Researchers detail new "Fake Stake" attacks against some Proof-of-Stake-based cryptocurrencies.
* [Georgios Konstantopoulos (@gakonst)](https://twitter.com/gakonst/status/1164550108152848385?s=12)
  > Is there any Proof of Stake chain with a secure light client protocol?
* [Donald McIntyre ☣️🗑️ (@TokenHash)](https://twitter.com/TokenHash/status/1177730919223808002?s=20)
  > Excellent article by @evoskuil explaining why PoS is not censorship resistant: [https://t.co/ENNmgufCnD](https://t.co/ENNmgufCnD) ht @eric_lombrozo
* [Classifying Staking Implementations: A Framework](https://blog.chorus.one/classifying-staking-implementations-a-framework)
  > There is a lot of confusion around Proof-of-Stake and staking cryptoassets in general. This post introduces a framework for classifying implementations and goes into detail distinguishing between DPoS and PoS, as well as delegation in the projects Cosmos, Cardano, Ethereum an...
* [Proof-of-Stake Resources - CASPER](https://souptacular.gitbooks.io/ethereum-tutorials-and-tips-by-hudson/content/proof-of-stake_resources.html)
* [Delegated Proof-of-Stake Consensus](https://web.archive.org/web/20190617190634/https://bitshares.org/technology/delegated-proof-of-stake-consensus/) - A robust and flexible decision making protocol
* [What is Proof-of-Stake (PoS)? What is Randomized Proof-of-Stake (R...](https://orbs.com/what-is-proof-of-stake-pos-vs-dpos-vs-rpos)
  > Randomized Proof-of-stake (RPoS) vs. Proof-of-Stake (PoS) vs. Delegated Proof-of-Stake (DPoS): What the future holds for blockchain consensus
* [Synchrony and Timing Assumptions in Consensus Algorithms Used in P...](https://medium.com/mechanism-labs/synchrony-and-timing-assumptions-in-consensus-algorithms-used-in-proof-of-stake-blockchains-5356fb253459)
  > Co-authored with Alexis Gauba.
* [Brian Fabian Crain (@crainbf)](https://twitter.com/crainbf/status/1047089258299682817)
  > 1/ This Friday at @delta_summit, I'll do a talk on the transition from Proof-of-Work to Proof-of-Stake. Here is my attempt to put core argument into a tweetstorm:
* [Proof-of-Stake & the Wrong Engineering Mindset – Hugo Nguyen](https://medium.com/@hugonguyen/proof-of-stake-the-wrong-engineering-mindset-15e641ab65a2)
  > Proof-of-Stake (PoS) is all the rage these days. Ethereum Casper, Cardano Ouroboros, etc.

### PoS History

* BitShares: [Delegated Proof-of-Stake Consensus - A robust and flexible decision making protocol](http://web.archive.org/web/20190317081015/https://bitshares.org/technology/delegated-proof-of-stake-consensus/) First coin to use DPoS 
* [DPOS Consensus Algorithm - The Missing White Paper — Steemit](https://steemit.com/dpos/@dantheman/dpos-consensus-algorithm-this-missing-white-paper)
  > This is the missing white paper and analysis of delegated proof of stake (DPOS). The goal of this paper is to provide… by dantheman
* [Proof of Stake and the History of Distributed Consensus: Part 1](https://medium.com/thunderofficial/proof-of-stake-and-the-history-of-distributed-consensus-part-1-nakamoto-consensus-byzantine-176e0156316e)
  > The Historical Context of Hybrid Consensus
* [PeerCoin White Paper](https://peercoin.net/assets/paper/peercoin-paper.pdf) - Arguably the first coin to introduce Proof of Stake as an alternative to Proof of Work for distributed consensus. 
* [Transactions as Proof-of-Stake](http://web.archive.org/web/20170616192438/https://bravenewcoin.com/assets/Uploads/TransactionsAsProofOfStake10.pdf) - Dan Larimer introduces Delegated Proof of Stake (DPoS) 
* Proof of Stake Thread: [Proof of stake instead of proof of work](https://bitcointalk.org/index.php?topic=27787.0) Shows the original idea of PoS and its criticisms and benefits
* [Proof of Stake Velocity](https://www.reddcoin.com/papers/PoSV.pdf)
* [Proof of Mainstake](https://zmnscpxj.github.io/sidechain/mainstake/index.html)
  > Proof-of-mainstake is a sidechain proposal similar to a federated peg, with the federation membership determined by a stake of coins on the mainchain (i.e. the mainstake). As the name suggests, it is similar to proof-of-stake in that staked coins are used to indicate a controlling interest.


### Proof of Authority - POA

* [Ep Igor Barinov: POA Network – Enabling Scaling Through Trust in Public Notaries - Aug 6, 2019](https://podcasts.apple.com/us/podcast/epicenter-learn-about-blockchain-ethereum-bitcoin-distributed/id792338939?i=1000446307025)
* [What is Proof of Authority Consensus? Staking Your Identity on The Blockchain](https://blockonomi.com/proof-of-authority/) 
  > As the cryptocurrency space continues to evolve at an accelerated pace, experimentation and implementation of a variety of consensus models is inevitable.
  > 
  > Proof of Authority (PoA) consensus is not necessarily a new consensus mechanism (has been around since March 2017), but has been implemented in some interesting platforms as a compromise between consensus models targeting complete decentralization and more efficient, centralized models.
* [What is Proof of Authority Consensus? (PoA) Staking Your Identity](https://blockonomi.com/proof-of-authority/)
  > PoA consensus is an optimized Proof of Stake model that leverages identity as the form of stake rather than actually staking tokens.
* [Ethereum Proof-of-Authority on Azure](https://azure.microsoft.com/en-us/blog/ethereum-proof-of-authority-on-azure/)
  > We’ve had great traction with our support of Ethereum on Azure. The existing Proof-of-Work solution has been deployed tens of thousands of times across a variety of industry verticals.

## Tendermint

* [tendermint/tendermint](https://github.com/tendermint/tendermint/wiki)
  > ⟁ Tendermint Core (BFT Consensus) in Go. Contribute to tendermint/tendermint development by creating an account on GitHub.
* [Tendermint: Consensus without Mining - Jae Kwon](https://tendermint.com/static/docs/tendermint.pdf) (2014)
  > Abstract. Cryptocurrencies such as Bitcoin enable users to submit payment transactions without going through a centralized trusted organization. Bitcoin relies on proof-of-work mining to secure consensus which is problematic; mining requires a massive expenditure of energy, confirmation of transactions is slow, and security is difficult to quantify. We propose a solution to the blockchain consensus problem that does not require mining by adapting an existing solution to the Byzantine Generals Problem
* [Why build a dapp or blockchain on Tendermint consensus?](https://medium.com/egeon/why-build-a-dapp-or-blockchain-on-tendermint-consensus-1b8ddc383b3c)
People keep asking me, why did I decide to build our Egeon blockchain on Tendermint consensus over other blockchain frameworks, like…
* [Consensus Compare: Casper vs. Tendermint – Cosmos Blog](https://blog.cosmos.network/consensus-compare-casper-vs-tendermint-6df154ad56ae)
This technical deep dive is written by Chjango Unchained. Enjoy.
* [List of projects in Cosmos & Tendermint Ecosystem](https://forum.cosmos.network/t/list-of-projects-in-cosmos-tendermint-ecosystem/243)
* [Kadena (@kadena_io)](https://twitter.com/kadena_io/status/1158729085788532736?s=12)
  > ANNOUNCEMENT: Introducing Kadenamint - We're bringing our secure smart contract language Pact to @tendermint_team and @cosmos with a grant from @interchain_io! Read the @coindesk story by @christine_dkim at [https://t.co/OmgqWl3zLf](https://t.co/OmgqWl3zLf) #Kadenamint | #Cosmos | #SmarterContracts

## Algorand

* [Algorand 2.0 at CESC](https://gist.github.com/Haseeb-Qureshi/d3b49afeec82eb77e6716ff6eb878b95)
  > Algorand 2.0 at CESC. GitHub Gist: instantly share code, notes, and snippets.
* ["Algorand: A Better Distributed Ledger," with Silvio Micali](https://www.youtube.com/watch?v=_nQE_HAGlmM)
  > Title: Algorand: A Better Distributed Ledger Date: 10/13/17 Speaker: Silvio Micali Abstract A distributed ledger is a tamperproof sequence of data that can b...

## DPoW
* [Delayed Proof of Work](https://komodoplatform.com/delayed-proof-of-work/)
  > Komodo’s delayed Proof of Work (dPoW) security is a secondary consensus mechanism that recycles the giant hash rate of the  Bitcoin network through a series of cross-chain notarizations.

## Hashgraph

* [Hashgraph Consensus Timing Vulnerability](https://ethresear.ch/t/hashgraph-consensus-timing-vulnerability/2120)
  > There is now a lot of interest in “Hashgraph-the-Blockchain-Killer” in the Silicon Valley investment community, so I have been asked recently to do a review of the Hashgraph whitepaper. I am publishing it here because it may be interesting for some people My humble opin...
* [Hashgraph: A Whitepaper Review – OpenToken – Medium](https://medium.com/opentoken/hashgraph-a-whitepaper-review-f7dfe2b24647)
  > We’ve been getting a lot of questions about Hashgraph recently. Although you can find plenty of great documentation on Hashgraph’s website, only a few external resources cover it in detail. With this post, we hope to provide a useful overview and evaluation for the whole community, while still covering enough technical nitty-gritty to entertain even the most die-hard distributed systems folks.
* [Holochain vs. Hashgraph …and when is consensus needed in distriuted computing](https://blog.p2pfoundation.net/holochain-vs-hashgraph-and-when-is-consensus-needed-in-distributed-computing/2018/09/25)
Hashgraph has been getting some press and many are excited about the speeds it promises... but there are some gaps.
* [hashgraph/awesome-hashgraph](https://github.com/hashgraph/awesome-hashgraph)
Hashgraph is a superior consensus mechanism / data structure alternative to blockchain. - hashgraph/awesome-hashgraph
* [Ep Mance Harmon: Hashgraph – A Radically Novel Consensus Algorithm - Jan 25, 2018](https://podcasts.apple.com/us/podcast/epicenter-learn-about-blockchain-ethereum-bitcoin-distributed/id792338939?i=1000437366948)
* [Eric Wall (@ercwl)](https://twitter.com/ercwl/status/1168634534793023489?s=12)
  > I just published "Hedera Hashgraph — Time for some FUD". Dedicated to @CoveringDelta. [https://t.co/3S8b1PWbSn](https://t.co/3S8b1PWbSn)


## Polkadot

* [From Bitcoin to Polkadot: A brief history of consensus and finality in blockchains](https://medium.com/polkadot-network/consensus-and-finality-in-blockchains-21b1f634fd00)
  > This piece will explore the need for fault tolerant consensus algorithms in blockchain networks and where development is headed in the…
* [GRANDPA Block Finality in Polkadot: An Introduction (Part 1)](https://medium.com/polkadot-network/grandpa-block-finality-in-polkadot-an-introduction-part-1-d08a24a021b5)
  > This article is the first in a series of articles exploring consensus and finality in Polkadot.


## Assorted

* [Proof of elapsed time research paper](http://i2c.cs.uh.edu/tiki-download_wiki_attachment.php?attId=70) 
* [Proof of Space Time](https://eprint.iacr.org/2016/035.pdf)
* [Proof of burn](https://en.bitcoin.it/wiki/Proof_of_burn)
* [Consensus Compare: Casper vs. Tendermint – Cosmos Blog](https://blog.cosmos.network/consensus-compare-casper-vs-tendermint-6df154ad56ae)
  > This technical deep dive is written by Chjango Unchained. Enjoy.
* [Ouroboros: A Provably Secure Proof-of-Stake Blockchain Protocol](https://eprint.iacr.org/2016/889.pdf)
* [Proof of Stake Velocity](https://www.reddcoin.com/papers/PoSV.pdf)
* [A Guide to 99% Fault Tolerant Consensus](https://vitalik.ca/general/2018/08/07/99_fault_tolerant.html)
  > Special thanks to Emin Gun Sirer for review
* [Vitalik Buterin Proposes 1% Consensus Algorithm - Crypto Disrupt](https://cryptodisrupt.com/vitalik-proposes-1-consensus-algorithm/)
  > In a complex document, the Ethereum creator Vitalik Buterin laid out plans for a blockchain consensus algorithm which can survive a 99% attack.
* [notsofast (@notsofast)](https://twitter.com/notsofast/status/1035531840503865344)
  > Why has nobody forked $BURST yet? It's one thing in $crypto that has truly perplexed me. That coin is awesome. PoW using committed hard drive space as a substitute for committed energy expenditure.
* [SPECTRE – Aviv Zohar – Medium](https://medium.com/@avivzohar/the-spectre-protocol-7dbbebb707b5)
  > A Fast and Scalable Distributed Ledger Protocol
* [PHANTOM, GHOSTDAG: Two Scalable BlockDAG protocols](https://eprint.iacr.org/2018/104.pdf)
* [Obelisk Consensus Algorithm Design Motivations](https://www.skycoin.net/blog/statement/obelisk-consensus-algorithm-design-motivations)
* [On Proof-of-Skill – Jay Berg – Medium](https://medium.com/@jaybny/on-proof-of-skill-6af149f45ce8)
  > Reaching Decentralized Distributed Consensus Without POW
* [SingularityNET Moves Toward Social Computing With Proof-of-Reputation](https://blog.singularitynet.io/singularitynet-moves-toward-social-computing-with-proof-of-reputation-14df7c6618f)
  > Our latest design overcomes one of blockchain’s major barriers: designing a decentralized reputation management system.
* [PaLa: A Simple Partially Synchronous Blockchain](https://eprint.iacr.org/2018/981.pdf)
* [Snowflake to Avalanche: A Novel Metastable Consensus Protocol Family for Cryptocurrencies](https://ipfs.io/ipfs/QmUy4jh5mGNZvLkjies1RWM4YuvJh5o2FYopNPVYwrRVGV)

## Resources

* [ML Alternative Consensus_MetaAnalysis_Chart](https://docs.google.com/spreadsheets/u/3/d/1IW5AuFQtL4z34HgIZrqpcVfZPnOiifsc3xmA9KIef6I/htmlview)
* [Mechanism-Labs/MetaAnalysis-of-Alternative-Consensus-Protocols](https://github.com/Mechanism-Labs/MetaAnalysis-of-Alternative-Consensus-Protocols/blob/master/MetaAnalysis.pdf)
  > This paper presents the first systematization of knowledge within these major blockchain protocols, understanding the common challenges and solutions, and providing a formal structure within which...
* [PoW, PoS, & Hybrid protocols: A Matter of Complexity?](https://arxiv.org/pdf/1805.08674.pdf)
* [Consensus Systems with Ethan Buchman - Software Engineering Daily](https://softwareengineeringdaily.com/2018/03/26/consensus-systems-with-ethan-buchman)
  > Consensus protocols are used to allow computers to work together. A consensus protocol lets different servers agree on the state of a system. For decades, these protocols have been used to establish consensus among database nodes, application servers, and other infrastructure...
* [9 Types of Consensus Mechanisms That You Didn’t Know About](https://medium.com/the-daily-bit/9-types-of-consensus-mechanisms-that-you-didnt-know-about-49ec365179da)
  > Reviewing lesser known consensus mechanisms and their implementations in distributed ledgers.
* [A Hitchhiker’s Guide to Consensus Algorithms – Hacker Noon](https://hackernoon.com/a-hitchhikers-guide-to-consensus-algorithms-d81aae3eb0e3)
  > A quick classification of cryptocurrency consensus types
* [r/CryptoTechnology - My brief observation of most common Consensus...](https://www.reddit.com/r/CryptoTechnology/comments/7znnq8/my_brief_observation_of_most_common_consensus?utm_source=reddit-android)
  > 161 votes and 50 comments so far on Reddit
* [dgryski/awesome-consensus](https://github.com/dgryski/awesome-consensus)
  > Awesome list for Paxos and friends. Contribute to dgryski/awesome-consensus development by creating an account on GitHub.
* [ConsensusPedia: An Encyclopedia of 30 Consensus Algorithms](https://hackernoon.com/consensuspedia-an-encyclopedia-of-29-consensus-algorithms-e9c4b4b7d08f)
  > A complete list of all consensus algorithms.
* [Web 3 Consensus Mechanisms – imbrexBlog – Medium](https://medium.com/imbrexblog/web-3-consensus-mechanisms-2dcfb7bfaadb)
  > …and the protocols that use them
* [zawy12/difficulty-algorithms](https://github.com/zawy12/difficulty-algorithms/issues)
  > See the Issues for difficulty algorithms. Contribute to zawy12/difficulty-algorithms development by creating an account on GitHub.
* [Alternative Consensus Deep Dive](https://docs.google.com/presentation/d/10YH5ssdES2C228SwDoQI3kM1X-mMw3NhHjlESPYi9iY/edit)
* [MerosCrypto/Merit-Caching](https://github.com/MerosCrypto/Merit-Caching/blob/master/Merit%20Caching.pdf) - Merit Caching Consensus Mechanism.