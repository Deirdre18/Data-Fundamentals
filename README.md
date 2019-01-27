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

   