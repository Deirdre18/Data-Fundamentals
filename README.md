# What is Data?
 
## What is it?

Stored information

## What does it do?

Structured pieces of information that are collected, stored and modified

## How do you use it?

By using it to answer questions, about your business, your processes, etc.

LESSON:

So let's first try to get an understanding of what data is.

Data are structured pieces of information that you collect and keep up to date.
This data then becomes something you can examine whenever you have a question and use to help you formulate an answer.
The concept of data tends to be very abstract.
So to make things clearer, let's use an example to illustrate and flesh out all the concepts we need to get familiar with - an online store.
Let's assume that we are the proud owners of an online store selling clothes and some other products online to customers and many cities across the world and that we are thinking of setting up an organized way of storing and retrieving all the data for a new organization.
As an organization, we want to be able to answer questions about matters that are important to us.
Starting from basic questions such as: how many shirts of a specific type do we have at the moment?
What was the price that we assigned to a specific product?
What products did a particular customer purchase from us?
And also ranging to more high-level strategic questions such as: what is our best selling shirt, or what is the expected future demand for a specific product?
All of these business questions and many others can be answered through looking at data.
That is assuming that we have collected and stored all the relevant data to begin with.

# Entities And Attributes
 
## What is it?

Data entities and attributes

## What does it do?

An entity is a data-based representation of a real-world object (a person), and an attribute is a specific piece of information belong to an entity (a name)

## How do you use it?

Use attributes and entities when creating and organizing data

LESSON:
So let's start talking about where data can be found in the wild.
In general, data does not just float out there by itself but only makes sense when attached to the concept of an entity.
An entity is a category of things in the real-world that each has a unique identity and persist over time.
For example, people are a kind of entity, and each particular person is an instance of that entity.
By unique identity, we mean that we have some way of distinguishing between particular instances of entities.
For example, no two people are exactly alike, and we have ways to distinguish between them.
And by persistence, we mean that even though we understand that real world objects change, you want to be sure that when we refer to a particular instance of an entity again at some future time, it will, in a basic sense, be the same thing.
Again, this is like people.
My circumstances may change, but I'm still basically me.
So let's see some examples of entities.
People, or perhaps a more specific subset of people, like lawyers or customers, would be entities.
Other kinds of entities would be inanimate objects, such as books, or kinds of locations, like cities.
I mentioned that data comes attached to entities.
The way this works is through the concept of attributes.
An attribute is any specific aspect of an entity that we care about and can record a value for.
Just as with the entities themselves, the list of attributes that we care about will strongly depend on the needs of our specific organization.
For example, a government's social insurance organization might have citizens as its most important entity.
And it might care about the following attributes for each citizen: their full name, their ID number, their date of birth, and a photo of them (the way they look.)
So going back to the concept of data, we can say that data describes the values of attributes for instances of entities that we care about.
Don't worry too much about this phrasing since we will be expanding upon this and going back to it throughout the module.
Going back to our online store example, we would want to record data about all the entity types that are relevant to our business processes.

# Where Is Data Stored?
 
## What is it?

A data store

## What does it do?

Acts as a repository to hold an organization's data

## How do you use it?

LESSON:
In the previous section, we mentioned what data looks like in the wild.
So now let's turn to what it means to have our organization store that data.
Let's start with the concept of a data store itself.
A data store is a repository to hold our organization's data.
After filling it with data, our data store becomes an archive that can then be searched.
It equips decision-makers with the power to find trends and unearth hidden patterns that are important to the organization such as what are the favorite products for each demographic, or which groups of products sell well together.
Data stores aren't, of course, a new concept.
Just think of paper-based catalogs maintained in large old libraries and museums.
It just so happens that computerized data stores have many advantages over the traditional paper-based ones.
So modern organizations all over the world have switched to computer-based data stores as quickly as they could.
According to some estimates in recent years, the exponential pace of data being stored in computers has become so rapid that more data is being generated and stored each year than the amount that has been generated in all the rest of human history combined.

# Where Data Comes From

## What is it?

Records, fields and metadata

## What does it do?

A record is the set of data stored about a particular instance of an entity. A field is a single piece of data in a record that corresponds to an attribute. Metadata is any data that describes other data.

## How do you use it?

Use records, fields and metadata to record and describe the contents of a data store

LESSON:

In the last part, we had a general overview of what organizational data is and what kinds of data we want to keep track of.
Having decided that, in this section, we will talk at a high level of how we actually get that data into our data store.
We are still discussing theory.
But let's now go one level down the rabbit hole from the completely abstract concepts of entities and attributes to the level of records and fields, which is what we actually keep in our data store.
So here are the new terms you should know.
A record is the set of data stored about a particular instance of an entity.
In our online store example, we care about the customer entity type.
So we will want to store a record for every particular customer, such as Jane Doe.
A field is a single piece of data in a record that corresponds to an attribute.
In our example, the fields are name, birthday, address, city, and country.
All the fields combined make up a record.
Just to recap, an entity is a category of things in the real world, and an instance of an entity is an actual thing in the world.
A record, on the other hand, is a set of data pieces that we present in a structured way, an instance of an entity.
For example, our Jane Doe is an actual person in reality, or in other words, she is an instance of the customer entity.
What you see on the slide is a record which represents Jane in our data store.
Also, I mentioned earlier that entities must be uniquely identifiable, but I did not discuss how.
So let's turn to that now.
For a record, we must have a field, or sometimes several fields combined together, that is completely unique to that record.
This is known as the record's primary key.
If we know the primary key for a record, we are then able to easily retrieve just that specific record.
In our example, what attribute of Jane Doe's can be used as a primary key?
Well, a name is not unique, nor an address, and not even the combination of both.
Potentially, a large building might have two people with the same name.
So in cases such as these, it is customary to create a unique numeric field to be used as the primary key.
It would then often be called an ID for the record.
In our example, we would add a customer ID field for each customer record to enable us to uniquely identify that customer.
Note that this is not a natural attribute that Jane Doe had, and indeed, she might never even know her customer ID.
Do you remember, or care about, or even know the customer ID for your electrical company?
But, from here on out, once we have an ID, we can always refer to Jane Doe through her ID, and we find her record.
This concept of a unique numerical identifier is not a new trick.
Just think of passport numbers, car registration numbers, and even street numbers.
All of these are IDs that serve for easy identification of instances of entities.
Another important concept regarding the organization of data is that of Metadata.
Metadata is defined as any data that describes other data.
In general, a data store contains both data records and all the Metadata needed to handle those records.
This includes the description of the structure of the records, where to find them, and any other property of the data that is important for that specific data store.
For example, in the age before modern computing, when data records were stored on pieces of paper inside boxes, the Metadata might include labels on those boxes describing the kinds of records stored in each box.
We will describe other kinds of Metadata later on in the module when we go into the description of different kinds of data stores.

# How We Acquire New Data
 
## What is it?

Running MySQL commands from Python code

## What does it do?

Connects to MySQL database with hostname, user and password.

## How do you use it?

Use the pymysql library and it's inbuilt methods

LESSON:

The main part of dealing with data is usually acquiring it.
Let's now turn to a discussion of how new data records come to life.
In our online store example, we add new products to our stock over time and store the data about them.
Also, we gain new customers over time and record relevant data about those.
The data about products is something we might need to manually enter into our systems, meaning that we would have an actual employee create a new record in our data store for each new product we are about to start selling manually.
Alternatively, if we want to stock up many products from a single wholesaler, you might be able to do a bulk import of data from their data store into ours.
This would still be an operation that an employee would have to perform manually, but instead of them creating a single record at a time, they would be creating all of the records in one go.
For this reason, these kinds of bulk operations are sometimes known as semi-manual.
In the case of new customers, we would want to design our online system to store the data automatically for us, such that when a new customer signs up for a website, the details they enter are automatically added into records in our data store without any human intervention on our part.
So to sum up, we have three ways of adding new data records to our data store.
Manually, semi-manually in bulk, and automatically through a system that manages the creation of records as part of our business processes.
The data management module will expand upon the business side of the acquisition and management of organizational data.

# CRUD Operations
 
## What is it?

Create, Read, Update, Delete (CRUD)

## What does it do?

Operations to be carried out against a data store

## How do you use it?

Use CRUD operations to interact with a data store

LESSON:

The main purpose of having a data store is to be able to perform operations on the data records in it.
Each such data store operation is a request sent by a user to the data store in order to change the data in it or retrieve any part of it.
We generally discern between four types of operations, known collectively by the acronym CRUD, standing for Create, Read, Update, and Delete.
Let's begin with looking into Create, Update, and Delete first.
These are collectively known as the data manipulation operations.
These are operations that we perform on a day-to-day basis based on our ongoing business processes in either a manual fashion or through an application that we create for that.
The first is Create, also known as an insert.
This is the operation of adding a new record to the data store, such as adding a new product.
Update is the operation of changing one or more fields in existing products and existing records, such as updating the price for a product.
Delete is the operation of completely removing a record from the data store, the opposite of create.
The fourth, and the most common CRUD operation, is Read: a request to retrieve some information from the data store without changing anything.
For example, when we intend to send a product to a customer, we would use that customer's unique ID to read their record and look up their name and address.
In addition to reading data from a specific record, we can also read data from many records in a single Read request to answer questions, such as what products we currently have on sale so that we would be able to showcase them on our website.
Another example for using the Read operation is for retrieving aggregated data, such as the average price for all kinds of pants, or the total number of all products we have.
Read operations are also commonly known as queries, and we will usually use the term query interchangeably with Read operation.
Occasionally, we might have a question that would necessitate reading a very large portion or even the entirety of our data store, but it would not necessarily acquire the latest version of the data.
A typical scenario for this may be needing to generate large reports containing information about all the business processes we had in the past month.
Another common scenario is that of having a business analyst go through the data and perform large-scale queries to answer questions regarding the customer demographics and the changes in demand for different products to allow for long-term planning.
Though in essence it is possible to perform all such queries as part of regular Read operations, a large field of business intelligence, or BI, has evolved around large-scale analytics with specialized tools created just for that.
Generally, organizations perform periodic exports of all the data records from the main data store to be used by these specialized tools.
Organizational analytics are often the main reason for exporting large portions of data.
But for some organizations, periodic exports to be used by other systems as well are very common too.
And indeed, one of the main reasons for collecting data in your data store might be to have the ability to export it in bulk to other systems.
   
   
# Data Access Patterns
 
## What is it?

Ways of interacting with a data store

## What does it do?

Describes a pattern of interaction depending on the data store's primary usage.

## How do you use it?

Implement the pattern based on your application needs

LESSON:
Throughout the last unit, we discussed the various operations that we would want to perform in records in our data store.
But we have kept the data store itself as a black box and haven't yet discussed any specific qualities that we want our data store to have.
There are many different ways to design a data store.
You should be aware that, in general, no specific kind of data store is better than another, and there are always trade-offs to be made.
In a sense, choosing the right data store for your organizational needs is perhaps the hardest question in the field.
And there is no single right answer because the needs of each organization are somewhat different.
The main considerations you should keep in mind when choosing your data store are the data access patterns for your organization.
That is, how often do you want to perform each of the CRUD operations we mentioned.
For example, if you need to constantly add and update records and then perform hourly exports on them but never need to perform regular Read operations, you would probably want a completely different data store than in the case of when you insert records once and constantly read them without ever updating anything.
In the next part, we will begin discussing the way different types of data stores work.
And for all that, I recommend that you keep in mind that each is good for some types of access patterns.

# Data Fundamentals Quiz

## Question One
Which of the following is a category of things in the real world, each of which has a unique identity and persists over time?

An entity 

## Question Two
Choose the correct sentence:

Fields are pieces of data stored as part of records. 

## Question Three
Which of the following can be used as a primary key for a citizen record?

Passport number 

## Question Four

Update Reduce Read Use Calculate Undo Divide Delete Create

## Question Five
Any type of data store is equally good, regardless of your data access patterns.

False

# Data Store Types Overview

## What is it?

Data store types

## What does it do?

Used for applications based on best fit

## How do you use it?

Determine your application needs and apply the appropriate data store

LESSON:

Data comes in many forms, and it can be represented in different types of data stores in many ways.
In general, any kind of data can be stored in any kind of data store, but some are usually a better fit than others.
We will discuss this later in the module, but for now, let's go over some of the main types of data stores in common use.
We distinguish between two general types of data stores: file-based data stores and databases.
File-based data stores are regular files that contain data records that can be accessed by people or applications directly.
And the other kind is databases, which are data stores managed by special software that mediates all access to the data store.
Most of the module will focus on databases, but first let's discuss file-based data stores, which are still relevant at times and understanding them will help us make sense of the need for a database.

# File Based Data Stores
 
## What is it?

A data storage type

## What does it do?

Stores data in simple files.

## How do you use it?

Use it when working with simple data such as data exported from Excel sheets or other comma separated value (CSV) formatted data.

LESSON:

File-based data stores are the most basic kinds of computerized data stores.
These data stores are very simple to set up and maintain, and by virtue of being regular text files, they can be inspected and edited by any text editor, such as Notepad.
All of the data is stored in a single text file such that every time the data needs to be accessed, the entire file needs to be read.
And every time data needs to be modified, the entire file needs to be saved back to disk.
One common type of file-based data store is called flat-files.
And the best-known type of a flat-file format that is still in common use is CSV, standing for Comma Separated Values.
In this format, records are put into a .txt file each on a separate line, and each field in a record is separated with commas.
For example, for our online store, to help organize our marketing efforts, we might choose to store some information about cities in the world.
If we want to describe a list of cities, the country they are in, and the populations in a CSV file, you could use this structure: name,country,population.
New line: Dublin,Ireland,530,000
New line: London,UK,800,000.
A title row like that above is optional and is handled separately from the rest of the rows which store regular records.
The title row is essentially Metadata within the flat-file.
A central property of file-based data stores is that they can only record records for a single kind of entity, in this case, cities.
Also, there is absolutely no structure or hierarchy connecting different records, and in this sense, the data is said to be flat.
So as we can see, a flat-file can only store a single kind of record.
If we want to store several different kinds of records, we need to use several separate flat-files.
A related alternative I should mention are spreadsheets.
Spreadsheet programs, such as Microsoft Excel, can be used to edit CSV files.
And indeed, a spreadsheet file can be considered a collection of several such flat-files with many additional capabilities.
But note that unless you explicitly save an Excel file as a CSV, it is not a text file, and then on can only be opened with a spreadsheet program.

# JSON And XML
 
## What is it?

JSON and XML data structure formats

## What does it do?

Formats data in markup or key/value pairs

## How do you use it?

Use XML or JSON structure in particular when data originates in nested formats

LESSON:
The main downside of flat-files is that they do not allow us to express any relationships between different data types.
For example, let's say I have a hierarchy of locations, cities within countries, and I want to store records concerning both.
One natural way of expressing this would be by having the city records nested within the record of the country they belong to.
Similar to flat-files, structured formats such as XML (Extensible Markup Language) and JSON (JavaScript Object Notation) emerged as a way of storing data and text files.
Unlike flat-files, these formats allow for hierarchical structuring of data records.
Instead of describing records for each entity in a separate file, these structured formats let you nest records one within the other.
For example, if we want to describe countries and the cities within them, we could use this JSON structure, which has a list of country records each with the field's name, population, and cities.
The interesting thing is that the cities field is in itself a nested collection of city records, each of which has the field's name and population.
Let's look at the JSON format itself for a bit.
It consists of records surrounded by curly braces, each consisting of field keys and field values delimited by colons.
A value can be either a simple number or a string, or an inner record, or a list of values surrounded by square brackets.
Another interesting property of formats such as JSON is that unlike the fixed structure of flat-files, in JSON, different records can have different fields.
For instance, let's say that we want to have the record about the city of Oxford contain a field about the city's motto, "Fortas est Veritas" (Truth is Strong).
In JSON, we can easily add that field, even if we do not have a motto to store for other cities' records.
But note that this lack of structure, when you do not know what fields any record has, can make handling of the data much harder.
So often developers will want to enforce a fixed structure anyway.
JSON originated from the way objects can be defined in the JavaScript language.
But due to its convenience and simplicity, it has since become widespread as a way to store and transfer data between applications written in all modern languages.
The same information can also be stored in XML in this way.
This may seem familiar to you if you are used to HTML since they were both developed based on an older standard called SGML and share most of their properties.
We will not go into XML structure here in this module because it is more complex than JSON and because it is becoming less common, at least in the Web world.
In essence, XML stores data in the same way as JSON with slight differences.
JSON is newer than XML, and due to the simplicity and easy integration with JavaScript, it has become the most widely used structured data format.
It is the main format used by the document-oriented database MongoDB, which we will discuss later.
File-based data stores have these advantages:
They are very simple to set up and to maintain.
They are widely supported in all programming languages and all kinds of systems.
It is very easy to copy between computers and back these formats up.
It is easy to examine and modify these files by any text editor.
But note that they do have some very big downsides that make them less useful for large-scale production needs.
Only a single change to the data store can be made at any point in time, unlike with databases where different changes can be performed concurrently (at the same time).
Access to specific records is very slow.
To find the record, you have to go through the entire file line-by-line until you find it.
In other words, files do not have indexes.
We will talk about indexes later in this module.
And finally, regular files have no protections against corruption.
Unlike with databases, that we will discuss later, there is nothing that can protect us from accidentally putting erroneous or badly structured data in regular files.
For these reasons, file-based data stores are rarely used as persistent long-lived data stores these days.
But due to their simplicity and wide support, they are often used for importing and exporting data between systems, even when you are using a database.
The API module in this course focuses on interfaces between applications and how they rely on formats such as JSON to transfer information between systems.

# Data Store Types Quiz

## A data store: (Select all that apply)
is most useful for short-term storage of data can be searched, contains records, might be something as low-tech as a cardboard box

## CRUD operations can be performed on which types of data storage? (Select all that apply)
File based, Database.

## Below are a few sentences concerning file-based data stores vs. databases (Select all that that are true)
File-based data stores are easier to set up and maintain than database. 
File-based data stores can be used for importing data to, and exporting data from a database.

#  An Introduction To Databases

## What is it?

A Database Managenent System (DBMS)

## What does it do?

A DBMS manages all access to the data providing security reliability ease of administration and performance

## How do you use it?

Use a DBMS when working with data that requires rapid retrieval and modification

LESSON:

As I mentioned, there are many disadvantages to using regular files to store your data.
A lot can be gained by the installation of specialized software that will manage the storage of data to disk and rapid retrieval of that data.
This kind of software that manages a data store is known as a database management system, a DBMS.
And by virtue of being managed by such software, the data store itself is then known as a database.
A DBMS manages all access to the data providing security, reliability, ease of administration, and much better performance than file-based data stores allow.
The DBMS is a server program.
By the word server, we mean that this is a program that runs continually and provides a service by processing requests from people and applications that want to use its services.
Those people and applications are then known as the server's clients.
And their requests are sometimes known as queries.
Though, usually, queries only refer to read request.
The computer that holds the DBMS is often referred to as a database server.
And the clients usually connect to the database server from other computers over the network.
This database being managed is, in essence, a structure that you build to hold your valuable data, while the DBMS is the tool you use to build that structure and operate on the data contained within the database.
Please note that for each type of database that we will mention, there are many different specific DBMS programs to choose from, from different vendors and versions.
End of transcript. Skip to the start.

# The Context Of A Database In Your Software

## What is it?

Using data as part of an application

## What does it do?

Data provides the meaning for your application's existence

## How do you use it?

Store data at rest in a DBMS. Manipulate data in motion as part of executing the application's business rules. Represent data as presented in the user interface (UI)

LESSON: 
The vast majority of software development involves creating programs that manipulate data in some fashion.
Let's zoom out a bit and look at the database in the context of a large software system.
Designers of modern computer systems of all kinds, strive to separate between the following different concerns of dealing with data.
The first concern is the presentation of data performed by the frontend.
This includes the user interface in which data is presented to the end-user and where that user can give commands to manipulate it.
The second concern is the manipulation of data based on business logic performed by the backend.
This includes the functionality in charge of processing data before presenting it to the user, and processing user commands to change the data before storing them as updated data in the database or denying those commands.
The third concern is the persistence of data performed by the DBMS.
This includes the functionality of storing data in a reliable manner and making it available for rapid retrieval and manipulation by the backend.
This is what our model focuses on.
These three concerns are often separated into tiers, which are implemented as separate software components that are often running on separate computers.
This separation has the benefit that changing and scaling of each component can then be achieved separately, without any regard to the others as long as the interfaces between those are well-defined.
This split is the classical approach known as the three-tier architecture.
But in some cases, the handling of data could be split into additional tiers, which is known as a Multi-tier or N-tier architecture.
For example, in cases where fast availability of data is critical, and serving of slightly stale data is fine, we might add what's known as a cache layer, which holds an out-of-date, read-only copy of the data for rapid access, perhaps refreshed every 10 minutes.
And thus splitting the persistence there into those two separate tiers: cache and the DBMS.

# An Introduction To Relational Databases
 
## What is it?

Relational Database

## What does it do?

Represents data in table form. Relationships can be created and maintained among tables

## How do you use it?

Use a relational database for highly structured, non-nested data formats

LESSON:

The most commonly used type of database is a relational database.
The concept of relational databases was developed by the computer scientist Edgar Codd in 1969 while working for IBM.
Codd introduced a rigorous mathematical model for databases, which allowed for many useful properties and optimizations, which in turn led to wide adoption of the relational model by most of the IT industry, such that nowadays, it is considered to be the default kind of database.
Relational databases are also widely known as SQL, often pronounced sequel databases.
SQL stands for Structured Query Language.
It is a special language which is used to send commands to relational databases.
SQL will be discussed later in the module.
Much of this module will focus on relational databases, and that is because they are an extremely mature and well-designed technology.
As a general guideline, unless a specific need arises based on the form of your data or your access patterns, you should generally prefer to use a relational database.
A relational database consists of tables, each of which is similar to a single flat-file but with lots of additional metadata to give it structure.
Each table can hold any number of data records of the same type, for example, a cities table.
Let's look at an example of how the location data for our online store's customers can be stored in a relational database.
We will split our data into two separate tables, each responsible for one of the entities we care about: cities and countries.
Just like in flat-files, each row in a table corresponds to a record for a single instance of that entity type, and each column corresponds to an attribute of the entity.
For example, we will have the record for the city of London as a row within the cities table, and the city's name field will appear in the name column of that table.
Tables in a relational database have a well-defined structure known as a schema.
This schema is metadata that defines what fields each record in the table is supposed to have, and this means that all the records in each table must have the same structure to conform to the table's schema.
Let's now look at all the columns in these two tables, starting from the countries table.
The name column is simply the country's name, and the currency column is the currency used there.
But the more interesting thing is the country ID column.
This special column contains the primary key for each country record.
Just a quick reminder: a primary key is a way to uniquely identify a record, regardless of any changes it might undergo.
In the case of countries, you most likely will not have two countries with the exact same name, but even so, a country's name might change, while the rest of it stays the same.
To be safe, we will generally want to create a special numeric ID column that will be used as the unique primary key, and then use that number as a way to refer to the record.
Let's look at the cities table now.
A city also has a numeric primary key, in this case, called city ID.
And all the other columns are simple data fields other than the special country ID column.
You might have guessed by now that the country ID is the way for a city to refer to a record in the countries table.
The values in this column are the countries' primary keys.
This is known as a foreign key inside the cities table.
A foreign key is a field in a record of one table, which refers to a primary key of record found in another table.
When using SQL to retrieve data from multiple tables, we can use an operation known as a join to connect the records in different tables based on these foreign keys.
The big difference between a relational database and a collection of flat-files or many other kinds of data stores is that relational databases also allow us to define connections between records in different tables.
This usage of primary and foreign keys to connect records of different kinds is a main property and a big advantage of using relational databases, particularly in how it allows us to store every piece of information only once.
Let's see how this might help us.
For example, if tomorrow, we are asked to begin always addressing the 'United Kingdom' as the 'United Kingdom of Great Britain and Northern Ireland', we would just need to make a single change in the name column of the countries table, instead of having to change many rows in the cities table.
In the next unit of this module, we will focus on the design and usage of relational databases.
But for now, let's discuss some other types of databases.

# Introduction To Document-Oriented Databases
 
## What is it?

A non-relational DBMS

## What does it do?

Provides a means of working with high volumes of non-relational data usually in JSON or XML format

## How do you use it?

Use a document-oriented DBMS as a way of grouping collections of similar formatted document data.

LESSON:

Document-oriented databases, also known as document stores, are perhaps the greatest success of the NoSQL movement and are the closest to providing the full set of functionalities available in relational databases.
The motivation behind these databases came from web companies with a very high rate of operations that needed to scale their database beyond what was possible with relational databases and were willing to forego some of the benefits provided by relational DBMS.
Similar to the way relational databases can be said to have emerged from flat-files, document-oriented databases have emerged from structured data formats, such as JSON and XML.
Document-oriented databases store data records in the form of documents, which are structured hierarchical entities inspired by the format used in JSON or XML.
In fact, document-oriented databases generally use JSON and XML as the main way of creating and reading data records.
Unlike with relational databases, each document in the document-oriented database is considered completely separate from other documents and can have a completely different set of fields.
In other words, unlike with relational databases that have a rigid structure defined by a schema, document-oriented databases do not have a schema.
And individual records can differ from one another in terms of the fields they contain.
Also, unlike relational databases in which in which each table contains only records for a single entity, and we can rely on joins to connect data from multiple tables, document-oriented databases do not support join operations.
And documents are expected to each contain within themselves all of the data records that are relevant to it.
In other words, documents often contain records belonging to more than one entity.
Let's consider, for example, that we want to perform market research of users in different countries and the cities in them.
For the needs of our analysis, countries are the main entity type, and cities only make sense as part of countries.
So we might structure our data as documents where each document contains a record of a country and, within it, a set of nested records for the cities in that country.
Similar to the function of a table in relational databases, which serves as a place to store all records representing a certain entity, document-oriented databases use collections as a way of grouping similar documents.
So in our example, we would put our country and city documents in a collection named countries.
Document-oriented databases are sets of such collections of documents where each collection is similar to a table, in that it contains records, but does not enforce a fixed structure for all the documents inside of it.
Some organizations choose to put all of your documents in one huge collection, but that does not have to be the case.
Similar to key-value stores and relational databases, every document in a collection has a primary key which allows you to find it.
But unlike with key value stores, there is a structure to the documents.
And the DBMS makes it possible to refer to specific attributes inside the document, such as querying specifically for the area of the city of Dublin without having to retrieve the entire document about the Republic of Ireland.

# NoSQL And Key-Value Databases
 
## What is it?

Key-value DBMS

## What does it do?

Stores data in key-value pairs when the actual data (the value) can be identified by an associated key.

## How do you use it?

Use a key-value based DBMS when working with data that doesn't have a very well defined structure

LESSON:

Despite their numerous advantages, relational databases are quite complicated and hard to maintain.
And for some types of data, they are hard to scale to internet scale usage where to serve all the users, you need more than one server.
Around 2009 there began a resurgence of interest in simpler database structures and DBMSs that would be easier to split to multiple servers.
This is known as the NoSQL movement.
Some organizations, particularly startups, gave up completely on SQL, but most organizations rely on relational databases where they work well and supplement them with NoSQL databases where needed.
Key-value databases, or key-value stores, are the most basic type of database imaginable and, indeed, are often not referred to as a database at all.
With key-value stores, each record is put in the database as a string value together with a key.
And it can then be fetched later by providing that key to the DBMS.
There is no other way to access a value.
The keys are similar to primary keys in a relational database, and they are usually numbers or short alphanumeric strings.
The values are usually long strings and don't have any predefined structure.
It is left to the decision of the application that uses that database how to use it, and any value in such a database can be completely different.
Key-value databases are used quite rarely as the main database but are often used as a cache to speed up retrieval of the most commonly accessed items.
The main key-value DBMS used in the industry, memcached, doesn't save the data on disk at all.
Instead, it stores all items in RAM (memory) and automatically deletes the least recently used items when new items are added, when it is beyond the memory capacity.
Using a key-value store such as memcached, an application that needs a specific piece of data, can quickly check if it is available in a key-value database.
And only if not, then look it up in the larger database.

# Specialised Databases & Summary Of Overview
 
## What is it?

Specialist database systems

# What does it do?

Provide specialization or niche storage formats

## How do you use it?

Consider these options based on very specific requierements and where an RDBMS is not effective

LESSON:

All the types of data stores we mentioned so far can be used for all types of data.
But for some very specific types of data, and the access patterns associated with them, specialized databases have evolved to optimize storage and access for those specific data types.
Even if you use a relational or document-oriented database as your main data store, you might want to consider these types of databases for separately storing any specialized data you may have.
Let's have a quick overview of three of the more common types of specialized databases.
A graph database is used to store many records for the same entity type that are related to one another in a network of similar connections.
A common use case for graph databases is to store data about social networks.
Each record describes a person and these records are connected to one another via the friendship relationship.
A graph database is very good at quickly answering questions related to finding friends of each person, or the list of a friend's other friends, or the closest path between any two people.
A time-series database is used when, instead of only caring about the most up-to-date values for each piece of data, you care about the entire history of those values.
Common use cases for such databases are often measuring constantly changing operational metrics important to your business.
A good example is for storing the values of stock prices as they change throughout the day.
Time-series databases let you quickly create up-to-date charts and graphs for how your data changes over time and help you discover short-term trends.
A geospatial database is used to store records with a physical location in the world based on their latitude and longitude.
These databases are mostly used for applications that involve interactions with a map and allow you to quickly answer queries to find all the records that are located inside a specific area of the world.
To sum up, these past few units gave us an overview of the most common data store types out there.
In the next units, we will dive deeper into relational databases, which are the most widely used database types, and document-orientated databases, which have been growing in popularity as a strong alternative to the relational approach.

# Quiz

# By definition, a database is a data store managed by a Database Management System (DBMS).
True.

# Which of the following are true about relational databases? (Select all that apply)
A relational database consists of tables, each of which is similar to a flat file.
Records are stored as rows in the table.
Fields are stored each in a separate column.

# Which of the following is used to send commands to relational databases?
Structured Query Language correct.

# What is the connection between primary and foreign keys?
A foreign key in one table references a primary key in another table.

# Document-oriented databases were inspired by the structure of JSON and XML.
True.

# Which of these is a common use-case for graph databases?
Social Networks.


   

   
   
   
   
   