DukesAgeRestService
===================

Simple REST-Webservice with Maven and Resteasy

Based on the tutorial [1] but instead of using Netbeans, Ant and Glasfish, 
this is using Maven and tested on JBoss AS 7.1. It's influenced by [2]. This short example 
implements a simple REST-Webservice using Resteasy [3] as JAX-RS implementation.

The DukesAgeResource calculates the current age of Duke [4]. After packaging and deploying it on a JBoss
it should be available at http://localhost:8080/dukesageservice-0.0.1-SNAPSHOT/dukesAge

[1] http://docs.oracle.com/javaee/6/firstcup/doc <br />
[2] http://indiwiz.com/2009/01/26/getting-started-with-jboss-resteasy-10/<br />
[3] http://www.jboss.org/resteasy <br />
[4] http://upload.wikimedia.org/wikipedia/commons/4/40/Wave.svg