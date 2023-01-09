---
layout: '../../layouts/Post.astro'
title: sdkman
image: /images/sdkman
publishedAt: "2023-01-05"
category: 'tools'
---

## [`sdkman`](https://sdkman.io)

> SDKMAN! is a tool for managing parallel versions of multiple Software Development Kits on most Unix based systems. It provides a convenient Command Line Interface (CLI) and API for installing, switching, removing and listing Candidates. Formerly known as GVM the Groovy enVironment Manager, it was inspired by the very useful RVM and rbenv tools, used at large by the Ruby community.

### Install SDKMAN
```bash
$ curl -s "https://get.sdkman.io" | bash
```

### Update SDKMAN

```bash
$ sdk selfupdate force
```

### Check Version
```bash
$ sdk version

==== BROADCAST =================================================================
* 2023-01-04: quarkus 2.15.2.Final available on SDKMAN! https://github.com/quarkusio/quarkus/releases/tag/2.15.2.Final
* 2022-12-29: gradle 8.0-rc-1 available on SDKMAN!
* 2022-12-29: kotlin 1.8.0 available on SDKMAN! https://github.com/JetBrains/kotlin/releases/v1.8.0
================================================================================

SDKMAN 5.16.0
```

### Update Installed Runtimes
```bash
$ sdk update

No new candidates found at this time.
```

### Show Runtimes Currently In Use
```bash
$ sdk current

Using:

java: 19.0.1-tem
springboot: 3.0.1sdk install java

```

### List All Available Runtimes
```bash
$ sdk list
$ sdk ls
```

### List Java Runtimes
```bash
$ sdk list java
```

### Install Specific Java Version
```bash
$ sdk install java 19.0.1-tem
```