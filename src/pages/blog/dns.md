---
layout: '../../layouts/Post.astro'
title: dns
image: /images/dns
publishedAt: "2023-02-10"
category: 'tools'
---

## [`dns`](https://en.wikipedia.org/wiki/Domain_Name_System)
<blockquote>The Domain Name System (DNS) is a hierarchical and distributed naming system for computers, services, and other resources in the Internet or other Internet Protocol (IP) networks. It associates various information with domain names assigned to each of the associated entities.</blockquote>

### `nslookup` 
Non-interactive
```bash
nslookup google.com
```

Interactive mode
```bash
nslookup
> google.com
Server:		2001:558:feed::1
Address:	2001:558:feed::1#53

Non-authoritative answer:
Name:	google.com
Address: 142.250.69.238
> exit
```

### Monitor DNS traffic with `tcpdump`

```bash
tcpdump -i en0 udp port 53
```
