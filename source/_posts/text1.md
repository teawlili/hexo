---
title: text1
author: lili
comments: true
copyright: true
cover: /gallery/covers/cover.jpg
thumbnail: /gallery/thumbnails/thumbnail.jpg
date: 2022-03-31 10:00:49
dateed: 2022-03-31 10:00:49
tags:
 - test
categories: hexo
permalink:
---

{% note default %}
default 提示块标签
{% endnote %}

{% note primary %}
primary 提示块标签
{% endnote %}

{% note success %}
success 提示块标签
{% endnote %}

<!-- more -->

{% note info %}
info 提示块标签
{% endnote %}

{% note warning %}
warning 提示块标签
{% endnote %}

{% note danger %}
danger 提示块标签
{% endnote %}


{% tabs mytab,2 %} 將 tab 取名為 mytab，預設會選取第二個頁籤，使用 -1 會不選取
<!-- tab -->
### 頁籤一

因沒有特別命名，所以此頁籤會用 `mytab` 加上流水號。
<!-- endtab -->
<!-- tab -->
### 頁籤二

開無痕進來會先看到我。
<!-- endtab -->
<!-- tab 這是頁籤三 -->
### 頁籤三

這裡有命名，會看到頁籤名不一樣。
<!-- endtab -->
<!-- tab -->
### 頁籤四

可以看到這裡的流水號是從 4 開始，應該是抓 array index 作為流水號。
<!-- endtab -->
<!-- tab 個人資料 @user -->
### 頁籤五

這裡有加 icon，有什麼 icon 可以來[這裡](https://fontawesome.com/icons)找。
<!-- endtab -->
{% endtabs %}


<font color=#FF00FF>粉紅色</font>

| 預設對齊 | 靠左對齊 | 靠右對齊 | 置中對齊 |
| ----- | :----- | -----: | :-----: |
| Text1 | Text2 | Text3 | Text4 |
| Text5 | Text6 | Text7 | Text8 |
| Text9 | Text10 | Text11 | Text12 |
 

<img src="https://i.imgur.com/0fmKhRP.png?1" width="100" height="100"> 