# Interview Questions and Prep - Update at least weekly
(For training purposes)  

## Business Week

### 1. TMAY
Hello, my name is Dunni and I graduated from Goldsmiths university with a degree in Computer Science.  
During the course of my degree I got cover a variety of subjects, including Web dev and software projects.  
I also got to work with Java, Python, HTML + CSS + JavaScript...  
Came to like Computer Science through Maths --> Might have done Engineering, but I found I was better suited to Computer Science.  
In my free time I like drawing (cats) and doing other creative things.

### 2. What is Agile, and what is the benefit of implementing it?
Agile can be described as a mindset or an approach to project management. It revolves around having an iterative approach to project management and software development. An Agile team delivers work in small increments instead of all at once. This allows the team to be more flexible and ready to deal with the inevitable changes they are going to face during development. Through the/(this?) process, requirements and plans are coninually evaluated to teams can respond to change quickly.  

### 3. Why did I choose Sparta?  
I first heard about Sparta through codemas.  
This was during lockdown and I was looking to improve my Java and Python skills.  
codemas sounded interesting so I gave it a look. I ended up really liking how the instructor taught so I decided to look into Sparta  
One thing I noticed was the sense of community. I really liked the focus on supporting trainees (and beyond).  
That, to me, set Sparta apart from the others like them.  

### 4. What is Scrum and what is the benefit of implementing it?
Scrum is an Agile framework *not* a methodology. Scrum is meant to be simple.  
It's built upon a series of sprints which which gives the team a chance to review work before proceeding.  
Useful because everyone is involved in development. Has a high level of transparency and openness so problems get caught before they get far

### 5. Where do you see yourself in 2-5 years?
At the end of my two years at Sparta I hope to move on to join the company I'm working with as a DevOps consultant if I like it there. If not, I'll likely stay on with Sparta and keep developing my skills with them. I'd like to work towards being on the more technical side of the role as a Senior DevOps engineer.

### 6. What is DevOps and benefit of using it?
A combination of Development and Operations.  
- It brings the Development and Operations teams together, allowing them to work better together.
- Without DevOps, the teams work independently and often run into problems because of slight differences in their goals. Development often prioritises rolling out new and frequent updates while Operations want stability with each build.
- With DevOps there's better communication between the teams

## SQL Week

### 1. What is SQL and why is it used?
- It stands for 'Structured Query Language'
- It's a query language that's used to create schema, store, manipulate, and retireve data from relational databases
- Unlike programming languages (think Python or Java) users of SQL are only concerned with what they're doing. The 'how' is unimportant
- An example of the above is writing a query to display the full name of all employees with first names beginning with 'A'. In SQL, you'd do something like this:

``` SQL
SELECT firstname, lastname
FROM Employees
WHERE firstname LIKE 'A%';
```
And you would get a table as a result. The user doesn't need to think about how the results are retrieved. All they need to know is *what* to do to get the results they want.

### 2. What are the sub-languages of SQL?
- DML, which is Data Manipulation language. This allows the user to access and modify data and some of the commands are SELECT, INSERT, UPDATE, and DELETE
- DDL, Data Definition Language. This is the schema creation aspect. These queries allow one to set up the structure of the data. Some commands are CREATE, DROP, ALTER, and TRUNCATE
- DCL, Data Control Language. Used to control access to data in the database. Some common commands: GRANT, REVOKE
- TCL, Tansactiona Control Language. Handles transactions in the database. Some commands: COMMIT, ROLLBACK, SAVEPOINT

### 3. What is a join?
- A join is used to, well, join tables together (connect them).
- Joins are based on keys that both tables contain

### 4. Explain what primary and foreign keys are.
- Keys are used to identify rows in a table.
- Primary keys must be unique and cannot be *Null* while Foreign keys can be non-unique and *Null*
- Foreign keys are the primary keys from other tables

### 5. What is Normalisation?
The process of organising data in databases to:
- reduce redundancy
- reduce the chance of insertion, upadate, and deletion anomalies (unexpected behaviour) 

### 6. Handling Entity Relationship Diagrams
**What are ERD's used for?**  
- Used to represent relationships between tables in a database
- a nice visual way to show how objects are linked

## (Git and GitHub)

### What is Git?
Git is a version control system

### What is GitHub, and what are its benefits?
GitHub is an online repository, which uses Git, that saves file in the cloud.

![image](https://user-images.githubusercontent.com/18092824/111987743-7cd07400-8b07-11eb-8061-2cf01fb9a0e7.png)

## Python Week (01)


