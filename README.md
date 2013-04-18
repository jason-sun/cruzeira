Cruzeira
============

Cruzeira brings [Netty.io](http://netty.io/) to [Spring Framework](http://www.springframework.org/) implementing a subset of the [Servlet API](http://docs.oracle.com/javaee/6/api/javax/servlet/package-summary.html).

How to test:

* Clone cruzeira repo

        git clone https://github.com/fabiofalci/cruzeira.git
        cd cruzeira

* Install cruzeira locally with maven

        cd cruzeira
        mvn install

* Install cruzeira maven plugin

        cd cruzeira-plugin
        mvn install

* Execute some of the samples projects

        cd cruzeira-samples/spring-mvc-showcase
        mvn compile exec:exec
        // try http://localhost:8080

        // or
        cd cruzeira-samples/cruzeira-sample
        mvn compile exec:exec
        // try http://localhost:8080/async or http://localhost:8080/controller


It will run an instance of Netty and will dispatch any HttpRequest to SpringMVC.

Attention
---------

This is a work in progress. Even if Netty and Spring appears to be handling requests nicely, it should not be used seriously before a release.
       
## License
The Cruzeira is released under version 2.0 of the [Apache License](http://www.apache.org/licenses/LICENSE-2.0).