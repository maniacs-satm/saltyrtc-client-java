# SaltyRTC Java Client

[![Travis](https://img.shields.io/travis/saltyrtc/saltyrtc-client-java/master.svg)](https://travis-ci.org/saltyrtc/saltyrtc-client-java)
[![Java Version](https://img.shields.io/badge/java-7%2B-orange.svg)](https://github.com/saltyrtc/saltyrtc-client-java)
[![License](https://img.shields.io/badge/license-MIT%20%2F%20Apache%202.0-blue.svg)](https://github.com/saltyrtc/saltyrtc-client-java)


This is a [SaltyRTC](https://github.com/saltyrtc/saltyrtc-meta) implementation
for Java 7+.

The development is still ongoing, the current version is only at alpha-level
and should not be used for production yet.

## Installing

The package is available [on Bintray](https://bintray.com/saltyrtc/maven/saltyrtc-client/).

Gradle:

```groovy
compile 'org.saltyrtc.client:saltyrtc-client:0.2.0'
```

Maven:

```xml
<dependency>
  <groupId>org.saltyrtc.client</groupId>
  <artifactId>saltyrtc-client</artifactId>
  <version>0.2.0</version>
  <type>pom</type>
</dependency>
```

## Logging

The library uses the slf4j logging API. Configure a logger (e.g. slf4j-simple)
to see the log output.

## Dependency Verification

This project uses [gradle-witness](https://github.com/WhisperSystems/gradle-witness)
to make sure that you always get the exact same versions of your dependencies.

## Publishing

To publish this library to Bintray:

    export BINTRAY_USER=...
    export BINTRAY_KEY=...
    ./gradlew build publish bintrayUpload

## License

    Copyright (c) 2016 Threema GmbH / SaltyRTC Contributors
    
    Licensed under the Apache License, Version 2.0, <see LICENSE-APACHE file>
    or the MIT license <see LICENSE-MIT file>, at your option. This file may not be
    copied, modified, or distributed except according to those terms.
