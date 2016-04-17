# Outline
1. Introduction to the topic of NoSQL DBs
	+ Definition
		+ Professional Nosql
			+ NoSQL's name infers that it opposes SQL
			+ "NoSQL is used today as an umbrella term for all databases and data
stores that don’t follow the popular and well-established RDBMS
principles and often relate to large data sets accessed and manipulated on a
Web scale"
	+ Advantages
		+ Clark 18
			+ Column-stored NoSQL databases can store many different attributes in the columns without hurting performance
		+ devbridge web
			+ NoSQL aims to solve the object-relational impedence mismatch problem
			+ Despite the existance of Object-relational mapping frameworkds, the
			  developer still has to devote time to figuring out the best way to
structure the database.
		+ oaister web
			+ "Object-relational impedance mismatch is the
term we use to refer to a difference between the schema of an
object-oriented program and the schema of a relational
database"
				+ This means that fitting a relational schema into an object-oriented
				  schema is difficult.
		+ TechRepublic
			+ Elastic scaling
			+ Big data
			+ Easier to set up
			+ Flexible data
			+ Changing data model doesn't have to change code all over
1. Discuss disadvantages to using NoSQL DBs
	+ TechRepublic
		+ Maturity
			+ "for most CIOs, the maturity of the RDBMS is reassuring."
		+ Support
			+ (This is changing with Microsoft 2016 adding support for NoSQL)
			+ The majority of popular NoSQL databases are open source and have no support options
			+ There are often no administrative solutions for databases
			+ Not as many developers are as familiar with NoSQL databases  as they
			  are with relational databases
1. Briefly describe MongoDB and the NoSQL DB2 you chose
	+ MongoDB
		+ MongoDB manual
			+ "MongoDB is an open-source document database that provides high performance, high availability, and automatic scaling."
			+ "A record in MongoDB is a document, which is a data structure composed of field and value pairs. MongoDB documents are similar to JSON objects. The values of fields may include other documents, arrays, and arrays of documents."
			+ "The advantages of using documents are:
Documents (i.e. objects) correspond to native data types in many programming languages.
Embedded documents and arrays reduce need for expensive joins.
Dynamic schema supports fluent polymorphism.
		+ kkovacs.eu
			+ "Retains some friendly properties of SQL, such as queries (using find) and index"
			+ Benefits JavaScript developers since queries are written in JavaScript
			+ Test javascript functions on the server
			+ Good performance
			+ Text search
			+ "Good if you prefer to define indexes and not map/reduce functions or
			  like regular SQL, but predefined columns would hold you back" presents
	+ CouchDB
		+ couchdb.apache.org
			+ "CouchDB is a database that completely embraces the web. Store your
			  data with JSON documents. Access your documents and query your indexes
with your web browser, via HTTP. Index, combine, and transform your documents
with JavaScript. CouchDB works well with modern web and mobile apps. You can
even serve web apps directly out of CouchDB. And you can distribute your data,
or your apps, efficiently using CouchDB’s incremental replication. CouchDB
supports master-master setups with automatic conflict detection.  CouchDB comes
with a suite of features, such as on-the-fly document transformation and
real-time change notifications, that makes web app development a breeze. It
even comes with an easy to use web administration console. You guessed it,
served up directly out of CouchDB! We care a lot about distributed scaling.
CouchDB is highly available and partition tolerant, but is also eventually
consistent. And we care a lot about your data. CouchDB has a fault-tolerant
storage engine that puts the safety of your data first."
		+ kkovacs.eu
			+ embedded map-reduce through views
			+ real-time updates via '+changes'(!)
			+ attachment handling
			+ MVCC operations do not block reads
			+ "Good for occasionally changing data, on which pre-defined queries are to be run"
1. Describe your experiences using each NoSQL DB.
 Was it convenient? 
Did it solve some of the limitations/disadvantages of SQL DBs? 
Did using a NoSQL DB introduce new limitations/disadvantages?
1. Based on your experiences using each NoSQL DB, describe how they differ from
	 each other.  Identify some categories for comparison.
1. Based on your experiences using each NoSQL DB, describe some of the
	 advantages and disadvantages/limitations to each NoSQL DB.
1. Include a few screen shots of your results from running NoSQL DB2 - I need
	 to see that you actually did it
1. In a conclusion, give your opinion of each NoSQL DB and your recommendation
	 as to which one to use.

# Works Cited
+ Ccp, and Shashank Tiwari. *Professional Nosql*. 
[Electronic Resource]. n.p.: Wrox [Imprint] Sept. 2011 Hoboken : 
John Wiley & Sons, Incorporated, 2011. 
*University of Alabama Libraries’ Classic Catalog*. 
Web. 17 Apr. 2016.
+ Clark, Lindsay. "Using Nosql Databases To Gain Competitive Advantage."
  *Computer Weekly* (2014): 17. *MasterFILE Premier*. Web. 17 Apr. 2016.
+ Krisciunas, Albertas. "Benefits of NoSQL." *Introducing NoSQL*. Devbridge
  Group, 20 May 2014. Web. 17 Apr. 2016.
<https://www.devbridge.com/articles/benefits-of-nosql/>.
+ "Exposing The Myth: Object-Relational Impedance Mismatch Is A Wicked
  Problem." (n.d.): *OAIster*. Web. 17 Apr. 2016.
+ Harrison, Guy. "10 Things You Should Know about NoSQL Databases -
TechRepublic." *TechRepublic*. 26 Aug. 2010. Web. 17 Apr. 2016.
<http://www.techrepublic.com/blog/10-things/10-things-you-should-know-about-nosql-databases/>.
+ "The MongoDB 3.2 Manual." *The MongoDB 3.2 Manual — MongoDB Manual 3.2*. Web.
  17 Apr. 2016.
<https://docs.mongodb.org/manual/?_ga=1.3950576.1786411152.1460915581>.
+ 
Kovacs, Kristof. "Cassandra vs MongoDB vs CouchDB vs Redis vs Riak vs HBase vs
Couchbase vs OrientDB vs Aerospike vs Neo4j vs Hypertable vs ElasticSearch vs
Accumulo vs VoltDB vs Scalaris vs RethinkDB Comparison." *Cassandra vs MongoDB
vs CouchDB vs Redis vs Riak vs HBase vs Couchbase vs Hypertable vs
ElasticSearch vs Accumulo vs VoltDB vs Scalaris Comparison*. Web. 17 Apr. 2016.
+ "Apache CouchDB™ Is a Database." *Apache CouchDB*. Web. 17 Apr. 2016.
<http://couchdb.apache.org/>.

