---
layout: single
title: Mark Sam Miller
description: "co-creator of the Agoric Paradigm of market-based distributed secure computing; and the open-source coordinator of the E programming language. He also designed the Caja programming language."
excerpt: "Mark S. Miller is an American computer scientist. He is known for his work as one of the participants in the 1979 hypertext project known as Project Xanadu; for inventing Miller columns; as the co-creator of the Agoric Paradigm of market-based distributed secure computing; and the open-source coordinator of the E programming language. He also designed the Caja programming language."
toc: false
classes: wide
share: true
last_modified_at: 2019-06-25T11:22:33-23:00
categories: ["Object Capabilities", "Smart Contracts"]
tags: ["Mark Miller", "Agoric"]
toc_sticky: true
permalink: /posts/agoric/mark-miller/
redirect_from:  
  - /posts/crypto/e-rights/
  - /archive/blockchain/agoric/
canonical_url: "https://agoric-records.xyz/posts/mark-miller/"
---


## Mark S Miller

>Mark S. Miller is an American computer scientist. He is known for his work as one of the participants in the 1979 hypertext project known as Project Xanadu; for inventing Miller columns; as the co-creator of the Agoric Paradigm[1] of market-based distributed secure computing; and the open-source coordinator of the E programming language. He also designed the Caja programming language.
>
>Miller earned a BS in computer science from Yale in 1980 and published his Johns Hopkins PhD thesis in 2006.[2] Previously Chief Architect with the Virus-Safe Computing Initiative at HP Labs, he is now a research scientist at Google[3] and a member of the ECMAScript (JavaScript) committee.[4] - [Wikipedia](https://en.wikipedia.org/wiki/Mark_S._Miller)

* [twitter.com/marksammiller](https://twitter.com/marksammiller)
  * [ai.google/research/people/author35958](https://ai.google/research/people/author35958)
  * [agoric.com/authors/mark-s-miller](https://agoric.com/authors/mark-s-miller/)
* [The Agoric Papers](https://e-drexler.com/d/09/00/AgoricsPapers/agoricpapers.html)
  > These three papers by Mark S. Miller and K. Eric Drexler appeared in The Ecology of Computation, Bernardo Huberman (ed.) Elsevier Science Publishers/North-Holland, 1988. 
* [Mark Miller: Agoric and the Decades-Long Quest for Secure Smart Contracts.](https://epicenter.tv/episode/286/) -Epicenter Podcast


### Dissertation

* [Robust Composition: Towards a Unified Approach to Access Control and Concurrency Control](http://www.erights.org/talks/thesis/markm-thesis.pdf) by Mark Samuel Miller 
  - A dissertation submitted to Johns Hopkins University in conformity with the requirements for the degree of Doctor of Philosophy.

#### 27.1  Contributions

> This dissertation makes seven primary contributions:
> * The object-capability model, a new model of secure computation that is abstract enough to describe both prior object-capability languages and operating systems, and concrete enough to describe authority-manipulating behavior.
> * A novel approach to concurrency control in terms of attenuating authority, including a unified architecture in which both access control and concurrency control concerns may be addressed together.
> * A clearly framed distinction between “permission” and “authority.” We develop a taxonomy of computable bounds on eventual permission and authority, enabling us to reason about many simple access abstractions. Using this framework, we provide a unified account of access control and authority in distributed systems consisting of object-capability islands sending messages to each other over a cryptographic capability sea.
> * A system of reference states, transition rules, and message delivery properties associated with each state, that reify partial failures in a manner that permits robust application-level recovery. In E, these are coupled to language constructs that enable programmers to anticipate and handle distributed plan failures at the syntactic locus where a dependency on remote behavior is introduced. These same syntactic constructs alert the programmer of the loci where interleavings of execution may occur.
> * A generalization of prior work on promise pipelining from asymmetric client-serversystems to symmetric peer-to-peer systems. Promises enable explicit expression ofdataflow in distributed computation. Promise pipelining enables this computationalstructure to be exploited without cascading round trips.
> * An adaptation of non-signaling errors to the propagation of broken references, allowingprogrammers to consistently defer handling of reference failure when direct defense is inappropriate, and to compose chains of data-dependent computation whose referencefailure propagation has a sensible semantics. By providing a coherent error reporting behavior for promise pipelines, this mechanism provides a manageable foundation forrecovery from delayed errors in distributed dataflow computations.
> * Finally, we introduce E-ORDER, a message delivery ordering constraint that achieves an enforceable middle ground between CAUSAL and FIFO message orderings. The resulting ordering is strong enough to prevent adversaries from exploiting race conditions to obtain inappropriate access, but weak enough to be enforceable. We show how the delivery ordering may be defined in terms of an attenuation of the authority provided by passed references. This allows us to reason about the effects of messaging within our unified model of concurrency and access control. 
>
> Several programming systems described in Chapter 26 have adopted (in varying subsets) each of the contributions noted above by borrowing elements from the E system. Twisted Python, in particular, is reported to be in use in more than 50 real-world applications at the time of this writing.

#### Bibliography

* [AW04] Mart ́ın Abadi and Ted Wobber. A Logical Account of NGSCB. InProc. For-mal Techniques for Networked and Distributed Systems – Forte 2004. Springer-Verlag, Berlin Germany, September 2004.
* [Bej96] Arturo Bejar.  The Electric Communities Distributed Garbage Collector,1996. www.crockford.com/ec/dgc.html.
* [BH77] Henry G. Baker, Jr. and Carl E. Hewitt. The Incremental Garbage Collectionof Processes. InProc. International Joint Conference on Artificial Intelligence,pages 55–59, Cambridge, Massachusetts, August 1977. IJCAI.
* [Bir05] Kenneth P. Birman.Reliable Distributed Systems. Springer Verlag, 2005.
* [BJ87] Ken Birman and T. Joseph. Exploiting Virtual Synchrony in Distributed Sys-tems. InSOSP ’87: Proc. Eleventh ACM Symposium on Operating SystemsPrinciples, pages 123–138, New York, NY, USA, 1987. ACM Press.
* [BL94] Phillip Bogle and Barbara Liskov. Reducing Cross Domain Call OverheadUsing Batched Futures. InOOPSLA ’94: Proc. Ninth Annual Conference onObject-Oriented Programming Systems, Language, and Applications, pages341–354, New York, NY, USA, 1994. ACM Press.
* [Bla85] Andrew P. Black.  Supporting Distributed Applications:  Experience withEden. InProc. Tenth Annual Symposium on Operating Systems Principles,pages 181–193. ACM, December 1985.
* [BNOW94] Andrew Birrell, Greg Nelson, Susan Owicki, and Edward Wobber. NetworkObjects. InProc. Fourteenth ACM Symposium on Operating Systems Princi-ples, pages 217–230, Asheville, NC, 1994. ACM Press.
* [Boe84] W. E. Boebert. On the Inability of an Unmodified Capability Machine to En-force the *-property. InProc. 7th DoD/NBS Computer Security Conference,pages 291–293, Gaithersburg, MD, USA, September 1984. National Bureauof Standards.
* [Boe03] Earl Boebert. Comments on Capability Myths Demolished, 2003. www.eros-os.org/pipermail/cap-talk/2003-March/001133.html.
* [Boe05] Hans-J. Boehm. Threads Cannot be Implemented as a Library.SIGPLANNotices, 40(6):261–268, 2005.
* [Bre73] T. H. Bredt. A Survey of Models for Parallel Computing. Technical ReportCSL-TR-70-8, Stanford University Computer Systems Laboratory, Stanford,CA, December 1973.
* [BS79] Matt Bishop and Lawrence Snyder.  The Transfer of Information and Au-thority in a Protection System. InProc. 7th ACM Symposium on OperatingSystems Principles, pages 45–54, December 1979.  Published as OperatingSystem Review, Vol 13, No 4.188
* [BST89] H. E. Bal, J. G. Steiner, and A. S. Tanenbaum. Programming Languages forDistributed Computing Systems.ACM Computing Surveys, 21(3):261–322,September 1989.
* [Car97] Luca Cardelli. Program Fragments, Linking, and Modularization. InThe 24thACM SIGPLAN-SIGACT Symposium on Principles of Programming Lan-guages, pages 266–277, Paris, January15–17 1997.
* [CC96] Antonio Cau and Pierre Collette.  Parallel Composition of Assumption-Commitment Specifications: A Unifying Approach for Shared Variable andDistributed Message Passing Concurrency.Acta Informatica, 33(2):153–176,1996.
* [CDM01] A. Chander, D. Dean, and J. Mitchell. A State-Transition Model of TrustManagement and Access Control. In14th IEEE Computer Security Founda-tions Workshop, Cape Breton, Nova Scotia, June 2001.
* [CF91] R. Cartwright and M. Fagan. Soft Typing. InProc. SIGPLAN ’91 Conferenceon Programming Language Design and Implementation, pages 278–292, 1991.
* [Chu41] Alonzo Church.The Calculi of Lambda Conversion. Number 6 in Annals ofMathematical Studies. Princeton University Press, 1941.
* [CL85] K. Mani Chandy and Leslie Lamport. Distributed Snapshots: DeterminingGlobal States of Distributed Systems.ACM Transactions on Computer Sys-tems, 3(1):63–75, 1985.
* [CL02] Miguel Castro and Barbara Liskov. Practical Byzantine Fault Tolerance andProactive Recovery.ACM Transactions on Computer Systems, 20(4):398–461,2002.
* [Cli81] W. D. Clinger.Foundations of Actor Semantics. PhD thesis, Dept. of Math-ematics, Massachusetts Institute of Technology, Cambridge, MA, 1981.
* [Clo04a] Tyler Close. Decentralized Identification, 2004. www.waterken.com/dev/YURL/Definition/.
* [Clo04b] Tyler Close. Waterken YURL, 2004. www.waterken.com/dev/YURL/httpsy/.
* [Clo04c] Tyler Close. Web-calculus, 2004. www.waterken.com/dev/Web/.
* [Clo06] Tyler Close. Credit Transfer Within Market-based Resource Allocation In-frastructure. Tech Report HPL-2006-5, Hewlett Packard Laboratories, 2006.
* [Con67] Control Data Corporation.6400/6500/6600 Computer Systems; ReferenceManual. Control Data Corp., Documentation Dept., Palo Alto, CA, USA,revised May 1967 edition, 1967. ed-thelen.org/comp-hist/CDC-6600-R-M.html.
* [Cro97] Douglas Crockford, 1997. Personal communication.189
* [Cud99] Brian Cudahy.The Malbone Street Wreck. Fordham University Press, NewYork, 1999.
* [CW87] D. D. Clark and D. R. Wilson. A Comparison of Commercial and MilitaryComputer Security Policies. InProc. 1987 IEEE Symposium on Security andPrivacy, pages 184–195, 1987.
* [DA99] T. Dierks and C. Allen. The TLS protocol version 1.0, January 1999. InternetRFC 2246.
* [Den87] Daniel C. Dennett.The Intentional Stance. MIT Press, Cambridge, Mas-sachusetts, 1987.
* [DH65] J. B. Dennis and E. C. Van Horn.  Programming Semantics for Multipro-grammed Computations. Technical Report MIT/LCS/TR-23, M.I.T. Labo-ratory for Computer Science, 1965.
* [Dij72] Edsger W. Dijkstra. The Humble Programmer.Communications of the ACM,15(10):859–866, 1972.
* [Dij76] Edsger W. Dijkstra.A Discipline of Programming. Prentice-Hall, EnglewoodCliffs, New Jersey, 1976.
* [DLP79] Richard A. DeMillo, Richard J. Lipton, and Alan J. Perlis.  Social Pro-cesses and Proofs of Theorems and Programs.Communications of the ACM,22(5):271–280, 1979.
* [DN66] Ole-Johan Dahl and Kristen Nygaard. SIMULA - an ALGOL-based simula-tion language.Communications of the ACM, 9(9):671–678, 1966.
* [Don76] Jed Donnelley. A Distributed Capability Computing System, 1976.nersc.gov/∼jed/papers/DCCS/.
* [Don79] James E. Donnelley. Components of a Network Operating System.ComputerNetworks, 3:389–399, 1979.
* [DZK+02] Frank Dabek, Nickolai Zeldovich, Frans Kaashoek, David Mazieres, andRobert Morris.  Event-driven Programming for Robust Software.  InProc.10th ACM SIGOPS European Workshop, September 2002.
* [EA03] Dawson Engler and Ken Ashcraft.  RacerX: Effective, Static Detection ofRace Conditions and Deadlocks. InProc. 19th ACM Symposium on OperatingSystems Principles, pages 237–252, Bolton Landing, NY, October 2003.
* [EFL+99] Carl Ellison, Bill Frantz, Butler Lampson, Ronald Rivest, B. Thomas, andT. Ylonen. SPKI Certificate Theory (IETF RFC 2693), September 1999.
* [Ell96] Carl Ellison. Establishing Identity Without Certification Authorities. InProc.Sixth USENIX Security Symposium, pages 67–76, Berkeley, 1996. Usenix.
* [Eng97] Robert Englander.Developing Java Beans. O’Reilly & Associates, Inc., 981Chestnut Street, Newton, MA 02164, USA, 1997
* [ES90] Margaret A. Ellis and Bjarne Stroustrup.The Annotated C++ ReferenceManual. Addison-Wesley, 1990.
* [Fab74] R. S. Fabry.  Capability-based Addressing.Communications of the ACM,17(7):403–412, 1974.
* [FF02] Robert Bruce Findler and Matthias Felleisen. Contracts for higher-order func-tions.SIGPLAN Notices, 37(9):48–59, September 2002.
* [Fie00] Roy Thomas Fielding.Architectural Styles and the Design of Network-basedSoftware Architectures. PhD thesis, Dept. of Information and Computer Sci-ence, University of California at Irvine, 2000.
* [Fro03] A. Michael Froomkin. Toward a Critical Theory of Cyberspace.Harvard LawReview, 116(3):750–871, 2003. www.icannwatch.org/article.pl?sid=03/01/16/057208.
* [FW76a] Daniel P. Friedman and D. S. Wise.  Cons Should not Evaluate its Argu-ments.  In S. Michaelson and Robin Milner, editors,Automata, Languagesand Programming, pages 257–284. Edinburgh University Press, 1976.
* [FW76b] Daniel P. Friedman and David S. Wise. The impact of Applicative Program-ming on Multiprocessing. InProc. 1976 International Conference on Paral-lel Processing (ICPP’76), pages 263–272, Walden Woods, Michigan, August1976. IEEE.
* [GD72] G. Scott Graham and Peter J. Denning. Protection — Principles and Practice.Proc. Spring Joint Computer Conference, 40:417–429, 1972.
* [GHJV94] Erich Gamma, Richard Helm, Ralph Johnon, and John Vlissides. Design Patterns, Elements Of Reusable Object-Oriented Software. Addison Wesley,1994.
* [GK76] Adele Goldberg and Alan Kay. Smalltalk-72 Instruction Manual. TechnicalReport SSL 76-6, Learning Research Group, Xerox Palo Alto Research Center,1976.
* [GMPS97] L. Gong, M. Mueller, H. Prafullchandra, and R. Schemers. Going Beyondthe Sandbox: An Overview of the New Security Architecture in the JavaDevelopment Kit 1.2. InUSENIX Symposium on Internet Technologies andSystems, pages 103–112, Monterey, CA, 1997.
* [Gon89] Li Gong. A Secure Identity-based Capability System. InProc. 1989 IEEESymposium on Security and Privacy, pages 56–65, 1989.
* [Gon99] Li Gong.Inside Java 2 Platform Security. The Java Series. Addison Wesley,1999.
* [GR83] Adele Goldberg and David Robson.Smalltalk-80, The Language and its Im-plementation. Addison-Wesley, Reading, MA, 1983.
* [Gra73] Mark Granovetter. The Strength of Weak Ties.American Journal of Sociol-ogy, 78:1360–1380, 1973.
* [Gra86] Jim Gray.  Why Do Computers Stop and What Can Be Done About It?InProc. 5th Symposium on Reliability in Distributed Software and DatabaseSystems, Los Angeles, CA, January 1986.
* [Gut04] Peter Gutmann.Cryptographic Security Architecture: Design and Verifica-tion. Springer Verlag, 2004.
* [Hal85] Robert H. Halstead, Jr.  Multilisp: A Language for Concurrent SymbolicComputation.ACM Transactions on Programming Languages and Systems,7(4):501–538, October 1985.
* [Han93] Per Brinch Hansen. Monitors and Concurrent Pascal: a Personal History. InHOPL-II: The Second ACM SIGPLAN Conference on History of Program-ming Languages, pages 1–35, New York, NY, USA, 1993. ACM Press.
* [Har85] Norman Hardy. KeyKOS Architecture.SIGOPS Operating Systems Review,19(4):8–25, 1985.
* [Har88a] Norm Hardy.  The Confused Deputy.Operating Systems Review, October1988.
* [Har88b] David Harel. On Visual Formalisms.Communications of the ACM, 31(5):514–530, 1988.
* [Hay37] Friedrich Hayek.  Economics and Knowledge.Economica IV, pages 33–54,1937.
* [Hay45] Friedrich Hayek.  The Uses of Knowledge in Society.American EconomicReview, 35:519–530, September 1945.
* [Hay64] Friedrich Hayek.  The Theory of Complex Phenomena.  In M Bunge, edi-tor,The Critical Approach to Science and Philosophy, pages 332–349. CollierMcMillan, London, 1964.
* [HB78] Carl Hewitt and Henry Baker. Actors and Continuous Functionals. In E. J.Neuhold, editor,Formal Description of Programming Concepts, pages 367–390. North-Holland, Amsterdam, 1978.
* [HBS73] Carl Hewitt, Peter Bishop, and Richard Steiger. A Universal Modular AC-TOR Formalism for Artificial Intelligence. In Nils J. Nilsson, editor, Proc. 3rd International Joint Conference on Artificial Intelligence, pages 235–245, Standford, CA, August 1973. William Kaufmann.
* [HDH03] Martin Hirzel, Amer Diwan, and Matthew Hertz. Connectivity-based GarbageCollection. InProc. ACM SIGPLAN Conference on Object-Oriented Programming, Systems, Languages, and Applications (OOPSLA ’03), pages 359–373,2003.
* [Hew77] Carl Hewitt. Viewing Control Structures as Patterns of Passing Messages. Journal of Artificial Intelligence, 8(3):323–364, 1977.
* [Hew85] Carl Hewitt. The Challenge of Open Systems: Current Logic Programming Methods May be Insufficient for Developing the Intelligent Systems of theFuture. BYTE, 10(4):223–242, 1985.
* [Hoa65] C.A.R Hoare. Record Handling, in Algol Bulletin 21.3.6, 1965.
* [Hoa69] C. A. R. Hoare. An Axiomatic Basis for Computer Programming. Commu-nications of the ACM, 12(10):576–580, 583, October 1969.
* [Hoa74] C. A. R. Hoare. Monitors: an Operating System Structuring Concept. Communications of the ACM, 17(10):549–557, 1974.
* [Hoa78] C. A. R. Hoare. Communicating Sequential Processes. Communications of the ACM, 21(8):666–677, 1978.
* [HP97] Lenwood S. Heath and Sriram V. Pemmaraju. Stack and Queue Layoutsof Posets. SIJDM: SIAM Journal on Discrete Mathematics, 10(4):599–625, November 1997.
* [HPW03] Michael Howard, Jon Pincus, and Jeannette Wing. Measuring Relative Attack Surfaces. Technical Report CMU-TR-03-169, Carnegie Mellon University, August 2003. Proc. 2003 Workshop on Advanced Developments in Software and Systems Security. www.cs.cmu.edu/∼wing/publications/Howard-Wing03.pdf.
* [HRB+87] Norman C. Hutchinson, Rajindra K. Raj, Andrew P. Black, Henry M. Levy,and Eric Jul. The Emerald Programing Lanuage Report. Technical Report 87-10-07, Department of Computer Science, University of Washington, Seattle,October 1987.
* [HRU75] Michael A. Harrison, Walter L. Ruzzo, and Jeffrey D. Ullman. On Protectionin Operating Systems. InThe Symposium on Operating Systems Principles,pages 14–24, 1975.
* [HT91] Kohei Honda and Mario Tokoro. An Object Calculus for Asynchronous Communication. In European Conference on Object Oriented Programming, pages 133–147, 1991.
* [IBM68] IBM Corporation. IBM System/360 Principles of Operation. IBM Corpora-tion, San Jose, CA, USA, eighth edition, 1968.
* [IoEE85] American National Standards Institute, Institute of Electrical, and ElectronicEngineers. IEEE Standard for Binary Floating-Point Arithmetic.ANSI/IEEEStandard, Std 754-1985,New York, 1985.
* [JLS76] Anita K. Jones, Richard J. Lipton, and Lawrence Snyder. A Linear Time Algorithm for Deciding Security. InFoundations of Computer Science, pages 33–41, 1976.
* [Jon73] Anita K. Jones.Protection in Programmed Systems. PhD thesis, Departmentof Computer Science, Carnegie-Mellon University, June 1973.
* [Jon83] Cliff B. Jones.  Specification and Design of (Parallel) Programs.  InIFIPCongress, pages 321–332, 1983.
* [Jon03] Cliff B. Jones.  The Early Search for Tractable Ways of Reasoning aboutPrograms.IEEE Annals of the History of Computing, 25(2):26–49, 2003.
* [Kah96] William Kahan. Lecture Notes on the Status of the IEEE Standard 754 forBinary Floating Point Arithmetic. www.cs.berkeley.EDU/∼wkahan/ieee754status/ieee754.ps, 1996.
* [Kar03] Alan H. Karp. Enforce POLA on Processes to Control Viruses. Communications of the ACM, 46(12):27–29, 2003.
* [Kay93] Alan C. Kay. The Early History Of Smalltalk.SIGPLAN Notices, 28(3):69–95, 1993.
* [Kay98] Alan Kay. Prototypes vs. Classes, 1998. lists.squeakfoundation.org/pipermail/squeak-dev/1998-October/017019.html.
* [KCR98] R. Kelsey, W. Clinger, and J. Rees.  Revised5Report on the AlgorithmicLanguage Scheme.ACM Sigplan Notices, pages 26–76, 1998.
* [Key81] Key Logic, Inc. Gnosis Design Documentation, 1981. www.agorics.com/Library/KeyKos/Gnosis/keywelcome.html.
* [Key86] Key Logic, Inc.U.S. Patent 4,584,639: Computer Security System. U. S.Patent Office, 1986.
* [KGRB01] Alan H. Karp, Rajiv Gupta, Guillermo Rozas, and Arindam Banerji. The Client Utility Architecture: The Precursor to E-Speak. Technical Report HPL-2001-136, Hewlett Packard Laboratories, June 09 2001.
* [KGRB03] Alan H. Karp, R. Gupta, G. J. Rozas, and A. Banerji. Using Split Capabilitiesfor Access Control.IEEE Software, 20(1):42–49, January 2003.
* [KH84] P. A. Karger and A. J. Herbert. An Augmented Capability Architecture toSupport Lattice Security and Traceability of Access. InProc. 1984 IEEESymposium on Security and Privacy, pages 2–12, Oakland, CA, April 1984.IEEE.
* [KK02] Alan H. Karp and Vana Kalogeraki. The Client Utility as a Peer-to-Peer System. In Revised Papers from the NETWORKING 2002 Workshops on Web Engineering and Peer-to-Peer Computing, pages 260–273, London, UK,2002. Springer-Verlag.
* [KL86] Richard Y. Kain and Carl E. Landwehr. On Access Checking in CapabilitySystems. In Proc. 1986 IEEE Symposium on Security and Privacy, pages95–100, 1986.
* [KM66] Richard M. Karp and Raymond E. Miller. Properties of a Model for Parallel Computations: Determinacy, Termination, Queueing. SIAM J. Appl. Math., 14(6):1390–1411, November 1966.
* [KM88] Kenneth M. Kahn and Mark S. Miller. Language Design and Open Systems. In Bernardo A. Huberman, editor,Ecology of Computation. Elsevier Science Publishers, North-Holland, 1988.
* [Kri80] Saul A. Kripke. Naming and Necessity.  Library of Philosophy and Logic.Blackwell, Oxford, 1980.
* [KTMB87] Kenneth M. Kahn, E. Dean Tribble, Mark S. Miller, and Daniel G. Bo-brow. Vulcan: Logical Concurrent Objects. InResearch Directions in Object-Oriented Programming, pages 75–112. MIT Press, 1987.
* [Lac56] Ludwig Lachmann. Capital and its Structure. Kansas City: Sheed Andrewsand McNeel Inc., 1956.
* [Lam73] Butler W. Lampson. A Note on the Confinement Problem.Communicationsof the ACM, 16(10):613–615, 1973.
* [Lam74] Butler W. Lampson. Protection.Operating Systems Review, 8(1):18–24, January 1974.
* [Lam78] Leslie Lamport. Time, Clocks, and the Ordering of Events in a Distributed System. Communications of the ACM, 21(7):558–565, 1978.
* [Lam98] Leslie Lamport. The Part-time Parliament.ACM Transactions on Computer Systems, 16(2):133–169, 1998.
* [Lan92] Charles R. Landau. The Checkpoint Mechanism in KeyKOS. InProc. Second International Workshop on Object Orientation in Operating Systems, pages 86–91. IEEE, September 1992.
* [Lee06] Edward A. Lee. The Problem with Threads. Technical Report UCB/EECS-2006-1, EECS Department, University of California, Berkeley, January 102006. www.eecs.berkeley.edu/Pubs/TechRpts/2006/EECS-2006-1.html
* [Lef03] Glyph Lefkowitz. Generalization of Deferred Execution in Python, 2003. python.org/pycon/papers/deferex/.
* [Lev84] Henry M. Levy. Capability-based Computer Systems. Digital Press, 1984.
* [LG86] B. Liskov and J. Guttag.Abstraction and Specification in Program Develope-ment. MIT Press, Cambridge, Mass., 1986.
* [LN79] Hugh C. Lauer and Roger M. Needham. On the Duality of Operating System Structures. In Proc. 2nd International Symposium on Operating Systems, pages 3–19. IRIA, October 1979. ACM Operating System Review.
* [LS76] Butler W. Lampson and Howard E. Sturgis.  Reflections on an Operating System Design. Communications of the ACM, 19(4):251–265, May 1976.

    
## E Language an Object Capability Language

* [erights.org](http://www.erights.org/smart-contracts/)
* [wiki.c3.com - E Language An ObjectCapabilityLanguage](http://wiki.c2.com/?EeLanguage)
* [Mailing list ARChives— e-lang The E capability-secure scripting language](https://marc.info/?l=e-lang)
* [monte.readthedocs.io](https://monte.readthedocs.io/en/latest/)
  >* Monte is a programming language inspired by the E and Python programming languages. Monte aims to be:
  >* A reliable scaffold for secure distributed computing
  >* An example of capability-safe programming language design
  >* A model for misuse-resistant programming
* [news.ycombinator.com - E Programming Language](https://news.ycombinator.com/item?id=19981720#19985614)
  * [kentonv](https://news.ycombinator.com/item?id=19987621)
    >I'm always astounded by the depth to which Mark has explored this space. On more than a few occasions, I've come up with an interesting idea for a new protocol or programming language feature or piece of distributed systems infrastructure and told Mark about it, only to find he had already thought of that problem and discovered and solved several issues I hadn't even thought about yet.
    >
    >Cap'n Proto RPC [https://capnproto.org/rpc.html](https://capnproto.org/rpc.html) is based on E's network protocol, CapTP, e.g. utilizing The Four Tables:
    >
    >[http://erights.org/elib/distrib/captp/4tables.html](http://erights.org/elib/distrib/captp/4tables.html)
    >
    >[https://github.com/capnproto/capnproto/blob/master/c++/src/capnp/rpc.capnp#L116](https://github.com/capnproto/capnproto/blob/master/c++/src/capnp/rpc.capnp#L116)
    >
    >(You can think of this design as an extension of the file descriptor table concept in Unix, except that both sides may export descriptors to the other side (so that calls can flow either way), and either side can be responsible for assigning the numeric descriptor value for any particular description (which makes it easier to compensate for a high-latency transport).)
    >
    >When I first told Mark I was working on an object-oriented RPC protocol, he insisted I visit him and listen while he explained all this to me, and boy am I glad he did... would have taken a lot longer for me to figure it out myself.
    >
    >It's crazy that most of the content of erights.org was written over 10 years ago -- I think some of it goes back to the 90's, even.
  * [7373737373](https://news.ycombinator.com/item?id=19986189)
    > Modern smart contract systems should learn a lesson or five from it, most importantly, (object) capability security.
    >
    >Why? Because it lets programs handle permissions like other objects, keeping them apart and thus reducing the attack surface and preventing Confused Deputy [0] attacks. 
    >
    > [https://en.m.wikipedia.org/wiki/Confused_deputy_problem](https://en.m.wikipedia.org/wiki/Confused_deputy_problem)
  * [ghosthamlet - news.ycombinator](https://news.ycombinator.com/item?id=19987751)
    > The E on Common Lisp Project website is down, code on github: https://github.com/kpreid/e-on-cl
    >
    > e-on-javascript: https://github.com/kpreid/e-on-javascript


