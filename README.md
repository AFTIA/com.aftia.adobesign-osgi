# Adobe Sign OSGI Wrapper

A simple OSGI wrapper for the publicly available [Adobe Sign Java SDK](https://github.com/adobe-sign/AdobeSignJavaSdk).

## Prerequisites 

* [Maven 3.3.x](https://maven.apache.org/download.cgi)
* [Java 8 or 11](https://adoptopenjdk.net/)

## How to build

To build all the modules run in the project root directory the following command with Maven 3:

    mvn clean install

## Modules

The main parts of the project are:

* `aggregator`: A Maven module that produces a JAR containing the Adobe Sign SDK along with all 3rd party dependencies.
* `wrapper`: A Maven module that produces a JAR that wraps and exposes the Adobe Sign SDK by generating an OSGI manifest. This JAR can be installed in an OSGI runtime to use the SDK.

