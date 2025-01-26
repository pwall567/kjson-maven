# kjson-maven

[![Build Status](https://github.com/pwall567/kjson-maven/actions/workflows/deploy.yml/badge.svg)](https://github.com/pwall567/kjson-maven/actions/workflows/deploy.yml)
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Kotlin](https://img.shields.io/static/v1?label=Kotlin&message=v2.0.21&color=7f52ff&logo=kotlin&logoColor=7f52ff)](https://github.com/JetBrains/kotlin/releases/tag/v2.0.21)
[![Maven Central](https://img.shields.io/maven-central/v/io.kjson/kjson-maven?label=Maven%20Central)](https://search.maven.org/search?q=g:%22io.kjson%22%20AND%20a:%22kjson-maven%22)

Maven parent POM for kjson projects

Includes plugin definitions for deployment to Sonatype OSSRH.

The current version is 6.0 &ndash; this version uses Kotlin 2.0.21, and the default Java version is 1.8.

## Usage

```xml
  <parent>
    <groupId>io.kjson</groupId>
    <artifactId>kjson-maven</artifactId>
    <version>6.0</version>
  </parent>
```

Peter Wall

2024-01-26
