# Redmine/Chiliproject Java API.

#### This fork information:
1.23 Redmine Java API version forked to be used with Maven format.

**Important:**
If you need an up-to-date API, use [Original Project](https://github.com/taskadapter/redmine-java-api).

#### Maven usage:
`mvn clean package` or `mvn clean package -DskipTests` to skip tests.

#### [Original description](https://github.com/taskadapter/redmine-java-api)

* Requires Java 6.
* Uses Redmine REST API
* Does not require any plugins installed on Redmine/Chiliproject server.
* Runs on any standard Java platform
* Supports HTTP proxy
* Supports GZipped responses from servers
* Uses SLF4J for logging. Provide [your own SLF4J binding](http://www.slf4j.org/codes.html#StaticLoggerBinder)
* [Supported Redmine versions] (https://github.com/taskadapter/redmine-java-api/wiki/Redmine-versions-compatibility)
* Available in Maven Central.

Gradle dependency:

    dependencies {
        compile 'com.taskadapter:redmine-java-api:1.21'
    }

Check the [latest release version in Maven Central](http://search.maven.org/#search%7Cgav%7C1%7Cg%3A%22com.taskadapter%22%20AND%20a%3A%22redmine-java-api%22)
