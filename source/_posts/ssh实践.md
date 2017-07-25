---
title: ssh实践
date: 2017-07-22 03:50:31
tags:
categories:
---

## Server

http://www.jianshu.com/p/33461b619d53

```
$ ssh-keygen -t rsa -P '' -f ~/.ssh/id_rsa
$ cat ~/.ssh/id_rsa.pub >> ~/.ssh/authorized_keys
$ chmod 0600 ~/.ssh/authorized_keys
```

## Client

https://my.oschina.net/zetaplusae/blog/141376

```
$ ssh-keygen -t rsa
$ ssh-copy-id -i ~/.ssh/id_rsa.pub root@192.168.1.1
$ ssh root@192.168.1.1
```