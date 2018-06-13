---
title: initMusicApi
date: 2018-06-04 11:22:18
tags: github 网易云音乐API NodeJS
---

# 初始化配置网易云音乐API

### git ssh key 配置
设置git的user name和email：

    $ git config --global user.name "Hertz"
    $ git config --global user.email "1364936400@qq.com"

生成密钥：

    $ ssh-keygen -t rsa -C "1364936400@qq.com"

此时会在系统用户文件夹下创建.ssh的文件夹，其中有id_rsa私钥和id_rsa.pub公钥