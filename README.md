#Explain, generally, what is meant by a NoSQL database
>A NoSQL (originally referring to "non SQL" or "non relational") database provides a mechanism for storage and retrieval of data which is modeled in means other 
>than the tabular relations used in relational databases. NoSQL databases are increasingly used in big data and real-time web applications.

![alt text](http://dataconomy.com/wp-content/uploads/2014/07/SQL-vs.-NoSQL.png "SQL vs noSQL")

Sources:
[Wikipedia](https://en.wikipedia.org/wiki/NoSQL)

#Explain Pros & Cons in using a NoSQL database like MongoDB as your data store, compared to a traditional 
Relational SQL Database like MySQL. 

- (+) Simplicity of design. (data does not have to be normalized. Just save everything you need, in a document, for a specific domain.)
- (+) Some operations faster in NoSQL. (especially when your data needs are "non-relationel in nature - you typically store and request data from the same domain)
- (+) Simpler "horizontal" scaling to clusters of machines. (Just add another machine to extend storage space. Speed will be constant)

- (-) Compromise consistency in favor of availability (CAP theorem).
- (-) No dedicated noSQL-language like SQL and lack of standardized interfaces (it's easier to design an ORM if you have this).
- (-) Huge previous investments in existing relational databases.
- (-) Mostly lack ACID

Sources: 

[Wikipedia NoSQL](https://en.wikipedia.org/wiki/NoSQL)
[Wikipedia CAP Theorem](https://en.wikipedia.org/wiki/CAP_theorem)
[MEAN slides NoSQL and MongoDB](http://js2016.azurewebsites.net/mongoDB/mongo.html#7)
[ACID](https://en.wikipedia.org/wiki/ACID)

#Explain how databases like MongoDB and redis would be classified in the NoSQL world 

##MongoDB
##Redis


#Explain reasons to add a layer like Mongoose, on top on of a schema-less database like MongoDB 
#Explain, using relevant examples, the strategy for querying MongoDB (all CRUD operations) 
#Demonstrate, using a REST-API, how to perform all CRUD operations on a MongoDB 
#Explain the benefits from using Mongoose, and provide an example involving all CRUD operations 
#Explain how redis "fits" into the NoSQL world, and provide an example of how to use it. 
#Explain, using a relevant example, how redis (or a similar) can increase scalability (drastic) for a server using 
server side sessions 
#Explain, using a relevant example, a full MEAN application including relevant test cases to test the REST-API 
(not on the production database) 