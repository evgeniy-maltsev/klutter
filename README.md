[![Kotlin M12](https://img.shields.io/badge/Kotlin-M12%20%40%200.12.1230-blue.svg)](http://kotlinlang.org) [![Maven Version](https://img.shields.io/maven-central/v/uy.klutter/klutter-core.svg)](http://search.maven.org/#search%7Cga%7C1%7Cg%3A%22uy.klutter%22) [![CircleCI branch](https://img.shields.io/circleci/project/klutter/klutter/master.svg)](https://circleci.com/gh/klutter/klutter/tree/master) [![Issues](https://img.shields.io/github/issues/klutter/klutter.svg)](https://github.com/klutter/klutter/issues?q=is%3Aopen) [![DUB](https://img.shields.io/dub/l/vibe-d.svg)](https://github.com/klutter/klutter/blob/master/LICENSE) 

# klutter
Random small libraries, usually extensions making other libraries happier.  

Please send contributions, fork the repo, issue a pull request and write a comment in the pull request granting the rights for the code to be used in Klutter.

## Maven Dependnecy

Each module has its own dependency.  And for any module, note if it has a version specific to your JDK version (use highest at or below), then include the dependency in your Gradle / Maven projects, ones that have Kotlin configured for Kotlin M12 versions `0.12.1218` or `0.12.1230`  For example, for the whole package (one of `klutter-all`, `klutter-all-jdk7`, or `klutter-all-jdk8`) using open dependency number while we are in development:

**Gradle:**
```
compile "uy.klutter:klutter-all:0.+"
```

**Maven:**
```
<dependency>
    <groupId>uy.klutter</groupId>
    <artifactId>klutter-all</artifactId>
    <version>[0.1.0,1.0.0)</version>
</dependency>
```

## Modules

|&nbsp;&nbsp;&nbsp;Maven&#8209;Artifact&nbsp;&nbsp;&nbsp;|Injektable|Size|Topic|
|------|------|------|------|
|aws-s3|Yes|tiny|Amazon AWS SDK S3 helper extensions|
|aws|No|tiny|Amazon AWS SDK helper extensions|
|config-typesafe-jdk7|No|medium|Typesafe Config easier loader and access to configuration|
|config-typesafe-jdk8|No|medium|Same as above, but with newer version of Typesafe Config that is JDK 8 only|
|core|No|small|Core extension methods on strings, numbers, dates, URI Builder, better URL Encoding/Decoding|
|core-JDK-7|No|tiny|Same as above with more extensions based on classes added in JDK-7, includes core|
|core-JDK-8|No|tiny|Same as above with more extensions based on classes added in JDK-8, includes core-JDK-7 & core|
|core-jodatime|No|tiny|Joda time extension methods, includes core|
|json-jackson|Yes|tiny|Jackson JSON Data Binding extensions + loading of Kotlin module|
|json-jackson-jdk8|Yes|tiny|Same as above + loading of JDK 8 datatypes, JDK 8 date/time, and JDK 8 parameter names modules|
|netflix-graph|No|medium|In memory graph building and compression/serialization.  A wrapper adding schema, ordinal tracking, serialization with ordinals, and is much easier to use API|

Injektable modules have intergration with [Kohesive/Injekt](http://github.com/kohesive/injekt) and provide prebuild injectable modules that you can easily import providing factories or singletons for dependency injection.
