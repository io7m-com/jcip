jcip
===

[![Maven Central](https://img.shields.io/maven-central/v/com.io7m.jcip/com.io7m.jcip.svg?style=flat-square)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22com.io7m.jcip%22)
[![Maven Central (snapshot)](https://img.shields.io/nexus/s/com.io7m.jcip/com.io7m.jcip?server=https%3A%2F%2Fs01.oss.sonatype.org&style=flat-square)](https://s01.oss.sonatype.org/content/repositories/snapshots/com/io7m/jcip/)
[![Codecov](https://img.shields.io/codecov/c/github/io7m-com/jcip.svg?style=flat-square)](https://codecov.io/gh/io7m-com/jcip)
![Java Version](https://img.shields.io/badge/17-java?label=java&color=e65cc3)

![com.io7m.jcip](./src/site/resources/jcip.jpg?raw=true)

| JVM | Platform | Status |
|-----|----------|--------|
| OpenJDK (Temurin) Current | Linux | [![Build (OpenJDK (Temurin) Current, Linux)](https://img.shields.io/github/actions/workflow/status/io7m-com/jcip/main.linux.temurin.current.yml)](https://www.github.com/io7m-com/jcip/actions?query=workflow%3Amain.linux.temurin.current)|
| OpenJDK (Temurin) LTS | Linux | [![Build (OpenJDK (Temurin) LTS, Linux)](https://img.shields.io/github/actions/workflow/status/io7m-com/jcip/main.linux.temurin.lts.yml)](https://www.github.com/io7m-com/jcip/actions?query=workflow%3Amain.linux.temurin.lts)|
| OpenJDK (Temurin) Current | Windows | [![Build (OpenJDK (Temurin) Current, Windows)](https://img.shields.io/github/actions/workflow/status/io7m-com/jcip/main.windows.temurin.current.yml)](https://www.github.com/io7m-com/jcip/actions?query=workflow%3Amain.windows.temurin.current)|
| OpenJDK (Temurin) LTS | Windows | [![Build (OpenJDK (Temurin) LTS, Windows)](https://img.shields.io/github/actions/workflow/status/io7m-com/jcip/main.windows.temurin.lts.yml)](https://www.github.com/io7m-com/jcip/actions?query=workflow%3Amain.windows.temurin.lts)|

## jcip

A clean room implementation of the [JCIP Annotations](https://jcip.net/) based entirely on the specification provided by the javadocs.

## Features

* Supported by most good IDEs; get real-time warnings about issues such as
  failing to acquire a lock before a guarded object is used.
* [OSGi-ready](https://www.osgi.org/)
* [JPMS-ready](https://en.wikipedia.org/wiki/Java_Platform_Module_System)
* Apache 2.0 / ISC license.

## Usage

See the [JCIP Javadoc](https://jcip.net/annotations/doc/index.html).

