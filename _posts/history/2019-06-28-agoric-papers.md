---
layout: single
title: "The Agoric Papers"
description: "These three papers by Mark S. Miller and K. Eric Drexler appeared in The Ecology of Computation, Bernardo Huberman (ed.) Elsevier Science Publishers/North-Holland, 1988"
excerpt: "These three papers by Mark S. Miller and K. Eric Drexler appeared in The Ecology of Computation, Bernardo Huberman (ed.) Elsevier Science Publishers/North-Holland, 1988"
sidebar:
  nav: sourcedisco 
toc: true
header:
  teaser: /images/agoric-papers-teaser.png
  og_image: /images/agoric-papers-teaser.png
share: true
last_modified_at: 2019-06-28T11:22:33-23:00
categories: ["history","Agoric"]
tags: ["Mark Miller", "Eric Drexler", "ObCap", "Smart Contracts", "literature"]
toc_sticky: true
permalink: /posts/history/agoric-papers-miller-drexler/
redirect_from: /literature/agoric-papers-miller-drexler/
canonical_url: "https://agoric-records.xyz/posts/markets-incentive-ecosystems/"
---

I was excited to catch this episode of Epicenter, recently. I've been interested in Mark Miller's work since I began studying the [history of smart contracts](https://sourcecrypto.pub/bitcoin-history/smart-contracts).

{% include video id="j5SuqIrgRJU" provider="youtube" %}


* [Mark Miller: Agoric and the Decades-Long Quest for Secure Smart Contracts.](https://epicenter.tv/episode/286/) -Epicenter Podcast


I'll be diving deeper into ObCap, Elang, and Agoric over the coming months. In the mean-time, I had a moment to review and create this directory to the Agoric Papers.

At the moment, its pretty simple. I've made a link, and chose a selection to quote by the link.

This will allow anyone to quickly review the papers, at a glance. Eventually I'd like to include related links, and maybe even some images, who knows. :)

Besides that just a little information to familiarize ourselves with the authors.

## Mark S Miller

>Mark S. Miller is an American computer scientist. He is known for his work as one of the participants in the 1979 hypertext project known as Project Xanadu; for inventing Miller columns; as the co-creator of the Agoric Paradigm[1] of market-based distributed secure computing; and the open-source coordinator of the E programming language. He also designed the Caja programming language.
>
>Miller earned a BS in computer science from Yale in 1980 and published his Johns Hopkins PhD thesis in 2006.[2] Previously Chief Architect with the Virus-Safe Computing Initiative at HP Labs, he is now a research scientist at Google[3] and a member of the ECMAScript (JavaScript) committee.[4] - [Wikipedia](https://en.wikipedia.org/wiki/Mark_S._Miller)

* [twitter.com/marksammiller](https://twitter.com/marksammiller)
  * [ai.google/research/people/author35958](https://ai.google/research/people/author35958)
  * [agoric.com/authors/mark-s-miller](https://agoric.com/authors/mark-s-miller/)

## Eric Drexler


* [Eric Drexler](http://metamodern.com/about-the-author/)

>Often described as “the founding father of nanotechnology”, Eric Drexler introduced the concept in his seminal 1981 paper in the Proceedings of the National Academy of Sciences, which established fundamental principles of molecular engineering and outlined development paths to advanced nanotechnologies. In his 1986 book, Engines of Creation: The Coming Era of Nanotechnology, he introduced a broad audience to a fundamental technology objective: using machines that work at the molecular scale to structure matter from the bottom up. Drexler’s research in this field has been the basis for numerous journal articles and a comprehensive, physics-based analysis in Nanosystems: Molecular Machinery, Manufacturing, and Computation. In his publications and lectures, Dr. Drexler describes the implementation and applications of advanced nanotechnologies and shows how they can be used solve, not merely delay, large-scale problems such as global warming.

* [agoric.com/authors/k-eric-drexler/](https://agoric.com/authors/k-eric-drexler/)
* [ethw.org/K._Eric_Drexler](https://ethw.org/K._Eric_Drexler)


## [The Agoric Papers](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers.html)

> These three papers by Mark S. Miller and K. Eric Drexler appeared in The Ecology of Computation, Bernardo Huberman (ed.) Elsevier Science Publishers/North-Holland, 1988. 

## Markets and Computation: Agoric Open Systems

> Like all systems involving goals, resources, and actions, computation can be viewed in economic terms. This paper examines markets as a model for computation and proposes a framework--agoric systems--for applying the power of market mechanisms to the software domain. It then explores the consequences of this model and outlines initial market strategies.

* [Agorics Open Systems Abstract](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.0.html) (5k)

* Mark S. Miller -Xerox Palo Alto Research Center,
* K. Eric Drexler - MIT Artificial Intelligence Laboratory,

>Like all systems involving goals, resources, and actions, computation can be viewed in economic terms. Computer science has moved from centralized toward increasingly decentralized models of control and action; use of market mechanisms would be a natural extension of this development. The ability of trade and price mechanisms to combine local decisions by diverse parties into globally effective behavior suggests their value for organizing computation in large systems.

>This paper examines markets as a model for computation and proposes a framework-agoric systems-for applying the power of market mechanisms to the software domain. It then explores the consequences of this model at a variety of levels. Initial market strategies are outlined which, if used by objects locally, lead to distributed resource allocation algorithms that encourage adaptive modification based on local knowledge. If used as the basis for large, distributed systems, open to the human market, agoric systems can serve as a software publishing and distribution marketplace providing strong incentives for the development of reusable software components. It is argued that such a system should give rise to increasingly intelligent behavior as an emergent property of interactions among software entities and people.


* [Introduction](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.1.html) (9k)

> This line of investigation leads us to propose what may be called the agoric approach to software systems. Agoric stems from agora, the Greek term for a meeting and market place. An agoric system is defined as a software system using market mechanisms, based on foundations that provide for the encapsulation and communication of information, access, and resources among objects. Each of these notions plays a role in supporting computational markets.

* [Overview of later sections](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.2.html) (5k)

* **Section 3: Computation and economic order.** - Basic characteristics of human markets illuminate the expected nature of computational markets. This section describes some of these characteristics and sketches some of the special issues raised in the context of computation.
* **Section 4: Foundations.** The foundations needed for agoric open systems may be summarized as support for the encapsulation and communication of information, access, and resources. This section describes these foundations and their role in computational markets.
* **Section 5:** Agents and strategies. The foundations of computational markets handle neither resource management (such as processor scheduling and garbage collection) nor market transactions. This section describes the idea of business agents and their use both in replacing centralized resource-allocation algorithms (discussed further by [III]) and in managing complex market behavior.
* **Section 6:** Agoric systems in the large. Large, evolved agoric systems are expected to have valuable emergent properties. This section describes how they can provide a more productive software market in human society-opening major new business opportunities-and how they can further the goal of artificial intelligence.
* **Section 7:** The absence of agoric systems. If market-based computation is a good idea, why has it not yet been developed? This section attempts to show why the current absence of agoric systems is consistent with their being a good idea.
* **Appendix I:** Issues, levels, and scale. Agoric open systems will be large and complex, spanning many levels of scale and complexity. This section surveys how issues such as security, reasoning, and trust manifest themselves at different levels of agoric systems.
* **Appendix II:** Comparison with other systems. Here are reviewed works ranging from those that draw analogies between human society and computational systems to those that explore adaptive computation from an economic point of view.

* [Computation and economic order](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.3.html) (26k)

>The objects participating in computational markets must initially be much simpler than the human participants in human markets. Can they participate successfully? Human markets are based on intelligent systems, but this does not show the impossibility of basing markets on simple objects-it merely shows that the argument for agoric systems cannot rest on analogy alone. Explicit attention must be paid to the question of the minimal competence and complexity necessary for an object to participate in a market system. (These issues provide another motivation to form computational "firms" and to open computational markets to human participation.)

* [Foundations](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.4.html) (23k)

>Computational foundations are frequently expressed in the form of programming language or operating system designs. Programming languages have evolved chiefly to provide abstractions for organizing computation on a small scale-the computation occurring inside a single machine and serving a single user. This has unfortunately led many programming lan- guage designers to make decisions (such as providing for global variables or access to arbitrary memory addresses) that make these languages unsuitable for organizing computation on a very large scale. The Actor languages, Argus, the concurrent logic programming languages (such as FCP), and the Mach operating system are examples of systems which have been designed to be extensible to large, open systems. These are covered in this book respectively in [II], [III], [IV], [V], and [VI]. All these projects have arrived at broadly similar models of computation from different directions, suggesting that their common elements will be of general value. This section briefly outlines some of the properties they share-properties which seem important for the implemention of computational markets.

* [Agents and strategies](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.5.html) (33k)

>Current resource allocation policies leave much to be desired. One sign of this is that most computing resources-including CPUs, disk heads, local area networks, and much more-sit idle most of the time. But such resources have obvious uses, including improving their own efficiency during later use. For example, heavily-used programs can be recompiled through optimizing compilers or partial evaluators; pages on disk can be rearranged to keep files contiguous; objects can be rearranged according to referencing structure to minimize paging [47], and so forth. In a computational market, a set of unused resources would typically have a zero or near-zero price of use, reflecting only the cost of whatever power consumption or maintenance could be saved by genuine idleness or complete shutdown. Almost any use, however trivial, would then be profitable. In practice, contention for use would bid up prices until they reflected the marginal value of use [5]. Idle time is a blatant sign of wasteful resource allocation policies; one suspects that it is just the tip of a very large iceberg.

* [Agoric systems in the large](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.6.html) (26k)

>Agoric systems will naturally support a charge-per-use market for software. In any market, software producers will attempt to extract substantial charges from high-volume users. With charge per use, however, the charges to be paid by high-volume users will no longer stand in the way of low-volume users; as a result, they will use expensive software that they could not afford today. At the same time, high-volume users will experience a finite marginal price for using software, rather than buying it and paying a zero marginal price for using it; they will cut back on some of their marginal, low-value uses. The overall benefit of numerous low-volume users making high-value use of the software will likely outweigh the loss associated with a few high-volume users cutting back on their low-value uses, yielding a net social benefit. It seems likely that some of this benefit will appear as increased revenues to software producers, encouraging increased software production.

* [The absence of agoric systems](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.7.html) (6k)

>Why have agoric open systems not been implemented already? In part, because the software community has lacked an immediate, compelling need. Advances have been made, through better programming environments and methodologies (including the encapsulation and communication of information and access), and through tools for making larger structures visible to programmers [64]-all without building markets. These environments and method- ologies have extended the programmer's conceptual span of control, enabling one mind or a few closely-coordinated, mutually-trusting minds to build ever larger and more complex programs. These advances have decreased the urgency of enabling extensive cooperation without mutual trust or extensive communications.

* [Conclusions](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.8.html) (5k)

>This paper has examined many of the concrete issues involved in actually creating computational markets, from hardware and software foundations, to initial market strategies for resource management (chiefly in [III]), to the organization of systems of objects and agents able to interact in a market context. As yet, no obstacle to their realization has been found.

>Distributed systems based on the charge-per-use sale of software services and computational resources promise a more flexible and effective software market, in which large systems will more often be built from pre-existing parts. With many minds building knowledge and competence into market objects, and with incentives favoring cooperation among these objects, the overall problem-solving ability of the system can be expected to grow rapidly.

>On a small scale, central planning makes sense; on a larger scale, market mechanisms make sense. Computer science began in a domain where central planning made sense, and central planning has thus been traditional. It seems likely, however, that some modern computer systems are already large and diverse enough to benefit from decentralized market coordination. As systems grow in scale and complexity, so will the advantages of market-based computational systems.

* [Agorics Open Systems Appendix I](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.9.html) (17k)

>This section has examined how a range of issues-security, compatibility, trust, reasoning, and coordination-may appear at different levels of market-based open systems. Certain themes have appeared repeatedly. Mechanisms at low levels often support those at higher levels, as (for example) high-level coordination mechanisms using simple serializers. Further, higher levels can inherit characteristics of lower levels, such as encapsulation and conservation laws.

>Issues often blur at the higher levels-security and trust become intertwined, and may both depend on due-process reasoning. The bulk of this paper concentrates on low- and mid-level concerns which must be addressed first, but high-level issues all present a wealth of important research topics. 

* [Appendix II. Comparison with other systems](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.10.html) (24k)

>The Xanadu hypertext publishing system This paper has compared agoric systems to other systems for computation. Our first exposure to many of the central ideas of markets and computation, however, stems from our work with the Xanadu hypertext system [23]. Xanadu is a proposed on-line publishing medium for hypertext documents. A hypertext document differs from the normal notion of a document in that it contains links, connections between documents which readers can follow at the click of a mouse. Published documents thus form not a set of disconnected islands, but a web connected by references, quotes, criticisms, comments, and rebuttals.
>
>How can a reader find a path in such an interconnected web? Rather than proposing that someone (somehow) create a single, official system index, the Xanadu project proposes support for decentralized indexing, and hence for pluralism. Any reader can author and publish a guide to any set of public documents. Other readers can then use this guide to sort material and orient themselves. Anyone can, of course, publish guides to other guides. Xanadu relies on the expectation that this activity will result in a spontaneous order-a richly-connected world of documents in which readers can find their way.
>
>Why will indexing be done where needed? In part because readers will do much of the basic searching and sorting for themselves, and then publish the results (since publishing is easy). In addition, however, Xanadu provides a charge-per-read royalty arrangement to encourage publication of material for which there is a demand. Just as charge-per-use software will make it economical to assemble software from diverse components, so Xanadu's royalty arrangement is designed to encourage the assembly of documents from parts of other documents: if one document quotes another, a reader's royalty payments are split between them.


* [References](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/aos/aos.refs.html) (41k)

Papers referenced with roman numerals can be found in the present volume: Huberman, Bernardo (ed.), Ecology of Computation (Elsevier Science Publishers/North-Holland, 1988).

* [I] Miller, Mark S., and Drexler, K. Eric, "Comparative Ecology: A Computational Perspective", this volume.
* [II] Hewitt, Carl, "Offices are Open Systems", this volume.
* [III] Drexler, K. Eric, and Miller, Mark S., "Incentive Engineering for Computational Resource Management", this volume.
* [IV] Kahn, Kenneth, and Miller, Mark S., "Language Design and Open Systems", this volume.
* [V] Liskov, Barbara, "Guardians and Actions: Linguistic Support for Robust, Distributed Programs", this volume.
* [VI] Rashid, Richard, "From RIG to Accent to Mach: The Evolution of a Network Operating System", this volume.
* [VII] Stefik, Mark, "The Next Knowledge Medium", this volume.
* [VIII] Malone, Thomas W., Fikes, R. E., and Howard, M. T., "Enterprise: A Market-Like Task Scheduler for Distributed Computing Environments", this volume.
* [IX] Lenat, Douglas B., and Brown, John Seely, "Why AM and EURISKO Appear to Work", this volume.
* [1] Popper, Karl R., Objective Knowledge: An Evolutionary Approach (Oxford University Press, London, 1972).
* [2] Hayek, Friedrich A., The Counter-Revolution of Science: Studies on the Abuse of Reason (Liberty Press, Indianapolis, 1979).
* [3] Clinger, Will, Foundations of Actor Semantics (MIT, Cambridge, MA, May 1981) MIT AI-TR-633.
* [4] Agha, Gul, Actors: A Model of Concurrent Computation in Distributed Systems (MIT Press, Cambridge, MA, 1986).
* [5] Alchian, Armen A., and Allen, William R., University Economics (Wadsworth, Belmont, CA, 1968, Second Edition).
* [6] Hayek, Friedrich A., The Constitution of Liberty (University of Chicago Press, Chicago, 1960) p.156.
* [7] Smith, Adam, An Inquiry into the Nature and Causes of The Wealth of Nations (University of Chicago Press, Chicago, 1976) p.531.
* [8] Hayek, Friedrich A., "Competition as a Discovery Procedure", in: New Studies in Philosophy, Politics, Economics and the History of Ideas (University of Chicago Press, Chicago, 1978) p.179-190.
* [9] Hayek, Friedrich A., "Economics and Knowledge", from: Economica, New Series (1937), Vol. IV, pp.33-54; reprinted in: Hayek, Friedrich A., (ed.), Individualism and Economic Order (University of Chicago Press, Chicago, 1948).
* [10] Hayek, Friedrich A., New Studies in Philosophy, Politics, Economics and the History of Ideas (University of Chicago Press, Chicago, 1978) p.71.
* [11] Drexler, K. Eric, "Molecular Engineering: An Approach to the Development of General Capabilities for Molecular Manipulation", in: Proceedings of the National Academy of Science USA (Sept. 1981) Vol. 78, No.9, pp.5275-5278.
* [12] Drexler, K. Eric, "Rod Logic and Thermal Noise in the Molecular Nanocomputer", in: Proceedings of the Third International Symposium on Molecular Electronic Devices (Elsevier Science Publishers / North Holland, 1987).
* [13] Drexler, K. Eric, Engines of Creation (Anchor Press / Doubleday, Garden City, New York, 1986).
* [14] Coase, R. H., "The Nature of the Firm", in: Economica, New Series (1937), Vol. IV, pp.386-405; reprinted in: Stigler, G. J., and Boulding, K. E., (eds.), Readings in Price Theory (Richard D. Irwin, Inc., Chicago, 1952).
* [15] Williamson, Oliver, Markets and Hierarchies: Analysis and Anti-Trust Implications (Free Press, New York, 1975).
* [16] Malone, Thomas W.; Yates, JoAnne; and Benjamin, Robert I., "Electronic Markets and Electronic Hierarchies", in: Communications of the ACM (June 1987) Vol.30, No. 6, pp.484-497.
* [17] Smith, Vernon L., "Experimental Methods in the Political Economy of Exchange", in: Science (10 October 1986) Vol.234, pp.167-173.
* [18] Star, Spencer, "TRADER: A Knowledge-Based System for Trading in Markets", in: Economics and Artificial Intelligence First International Conference (Aix-En-Provence, France, September 1986).
* [19] Hoare, C.A.R., Communicating Sequential Processes (Prentice-Hall, New York, 1985).
* [20] INMOS Limited, Occam Programming Manual (Prentice-Hall International, London, 1984).
* [21] Shapiro, Ehud, (ed.), Concurrent Prolog: Collected Papers (MIT Press, Cambridge, MA, 1987) in press.
* [22] Artsy, Yeshayahu, and Livny, Miron, An Approach to the Design of Fully Open Computing Systems (University of Wisconsin / Madison, March 1987) Computer Sciences Technical Report #689.
* [23] Nelson, Theodor, Literary Machines (published by author, version 87.1, 1987, available from Project Xanadu, 8480 Fredricksburg #8, San Antonio, TX 78229. Available as hypertext on disk from Owl International, 14218 NE 21st St., Bellevue, WA 98007. 1981).
* [24] Granovetter, Mark, "The Strength of Weak Ties", in: American Journal of Sociology (1977) Vol. 78, pp.1360-1380.
* [25] Miller, Mark S., Bobrow, Daniel G., Tribble, Eric Dean, and Levy, Jacob, "Logical Secrets", in: Shapiro, Ehud, (ed.), Concurrent Prolog: Collected Papers (MIT Press, Cambridge, MA, 1987) in press.
* [26] Hardin, Garrett, "The Tragedy of the Commons", in: Science (13 December 1968) Vol. 162, pp.1243-1248.
* [27] Kurose, James F., Schwartz, Mischa, and Yemini, Yechiam, "A Microeconomic Approach to Decentralized Optimization of Channel Access Policies in Multiaccess Networks", in: Proceedings of the Fifth International Conference on Distributed Computing Systems (IEEE, Denver CO, May 1985) pp.70-77.
* [28] Goldberg, Adele, and Robson, Dave, Smalltalk-80: The Language and its Implementation (Addison-Wesley, Reading MA, 1983).
* [29] Rivest, R., Shamir, A., and Adelman, L., "A Method for Obtaining Digital Signatures and Public-Key Cryptosystems", in: Communications of the ACM (Feb. 1978) Vol. 21, No. 2, pp.120-126.
* [30] Tanenbaum, Andrew S., and van Renesse, Robbert, "Distributed Operating Systems", in: ACM Computing Surveys (ACM, New York, December 1985) Vol. 17, No. 4, pp.419-470.
* [31] Hayek, Friedrich A., Denationalisation of Money (The Institute of Economic Affairs, Westminster, London, 1978, Second Edition).
* [32] Denning, Peter J., "The Working Set Model for Program Behavior", in: Communications of the ACM (May 1968) Vol 2, No. 5, pp.323-333.
* [33] Artsy, Y., Chang, H-Y, and Finkel, R., Processes Migrate in Charlotte (University of Wisconsin / Madison, August 1986) Computer Sciences Technical Report #655.
* [34] Artsy, Y., and Finkel, R., "Simplicity, Efficiency, and Functionality in Designing a Process Migration Facility", in: Proceedings of the Second Israel Conference on Computer Systems and Software Engineering (IEEE, Tel-Aviv, Israel, May 1987) 3.1.2, pp.1-12.
* [35] Cheriton, D.R., "The V Kernel: A Software Base for Distributed Systems", in: IEEE Software (April 1984) 1, 2, pp.19-42.
* [36] Leach, P.J., Levine, P.H., Douros, B.P., Hamilton, J. A., Nelson, D.L., and Stumph, B.L., "The Architecture of an Integrated Local Network", in: IEEE Journal on Selected Areas in Communication (IEEE, November 1983) SAC-1, 5, 842-857.
* [37] Bishop, Peter B., Computers with a Large Address Space and Garbage Collection (MIT, Cambridge, MA, May 1977) MIT/LCS/TR-178.
* [38] Birrell, Andrew D.; Levin, Roy; Needham, Roger M.; and Schroeder, Michael D., "Grapevine: an Exercise in Distributed Computing", in: Communications of the ACM (April 1982) Vol. 25, No. 4.
* [39] Terry, Douglas Brian, Distributed Name Servers: Naming and Caching in Large Distributed Environments (Xerox PARC, February 1985) CSL-85-1.
* [40] Barak, A., and Shiloh, A., "A Distributed Load-Balancing Policy for a Multicomputer" in: Software Practice and Experience (September 1985) 15, pp.901-913.
* [41] Shapiro, Ehud, "Systolic Programming: A Paradigm for Parallel Processing", in: Proceedings of the International Conference on Fifth Generation Computer Systems (1984) pp.458-471.
* [42] Kahn, Kenneth, A Partial Evaluator of Lisp Written in a Prolog Written in Lisp Intended to be Applied to the Prolog and Itself which in turn is Intended to be Given to Itself Together with the Prolog to Produce a Prolog Compiler (University of Uppsala, Sweden, 1983) UPMAIL Tech. Report No. 17.
* [43] Theriault, D., Issues in the Design and Implementation of Act 2 (MIT AI Lab, Cambridge, MA., 1983) AI-TR-728.
* [44] Winograd, Terry, and Flores, Fernando, Understanding Computers and Cognition (Ablex, Norwood, NJ, 1986).
* [45] Witham, Steve, personal communication (1987).
* [46] Safra, S., and Shapiro, Ehud, "Meta-Interpreters For Real", in: Proceedings, IFIP-86 (1986) pp.271-278.
* [47] Stamos, James W., A Large Object-Oriented Virtual Memory: Grouping Strategies, Measurements, and Performance (Xerox PARC, Palo Alto, CA, May 1982) SCG-82-2.
* [48] Stanley, Terry, personal communication (1987).
* [49] Hamming, R. W., "One Man's View of Computer Science", in: Ashenhurst, Robert L., and Graham, Susan, (eds.), ACM Turing Award Lectures: The First Twenty Years 1966-1985 (Addison-Wesley, Reading, MA, 1987) pp.216.
* [50] Cox, Brad J., Object Oriented Programming: An Evolutionary Approach (Addison-Wesley, Reading, MA, 1986) pp.26-28.
* [51] Jacobson, Gary, and Hillkirk, John, Xerox: American Samurai (Macmillan, New York, 1986).
* [52] Chaum, David, "Design Concepts for Tamper Responding Systems", in: Advances in Cryptology: Proceedings of Crypto '83 (Plenum Press, NY, 1984) pp.387-392.
* [53] Levy, Henry M., Capability-Based Computer Systems (Digital Press, Bedford, MA, 1984).
* [54] Gehringer, Edward F., Capability Architectures and Small Objects (UMI Research Press, Ann Arbor, MI, 1982).
* [55] Organick, Elliott I., A Programmer's View of the Intel 432 System (McGraw-Hill, New York, 1983).
* [56] Rees, Jonathan A., and Adams, Norman I., IV, "T: a Dialect of Lisp or, Lambda: The Ultimate Software Tool", in: Proceedings of the 1982 ACM Symposium on Lisp and Functional Programming (August 1982).
* [57] Conway, M.E., "How Do Committees Invent?", in: Datamation (April 1968) 14, 4, pp.28-31.
* [58] Brooks, Frederick P., Jr., The Mythical Man Month (Addison-Wesley Publishing Company, Reading, MA, 1975) pp.111.
* [59] Hayek, Friedrich A., "Cosmos and Taxis" in: Law, Legislation and Liberty, Vol. 1: Rules and Order, (University of Chicago Press, Chicago, 1973) pp.35-54.
* [60] Minsky, Marvin, The Society of Mind (Simon and Schuster, New York, 1986).
* [61] Kornfeld, William A., and Hewitt, Carl, "The Scientific Community Metaphor", in: IEEE Transactions on Systems, Man, and Cybernetics (IEEE, 1981) SMC-11, pp.24-33.
* [63] March, J. G., "Footnotes to Organizational Change", in: Administrative Science Quarterly (1981) 26, pp.563-577.
* [64] Barstow, David R., Shrobe, Howard E., and Sandewall, Erik, (eds.), Interactive Programming Environments (McGraw-Hill, New York, 1984).
* [65] Xerox, Courier: The Remote Procedure Call Protocol (Xerox Corp, Stamford CT, 1982) p.5.
* [66] Rao, Ramana Balusu, Toward Interoperability and Extensibility in Window Environments via Object-Oriented Programming (MIT Press, 1987) submitted as Masters Thesis.
* [67] Shrager, Jeff, and Klahr, David, "Instructionless Learning about a Complex Device: The Paradigm and Observations", in: Int. J. Man-Machine Studies (1986) 25, pp.153-189.
* [68] Dawkins, Richard, The Selfish Gene (Oxford University Press, New York, 1976).
* [69] Axelrod, Robert, The Evolution of Cooperation (Basic Books, New York, 1984).
* [70] McDermott, Drew, "A Critique of Pure Reason", to appear in: Levesque, Hector, (ed.), Computational Intelligence (National Research Council of Canada, August or September, 1987).
* [71] Dijkstra, E. W., "Co-operating Sequential Processes", in: Genuys, F., (ed.), Programming Languages (Academic Press, New York, 1968) pp.43-112.
* [72] Demers, Alan, Greene, Dan, Hauser, Carl, Irish, Wes, Larson, John, Shenker, Scott, Sturgis, Howard, Swinehart, Dan, and Terry, Doug, "Epidemic Algorithms for Replicated Database Maintenance", in: Proceedings of the Sixth Annual ACM Symposium on Principles of Distributed Computing (ACM, Vancouver, British Columbia, Canada, August 10-12, 1987) pp.1-12.
* [73] Hanson, Robin, Toward Hypertext Publishing: Issues and Choices in Database Design (draft available from Foresight Institute, Palo Alto, CA, 1987).
* [74] Stefik, Mark, Foster, Gregg, Bobrow, Daniel G., Lahn, Kenneth, Lanning, Stan, and Suchman, Lucy, "Beyond the Chalkboard: Computer Support for Colaboration and Problem Solving in Meetings", in: Communications of the ACM (January 1987) Vol. 30, No. 1, pp.32-47.
* [75] Hewitt, Carl, "Robert's Rules of Order" (in press).
* [76] Malone, Thomas W., "Organizing Information Processing Systems: Parallels Between Human Organizations and Computer Systems", in: Zacharay, W., Robertson, S., and Black, J., (eds.), Cognition, Computation, and Cooperation (Ablex Publishing Corp., Norwood, NJ, 1986).
* [77] Lenat, Douglas B., "The Role of Heuristics in Learning by Discovery: Three Case Studies", in: Michalski, Ryszard S., Carbonell, Jaime G., and Mitchell, Tom M. (eds.), Machine Learning: An Artificial Intelligence Approach (Tioga Publishing Company, Palo Alto, CA, 1983) pp.243-306.
* [78] Harris, Jed, Yu, Chee, Harris, Britton, Market Based Scheduling (1987) in preparation.
* [79] Sutherland, I.E., "A Futures Market in Computer Time", in: Communications of the ACM (June 1968) Volume 11, Number 6.
* [80] McClelland, James L., Rumelhart, David E., and PDP Research Group, Parallel Distributed Processing (MIT Press, Cambridge, MA, 1986) Volumes 1 and 2.
* [81] Holland, John H., Holyoak, Keith J., Nisbett, Richard E., and Thagard, Paul R., Induction: Processes of Inference, Learning, and Discovery (MIT Press, Cambridge, MA, 1986).
* [82] Holland, John H., Holyoak, Keith J., Nisbett, Richard E., and Thagard, Paul R., Induction: Processes of Inference, Learning, and Discovery (MIT Press, Cambridge, MA, 1986) pp.72-75, 79.
* [83] Barto, Andrew G., "Game Theoretic Cooperativity in Networks of Self-Interested Units", in: Denker, John S. (ed.), Neural Networks for Computing (American Institute of Physics, New York, 1986) pp.41-46.
* [84] Minsky, Marvin, "Steps Toward Artificial Intelligence", in: Feigenbaum, Edward A., and Feldman, Julian, (eds.), Computers and Thought (Robert E. Krieger, Malabar, FL, 1981) pp.406-450.
* [85] Minsky, Marvin, personal communication (1987).

## Incentive Engineering: for Computational Resource Management

>Agoric computation will require market-compatible mechanisms for the allocation of processor time and storage space. Recasting processor scheduling as an auction process yields a flexible priority system. Recasting storage management as a system of decentralized market negotiations yields a distributed garbage collection algorithm able to collect unreferenced loops that cross trust boundaries. Algorithms that manage processor time and storage in ways that enable both conventional computation and market-based decision making will be useful in establishing agoric systems: they lie at the boundary between design and evolution. Algorithms are described in detail.

* [Incentive Engineering: Abstract](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ie/ie0.html) (3k)

> Agoric computation [I,II] will require market-compatible mechanisms for the allocation of processor time and storage space. Recasting processor scheduling as an auction process yields a flexible priority system. Recasting storage management as a system of decentralized market negotiations yields a distributed garbage collection algorithm able to collect unreferenced loops that cross trust boundaries. Algorithms that manage processor time and storage in ways that enable both conventional computation and market-based decision making will be useful in establishing agoric systems: they lie at the boundary between design and evolution. We describe such algorithms in some detail.

* [Introduction](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ie/ie1.html) (21k)

 Several systems-programming constraints are important in storage management. First, non-garbage-everything reachable by a chain of strong pointers leading from a well-funded object-must not be collected. Second, garbage-everything that is unreferenced and cannot induce other objects to reference or pay it-should eventually be collected. Finally, overhead costs should be reasonable: bookkeeping storage per object should be bounded and the computational burden of the algorithms should scale roughly linearly (at most) with the number of objects.

* [Processor scheduling](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ie/ie2.html) (21k)

>This section describes initial market strategies for both sellers and buyers. In processor scheduling, we will term the time-seller (or agent for the seller) an auction house, and a time-buyer (or agent for a buyer) a bidder. A system may have any number of competing sellers.

* [Storage management](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ie/ie3.html) (44k)

>In rent-based storage management, we again must specify strategies both for the relationships between buyers and sellers (here, renters and landlords) and for the relationships among renters (in their roles as clients and consultants). The latter are complex.

* [Initial strategies](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ie/ie4.html) for trust (5k)

>Many of the above algorithms make strategic sense only if one object can trust another object to follow them. For example, there are direct financial incentives to embezzle funds or misreport earnings by violating the dividend algorithm, and there are market-share incentives to produce falsely low cost estimates by violating the base-demand algorithm. Further, improper market intelligence (who is using what services?) can be gleaned by comparing alert- ID values arriving via different consultants. Thus, one needs what may be called initial strategies for trust. 

* [Probabilistic cash](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ie/ie5.html) flows (9k)

>As noted in the discussion of accounting overhead in the dividend algorithm, the incentive structure of an algorithm (in the absence of risk aversion) is determined by its average expected payoffs, which can deviate from its actual payoffs on any given occasion. This principle has general applicability. 

* [Conclusions](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ie/ie6.html) (5k)

>This paper has explored mechanisms for the allocation of processor time and storage that are compatible both with programming practice and with market mechanisms. Processor scheduling through an auction process yields a flexible, decentralized priority system, allowing a variety of strategies that make tradeoffs involving the speed, certainty, and cost of service. Storage can be managed through auctioning of rental space and decentralized networks of client-consultant relationships. This yields a distributed garbage collection algorithm able both to collect unreferenced loops that cross trust boundaries and to accumulate rough price information to guide economic decisions regarding, for example, local caching in distributed systems.

>Some of these algorithms (e.g., for processor scheduling) have per-decision costs comparable to those of non-market mechanisms in current use; others have costs that are much greater. In general, these costs will be acceptable for objects of sufficient size and processes of sufficient duration. 

* [Incentive Engineering Appendix](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ie/ieappendix.html) (3k)

>The alert algorithm is the most procedurally intricate of the initial strategies described here, hence it is the one least suited to description in English. It is documented here by code written in the programming language FCP [V,16]; this code has not been run. To facilitate object-oriented programming, we are using a form of syntactic sugar known as "keyword terms" [17]. 

* [References](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ie/ie.refs.html) (11k)

Papers referenced with roman numerals can be found in the present volume: Huberman, Bernardo (ed.), Ecology of Computation (Elsevier Science Publishers/North-Holland, 1988).

* [I] Miller, Mark S., and Drexler, K. Eric, "Comparative Ecology: A Computational Perspective", this volume.
* [II] Miller, Mark S., and Drexler, K. Eric, "Markets and Computation: Agoric Open Systems", this volume.
* [III] Liskov, Barbara, "Guardians and Actions: Linguistic Support for Robust, Distributed Programs", this volume.
* [IV] Rashid, Richard F., "From RIG to Accent to Mach: The Evolution of a Network Operating System", this volume.
* [V] Kahn, Kenneth, and Miller, Mark S., "Language Design and Open Systems", this volume.
* [1] Lieberman-Hewitt Algorithm: Lieberman, Henry, and Hewitt, Carl, "A Real-Time Garbage Collector Based on the Lifetimes of Objects", in: Communications of the ACM (June 1983) 26, 6, pp.419-429.
* [2] Quarterman, John S., Silbershatz, Abraham, Peterson, James L., "4.2BSD and 4.3BSD as Examples of the UNIX System", in: ACM Computing Surveys (December 1985) Vol. 17 No. 4 pp.379-418.
* [3] Rees, Jonathan A., and Adams, Norman I., IV, "T: a Dialect of Lisp or, Lambda: The Ultimate Software Tool", in: Proceedings of the 1982 ACM Symposium on Lisp and Functional Programming (August 1982).
* [4] Bishop, Peter B., Computers with a Large Address Space and Garbage Collection (MIT, Cambridge, MA, May 1977) MIT/LCS/TR-178.
* [5] Smith, Vernon L., "Experimental Methods in the Political Economy of Exchange", in: Science (10 October 1986) Vol. 234, pp.167-173.
* [6] Friedman, Daniel, "On the Efficiency of Experimental Double Auction Markets", in: American Economic Review (March 1984) Vol. 24, No. 1, pp. 60-72.
* [7] Theriault, D., Issues in the Design and Implementation of Act 2 (MIT AI Lab, Cambridge, MA., 1983) AI-TR-728.
* [8] Kornfeld, William A., "Using Parallel Processing for Problem Solving" (MIT AI Lab, Cambridge, MA, 1979) MIT-AI-561.
* [9] Ungar, David Michael, The Design and Evaluation of a High Performance Smalltalk System (MIT Press, Cambridge, MA, 1987).
* [10] Axelrod, Robert, The Evolution of Cooperation (Basic Books, New York, 1984).
* [11] Agha, Gul, Actors: A Model of Concurrent Computation in Distributed Systems (MIT Press, Cambridge, MA, 1986).
* [12] Raffia, Howard, Decision Analysis: Introductory Lectures on Choices under Uncertainty (Addison-Wesley, Reading, MA, 1970).
* [13] Dawkins, Richard, The Selfish Gene (Oxford University Press, New York, 1976).
* [14] Hofstadter, Douglas R., "Dilemmas for Superrational Thinkers, Leading Up to a Luring Lottery", in: Metamagical Themas: Questing for the Essence of Mind and Pattern (Basic Books, New York, 1985) pp. 739-755.
* [15] Genesereth, M. R., Ginsberg, M. L., and Rosenschein, J. S., Cooperation without Communication (1984) HPP Report 84-41.
* [16] Shapiro, Ehud, (ed.), Concurrent Prolog: Collected Papers (MIT Press, Cambridge, MA, 1987) in press.
* [17] Hirsh, Susan, Kahn, Kenneth M., and Miller, Mark S., Interming: Unifying Keyword and Positional Notations (Xerox PARC, Palo Alto, CA, 1987) in press.

## Comparative Ecology: A Computational Perspective 

>A long-standing dream in the field of artificial intelligence has been to use evolutionary processes to produce systems of greater competence than those we can directly design. This paper compares different evolutionary models--such as biological ecosystems, markets, and EURISKO--with respect to this goal. This comparison suggests that a form of ecosystem here termed a direct market (as opposed to the indirect market of human society) is a promising basis for computational ecosystems.
        
* [Comparative Ecology Abstract](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ce/ce0.html) (3k)

>A long-standing dream in the field of artificial intelligence has been to use evolutionary processes to produce systems of greater competence than those we can directly design. This paper compares different evolutionary models-such as biological ecosystems, markets, and EURISKO-with respect to this goal. This comparison suggests that a form of ecosystem here termed a direct market (as opposed to the indirect market of human society) is a promising basis for computational ecosystems. Related papers [I,II] in this book elaborate a vision of direct computational markets termed agoric open systems.

* [Introduction](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ce/ce1.html) (8k)

>Ecosystems discussed in this paper include Axelrod's iterated prisoner's dilemma game [5], which can serve as a sort of E. coli of ecosystems, and biological ecosystems, which are familiar enough to serve as a point of reference for the rest. Others discussed are Lenat's EURISKO program [III,6], political ecosystems, and what will here be termed direct and indirect market ecosystems. Markets are the central theme-other ecosystems are compared to markets, and markets themselves are generalized from existing human systems to proposed computational systems.

* [Evolution in ecosystems](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ce/ce2.html) (12k)

> The Axelrod tournament Robert Axelrod developed an ecosystem in which the entities interact in rounds of iterated prisoner's dilemma games [5]. To understand it, one must first understand the dilemma itself. Instead of the traditional scenario of prisoners being interrogated, Hofstadter's illustration with the following scenario seems more intuitive.

>Two dealers arrange to trade items. Each dealer agrees to place his item in a bag and leave it at a designated place to be retrieved by the other dealer. The dilemma presents itself when each dealer considers how best to interact with the other-given that they are strangers, will not meet face to face for this exchange, and will never deal with each other in the future. As Hofstadter describes, each dealer reasons as follows:

>"`If the [other] dealer brings a full bag, I'll be better off having left an empty bag, because I'll have gotten all that I wanted and given away nothing. If the dealer brings an empty bag, I'll be better off having left an empty bag, because I'll not have been cheated. I'll have gained nothing but lost nothing either. Thus it seems that no matter what the dealer chooses to do, I'm better off leaving an empty bag. So I'll leave an empty bag.' . . .And so both of you, with your impeccable (or impeccable-seeming) logic, leave empty bags, and go away empty handed. How sad, for if you both had just cooperated, you could have each gained something you wanted to have. Does logic prevent cooperation? This is the issue of the Prisoner's Dilemma." [emphasis in the original] [9]

>The underlying strategic situation can be made precise in the following fashion: In a single prisoner's dilemma interaction, two players each choose between moves (termed cooperate and defect) in ignorance of the other's choice. If both cooperate, both are rewarded (in Axelrod's case, with a payoff of 3 points). If one cooperates and the other defects, the defector receives an even greater reward (5 points), while the cooperator receives nothing (0 points). If both defect, both are punished (by receiving only 1 point).

>In a single move, each player has an incentive to defect regardless of the other player's move, but double-cooperation is better than double-defection. Overall, pairs of players that cooperate earn higher scores than those that do not.

>In an iterated prisoner's dilemma game, two players go through a long series of moves, and can base their actions on the history of play. When one expects (and hopes for) further transactions with the other party, simple defection no longer seems as attractive. Indeed, by running a computer tournament, Axelrod showed that the logic of an iterated prisoner's dilemma actually fosters cooperation.

>Robert Axelrod ran a Computer Prisoner's Dilemma Tournament based on the above rules. A diverse group of game theorists were invited to submit programs to play against each other in a round-robin of games, each averaging 200 single moves. After the first tournament, Axelrod circulated the results-including the nature of the winning program, judged by cumulative points-and solicited entries for a second tournament.

>Axelrod's pair of tournaments may be described as a simple evolutionary ecosystem. The replicators were the programs themselves (or the strategies those programs embody), the variation mechanism was human ingenuity (since programs were modified between tournaments), and the selection criterion during a tournament was simply the number of points earned. Programs interacted with each other in an environment imposing certain rules, and their success depended on each others' behavior. Further, Axelrod went on to simulate the population dynamics of a set of programs, given the assumption that points earned determined the "population density" of that program in the next time period.

>In both tournaments a very simple program won. That program was TIT FOR TAT, submitted by psychologist Anatol Rapoport. In the population dynamics simulation, the success of TIT FOR TAT was even more pronounced. Analyzing TIT FOR TAT's success can suggest how to analyze other ecosystems.

* [Evolutionarily stable strategies](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ce/ce3.html) (6k)

> A single population-dynamics process can be described as an ecosystem, but not as an evolutionary ecosystem, since there is no source of variation. Axelrod's series of two tournaments included variation from one to the next, and hence qualifies. To transform it into a better example of an evolutionary ecosystem, imagine a continuing tournament open to outside contestants able to create new strategies and introduce them in small numbers. In any such open, evolving ecosystem, given no special restrictions on allowable variations, one should expect the ecosystem to become populated primarily by an ESS. The properties of such an ESS will often indicate emergent properties of the system. For example, in any open Axelrod ecosystem most moves will be cooperative.

>The above discussion of Axelrod's system benefits from hindsight. The original game-theory experts who submitted the original strategies knew the rules, and those who submitted strategies for the second tournament even had the benefit of a bit of hindsight from the first tournament. Nevertheless, in both cases most of the strategies submitted were not nice, and so were not ESSs. The analyses which follow cover much more complex ecosystems, in which the nature of strategies and payoffs are much more subtle.

* [Biological and market ecosystems](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ce/ce4.html) (30k)

>Biological and market ecosystems both contain a mixture of symbiotic and negative-sum relationships. This paper argues that biological ecosystems involve more predation, while idealized market ecosystems involve more symbiosis. Indeed, one can make a case that this is so even for human market ecosystems-that biological ecosystems are, overall, dominated by predation, while market ecosystems are, overall, dominated by symbiosis.

>In human markets (as in idealized markets) producers within an industry compete, but chains of symbiotic trade connect industry to industry. Competition in biology likewise occurs most often among those occupying the same niche, but here, it is predation that connects from niche to niche. Because of the lack of reputations and trademarks, symbiosis in biology occurs most often in situations where the "players" find themselves in a highly-iterated game. In the extreme, the symbiotic system itself becomes so tightly woven that it is considered a single organism-as with lichens composed of fungi and algae, or animals composed of eukaryotic cells containing mitochondria. Predation, of course, links one symbiotic island to the next.

* [EURISKO and markets](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ce/ce5.html) (15k)

>Lenat's EURISKO system [6] may be viewed as an ecosystem in which the replicators are interacting, evolving heuristics-that is, evolving, computational rules of thumb. Two kinds of heuristics populate EURISKO: object-level heuristics whose subject domain is some topic to be explored (such as war games or three-dimensional VLSI), and meta-heuristics whose subject domain is heuristics. Variation occurs as meta-heuristics create new heuristics from old ones via mutation, and selection occurs as meta-heuristics judge and determine the "interestingness" of heuristics (a numeric value associated with a heuristic). This quantity determines allocation of processing resources, so heuristics compete for survival and influence based on their degree of "interestingness". 

* [Memes and markets: direct and indirect market ecosystems](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ce/ce6.html) (11k)

>Human cultures evolve. Their replicators are any of the information patterns which make up a culture, and which spread (with variation) from human to human via imitation. By analogy with genes, these replicators are known as memes [7]; they include ideas, beliefs, habits, morals, fashions, designs, techniques, jokes, and more. Any pattern which can spread via imitation is a meme, even if its human host cannot articulate it or is unaware of its existence.

>It is important to recognize that the replicators of human culture are memes, not people. The lack of this distinction has led to the unfortunate confusion called "social darwinism". Our ability to change our minds allows cultural evolution to proceed not by selection of humans, but, as Karl Popper says, by "letting our theories die in our stead" [4].

* [Computational legal systems and markets](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ce/ce7.html) (20k)

Like human markets, direct computational markets will have many problems. Computational markets are enough like human societies that it is worth examining mechanisms-such as law and regulation-used by human societies to try to deal with these problems. However, these analogies must be used with care-there are also many differences between human and computational markets.

* [Conclusions](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ce/ce8.html) (3k)

>Although evolutionary reasoning is most often applied to biological ecosystems, it is also of use in understanding human markets, culture, and politics, and adaptive computational systems such as EURISKO. By assuming that an ecosystem's foundational rules will shape its evolutionarily stable strategies, and that these strategies will dominate behavior in the ecosystem, one can relate foundations to emergent properties-including properties sought by a designer. This paper has examined a variety of evolutionary ecosystems and compared them with "direct, idealized-market ecosystems"; for the purpose of evolving useful computational behavior, the latter have strong advantages. Other papers in this volume explore the implementation and properties of computational markets of this sort in greater depth [I,II]. 

* [References](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers/ce/ce.refs.html) (20k)

Papers referenced with roman numerals can be found in the present volume: Huberman, Bernardo (ed.), Ecology of Computation (Elsevier Science Publishers/North-Holland, 1988).
* [I] Miller, Mark S., and Drexler, K. Eric, "Markets and Computation: Agoric Open Systems", this volume.
* [II] Miller, Mark S., and Drexler, K. Eric, "Incentive Engineering for Computational Resources", this volume.
* [III] Lenat, Douglas B. and Brown, John Seely,, "Why AM and EURISKO Appear to Work", this volume.
* [IV] Kahn, Kenneth, and Miller, Mark S., "Language Design and Open Systems", this volume.
* [V] Rashid, Richard F., "From RIG to Accent to Mach: The Evolution of a Network Operating System", this volume.
* [VI] Perlis, Alan, "The Evolution of Software Systems", this volume.
* [VII] Stefik, Mark, "The Next Knowledge Medium", this volume.
* [1] Dawkins, Richard, "The Blind Watchmaker: Why the Evidence of Evolution Reveals a Universe Without Design (W.W. Norton and Company, New York, 1986
* [2] Hayek, Friedrich A., "Cosmos and Taxis", in: Law, Legislation and Liberty, Vol. 1: Rules and Order (University of Chicago Press, Chicago, 1973) pp.35-54.
* [3] Gardner, Martin, Wheels, Life, and Other Mathematical Amusements (W. H. Freeman, New York, 1983).
* [4] Popper, Karl R., "Evolutionary Epistomology", in Miller, David, (ed.), Popper Selections (Princeton University Press, Princeton NJ, 1985) pp.78-86.
* [5] Axelrod, Robert, The Evolution of Cooperation (Basic Books, New York, 1984).
* [6] Lenat, Douglas B., "The Role of Heuristics in Learning by Discovery: Three Case Studies",in Michalski, Ryszard S., Carbonell, Jaime G., and Mitchell, Tom M. (eds.), Machine Learning: An Artificial Intelligence Approach (Tioga Publishing Company, Palo Alto, CA, 1983) pp.243-306.
* [7] Dawkins, Richard, The Selfish Gene (Oxford University Press, New York, 1976).
* [8] Wilson, Edward O., Sociobiology (Belknap Press/ Harvard University Press, Cambridge, MA, 1975).
* [9] Hofstadter, Douglas R., "The Prisoner's Dilemma Computer Tournaments and the Evolution of Cooperation", in Metamagical Themas: Questing for the Essence of Mind and Pattern (Basic Books, New York, 1985) pp.715-716.
* [10] Smith, Maynard J. and Price, G.R., "The Logic of Animal Conflicts", in Nature (1973) 246, pp.15-18.
* [11] Drexler, K. Eric, "Molecular Engineering: An Approach to the Development of General Capabilities for Molecular Manipulation", in: Proceedings of the National Academy of Science USA (Sept. 1981) Vol. 78, No 9, pp. 5275-5278.
* [12] Drexler, K. Eric, Engines of Creation (Anchor Press/Doubleday, Garden City, New York, 1986).
* [13] Rivest, R., Shamir, A., and Adelman, L., "A Method for Obtaining Digital Signatures and Public-Key Cryptosystems" in: Communications of the ACM (Feb. 1978) Vol. 21, No. 2, pp. 120-126.
* [14] Miller, Mark S.; Bobrow, Daniel G.; Tribble, Eric Dean; and Levy, Jacob, "Logical Secrets", in Shapiro, Ehud, (ed.), Concurrent Prolog: Colected Papers (MIT Press, Cambridge, MA, 1987) in press.
* [15] Hayek, Friedrich A., Denationalisation of Money (The Institute of Economic Affairs, Westminster, London, 1978, Second Edition).
* [16] Keynes, John Maynard, The General Theory of Employment, Interest, and Money (Harcourt Brace Jovanovich, San Diego, CA, 1964).
* [17] Wickler, Wolfgang, Mimicry in Plants and Animals (World University Library/ MaGraw-Hill, New York, 1968).
* [18] Dawkins, Richard, The Extended Phenotype (Oxford University Press, New York, 1982).
* [19] Holland, John H., Holyoak, Keith J., Nisbett, Richard E., and Thagard, Paul R., Induction: Processes of Inference, Learning, and Discovery (MIT Press, Cambridge, MA, 1986).
* [20] Ames, Bruce N., Magaw, Renae, and Gold, Lois Swirsky, "Ranking Possible Carcinogenic Hazards", in Science (17 April 1987) Vol. 236, pp. 271-285.
* [21] Nisbett, Richard, and Ross, Lee, Human Inference: Strategies and Shortcomings of Social Judgment (Prentice-Hall, Englewood Cliffs, NJ, 1980).
* [22] Haase, Kenneth W., Jr., "Discovery Systems", in ECAI '86: The 7th European Conference on Artificial Intelligence (July 1986) Vol. 1, pp. 546-555.
* [23] Hardin, Garret, "The Tragedy of the Commons", in Science (13 December 1968) Vol. 162, pp. 1243-1248.
* [24] Tullock, Gordon, The Organization of Inquiry (Duke University Press, Durham, NC, 1966).
* [25] Nelson, Theodor, Literary Machines (published by author, version 87.1, 1987, available from Project Xanadu, 8480 Fredricksburg #8, San Antonio, TX 78229. Available as hypertext on disk from Owl International, 14218 NE 21st St., Bellevue, WA 98007. 1981).
* [26] Drexler, K., Eric, Hypertext Publishing and the Evolution of Knowledge (Foresight Institute, Los Altos, CA, 1986).
* [27] Kornfield, William A., and Hewitt, Carl, "The Scientific Community Metaphor", in IEEE Transactions on Systems, Man, and Cybernetics (IEEE, 1981) SMC-11, pp. 24-33.
* [28] Kornfield, William A., "Using Parallel Processing for Problem Solving" (MIT AI Lab, Cambridge, MA, 1979) MIT-AI-561.
* [29] Hayek, Friedrich A., Unemployment and Monetary Policy: Government as a Generator of the "Business Cycle" (Cato Institute, San Francisco, CA, 1979).
* [30] Friedman, David, The Machinery of Freedom: Guide to a Radical Capitalism (Harper and Row, New York, 1973).
* [31] Friedman, Milton, and Schwartz, Anna, "The Great Contraction", in A Monetary History of the United States, 1867-1960 (Princeton University Press/ National Bureau of Economic Research, 1963) Chap. 7.
* [32] McGee, John S., "Predatory Price Cutting; The Standard Oil (NJ) Case", in Journal of Law and Economics (October 1958) 1, 137.
* [33] Epstein, Richard A., Takings: Private Property and the Power of Eminent Domain (Harvard University Press, Cambridge, MA, 1985).
* [34] Buchanan, James M. and Tullock, Gordon, The Calculus of Consent: Logical Foundations of Constitutional Democracy (University of Michigan Press, Ann Arbor, MI, 1965).
* [35] Tullock, Gordon, The Vote Motive (The Institute of Economic Affairs, Westminster, London, 1976).
