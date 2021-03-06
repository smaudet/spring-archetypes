# spring-archetypes
Automatically exported from code.google.com/p/spring-archetypes

What is it?
===========

This archetype will create a Maven project with the following characteristics:

* Everything is configured using Spring 3
* Hibernate 3.5 is used for persistence in Hypersonic in-memory db (HSQLDB)
* Base class for CRUD-operations
* Base class for unit tests and simple integration test
* Sitemesh configured as jsp layout manager
* Configured embedded jetty server

How to run
==========

* checkout
* run mvn install. This will public archetype to local repo
* run mvn archetype:generate -DarchetypeCatalog=local. This will prompt you with list of locally installed artifact where you should choose appropriate number of recently installed one.
* Patches are welcome
Please do not hesitate to send me patches or contacting me on joining the project at stas.fedotov[at]gmail.com

Additional resources
====================

* http://start.spring.io/
* https://github.com/kolorobot/spring-mvc-quickstart-archetype
