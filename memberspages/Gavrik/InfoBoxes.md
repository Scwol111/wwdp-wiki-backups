---
title: InfoBoxes
description: 
published: true
date: 2024-11-26T14:57:12.326Z
tags: 
editor: markdown
dateCreated: 2024-11-25T17:19:16.041Z
---

# InfoBoxes

## Пример

ID_ОБЪЕКТА - это айди узла, который можно быстро узнать при помощи сканера узлов. Если печатать отчеты после сканирования, то можно проводить быстрый анализ, сверяя айди, полученный от сканера и айди в отчете.
ID_ОБЪЕКТА - это айди узла, который можно быстро узнать при помощи сканера узлов. Если печатать отчеты после сканирования, то можно проводить быстрый анализ, сверяя айди, полученный от сканера и айди в отчете.
{.infobox}

текст
{.infobox .success-custom}

текст
{.infobox .warning-custom}

текст
{.infobox .danger-custom}

## html

### Info

```html
текст
{.infobox}
```

### Success

```html
текст
{.infobox .success-custom}
```

### Warning

```html
текст
{.infobox .warning-custom}
```

### Danger

```html
текст
{.infobox .danger-custom}
```
## css

```css
.infobox {
  border-radius: 3px;
  border-left: solid 3px #607D8B;
	padding: 10px!important;
  margin-bottom: 1em!important;
  box-shadow: 0 3px 1px -2px rgba(0,0,0,.2),0 2px 2px 0 rgba(0,0,0,.14),0 1px 5px 0 rgba(0,0,0,.12);
  background-color: #252525;
}
.warning-custom { 
  border-left-color: #CB7B05;
}
.success-custom { 
  border-left-color: #4CAF50;
}
.danger-custom { 
  border-left-color: #F44336;
}
```