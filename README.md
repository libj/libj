# LibJ

[![Build Status](https://github.com/libj/libj/actions/workflows/build.yml/badge.svg)](https://github.com/libj/libj/actions/workflows/build.yml)
[![Coverage Status](https://coveralls.io/repos/github/libj/libj/badge.svg)](https://coveralls.io/github/libj/libj)
[![Javadocs](https://www.javadoc.io/badge/org.libj/libj.svg)](https://www.javadoc.io/doc/org.libj/libj)
[![Released Version](https://img.shields.io/maven-central/v/org.libj/libj.svg)](https://mvnrepository.com/artifact/org.libj/libj)
![Snapshot Version](https://img.shields.io/nexus/s/org.libj/libj?label=maven-snapshot&server=https%3A%2F%2Foss.sonatype.org)

LibJ is a collection of simple, convenient, and high-performance supplements to Java Standard libraries

## Simple

The supplementary APIs are designed to be simple, and as non-coupling as possible.

## High-Performance

The APIs are implemented to minimize both process and memory complexity.

## Modules

* **[exec][exec]**: APIs for external process execution and environment management.
* **[io][io]**: APIs that supplement the `java.io` and `java.nio` packages for I/O operations.
* **[jci][jci]**: _Java Compiler Interface_ An implementation of an in-memory-compiler.
* **[lang][lang]**: APIs that supplement the `java.lang` package with simple and useful extensions.
* **[logging][logging]**: APIs that provide simple _logging_ extensions to [SLF4J][slf4j].
* **[mail][mail]**: APIs that supplement the `java.mail` package with simple and useful extensions.
* **[math][math]**: APIs that supplement the `java.math` package with higher-performance alternatives, and simple and useful extensions.
* **[net][net]**: APIs that supplement the `java.net` package with higher-performance alternatives, and simple and useful extensions.
* **[sql][sql]**: APIs that supplement the `java.sql` package with simple and useful extensions.
* **[test][test]**: APIs that provide simple _test_ extensions to [JUnit][junit], and Maven's [maven-surefire-plugin][maven-surefire-plugin].
* **[util][util]**: APIs that supplement the `java.util` package with higher-performance alternatives, and simple and useful extensions.

### License

This project is licensed under the MIT License - see the [LICENSE.txt](LICENSE.txt) file for details.

[exec]: /../../../../libj/exec
[io]: /../../../../libj/io
[jci]: /../../../../libj/jci
[lang]: /../../../../libj/lang
[logging]: /../../../../libj/logging
[mail]: /../../../../libj/mail
[math]: /../../../../libj/math
[net]: /../../../../libj/net
[sql]: /../../../../libj/sql
[test]: /../../../../libj/test
[util]: /../../../../libj/util

[junit]: https://junit.org
[maven-surefire-plugin]: https://maven.apache.org/surefire/maven-surefire-plugin/
[slf4j]: https://www.slf4j.org/