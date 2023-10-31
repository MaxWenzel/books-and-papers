# Books and Papers
Must-read books and papers for developers

## Books

- [Software Architecture Books](https://github.com/mhadidg/software-architecture-books#system-architecture)

### Essentials
These are the essentials; any first-year junior developer should have read them:

- [Thomas & Hunt, The Pragmatic Programmer](https://www.amazon.de/Pragmatic-Programmer-journey-mastery-Anniversary/dp/0135957052/):
Probably the first book anyone should read. Lots of solid advice on how to become a professional software developer who gets stuff done.
- [Martin, Clean Code](https://www.amazon.de/Robert-Martin/dp/):
Writing code so that not only the compiler understands it. Essential practices that will shape your own style and required reading in many development organizations.
- [Bloch, Effective Java](https://www.amazon.de/Effective-Java-Joshua-Bloch/dp/0134685997/):
If you're programming Java, you have to read this book. Best Practices on how to use the language by Josh Bloch, who designed many features in modern Java.

### Advanced Topics
Pick and choose depending what you need and/or are interested in:

- [Gamma et al, Design Patterns. Elements of Reusable Object-Oriented Software](https://www.amazon.de/Erich-Gamma/dp/0201633612/):
An old book, but still the definitive reference on design patterns (when first reading it, pick the top 10 patterns, don't read it cover to cover). Alternatively, you can read - [Head First Design Patterns]():, which is easier, twice as long, and doesn't cover as many patterns.
- [Goetz, Java Concurrency in Practice](https://www.amazon.de/Java-Concurrency-Practice-Brian-Goetz/dp/0321349601/):
Anyone who builds Java services needs a basic understanding of concurrency. If you haven't read the book, you will most likely have already introduced concurrency bugs.
- [Nygard, Release It! Design and Deploy Production-Ready Software](https://www.amazon.de/Release-Design-Deploy-Production-Ready-Software/dp/1680502395/):
Best practices for delivering robust software that doesn't fail in the production environment.
- [Fowler, UML Distilled: A Brief Guide to the Standard Object Modeling Language](https://www.amazon.de/UML-Distilled-Standard-Addison-wesley-Technology/dp/0321193687/):
Learn how to use UML in a pragmatic way. This very short book covers everything you ever need to know on the subject.
- [Fowler, Patterns of Enterprise Application Architecture](https://www.amazon.de/Martin-Fowler/dp/0321127420/)
- [Grikorik, High Performance Browser Networking](https://hpbn.co/):
This online book covers networking in general (not just browser-based) and gives you all the basics you'd typically learn in a two-semester networking course.
- [Evans, Domain-Driven Design: Tackling Complexity in the Heart of Software](https://www.amazon.de/Domain-Driven-Design-Tackling-Complexity-Software/dp/0321125215/):
How to model your business domain in alignment with your business stakeholders. One of the most influential books in software design to date.
- [Hohpe, Woolf: Enterprise Integration Patterns: Designing, Building, and Deploying Messaging Solutions](https://www.amazon.de/Enterprise-Integration-Patterns-Designing-Deploying/dp/0321200683): Enterprise Integration Patterns provides an invaluable catalog of sixty-five patterns, with real-world solutions that demonstrate the formidable of messaging and help you to design effective messaging solutions for your enterprise.

### Online

- [SERVERLESS HANDBOOK](https://serverlesshandbook.dev/): a resource teaching frontend engineers everything they need to know to dive into backend
- [Hands-on Scala Programming](https://www.handsonscala.com/): Hands-on Scala teaches you how to use the Scala programming language in a practical, project-based fashion
- [Git Book](https://git-scm.com/book/en/v2): the entire Pro Git book
- [The outstanding developer](https://theoutstanding.dev/): boost your soft skills to become a better developer
- [Scala from Scratch](https://leanpub.com/scala-from-scratch-exploration)
- [OAuth 2.0 Simplified](https://www.oauth.com/): a guide to building an OAuth 2.0 server. Through high-level overviews, step-by-step instructions, and real-world examples, you will learn how to take advantage of the OAuth 2.0 framework while building a secure API.
- [Dev Concepts](https://dev-concepts.dev/): a 12 volumes e-book collection explaining every concept of Software Development
- [Getting Real](https://basecamp.com/books/getting-real): A must read for anyone building a web app.
- [Versioning in Event Sourced System](https://leanpub.com/esversioning/read)

### Free eBooks

- [Kong](https://konghq.com/resources/)
- [NginX](https://www.nginx.com/resources/library/)
- [O'Reilly](https://www.oreilly.com/free/)


## Papers

You can find many of the following papers also here: [Papers we love](https://github.com/papers-we-love/papers-we-love)

### Actors

- [Carl Hewitt: Actor Model of Computation](https://arxiv.org/vc/arxiv/papers/1008/1008.1459v8.pdf): The Actor model is a mathematical theory that treats “Actors” as the universal primitives of concurrent digital computation.
- [Carl Hewitt, Peter Bishop, Richard Steiger: A Universal Modular Actor Formalism for Artificial Intelligence](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.77.7898): This paper proposes a modular ACTOR architecture and definitional method for artificial intelligence that is conceptually based on a single kind of object: actors. 

### AI

- [Lin, Ma et al.: Explaining AlphaGo: Interpreting Contextual Effects in Neural Networks](https://arxiv.org/abs/1901.02184): Google Alpha Go
- [Superhuman AI for multiplayer poker](https://www.cs.cmu.edu/~noamb/papers/19-Science-Superhuman.pdf): Poker AI

## Amazon

- [Dynamo: Amazon's highly available key-value store](https://www.researchgate.net/publication/220910159_Dynamo_Amazon's_highly_available_key-value_store): This paper presents the design and implementation of Dynamo, a highly available key-value storage system that some of Amazon's core services use to provide an "always-on" experience.

### Difference 

- [Eugen W. Myers: An O(ND) Difference Algorithm and Its Variations](http://citeseerx.ist.psu.edu/viewdoc/summary?doi=10.1.1.4.6927): finding a longest common subsequence of two sequences A and B and a shortest edit script for transforming A into B have long been known to be dual problems
- [Keil: ](https://fusion.cs.uni-jena.de/fusion/wp-content/uploads/2018/12/btw2019-jmkeil-camera-ready.pdf): Efficient Bounded Jaro-Winkler Similarity Based Search

## Data

- [DBLog: A Watermark Based Change-Data-Capture Framework](https://arxiv.org/abs/2010.12597#:~:text=DBLog%20utilizes%20a%20watermark%20based,without%20stalling%20while%20processing%20selects.)
- [Online EventProcessing](https://martin.kleppmann.com/papers/olep-cacm.pdf)

## Google

- [Large-scale cluster management at Google with Borg](https://research.google/pubs/pub43438/): Google's Borg system is a cluster manager that runs hundreds of thousands of jobs, from many thousands of different applications, across a number of clusters each with up to tens of thousands of machines.
- [The Google File System](https://research.google/pubs/pub51/): a scalable distributed file system for large distributed data-intensive applications. It provides fault tolerance while running on inexpensive commodity hardware, and it delivers high aggregate performance to a large number of clients.
- [Bigtable: A Distributed Storage System for Structured Data](https://research.google/pubs/pub27898/): Bigtable is a distributed storage system for managing structured data that is designed to scale to a very large size: petabytes of data across thousands of commodity servers.
- [Dapper, a Large-Scale Distributed Systems Tracing Infrastructure](https://research.google/pubs/pub36356/): Modern Internet services are often implemented as complex, large-scale distributed systems. These applications are constructed from collections of software modules that may be developed by different teams, perhaps in different programming languages, and could span many thousands of machines across multiple physical facili- ties. Tools that aid in understanding system behavior and reasoning about performance issues are invaluable in such an environment.
- [Spanner](https://research.google/pubs/pub44915/): Spanner is Google’s scalable, multiversion, globally distributed, and synchronously replicated database. 
- [Why Google Stores Billions of Lines of Code in a Single Repository](https://research.google/pubs/pub45424/): Google's monolithic repository provides a common source of truth for tens of thousands of developers around the world.
- [Spanner, TrueTime and the CAP Theorem](https://research.google/pubs/pub45855/): Spanner is Google's highly available global-scale distributed database. It provides strong consistency for all transactions. This combination of availability and consistency over the wide area is generally considered impossible due to the CAP Theorem. We show how Spanner achieves this combination and why it is consistent with CAP. We also explore the role that TrueTime, Google's globally synchronized clock, plays in consistency for reads and especially for snapshots that enable consistent and repeatable analytics.
- [MapReduce](https://research.google/pubs/pub62/): MapReduce is a programming model and an associated implementation for processing and generating large data sets. Users specify a map function that processes a key/value pair to generate a set of intermediate key/value pairs, and a reduce function that merges all intermediate values associated with the same intermediate key. 
- [Borg, Omega, and Kubernetes](https://queue.acm.org/detail.cfm?id=2898444): Lessons learned from three container-management systems over a decade

## Misc

- [Paxos Made Simple](https://lamport.azurewebsites.net/pubs/paxos-simple.pdf): Paxos algorithm for implementing a fault-tolerant distributed system
- [The Part-Time Parliament](https://lamport.azurewebsites.net/pubs/lamport-paxos.pdf): Paxos algorithm for implementing a fault-tolerant distributed system
- [Fallacies of distributed computing](https://web.archive.org/web/20171107014323/http://blog.fogcreek.com/eight-fallacies-of-distributed-computing-tech-talk/): a set of assertions made by L Peter Deutsch and others at Sun Microsystems describing false assumptions that programmers new to distributed applications invariably make.
- [The Eight Fallacies of Distributed Computing](https://nighthacks.com/jag/res/Fallacies.html)
- [CQRS](https://cqrs.files.wordpress.com/2010/11/cqrs_documents.pdf)
- [Sagas Pattern](https://www.cs.cornell.edu/andru/cs711/2002fa/reading/sagas.pdf)
- [The Limit of Sagas](https://www.ufried.com/blog/limits_of_saga_pattern/)
- [Scrum-Guide](https://scrumguides.org/index.html)
- [There is no Now](https://queue.acm.org/detail.cfm?id=2745385)
- [CUPID—for joyful coding](https://dannorth.net/cupid-for-joyful-coding/)
 
## Security

- [Fast Dictionary Attacks on Passwords Using Time-Space Tradeoff](https://www.cs.utexas.edu/~shmat/shmat_ccs05pwd.pdf)

## Resources

- [arXiv.org](https://arxiv.org/): arXiv is a free distribution service and an open-access archive for scholarly articles in the fields of physics, mathematics, computer science, quantitative biology, quantitative finance, statistics, electrical engineering and systems science, and economics. Materials on this site are not peer-reviewed by arXiv.
- [Google Research](https://research.google/pubs/)
- [Resources on Software Architecture](https://github.com/domrost/software-architecture-resources)
