---
layout: '../../layouts/Post.astro'
title: git
image: /images/git
publishedAt: "2023-01-07"
category: 'tools'
---

## [`git`](https://git-scm.com)
<blockquote>Git is a free and open source distributed version control system designed to handle everything from small to very large projects with speed and efficiency.</blockquote>

### Install `git`
```bash
brew install git
```

### Upgrade `git`
```bash
brew upgrade git
```

### Install `git-extras`
```bash
brew install git-extras
```

### Upgrade `git-extras`
```bash
brew upgrade git-extras
```

### Check Current Version of `git`
```bash
git -v
```

### Clone a Git Repository
```bash
git clone https://github.com/geofffilippi/first-contributions.git
```

### Show Remotes
```bash
git remote -v
```

### Add an Upstream Remote
```bash
git remote add upstream git@github.com:littlesticks/astro-template-foundation.git
```

### Show Branches
```bash
git branch -a
```

### Create a New Branch
```bash
git checkout -b 1-fix-json5
```

### See Changed Files
```bash
git status
```

### View Differences Between Current Code and Last Commit
```bash
git diff
```

### Add All Changes
```bash
git add .
```

### View Commit History
```bash
git log
```

### Commit Changes
```bash
git commit -m "fixes littlesticks#1 json5 prototype pollution via parse method"
```

### Push Code to Server
```bash
git push
```

### Push the Current Branch and Set the Remote as Upstream
```bash
git push --set-upstream origin 1-fix-json5
```