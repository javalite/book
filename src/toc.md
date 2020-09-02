# Foreword 

Why JavaLite was created: 

* Igor started writing in Java in 1996, when Java was fun. It offered a huge productivity leap compared to C++.
* Igor developed a first web app in 1999, but since containers were not available or were very buggy, he developed the entire web 
    server, a form of a templating system and a way to write code fast, without realizing this was a product in itself.
* Web just started to come out if its infancy and Sun released very useful specifications, such as JDBC and Servlets API. 
* Late 90s Java was all the ragem and Sun pushed out so-called Enterprise standards, which immediately killed all the productivity. 
* That took out the wind out of a fresh breath Java had in the 90s and killed the speed of develppment. 
* In early 2000s, Java was hard, and Spring came out to aleviate some pains. 
* Rails came out in 2005, and Igor was at the SD West conference, seeing the Rails presentation. 
** The presenter focused on building pretty HTML, so Igor "did not get" it
* In 2007, Sears project was done in a typical Java "agile" fashion: Spring, Hybernate, Struts. It was slow to execute and slow to develop. 
* A few Rails developers joined the project and convinced the Sears management that Rails is better.
* In a typical Sears management style (no analysis), the management made a technical decision to keep the existing Java features but build all new features in Rails in a mixed technical environment. 
* From a tech stand point, it was very hard, but presented an opportulity to learn Rails 
* Rails turned out to be was very impressive because: 
  * It was the first comprehensive framework with everything built to work together: 
  * processing web requests, 
  * generating views, 
  * access to database
  * db migrations
  * Logging
  * Caching
  * Etc.
  
In other words, it was build to have alll components as opposed to having to integrate them by hand. 

The Ruby as a language was easy to pickup if you are a Java developer (I would argue it is much the same as 
Java, despite that Ruby developers at the time), but it was the frameworks approach to 

## Acknowledgments 

Team effort - list top contributors to the framework, including 
* Tyler Jennings for introducing me to Rails 
* Toby Tripp and Nick Zalabak  for many inspirational conversations and "..till blue in the face" arguments.

* Obie Henrandez - for writing the "The Rails Way" book that served as a guide for writing this one. 

h1. About the Authors

* Igor Polevoy - praise yourself
* ??


# Introduction

This books is long overdue. The initial code for the framework was written and and put into production back in 2009, and 
powered a massive product for a well known insurance company. In other words, the initial deployment was already commercial and 
development rose from the necessity to have a technology that  allowed the following:

* Minimal code 
* Almost no  configuration
* Fast development cycle
* Ability to  write readable code, since maintenance is a bulk of software cost. 


##  About This Book

##  Who should read this book

* A Java developer - beginner, journeyman and a master, anyone can  benefit 
 
##  Goals

* Gaining  understanding of the agile approach for building modern business systems 
in Java with the help of JavaLite.  
 

##  Required Technology

* The Java Programming language
* At least a cursory understanding of SQL and relational databases.
* Some understanding of web applications practices and some standards,
    * HTTP
    * Ajax
    * REST

## What is JavaLite

* Umbrella  for AJ, AW, Async, Migrator, etc. 
* Each component can be used independently and also together 
* Simplicity is a driving factor 


### Principles: 

* Get the best idea from Ruby on Rails, as long as they still make sense in Java 
* Get  the best ideas  from Java, including low level specifications: JDBC, JMS, Servlets, Maven, Gradle, Jar, War deployment.
* Stay container - agnostic  
* Allow to use any other tools Java developers use. 
* Allow for fast prototyping 
* Provide everything you need in a typical app, aside from specialized features
* Provide the highest levels of support for TDD. Tests  (also known as specs) are the backbone of modern software development. 

### Components

* ActiveJDBC - description here 
* ActiveWeb - ---
* DBMigrator - --
* JSpec - - 
* Async ---
* AppConfig


## ActiveJDBC ORM and the database access

### Low level, just above JDBC

* Connection management uses ThreadLocal a novel idea - parallel to Aspect-oriented programming   
* Describe DB  and  Base classes



> Below  is a TOC from RoR book top poach for ideas
 


1.2 Startup and Application Settings
1.3 Development Mode
1.4 Test Mode
1.5 Production Mode
1.6 Configuring a Database
1.7 Configuring Application Secrets
1.8 Logging

2 Routing
2.1 The Two Purposes of Routing
2.2 The routes.rb File
2.3 Route Globbing
2.4 Named Routes
2.5 Scoping Routing Rules
2.6 Listing Routes
2.7 Conclusio

3. REST, Resources, and Rails
3.1 REST in a Rather Small Nutshell
3.2 Resources and Representations
3.3 REST in Rails
3.4 Routing and CRUD
3.5 The Standard RESTful Controller Actions
3.6 Singular Resource Routes
3.7 Nested Resources
3.8 Routing Concerns
3.9 RESTful Route Customizations
3.10 Controller-Only Resources
3.11 Different Representations of Resources
3.12 The RESTful Rails Action Set
3.13 Conclusion

5 Working with Active Record
5.1 The Basics
5.2 Macro-Style Methods
5.3 Defining Attributes
5.4 CRUD: Creating, Reading, Updating, Deleting
5.5 Database Locking
5.6 Where Clauses
5.7 Connections to Multiple Databases in Different Models
5.8 Using the Database Connection Directly
5.9 Other Configuration Options
5.10 Conclusion


6 Active Record Migrations
6.1 Creating Migrations
6.2 Data Migration
6.3 schema.rb
6.4 Database Seeding
6.5 Database-Related Rake Tasks
6.6 Conclusion


7 Active Record Associations
7.1 The Association Hierarchy
7.2 One-to-Many Relationships
7.3 The belongs_to Association
7.4 The has_many Association
7.5 Many-to-Many Relationships
7.6 One-to-One Relationships
7.7 Working with Unsaved Objects and Associations
7.8 Association Extensions
7.9 The CollectionProxy Class
7.10 Conclusion


8 Validations
8.1 Finding Errors
8.2 The Simple Declarative Validations
8.3 Common Validation Options
8.4 Conditional Validation
8.5 Short-form Validation
8.6 Custom Validation Techniques
8.7 Skipping Validations
8.8 Working with the Errors Hash
8.9 Testing Validations with Shoulda
8.10 Conclusion

9 Advanced Active Record
9.1 Scopes
9.2 Callbacks
9.3 Calculation Methods
9.4 Single-Table Inheritance (STI)
9.5 Abstract Base Model Classes
9.6 Polymorphic has_many Relationships
9.7 Enums
9.8 Foreign-key Constraints
9.9 Modules for Reusing Common Behavior
9.10 Modifying Active Record Classes at Runtime
9.11 Using Value Objects
9.12 Non-Persisted Models
9.13 PostgreSQL enhancements
9.14 Conclusion


10 Action View
10.1 Layouts and Templates
10.2 Partials
10.3 Conclusion


14 Authentication and Authorization 428
14.1 Devise 428
www.it-ebooks.infoCONTENTS
14.2 has_secure_password 434
14.3 Pundit 439
14.4 Conclusion


15 Security
15.1 Password Management
15.2 Log Masking
15.3 SSL (Secure Sockets Layer)
15.4 Model mass-assignment attributes protection
15.5 SQL Injection
15.6 Cross-Site Scripting (XSS)
15.7 XSRF (Cross-Site Request Forgery)
15.8 Session Fixation Attacks
15.9 Keeping Secrets
15.10 Conclusion


17 Caching and Performance
17.1 View Caching
17.2 Data Caching
17.3 Control of Web Caching
17.4 ETags
17.5 Conclusion


18 Background Processing
18.1 Delayed Job
18.2 Sidekiq
18.3 Resque
18.4 Rails Runner
18.5 Conclusion


19 Ajax on Rails
19.1 Unobtrusive JavaScript
19.2 Turbolinks
19.3 Ajax and JSON
19.4 Ajax and HTML
19.5 Ajax and JavaScript
19.6 Conclusion


20 Asset Pipeline
20.1 Asset Pipeline
20.2 Wish List
20.3 The Big Picture
20.4 Organization. Where does everything go?
20.5 Manifest files
20.6 Custom format handlers
20.7 Post-Processing
20.8 Helpers
20.9 Fingerprinting
20.10 Serving the files
20.11 Rake Tasks
20.12 Conclusion


21 RSpec
21.1 Introduction
21.2 Basic Syntax and API
21.3 Matchers
21.4 Custom Expectation Matchers
21.5 Shared Behaviors
21.6 Shared Context
21.7 RSpec’s Mocks and Stubs
21.8 Running Specs
21.9 RSpec Rails Gem
21.10 RSpec Tools
21.11 Conclusion


22 XML
22.1 The to_xml Method
22.2 The XML Builder
22.3 Parsing XML
22.4 Conclusion


Rails Essentials
Environmental Concerns
Essential Gems
Ruby Toolbox
Screencasts
