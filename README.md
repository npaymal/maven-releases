maven-releases
==============

This repository contains versions for Android libraries using Maven.

# How to Include In Project

```groovy

subprojects {
  repositories {
        maven { url "https://raw.github.com/Raizlabs/maven-releases/master/releases" }
  }
}

```

Reference the repository from this location using:

```groovy

dependencies {
  compile "com.raizlabs.android:{libraryname}:{version}"
}


```
