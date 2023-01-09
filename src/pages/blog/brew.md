---
layout: '../../layouts/Post.astro'
title: brew
image: /images/brew
publishedAt: "2023-01-07"
category: 'tools'
---

## [`brew`](https://brew.sh)
<blockquote>The Missing Package Manager for macOS (or Linux)</blockquote>

### Install the Latest Version of `brew`
```bash
/bin/bash -c "$(curl -fsSL https://raw.githubusercontent.com/Homebrew/install/HEAD/install.sh)"
```

### [Install the Latest Version of `brew` into `home`](https://docs.brew.sh/Installation)
```bash
git clone https://github.com/Homebrew/brew ~
```

### Update `brew` Itself
```bash
brew update
```

### Show Outdated Formulae
```bash
brew outdated
```

### Upgrade Specific Formula
```bash
brew upgrade awscli
```

### Upgrade All Outdated Formulae
```bash
brew upgrade
```