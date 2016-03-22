[![Build Status](https://travis-ci.org/jboss-set/aphrodite.svg?branch=master)](https://travis-ci.org/jboss-set/jboss-streams)

JBoss-Streams
===========
A repository which contains a json file detailing the relationships between
various JBoss streams, as well as repository and branch information for each
component contained within a stream. Currently this file is utilised by various
SET tooling projects.

# Contributing
The streams.json file is very much a work in progress, so if you would like to
add additional data please issue a PR.

When adding additional components to a stream, please ensure that you add the
component to all of the streams that it belongs, along with the relevant repository
branch. For example, Hal belongs to wildfly and jboss-eap-6.4.z so it must be added
to both streams for completeness.

# Validate JSON

After your change, you can also validate the streams.json file by running:

```
mvn clean verify
```
