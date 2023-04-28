---
layout: '../../layouts/Post.astro'
title: Metasploit Framework
image: /images/metasploit
publishedAt: "2023-04-26"
category: 'Tools'
---

## [`Metasploit Framework`](https://docs.rapid7.com/metasploit/msf-overview/)

> The Metasploit Framework is a Ruby-based, modular penetration testing platform that enables you to write, test, and execute exploit code.

### Run with Docker
#### [Pull Docker Image](https://hub.docker.com/r/metasploitframework/metasploit-framework/)

```bash
docker pull metasploitframework/metasploit-framework
```

#### Open a Shell

```
docker run -it d45cf5ec473b /bin/bash
```

### Run `msfconsole`

```
./msfconsole
```

### [`help`](https://www.stationx.net/metasploit-commands/)

```bash
help
```

```bash
?
```

### List Exploits

```
show exploits
```