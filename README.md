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

Swagger:

* [Swagger](http://swagger.io/) - The World's most popular API-Tooling
* [jaxrs-analyzer](https://github.com/sdaschner/jaxrs-analyzer) - generate your swagger docu with bytecode magic from your JAX-RS service
  * comment your javadoc with [markdown language](https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet#lines)
  * generate nice html with [pretty-swag](https://github.com/twskj/pretty-swag) -i swagger.json -f lite -m true
