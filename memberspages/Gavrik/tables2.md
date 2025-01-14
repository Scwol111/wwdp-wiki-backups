---
title: Tables
description: 
published: false
date: 2024-12-17T18:34:15.669Z
tags: 
editor: markdown
dateCreated: 2024-12-17T18:34:14.834Z
---

## Общий css

```css
.table-with-II-columns,
.table-with-III-columns,
.table-with-IV-columns {
  display: grid;
  margin-top: 2em;
  margin-bottom: 1em;
  border-radius: 5px;
  border: solid #757575 1px;
  overflow: auto
}
.table-title {
  text-align: center;
  justify-content: center;
  padding: 10px 0;
  font-weight: 700;
  border-bottom: solid #757575 2px;
  color: #bbb;
  background-color: #090909
}
.table-item {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 5px 8px;
  border-right: solid #616161 1px;
  border-bottom: solid #424242 1px
}
.table-with-II-columns > .table-item:nth-child(odd),
.table-with-III-columns > .table-item:nth-child(3n+1),
.table-with-IV-columns > .table-item:nth-child(4n+1) {
  background-color: #171717
}
.table-with-II-columns > .table-item:nth-child(odd) > img,
.table-with-III-columns > .table-item:nth-child(3n+1) > img,
.table-with-IV-columns > .table-item:nth-child(4n+1) > img {
  width: 64px;
  filter: drop-shadow(2px 0px 4px #000)
}
.table-with-II-columns > .table-item:nth-child(odd),
.table-with-III-columns > .table-item:nth-child(3n+1),
.table-with-IV-columns > .table-item:nth-child(4n+1) {
  align-items: center;
  text-align: center;
  flex-direction: column;
  font-weight: 700
}
.table-item > p {
  padding: 2px!important
}
@media (orientation:landscape) {
  .table-with-II-columns {
    grid-template-columns: 12em 1fr
  }
  .table-with-III-columns {
    grid-template-columns: 12em 23em 1fr
  }
  .table-with-IV-columns {
    grid-template-columns: 12em 20em 20em 1fr
  }
  .table-with-II-columns,
  .table-with-III-columns {
    width: 95%;
    margin-left: auto;
    margin-right: auto
  }
  .table-with-II-columns > div:nth-last-of-type(-n+3),
  .table-with-III-columns > div:nth-last-of-type(-n+4),
  .table-with-IV-columns > div:nth-last-of-type(-n+5) {
    border-bottom: none
  }
  .table-with-II-columns > .table-item:nth-child(2n+2),
  .table-with-III-columns > .table-item:nth-child(3n+3),
  .table-with-IV-columns > .table-item:nth-child(4n+4) {
    border-right: none
  }
}
@media (orientation:portrait) or (max-width:581px) {
  .table-wirh-II-columns,
  .table-with-III-columns,
  .table-with-IV-columns {
    grid-template-columns: 1fr
  }
  .table-with-II-columns > .table-item:nth-child(2n),
  .table-with-III-columns > .table-item:not(.table-item:nth-child(3n+1)),
  .table-with-IV-columns > .table-item:not(.table-item:nth-child(4n+1)) {
    max-height: 0;
    overflow: hidden;
    padding: 0 8px!important;
    transition: max-height .6s
  }
  .table-with-II-columns > .table-item:not(.table-item.button),
  .table-with-III-columns > .table-item:not(.table-item.button),
  .table-with-IV-columns > .table-item:not(.table-item.button) {
    border-width: 0
  }
  .table-with-II-columns .button,
  .table-with-III-columns .button,
  .table-with-IV-columns .button {
    transition-duration: .3s
  }
  .table-with-II-columns .button:active,
  .table-with-III-columns .button:active,
  .table-with-IV-columns .button:active {
    opacity: .4
  }
}
```

## Таблица с II столбцами
<div class="table-with-II-columns">
    <div class="table-title" id="">Заголовок</div>
    <div class="table-title">Описание</div>
  <!--  -->
  <div class="table-item button">
    <img src="/ghost.png"/>
    Объект
  </div>
  <div class="table-item">
    <p>Какой-то текст</p>
    <p>Какой-то текст</p>
    <p>Какой-то текст</p>
  </div>
  <!--  -->
  <div class="table-item button">
    <img src="/ghost.png"/>
    Объект
  </div>
  <div class="table-item">
    <p>Какой-то текст</p>
    <p>Какой-то текст</p>
    <p>Какой-то текст</p>
  </div>
  <div class="button" style="position:fixed"></div>
</div>

### HTML

```html
<div class="table-with-II-columns">
  <div class="table-title">Заголовок</div>
  <div class="table-title">Заголовок</div>
  <div class="table-item button">
    <img src="/ghost.png"/>
    Объект
  </div>
  <div class="table-item">
		Какой-то текст
  </div>
  <!-- <Обязателен> -->
  <div class="button"></div>
  <!-- </Обязателен> -->
</div>
```

### СSS

```css
.table-with-II-columns {
  display: grid;
  margin-top: 2em;
  margin-bottom: 1em;
  border-radius: 5px;
  border: solid #757575 1px;
  overflow: auto
}
.table-with-II-columns > .table-title {
  text-align: center;
  justify-content: center;
  padding: 10px 0;
  font-weight: 700;
  border-bottom: solid #757575 2px;
  color: #bbb;
  background-color: #090909
}
.table-with-II-columns > .table-item {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 5px 8px;
  border-right: solid #616161 1px;
  border-bottom: solid #424242 1px
}
.table-with-II-columns > .table-item:nth-child(odd) {
  background-color: #171717
}
.table-with-II-columns > .table-item:nth-child(odd) {
  align-items: center;
  text-align: center;
  flex-direction: column;
  font-weight: 700
}
.table-with-II-columns > .table-item > p {
  padding: 2px!important
}
@media (orientation:landscape) {
  .table-with-II-columns {
    grid-template-columns: 12em 1fr
  }
  .table-with-II-columns {
    width: 95%;
    margin-left: auto;
    margin-right: auto
  }
  .table-with-II-columns > div:nth-last-of-type(-n+3) {
    border-bottom: none
  }
  .table-with-II-columns > .table-item:nth-child(2n+2) {
    border-right: none
  }
}
@media (orientation:portrait) or (max-width:581px) {
  .table-wirh-II-columns {
    grid-template-columns: 1fr
  }
  .table-with-II-columns > .table-item:nth-child(2n) {
    max-height: 0;
    overflow: hidden;
    padding: 0 8px;
    transition: max-height .6s .01s
  }
  .table-with-II-columns > .table-item:not(.table-item.button) {
    border-width: 0;
  }
  .table-with-II-columns .button {
    transition-duration: .3s
  }
  .table-with-II-columns .button:active {
    opacity: .4
  }
}
```

## Таблица с III столбцами

<div class="table-with-III-columns med">
  <div class="table-title">Заголовок</div>
  <div class="table-title">Заголовок</div>
  <div class="table-title">Заголовок</div>
  <!--  -->
  <div class="table-item button">
    <img src="/ghost.png"/>
    Объект
  </div>
  <div class="table-item">
    <p>Какой-то текст</p>
    <p>Какой-то текст</p>
    <p>Какой-то текст</p>
  </div>
  <div class="table-item">
    <p>Еще какой-то текст</p>
    <p>Еще какой-то текст</p>
    <p>Еще какой-то текст</p>
  </div>
  <!--  -->
  <div class="table-item button">
    <img src="/ghost.png"/>
    Объект
  </div>
  <div class="table-item">
    <p>Какой-то текст</p>
    <p>Какой-то текст</p>
    <p>Какой-то текст</p>
  </div>
  <div class="table-item">
    <p>Еще какой-то текст</p>
    <p>Еще какой-то текст</p>
    <p>Еще какой-то текст</p>
  </div>
  <div class="button"></div>
</div>

### HTML

```html
<div class="table-with-III-columns">
  <div class="table-title">Заголовок</div>
  <div class="table-title">Заголовок</div>
  <div class="table-title">Заголовок</div>
  <div class="table-item button">
    <img src="/ghost.png"/>
    Объект
  </div>
  <div class="table-item">
		Какой-то текст
  </div>
  <div class="table-item">
    Еще какой-то текст
  </div>
  <!-- <Обязателен> -->
  <div class="button"></div>
  <!-- </Обязателен> -->
</div>
```

### СSS
```css
.table-with-III-columns {
  display: grid;
  margin-top: 2em;
  margin-bottom: 1em;
  border-radius: 5px;
  border: solid #757575 1px;
  overflow: auto
}
.table-with-III-columns > .table-title {
  text-align: center;
  justify-content: center;
  padding: 10px 0;
  font-weight: 700;
  border-bottom: solid #757575 2px;
  color: #bbb;
  background-color: #090909
}
.table-with-III-columns > .table-item {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 5px 8px;
  border-right: solid #616161 1px;
  border-bottom: solid #424242 1px
}
.table-with-III-columns > .table-item:nth-child(3n+1) {
  background-color: #171717
}
.table-with-III-columns > .table-item:nth-child(3n+1) {
  align-items: center;
  text-align: center;
  flex-direction: column;
  font-weight: 700
}
.table-with-III-columns > .table-item > p {
  padding: 2px!important
}
@media (orientation:landscape) {
  .table-with-III-columns {
    grid-template-columns: 12em 23em 1fr
  }
  .table-with-III-columns {
    width: 95%;
    margin-left: auto;
    margin-right: auto
  }
  .table-with-III-columns > div:nth-last-of-type(-n+4) {
    border-bottom: none
  }
  .table-with-III-columns > .table-item:nth-child(3n+3) {
    border-right: none
  }
}
@media (orientation:portrait) or (max-width:581px) {
  .table-with-III-columns {
    grid-template-columns: 1fr
  }
  .table-with-III-columns > .table-item:not(.table-item:nth-child(3n+1))  {
    max-height: 0;
    overflow: hidden;
    padding: 0 8px;
    transition: max-height .6s .01s
  }
  .table-with-III-columns > .table-item:not(.table-item.button) {
    border-width: 0;
  }
  .table-with-III-columns .button {
    transition-duration: .3s
  }
  .table-with-III-columns .button:active{
    opacity: .4
  }
}
```

## Таблица с IV столбцами

<div class="table-with-IV-columns">
  <div class="table-title">Заголовок</div>
  <div class="table-title">Характеристики скафандра</div>
  <div class="table-title">Характеристики шлема</div>
  <div class="table-title">Описание</div>
  <!--  -->
  <div class="table-item button">
    <img src="/ghost.png"/>
    Объект
  </div>
  <div class="table-item">
    <p>Какой-то текст</p>
    <p>Какой-то текст</p>
    <p>Какой-то текст</p>
  </div>
  <div class="table-item">
    <p>Еще какой-то текст</p>
    <p>Еще какой-то текст</p>
    <p>Еще какой-то текст</p>
  </div>
  <div class="table-item">
    <p>И еще какой-то текст</p>
    <p>И еще какой-то текст</p>
    <p>И еще какой-то текст</p>
  </div>
  <!--  -->
  <div class="table-item button">
    <img src="/ghost.png"/>
    Объект
  </div>
  <div class="table-item">
    <p>Какой-то текст</p>
    <p>Какой-то текст</p>
    <p>Какой-то текст</p>
  </div>
  <div class="table-item">
    <p>Еще какой-то текст</p>
    <p>Еще какой-то текст</p>
    <p>Еще какой-то текст</p>
  </div>
  <div class="table-item">
    <p>И еще какой-то текст</p>
    <p>И еще какой-то текст</p>
    <p>И еще какой-то текст</p>
  </div>
  <div class="table-item button"></div>
</div>

### HTML

```html
<div class="table-with-IV-columns">
  <div class="table-title">Заголовок</div>
  <div class="table-title">Заголовок</div>
  <div class="table-title">Заголовок</div>
  <div class="table-title">Заголовок</div>
  <div class="table-item button">
    <img src="/ghost.png"/>
    Объект
  </div>
  <div class="table-item">
    Какой-то текст
  </div>
  <div class="table-item">
    Еще какой-то текст
  </div>
  <div class="table-item">
    И еще какой-то текст
  </div>
  <!-- <Обязателен> -->
  <div class="button"></div>
  <!-- </Обязателен> -->
</div>
```

### СSS

```css
.table-with-IV-columns {
  display: grid;
  margin-top: 2em;
  margin-bottom: 1em;
  border-radius: 5px;
  border: solid #757575 1px;
  overflow: auto
}
.table-with-IV-columns > .table-title {
  text-align: center;
  justify-content: center;
  padding: 10px 0;
  font-weight: 700;
  border-bottom: solid #757575 2px;
  color: #bbb;
  background-color: #090909
}
.table-with-IV-columns > .table-item {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 5px 8px;
  border-right: solid #616161 1px;
  border-bottom: solid #424242 1px
}
.table-with-IV-columns > .table-item:nth-child(4n+1) {
  background-color: #171717
}
.table-with-IV-columns > .table-item:nth-child(4n+1) {
  align-items: center;
  text-align: center;
  flex-direction: column;
  font-weight: 700
}
.table-with-IV-columns > .table-item > p {
  padding: 2px!important
}
@media (orientation:landscape) {

  .table-with-IV-columns {
    grid-template-columns: 12em 20em 20em 1fr
  }
  .table-with-IV-columns {
    width: 100%;
    margin-left: auto;
    margin-right: auto
  }
  .table-with-IV-columns > div:nth-last-of-type(-n+5) {
    border-bottom: none
  }
  .table-with-IV-columns > .table-item:nth-child(4n+4) {
    border-right: none
  }
}
@media (orientation:portrait) or (max-width:581px) {
  .table-with-IV-columns {
    grid-template-columns: 1fr
  }
  .table-with-IV-columns > .table-item:not(.table-item:nth-child(4n+1)) {
    max-height: 0;
    overflow: hidden;
    padding: 0 8px;
    transition: max-height .6s .01s
  }
  .table-with-IV-columns > .table-item:not(.table-item.button) {
    border-width: 0;
  }
  .table-with-IV-columns .button {
    transition-duration: .3s
  }
  .table-with-IV-columns .button:active {
    opacity: .4
  }
}
```



### HTML

```html
<div class="InDevelopment">
  <div>
  	<img src="/guides/64px-wrench_and_crowbar.png"/>
    <p>СТАТЬЯ НАХОДИТСЯ В РАЗРАБОТКЕ</p>
    <img src="/guides/64px-wrench_and_crowbar.png"/>
  </div>
  <div>
    <ul>
      <li>Редакторы вики уже ведут работу над данной статьёй.</li>
      <li>Данный этап: <span style="color:#94322D;">Начинающий</span>.</li>
    </ul>
  </div>
</div>
```



