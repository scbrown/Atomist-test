
Atomist-test microservice
===========================

Originally created on 2016-10-04.

My new project

To run locally
--------------

This Spring Boot microservice is driven using Maven. To run locally simply execute the following from the command line:

```shell
> ./mvnw spring-boot:run
```

To run tests
------------

This microservice comes with some rudimentary tests as a good starting point for writing your own. Use the following command to execute the tests using Maven:

```shell
> ./mvnw test
```


---
Created by Atomist. Need Help? <a href="https://join.atomist.com/">Join our Slack team</a>

To run inside a docker container
--------------------------------

You can now build, package and run this microservice using Docker.

Now you can build your docker image by entering from a terminal where you have access to Docker, execute the following command:

```shell
> ./mvnw clean package docker:build
```

Even push it to a repository of your choice:

```shell
> ./mvnw clean package docker:build -DpushImage
```

To run inside a docker container
--------------------------------

You can now build, package and run this microservice using Docker.

Now you can build your docker image by entering from a terminal where you have access to Docker, execute the following command:

```shell
> ./mvnw clean package docker:build
```

Even push it to a repository of your choice:

```shell
> ./mvnw clean package docker:build -DpushImage
```
