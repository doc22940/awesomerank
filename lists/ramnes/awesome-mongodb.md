![Awesome MongoDB](logo.png)

# Awesome MongoDB [![Awesome](https://cdn.rawgit.com/sindresorhus/awesome/d7305f38d29fed78fa85652e3a63e154dd8e8829/media/badge.svg) ★57421](https://github.com/sindresorhus/awesome)

> A curated list of awesome MongoDB resources, libraries, tools and applications

Inspired by the [awesome](https://github.com/sindresorhus/awesome) list thing. Feel free to improve this list by [contributing](CONTRIBUTING.md)!

## Table of Contents
 - [Resources](#resources)
  - [Documentation](#documentation)
  - [Articles](#articles)
  - [Talks](#talks)
  - [Tutorials](#tutorials)
  - [More](#more)
 - [Libraries](#libraries)
  - [C](#c)
  - [C++](#c-1)
  - [C#/.NET](#cnet)
  - [Delphi](#delphi)
  - [Erlang](#erlang)
  - [Go](#go)
  - [Haskell](#haskell)
  - [Java](#java)
  - [JavaScript](#javascript)
  - [Julia](#julia)
  - [Lisp](#lisp)
  - [Mathematica](#mathematica)
  - [Perl](#perl)
  - [PHP](#php)
  - [Python](#python)
  - [R](#r)
  - [Ruby](#ruby)
  - [Rust](#rust)
  - [Scala](#scala)
 - [Tools](#tools)
  - [Administration](#administration)
  - [Big Data](#big-data)
  - [Clients](#clients)
    - [GUI](#gui)
    - [Shell](#shell)
    - [Web](#web)
  - [Deployment](#deployment)
  - [Monitoring](#monitoring)
 - [Applications](#applications)

## Resources
### Documentation
 - [MongoDB introduction](https://docs.mongodb.org/manual/core/introduction/)
 - [MongoDB documentation](https://docs.mongodb.org/manual/)
 - [MongoDB tutorials](https://docs.mongodb.org/manual/tutorial/)

### Articles
 - [Five Things About Scaling MongoDB (A. Jesse Jiryu Davis, MongoDB Inc.)](https://emptysqua.re/blog/five-things/) - Scale 101
 - [Optimizing MongoDB Compound Indexes (A. Jesse Jiryu Davis, MongoDB Inc.)](http://emptysqua.re/blog/optimizing-mongodb-compound-indexes/) - Everything you need/have to know about indexes
 - [Server Discovery And Monitoring In PyMongo, Perl, And C (A. Jesse Jiryu Davis, MongoDB Inc.) ](https://emptysqua.re/blog/server-discovery-and-monitoring-in-pymongo-perl-and-c/)
 - [Monitoring MongoDB performance metrics (Jean-Mathieu Saponaro, Datadog)](https://www.datadoghq.com/blog/monitoring-mongodb-performance-metrics-wiredtiger/)

### Talks
 - [MongoDB Schema Design (Tugdual Grall, MongoDB Inc.)](https://www.youtube.com/watch?v=csKBT8zkRf0) [47']
 - [Partial and Fuzzy Matching with MongoDB (John Page, MongoDB Inc.)](https://www.youtube.com/watch?v=hXbLHInH5qU) [35']
 - [Scaling MongoDB on Amazon Web Services (Michael Saffitz, Apptentive)](https://www.youtube.com/watch?v=bkjVhEQocFI) [50']

### Tutorials
 - [Create a TV Show Tracker Using AngularJS, Node.js, and MongoDB](http://sahatyalkabov.com/create-a-tv-show-tracker-using-angularjs-nodejs-and-mongodb/) - Build a REST API using Mongoose to create and retrieve data from MongoDB
 - [Write a Tumblelog Application with Flask and MongoEngine](https://docs.mongodb.org/ecosystem/tutorial/write-a-tumblelog-application-with-flask-mongoengine/) - Nice Python tutorial hidden into the official Python driver documentation
 - [Kubernetes examples](https://github.com/kubernetes/kubernetes/tree/master/examples/nodesjs-mongodb) - Deployment tutorial of a basic Node.js and MongoDB web stack on [Kubernetes](https://kubernetes.io/docs/whatisk8s/)

### More
 - [MongoDB source code ★11405](https://github.com/mongodb/mongo)
 - [MongoDB University](https://university.mongodb.com/) - Certifications and free online courses
 - [MongoDB Cloud Manager](https://www.mongodb.com/cloud/) - MongoDB Inc. cloud offer
 - [MongoLab](https://mongolab.com/) - Fully managed MongoDB-as-a-Service
 - [Scalegrid](https://scalegrid.io) - Fully managed MongoDB-as-a-Service (with option to bring your own Azure/AWS account)

## Libraries
### C
 - [mongo-c-driver ★319](https://github.com/mongodb/mongo-c-driver) - Official C driver

### C++
 - [mongo-cxx-driver ★364](https://github.com/mongodb/mongo-cxx-driver) - Official C++ driver

### C#/.NET ###
 - [mongo-csharp-driver ★1561](https://github.com/mongodb/mongo-csharp-driver) - Official C# driver
 - [mongo-queue-csharp ★23](https://github.com/dominionenterprises/mongo-queue-csharp) - C# message queue backed by MongoDB
 - [MongoDB Messaging ★34](https://github.com/loresoft/MongoDB.Messaging) - Lightweight queue pub/sub processing library
 - [MongoRepository ★162](https://github.com/RobThree/MongoRepository) - Repository abstraction layer on top of the C# driver

### Delphi
 - [TMongoWire ★62](https://github.com/stijnsanders/TMongoWire) - Minimal community Delphi driver

### Erlang
 - [mongodb-erlang ★243](https://github.com/comtihon/mongodb-erlang) - Community Erlang driver

### Go
 - [mgo ★1354](https://github.com/go-mgo/mgo) - Community Go driver

### Haskell
 - [mongodb ★62](https://github.com/mongodb-haskell/mongodb) - Community Haskell driver

### Java
 - [Jongo ★451](https://github.com/bguerout/jongo) - Query in Java as in Mongo shell
 - [Hibernate OGM ★223](https://github.com/hibernate/hibernate-ogm) - The power and simplicity of JPA for NoSQL datastores
 - [mongo-java-driver ★1743](https://github.com/mongodb/mongo-java-driver) - Official Java driver
 - [mongo-queue-java ★24](https://github.com/gaillard/mongo-queue-java) - Java message queue backed by MongoDB
 - [mongoFS ★16](https://github.com/dbuschman7/mongoFS) - An enhancement of MongoDB's GridFS to allow for more features and capabilities
 - [Mongojack ★170](https://github.com/mongojack/mongojack) - Based on Jackson, allows you to easily handle your mongo objects as POJOs
 - [Morphia ★1123](https://github.com/mongodb/morphia) - Official Java ODM
 - [Morphium ★38](https://github.com/sboesebeck/morphium) - Java ODM and caching layer
 - [Mungbean ★20](https://github.com/jannehietamaki/mungbean) - Community driver for languages running on the JVM
 - [Spring Data MongoDB ★673](https://github.com/spring-projects/spring-data-mongodb) - Spring based, object-document support and repositories for MongoDB

### JavaScript
 - [Camo ★310](https://github.com/scottwrobinson/camo) - Class-based ES6 ODM for Mongo-like databases
 - [MEAN.JS ★4134](https://github.com/meanjs/mean) - Full-Stack based on MongoDB, Express, AngularJS, and Node.js
 - [MERN (mern-starter) ★3663](https://github.com/Hashnode/mern-starter) - Full-Stack based on MongoDB, Express, React and Node.js
 - [Mongoose ★12125](https://github.com/Automattic/mongoose) - Node.js asynchronous ODM
 - [mongration](https://github.com/eberhara/mongration) - Node.js migration framework
 - [Moonridge ★54](https://github.com/capaj/Moonridge) - Framework with live querying on top of Mongoose and socket.io
 - [node-mongodb-native ★5649](https://github.com/mongodb/node-mongodb-native) - Official Node.js driver

### Julia
 - [Mongo.jl ★28](https://github.com/Lytol/Mongo.jl) - Bindings on MongoDB official C driver

### Lisp
 - [cl-mongo ★109](https://github.com/fons/cl-mongo) - Community Common Lisp interface
 - [mongo-cl-driver ★29](https://github.com/archimag/mongo-cl-driver) Community Common Lisp driver
 - [mongo-el ★38](https://github.com/m2ym/mongo-el) - Community Emacs Lisp driver

### Mathematica
 - [MongoDBLink ★12](https://github.com/zbjornson/MongoDBLink) - Community Mathematica driver

### Perl
 - [mongo-perl-driver ★187](https://github.com/mongodb/mongo-perl-driver) - Official Perl driver

### PHP
 - [Doctrine MongoDB ★282](https://github.com/doctrine/mongodb) - Wrapper around the native PHP Mongo PECL extension to provide additional functionality
 - [eloquent-mongodb-repository](https://github.com/PHPRepository/php-eloquent-mongodb-repository) - Repository implementation built on top of laravel-mongodb
 - [laravel-mongodb ★2488](https://github.com/jenssegers/laravel-mongodb) - Eloquent model and query builder for Laravel
 - [mongodb-repository](https://github.com/PHPRepository/php-mongodb-repository) - Repository implementation
 - [pecl/mongodb ★353](https://github.com/mongodb/mongo-php-driver) - Official PHP driver

### Python
 - [Flask-PyMongo ★319](https://github.com/dcrosta/flask-pymongo) - PyMongo support for Flask applications
 - [MongoEngine ★1674](https://github.com/MongoEngine/mongoengine) - Python ODM on top of PyMongo
 - [MongoLog ★95](https://github.com/puentesarrin/mongodb-log) - MongoDB logging handler
 - [Mongo-Thingy ★3](https://github.com/numberly/mongo-thingy) - The most Pythonic and friendly-yet-powerful way to use MongoDB
 - [Motor ★772](https://github.com/mongodb/motor) - Non-blocking Python driver for Tornado applications
 - [PyMongo](https://github.com/mongodb/mongo-python-driver) - Official (and recommended) Python driver
 - [minimongo ★290](https://github.com/slacy/minimongo) - A lightweight, schemaless, Pythonic Object-Oriented interface
 - [scrapy-mongodb ★204](https://github.com/sebdah/scrapy-mongodb) - MongoDB pipeline for Scrapy
 - [μMongo ★43](https://github.com/Scille/umongo) - Driver-independent (async/sync) ODM based on marshmallow

### R
 - [mongolite](https://github.com/jeroenooms/mongolite) - Fast and Simple MongoDB Client for R

### Ruby
 - [mongo-ruby-driver ★1291](https://github.com/mongodb/mongo-ruby-driver) - Official Ruby driver
 - [Mongoid ★3485](https://github.com/mongodb/mongoid) - Ruby ODM framework

### Rust
 - [mongo-rust-driver-prototype ★168](https://github.com/mongodb-labs/mongo-rust-driver-prototype) - Prototype driver written for Rust 1.x and MongoDB 3.0.x

### Scala
 - [mongo-scala-driver ★150](https://github.com/mongodb/mongo-scala-driver) - Official Scala driver
 - [ReactiveMongo ★706](https://github.com/ReactiveMongo/ReactiveMongo) - Non-blocking Scala driver
 - [Spark-MongoDB ★262](https://github.com/Stratio/Spark-MongoDB) - Read/write data with Spark SQL

## Tools
### Administration
 - [mongo_fdw ★98](https://github.com/EnterpriseDB/mongo_fdw) - PostgreSQL foreign data wrapper for MongoDB
 - [mongoctl ★157](https://github.com/mongolab/mongoctl) - Manage MongoDB servers and replica sets using JSON configurations
 - [MongoDB Smasher ★18](https://github.com/duckie/mongo_smasher) - Generate randomized datasets and benchmark your MongoDB setup
 - [mongodb-tools ★232](https://github.com/jwilder/mongodb-tools) - Three neat Python scripts to work with collections and indexes
 - [Mongolastic ★51](https://github.com/ozlerhakan/mongolastic) - A dataset migration tool from MongoDB to Elasticsearch and vice versa
 - [MongoMultiMaster ★51](https://github.com/rick446/mmm) - Multi-Master MongoDB replication
 - [MoSQL ★1359](https://github.com/stripe/mosql) - MongoDB to PostgreSQL streaming replication
 - [mtools ★872](https://github.com/rueckstiess/mtools) - Collection of scripts to set up MongoDB test environments and parse and visualize MongoDB log files
 - [nginx-gridfs ★742](https://github.com/mdirolf/nginx-gridfs) - Nginx module for serving files from MongoDB's GridFS
 - [nginx-mongodb-rest ★30](https://github.com/minhajuddin/nginx-mongodb-rest) - MongoDB REST client written as an Nginx module
 - [Variety ★927](https://github.com/variety/variety) - Schema analyzer: see what fields are in your collection and what's their content

### Big Data
 - [mongo-hadoop ★1233](https://github.com/mongodb/mongo-hadoop) - MongoDB connector for Hadoop

### Clients
#### GUI
 - [HumongouS.io](https://www.humongous.io) - Web based GUI
 - [MongoChef](http://3t.io/mongochef) - Cross-platform MongoDB manager, stable and powerful
 - [MongoBooster](http://www.mongobooster.com) - Feature-rich but easy-to-use cross-platform MongoDB manager
 - [MongoHub ★2164](https://github.com/jeromelebel/MongoHub-Mac) - Mac native client
 - [Robomongo](https://github.com/paralect/robomongo) - Native and cross-platform MongoDB manager

#### Shell
 - [mongo-hacker ★1229](https://github.com/TylerBrock/mongo-hacker) - MongoDB shell enhancements

#### Web
 - [adminMongo ★817](https://github.com/mrvautin/adminMongo) - Web-based user interface to handle connections and databases needs
 - [mongo-express ★2093](https://github.com/mongo-express/mongo-express) - Web-based admin interface written with Node.js, Express and Bootstrap3
 - [mongoadmin ★261](https://github.com/thomasst/mongoadmin) - Admin interface for MongoDB built using Django and Bootstrap
 - [mongri](https://github.com/dongri/mongri) - Web-based user interface for MongoDB (written in JavaScript)
 - [Rockmongo ★744](https://github.com/iwind/rockmongo) - PHPMyAdmin for MongoDB, sort of

### Deployment
 - [ansible-role-mongodb ★102](https://github.com/UnderGreen/ansible-role-mongodb) - Ansible role
 - [chef-mongodb ★379](https://github.com/edelight/chef-mongodb) - Chef cookbook
 - [Dockerfile ★194](https://github.com/dockerfile/mongodb)
 - [Helm Chart](https://github.com/kubernetes/charts/tree/master/stable/mongodb) - Bootstraps a MongoDB deployment on a [Kubernetes](https://kubernetes.io/docs/whatisk8s/) cluster using the [Helm ★1504](https://github.com/kubernetes/helm) package manager.
 - [puppetlabs-mongodb ★81](https://github.com/puppetlabs/puppetlabs-mongodb) - Puppet module

### Monitoring
 - [check_mongodb](https://github.com/dalenys/check_mongodb) - Nagios plugin (in Bash)
 - [Datadog](https://www.datadoghq.com/blog/monitor-mongodb-performance-with-datadog?ref=awesome) - SaaS-based MongoDB monitoring
 - [Mongoop ★30](https://github.com/Lujeni/mongoop) - Long operations monitoring and alerting
 - [Motop ★56](https://github.com/tart/motop) - MongoDB top clone
 - [mtop ★50](https://github.com/beaufour/mtop) - Another top clone
 - [mongo-munin ★149](https://github.com/erh/mongo-munin) - Collection of Munin plugins
 - [mongomon ★24](https://github.com/pcdummy/mongomon) - More Munin plugins
 - [nagios-plugin-mongodb](https://github.com/mzupan/nagios-plugin-mongodb) - Nagios plugin (in Python)

## Applications
 - [Leanote ★5251](https://github.com/leanote/leanote) - Evernote clone built with Go and MongoDB
 - [Quokka ★1624](https://github.com/quokkaproject/quokka) - Python CMS built on top of Flask and MongoDB
 - [uptime ★3271](https://github.com/fzaninotto/uptime) - Remote monitoring application using Node.js, MongoDB, and Bootstrap

## License
[![CC0](http://mirrors.creativecommons.org/presskit/buttons/88x31/svg/cc-zero.svg)](https://creativecommons.org/publicdomain/zero/1.0/)

To the extent possible under law, [Guillaume Gelin](https://github.com/ramnes) has waived all copyright and related or neighboring rights to this work.