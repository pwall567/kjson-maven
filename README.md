# kjson-maven

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Kotlin](https://img.shields.io/static/v1?label=Kotlin&message=v1.7.21&color=7f52ff&logo=kotlin&logoColor=7f52ff)](https://github.com/JetBrains/kotlin/releases/tag/v1.7.21)

Maven parent POM for kjson projects

Includes plugin definitions for deployment to Sonatype OSSRH.

The current version is 3.1 - this version uses Kotlin 1.7.21, and the default Java version is 1.8.

## Usage

```xml
  <parent>
    <groupId>io.kjson</groupId>
    <artifactId>kjson-maven</artifactId>
    <version>3.1</version>
  </parent>
```

Peter Wall

2023-06-08
