# CPT 166 Introduction

## Welcome


Welcome to CPT 166!  This week we will be completing the following:

- Introducing the concept of Data, Databases, and sql
- Working with data in one of the most widely-used business formats (Excel)
- Connecting to your Virtual Machines in our lab environment and installing DBeaver (SQL Client)


## Introduction

### Introducing Data

Please read the following:

- [IBM What is Data](https://www.ibm.com/think/topics/data)

  This link gives a really good high-level overview of what data is and its importance in the world. In this class we will be working in group projects with other CPT classes to construct a "Data Lake" which holds a variety of data sets which you all will are interested in!
- [Data IRL](https://www.betterbuys.com/dms/visualizing-the-size-of-databases/#:~:text=A%20kilobyte%20(KB)%20is%201%2C000,just%20over%20half%20a%20ream)

  Ever wonder if we converted electronic data to "physical" data how much space (almost literally!) it'd take up?  This webpage does a really good job of highlighting just how "big" our data really is!

Now imagine a world where we didn't have computers and would need to manage all of this data "by hand"!  The reality is that was not all that long ago.  I'm sure many of you have relatives who work in offices who would describe their first jobs or internships as organizing, sorting, and retrieving physical files from storage cabinets which were almost always cluttered and disorganized!


#### Introducing Databases

This is where databases come in!  

The world we live in today would be IMPOSSIBLE without the assistance of electronic databases.  There are mainly two types of databases, relational (the ones we'll mainly be using in this class) and non-relational (NoSQL) databases.  Relational databases allow for the efficient storage and retrieval of massive amounts of data super quickly! While there are many "licensed" (non-free) database platforms (mainly Oracle and SQL Server), we will be using PostgreSQL to teach database concepts in this class.  Please read the following article on Postgres's own website on what the project is about [PostgreSQL](https://www.postgresql.org/about/) and you can also watch this short video on why [PostgreSQL is so Popular](https://youtu.be/0lXjf3nxiGg?si=zixWH9PSZbt9NvKV)

Don't worry if you didn't follow much of that - it's ok!  There are a LOT of features we will not be getting to in this class.  Really the important takeaways for me are:

- PostgreSQL has a TON of built-in features which make it super powerful
- PostgreSQL is EXTREMELY extensible which makes it super flexible
- and most importantly...PostgreSQL is FREE!

Before we get into the cool stuff however we're going to touch on working with data in a way that many people in the business world today manipulate it.  Excel!

### Hands-On Assignments - Excel

Please Download and open the Excel file attached to this GitHub repository.  It is a free file which 
