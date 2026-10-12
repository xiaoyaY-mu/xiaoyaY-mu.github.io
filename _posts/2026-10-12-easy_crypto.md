---
layout: post
title: "BugKu CTF Writeup-easy_crypto"
date: 2026-10-12
categories: CTF
tags: [BugKu, Crypto]
---

## 题目类型

Crypto

## 解题过程

打开附件，得到一串被空格分隔的`0`和`1`组成的字符串。第一眼容易误以为是二进制编码。
观察格式：每一段长短不一，空格分组，这是摩斯密码特征。
直接使用摩斯密码解码器解密。
再转换大小写。
