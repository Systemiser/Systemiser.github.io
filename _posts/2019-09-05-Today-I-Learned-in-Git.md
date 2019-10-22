---
layout: post
title: Today I learned in Git
categories: webdev
tags: git,linux,shell,terminal
---
![Git image](https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fcdn.arstechnica.net%2Fwp-content%2Fuploads%2F2017%2F02%2Fgit-branching.png&f=1&nofb=1 "Git branching")

### Storing git username and password for pushing without entering username and password 

In any directory (non .git)

`$ git config --global credential.helper cache`

In a repository (To enable for this repository)

`$ git config credential.helper cache`

Then

`$ git push`

Enter username and password and after that, all pushes will not require you to enter your password.

### Github SSH Keys
