---
title: InfoBoxes
description: 
published: true
date: 2024-11-27T15:57:00.025Z
tags: 
editor: markdown
dateCreated: 2024-11-25T17:19:16.041Z
---

# InfoBoxes

## html

### Info

Тут должно быть очень много текста, но мне лень
Можете сами придумать, если вам не лень. Такие вот дела.
{.infobox}

```html
текст
{.infobox}
```

### Info with img

<div class="infobox">
  <img src="/" width="64px" height="64px"/>
  <p>текст</p>
</div>

```html
<div class="infobox">
  <img src="/" width="64px" height="64px"/>
  <p>текст</p>
</div>
```



### Success

текст
{.infobox .success-custom}

```html
текст
{.infobox .success-custom}
```

### Warning

текст
{.infobox .warning-custom}

```html
текст
{.infobox .warning-custom}
```

### Danger

текст
{.infobox .danger-custom}

```html
текст
{.infobox .danger-custom}
```
## css

```css
.infobox {
  display: flex;
  align-items: center;
  padding: 10px 20px!important;
  margin-top: 1em!important;
  border-radius: 3px;
  border-left: solid 3px #607d8b;
  background-color: #252525;
  box-shadow: 0 3px 1px -2px rgba(0,0,0,.2),0 2px 2px 0 rgba(0,0,0,.14),0 1px 5px 0 rgba(0,0,0,.12)
}
.infobox > img {
  float: left;
  margin-right: 20px
}
.infobox > br {
  margin-bottom: .5em
}
.infobox > p {
 	padding: 0!important 
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