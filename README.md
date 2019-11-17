# Kotio trigger

Automation of turning devices on or off based on given input e.g. sensor data.

## Requirements

* Java 8
  * SBT doesn't work with newer versions of Java
  * see [AdoptOpenJDK](https://adoptopenjdk.net/installation.html) for details how install

## SBT and Eclipse/Scala IDE

Generate Eclipse project definitions with [sbteclipse plugin](https://github.com/sbt/sbteclipse).

## SBT and Intellij IDEA

Import the project.

## SBT and Java 8 is not the default Java

Run sbt with `-java-home` parameter e.g. `./sbt eclipse -java-home /usr/lib/jvm/adoptopenjdk-8-hotspot-amd64/`


