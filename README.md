# Overview over useful links, which will grow over time

Docker:

* [Docker Cheat Sheet](https://github.com/wsargent/docker-cheat-sheet)
* [SSH Example](https://docs.docker.com/engine/examples/running_ssh_service/)
* [Automated nginx proxy for Docker containers](http://blog.florianlopes.io/host-multiple-websites-on-single-host-docker/)
* [Docker for Java Developers](https://github.com/docker/labs/tree/master/developer-tools/java)
* [Docker labs](https://github.com/docker/labs/tree/master/beginner)
* [Rancher](http://rancher.com/) - open source platform for deploying and managing containers in production

```
docker search <repository>:<port>/<library>:<version>

docker exec -i -t <image> /bin/bash -> [cat <file>]

docker pull <image>
docker images
docker start/stop <image>
docker ps
docker exec <container> env
docker inspect <image>
```

Database:

* [Dbeaver](http://dbeaver.jkiss.org/) - Universal SQL Client
* [Jailer](https://github.com/Wisser/Jailer) - an tool for database subsetting, schema and data browsing. Perfect for create consistent DB test data.
* [Debezium](http://debezium.io/) - a amazing distributed platform for change data capture
* [Jeddict](https://github.com/jeddict/jeddict) - before JPAModeller, JPA, Java EE 8 and MicroProfile application generator
* [KissMDA](https://github.com/crowdcode-de/KissMDA) - Model Driven Architecture (MDA) generator

Swagger:

* [Swagger](http://swagger.io/) - The World's most popular API-Tooling
* [jaxrs-analyzer](https://github.com/sdaschner/jaxrs-analyzer) - generate your swagger docu with bytecode magic from your JAX-RS service
  * comment your javadoc with [markdown language](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#lines)
  * generate nice html with [pretty-swag](https://github.com/twskj/pretty-swag) -i swagger.json -f lite -m true

Enterprise Integration Patterns:

* [Apache Karaf](https://karaf.apache.org/) - modern and polymorphic container
  - [Apache Decanter](https://karaf.apache.org/projects.html#decanter) - Business Activity Monitoring
* [Apache Camel](http://camel.apache.org/) - concrete implementations of all the widely used Enterprise Integration Patterns (EIPs)
* [Smooks](http://www.smooks.org/) - Smooks is an extensible framework for building applications for processing XML and non XML data (CSV, EDI, Java etc) using Java

Web Frontend Systems:

* [Errai](http://erraiframework.org/) - Java EE In The Browser, GWT based
* [Vaadin](https://vaadin.com/) - Vaadin Framework is a Java UI framework that simplifies your web app development, GWT based, new with web components
* [Vue](https://vuejs.org/) - The Progressive JavaScript Framework, can be compared to REACT
