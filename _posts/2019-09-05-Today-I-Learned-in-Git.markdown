---
layout: post
title: "Today I learned in Git"
categories: [webdev]
tags: [git,linux,shell,terminal]
---
##Storing git username and password for pushing without entering username and password 

In any directory (non .git)

`$ git config --global credential.helper cache`

In a repository (To enable for this repository)

`$ git config credential.helper cache`

Then

`$ git push`

Enter username and password and after that, all pushes will not require you to enter your password.

Github SSH Keys
