# DBMS
A database management system (DBMS) is system software for creating and managing databases. The DBMS provides users and programmers with a systematic way to create, retrieve, update and manage data.A DBMS makes it possible for end users to create, read, update and delete data in a database. The DBMS essentially serves as an interface between the database and end users or application programs, ensuring that data is consistently organized and remains easily accessible.


The DBMS manages three important things: the data, the database engine that allows data to be accessed, locked and modified -- and the database schema, which defines the database’s logical structure. These three foundational elements help provide concurrency, security, data integrity and uniform administration procedures. Typical database administration tasks supported by the DBMS include change management, performance monitoring/tuning and backup and recovery. Many database management systems are also responsible for automated rollbacks, restarts and recovery as well as the logging and auditing of activity.

The DBMS is perhaps most useful for providing a centralized view of data that can be accessed by multiple users, from multiple locations, in a controlled manner. A DBMS can limit what data the end user sees, as well as how that end user can view the data, providing many views of a single database schema. End users and software programs are free from having to understand where the data is physically located or on what type of storage media it resides because the DBMS handles all requests.

The DBMS can offer both logical and physical data independence. That means it can protect users and applications from needing to know where data is stored or having to be concerned about changes to the physical structure of data (storage and hardware). As long as programs use the application programming interface (API) for the database that is provided by the DBMS, developers won't have to modify programs just because changes have been made to the database.

With relational DBMSs (RDBMSs), this API is SQL, a standard programming language for defining, protecting and accessing data in a RDBMS.



Popular types of DBMSes
Popular database models and their management systems include:

Relational database management system (RDMS)  - adaptable to most use cases, but RDBMS Tier-1 products can be quite expensive.

NoSQL DBMS - well-suited for loosely defined data structures that may evolve over time. 

In-memory database management system (IMDBMS) - provides faster response times and better performance.

Columnar database management system (CDBMS) - well-suited for data warehouses that have a large number of similar data items.

Cloud-based data management system - the cloud service provider is responsible for providing and maintaining the DBMS.

Advantages of a DBMS
Using a DBMS to store and manage data comes with advantages, but also overhead. One of the biggest advantages of using a DBMS is that it lets end users and application programmers access and use the same data while managing data integrity. Data is better protected and maintained when it can be shared using a DBMS instead of creating new iterations of the same data stored in new files for every new application. The DBMS provides a central store of data that can be accessed by multiple users in a controlled manner.

Central storage and management of data within the DBMS provides:

Data abstraction and independence
Data security
A locking mechanism for concurrent access
An efficient handler to balance the needs of multiple applications using the same data
The ability to swiftly recover from crashes and errors, including restartability and recoverability
Robust data integrity capabilities
Logging and auditing of activity
Simple access using a standard application programming interface (API)
Uniform administration procedures for data
Another advantage of a DBMS is that it can be used to impose a logical, structured organization on the data. A DBMS delivers economy of scale for processing large amounts of data because it is optimized for such operations.

A DBMS can also provide many views of a single database schema. A view defines what data the user sees and how that user sees the data. The DBMS provides a level of abstraction between the conceptual schema that defines the logical structure of the database and the physical schema that describes the files, indexes and other physical mechanisms used by the database. When a DBMS is used, systems can be modified much more easily when business requirements change. New categories of data can be added to the database without disrupting the existing system and applications can be insulated from how data is structured and stored.

Of course, a DBMS must perform additional work to provide these advantages, thereby bringing with it the overhead. A DBMS will use more memory and CPU than a simple file storage system. And, of course, different types of DBMSes will require different types and levels of system resources.

Changes in how DBMS are built, sold and serviced
By 2019, the most significant trends in the DBMS sector were how databases were constructed and how they were used. Open source DBMS were rapidly gaining traction. In fact, Gartner projected that 10% of total spending on database software by 2019 due to increased enterprise adoption. Most mainstream IT organizations use open source software in some of their mission-critical operations.


This trend complements two other trends: the acquisition of open-source database vendors by bigger rivals and the expansion of the cloud-based database service market. In 2019, MongoDB, maker of the Atlas cloud platform, acquired mobile app database maker Realm to boost. And Microsoft acquired Citrus Data, whose open source software allows PostgreSQL to be used as a distributed database in a public cloud setting. Three vendors, in particular, were prominent in the cloud-based DBMS market in 2019:

This was last updated in May 2019
Next Steps
Different types of DBMSes require different levels of system resources, so it's important to understand the types and categories of DBMSes. Expert Craig S. Mullins evaluates different types of DBMSes to help you with your purchasing decisions.

Discover more about MySQL open source RDBMS

Find in-depth information to help you decide if a Relational DBMS, NoSQL DBMS or in-memory DBMS is the right fit for your organization.

Expert Craig S. Mullins reviews the top RDBMS products on the market to help with your decision-making process.

Continue Reading About database management system (DBMS)
Learn IT: The Power of the Database
Expert Craig S. Mullins provides helpful, educational articles about database management on his website.
Optimizing database performance: Denormalization and clustering
Types of DBAs
Oracle RDBMS vs. NoSQL databases in the era of big data
Related Terms
Microsoft SQL Server
Microsoft SQL Server is a relational database management system, or RDBMS, that supports a wide variety of transaction processing... See complete definition
RDBMS (relational database management system)
A relational database management system (RDBMS) is a collection of programs and capabilities that enable IT teams and others to ... See complete definition
relational database
A relational database is a set of formally described tables from which data can be accessed or reassembled in many different ways... See complete definition
