---
layout: '../../layouts/Post.astro'
title: nvm
image: /images/nvm
publishedAt: "2023-01-06"
category: 'tools'
---

## [`nvm`](https://github.com/nvm-sh/nvm)
> nvm allows you to quickly install and use different versions of node via the command line.

### Install `nvm`
```bash
$ curl -o- https://raw.githubusercontent.com/nvm-sh/nvm/v0.39.3/install.sh | bash
```

### Set Environment
```bash
$ export NVM_DIR="$HOME/.nvm"
$ [ -s "$NVM_DIR/nvm.sh" ] && \. "$NVM_DIR/nvm.sh"  # This loads nvm
$ [ -s "$NVM_DIR/bash_completion" ] && \. "$NVM_DIR/bash_completion"  # This loads nvm bash_completion
```
### Check Current Version of `nvm`
```bash
nvm --version
```

### Show Local `node` Versions
```bash
nvm ls
```

### Show All Available `node` Versions
```bash
nvm ls-remote
```

### Install Specific `node` Versions
```bash
nvm install v18.12.1
nvm install v19.3.0
```

### Switch to a Specific `node` Version
```bash
nvm use v19.3.0
```

### Set Default `node` Version
```bash
nvm alias default v19.3.0
```