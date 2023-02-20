---
layout: '../../layouts/Post.astro'
title: npm
image: /images/npm
publishedAt: "2023-01-06"
category: 'Tools'
---

## [`npm`](https://docs.npmjs.com/downloading-and-installing-node-js-and-npm)
> Package manager for Node.js

### Install the Latest Version of `npm`
```bash
npm install -g npm
npm i -g npm
```

### Check Current Version of `npm`
```bash
npm --v
```

### Check for Security Vulnerabilities
```bash
npm audit
```

### [`package-lock.json`](https://docs.npmjs.com/cli/v9/configuring-npm/package-lock-json)

<blockquote>package-lock.json is automatically generated for any operations where npm modifies either the node_modules tree, or package.json. It describes the exact tree that was generated, such that subsequent installs are able to generate identical trees, regardless of intermediate dependency updates.

This file is intended to be committed into source repositories...
</blockquote>
