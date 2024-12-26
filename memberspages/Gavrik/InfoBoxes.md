---
title: InfoBoxes
description: 
published: true
date: 2024-12-26T20:33:20.534Z
tags: 
editor: markdown
dateCreated: 2024-11-25T17:19:16.041Z
---

# InfoBoxes

## html

### Info

Тут должно быть очень много текста, чтобы показать интервалы между строками, но мне лень
Можете сами придумать, если вам не лень. Такие вот дела.
{.infobox}

```html
текст
текст
{.infobox}
```

### Info with img

<div class="infobox">
  <img src="/" width="64px" height="64px"/>
  <div>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
    <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
  </div>
</div>

```html
<div class="infobox">
  <img src="/" width="64px" height="64px"/>
  <div>
    <p>текст</p>
    <p>текст</p>
  </div>
</div>
```

<div class="infobox">
  <img src="/" width="64px" height="64px"/>
  <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.</p>
</div>

```html
<div class="infobox">
  <img src="/" width="64px" height="64px"/>
  <p>текст</p>
</div>
```

### Success

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
{.infobox .success-custom}

```html
текст
{.infobox .success-custom}
```

### Warning

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
{.infobox .warning-custom}

```html
текст
{.infobox .warning-custom}
```

### Danger

Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et dolore magna aliqua. Ut enim ad minim veniam, quis nostrud exercitation ullamco laboris nisi ut aliquip ex ea commodo consequat. Duis aute irure dolor in reprehenderit in voluptate velit esse cillum dolore eu fugiat nulla pariatur.
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
  gap: 20px;
  padding: 10px 20px!important;
  margin-top: 1em!important;
  border-radius: 3px;
  border-left: solid 3px #607d8b;
  background-color: #252525;
  box-shadow: 0 3px 1px -2px rgba(0,0,0,.2),0 2px 2px 0 rgba(0,0,0,.14),0 1px 5px 0 rgba(0,0,0,.12)
}
.infobox p {
  padding: 0!important
}
.infobox > br {
  margin-bottom: .5em
}
.infobox > div {
  display: flex;
  flex-flow: column;
  gap: .5em
}
.warning-custom {
  border-left-color: #cb7b05
}
.success-custom {
  border-left-color: #4caf50
}
.danger-custom {
  border-left-color: #f44336
}
```