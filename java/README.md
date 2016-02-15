# cucumber-boilerplate: java

A JavaScript project including dependencies for use with
[Cucumber](https://cucumber.io).

## Basic requirements

- [Java](http://www.oracle.com/technetwork/java/javase/downloads/index.html)
- [Maven](https://maven.apache.org/download.cgi)

## Install dependencies

`mvn test`

**Note:** Running this command may create a folder structure, so it's not
advisable to run this in an existing project. If you wish to add Cucumber to a
project, combine the dependencies of the `pom.xml` file with your existing
project.

## Write tests

Place [features](https://cucumber.io/docs/reference#gherkin) in
`src/test/resources`.

Place [step definitions](https://github.com/cucumber/cucumber-jvm) in
`src/test/java`.

## Run tests

`mvn test`
