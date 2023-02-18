---
layout: '../../layouts/Post.astro'
title: tcpdump
image: /images/tcpdump
publishedAt: "2023-02-17"
category: 'tools'
---

## [`tcpdump`](https://www.tcpdump.org)

> a powerful command-line packet analyzer

### Monitor DNS traffic

```bash
tcpdump -i en0 udp port 53
```