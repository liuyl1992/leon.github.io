---
title: 在vscode下的golang环境搭建记录
tags: [go,vscode,笔记]
image: https://gcdnb.pbrd.co/images/b6QhYJLiKQXN.png
style: fill
color: danger
description: 在vscode下的golang环境搭建记录
---

# 在vscode下的golang环境搭建记录

为了避免每次较长时间后再重新拾起导致重复学习搭建过程，特此记录，并不代表准确性，仅作为个人笔记使用

---

## 下载安装
首先点击链接下载对应平台版本的Golang SDK，并进行安装
[Download](https://golang.google.cn/dl/)


## 配置Go Module的代理地址
开发golang程序的前提条件指定一个可靠安全的模块下载源服务器，
推荐中国最可靠的 Go 模块代理，点击(https://goproxy.cn)[https://goproxy.cn] 了解详情配置

Windows:

打开你的 PowerShell 并执行

```PowerShell
C:\> $env:GO111MODULE = "on"
C:\> $env:GOPROXY = "https://goproxy.cn"
```

## Vscode环境配置


1、在Vscode中进行开发首先需要安装相关Go插件，(Go for Visual Studio Code)[https://marketplace.visualstudio.com/items?itemName=golang.go]
2、Ctrl+Shift+P ,点击Go:Install/Update Tools 后勾选全部选项，安装Go的依赖库，自此支持智能提示与跳转




