# QuickHibernate
A quick bare bones example of using hibernate.

Features
--------

* A simple usage of hibernate with a couple of models
* Hibernate configurations and mappings (XML)
* Manage models with basic CRUD operations


Setup
--------

* Create a database and specify it in config file.
* Create a table with following query:-

create table EMPLOYEE (
   id INT NOT NULL auto_increment,
   first_name VARCHAR(20) default NULL,
   last_name  VARCHAR(20) default NULL,
   salary     INT  default NULL,
   PRIMARY KEY (id)
);

Links
--------
 * [Hibernate Docs](http://hibernate.org/orm/documentation/5.1/)
 * [Hibernate Docs](https://docs.jboss.org/hibernate/orm/4.1/manual/en-US/html/)
 * [Java API Docs](https://docs.oracle.com/javase/7/docs/api/)
 * [Tutorial](http://www.tutorialspoint.com/hibernate/hibernate_examples.htm)
