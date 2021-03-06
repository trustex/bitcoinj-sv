[![Build Status](https://travis-ci.org/bitcoinj-sv/bitcoinj-sv.png)](https://travis-ci.org/bitcoinj-sv/bitcoinj-sv)   [![Coverage Status](https://coveralls.io/repos/github/bitcoinj-sv/bitcoinj-sv/badge.svg)](https://coveralls.io/github/bitcoinj-sv/bitcoinj-sv) 

### NOTICE
This is a work in progress. It is not ready for release and I don't advise using it yet. It's future is also uncertain at this time.

### Welcome to bitcoinj-sv

The bitcoinj-sv library is a Java implementation of the Bitcoin SV protocol. This library is a fork of Mike Hearn's original bitcoinj library aimed at supporting Bitcoin SV.

It allows maintaining a wallet and sending/receiving transactions without needing a full blockchain node.

### Technologies

* Java 8 
* [Maven 3+](http://maven.apache.org) - for building the project
* [Google Protocol Buffers](https://github.com/google/protobuf) - for use with serialization and hardware communications

### Getting started

To get started, it is best to have the latest JDK and Maven installed. The HEAD of the `master` branch contains the latest release and the `dev` branch contains development code.

#### Building from the command line

To perform a full build use
```
mvn clean package
```
The outputs are under the `target` directory.

#### Building from an IDE

Alternatively, just import the project using your IDE. [IntelliJ](http://www.jetbrains.com/idea/download/) has Maven integration built-in and has a free Community Edition. Simply use `File | Import Project` and locate the `pom.xml` in the root of the cloned project source tree.

### Example applications

These are found in the `examples` module.

### Contributing to bitcoinj-sv

Contributions to bitcoinj-sv are welcome and encouraged.

* the development branch is `dev` 
* Travis-CI is [here](https://travis-ci.org/bitcoinj-sv/bitcoinj-sv)
* Coveralls test coverage report is [here](https://coveralls.io/github/bitcoinj-sv/bitcoinj-sv)
