---
title: Как да качвам снимки?
description: Транспорт инфраструктура и мобилност
published: true
date: 2023-01-08T08:21:38.522Z
tags: 
editor: markdown
dateCreated: 2023-01-07T21:15:10.763Z
---

## 1. Права
Трябва да имаш права да редактираш (Ако искаш да качваш пиши на trinmobg@gmail.com)


## 2. Избор на страница
Избираш страницата която искаш да редактираш, като има два вида страници: 
- линии на градския транспорт
- модели превозни средства

> При линиите снимките се добавят по модели. 
> При моделите снимките се добавят по линии.
{.is-info}


## 3. Генериране на линк
Ако снимката не е от фликр се слага директен линк към нея. 

Ако снимката е от фликр, то линковете се генерират от самия фликр. При избор за споделяне се избира опцията embed. 

Ето примерн линк който излиза от фликр.
`<a data-flickr-embed="true" href="https://www.flickr.com/photos/196876073@N04/52480112812" title="IMG_2325"><img src="https://live.staticflickr.com/65535/52480112812_feee63d2c2_k.jpg" width="2048" height="1365" alt="IMG_2325"></a><script async src="//embedr.flickr.com/assets/client-code.js" charset="utf-8"></script>`

От този линк се изполват само два:
- (**линк 1**) https://www.flickr.com/photos/196876073@N04/52480112812
- (**линк 2**) https://live.staticflickr.com/65535/52480112812_feee63d2c2_k.jpg
Първият е директната връзка към фликр, втория е директната връзка към самата снимка. 

Това е готовият линк който само се копи пейства и слага в страницата. 

`<div class="dropdown"><button class="imgbtn">
  <img src="(линк 2 се пейства тук)" height="200px"></button><div class="dropdown-content">
  <a href="(линк 1 се пейства тук)" target="_blank" title="Примерно линия и автор или модел и автор зв зависимост от страницата">
 <img src="(линк 2 се пейства тук)" width="100%"></a></div></div>`

## Резулатат

<div class="dropdown"><button class="imgbtn">
  <img src="https://live.staticflickr.com/65535/52480112812_feee63d2c2_k.jpg" height="200px"></button><div class="dropdown-content">
  <a href="https://www.flickr.com/photos/196876073@N04/52480112812" target="_blank" title="1761 - Александър Бахчевански">
 <img src="https://live.staticflickr.com/65535/52480112812_feee63d2c2_k.jpg" width="100%"></a></div></div>
