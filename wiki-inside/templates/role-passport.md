---
title: Шаблон паспорта роли
description: 
published: false
date: 2025-03-21T21:32:25.443Z
tags: 
editor: markdown
dateCreated: 2024-09-26T19:21:17.004Z
---

<div style="display: flex; justify-content: center;">
  <div class="roles-passport comm">
    <div class="title comm">
      <a href="/roles/command">Командование</a>
    </div>
    <div><div><div><img src="/roles/captain.png"></div></div><div><div>
      <h1>Капитан</h1>
        <p><strong>Сложность:</strong> Сложная</p>
        <strong>Обязанности:</strong> Глава объекта. Занимается руководством всей станции.
      <br>
        <b>Руководители</b>: <a href="/roles/centralcommand">ЦентКом</a>
      <br>
        <b>Руководства</b>: <a href="/guides/hierarchyofcommand">Иерархия Командования</a> • <a href="/guides/especiallyvaluableitems">Особо ценные предметы</a>
</div></div></div></div></div>

Для редактирования паспорта на разные отделы необходимо в
`<div class="roles-passport COMM"> <div class="title COMM"` Поменять COMM на необходимый отдел. (есть в css).

HTML
```html
<div style="display: flex; justify-content: center;">
  <div class="roles-passport comm">
    <div class="title comm">
      <a href="/roles/command">Командование</a>
    </div>
    <div><div><div><img src="/roles/captain.png"></div></div><div><div>
      <h1>Капитан</h1>
        <p><strong>Сложность:</strong> Сложная</p>
        <strong>Обязанности:</strong> Глава объекта. Занимается руководством всей станции.
      <br>
        <b>Руководители</b>: <a href="/roles/centralcommand">ЦентКом</a>
      <br>
        <b>Руководства</b>: <a href="/guides/hierarchyofcommand">Иерархия Командования</a> • <a href="/guides/especiallyvaluableitems">Особо ценные предметы</a>
</div></div></div></div></div>
```

CSS
```css
.roles-passport {
  display: flex;
  flex-direction: column;
  justify-content: center;
  padding: 0!important;
  margin: 16px auto 0 auto;
  border-radius: 16px;
  max-width: 80%
}
.roles-passport div {
  background-color: #292929
}
.roles-passport h1 {
  margin: 0!important;
  text-align: center;
  font-size: 1.4em;
  width: 100%
}
.roles-passport h1:after {
  background: #aaa!important
}
.roles-passport a {
  text-decoration: none
}
.roles-passport > div:nth-child(2) {
  display: flex;
  justify-content: flex-start;
  align-items: center;
  flex-direction: row;
  width: 100%;
  border-radius: 0 0 16px 16px
}
.roles-passport > div:nth-child(2) > div:first-child {
  border-radius: 0 0 0 16px;
  display: flex;
  align-self: stretch;
  justify-content: center;
  border-right: 1px solid grey;
  width: 224px;
  flex: 0 0 224px;
  padding: 0 16px
}
.roles-passport > div:nth-child(2) > div:first-child > div {
  display: flex;
  justify-content: center;
  align-items: center
}
.roles-passport > div:nth-child(2) > div:nth-child(2) {
  display: flex;
  justify-content: flex-start;
  align-self: center;
  padding: 16px;
  border-radius: 0 0 16px 0;
  flex: 1 0 0
}
.roles-passport > div:nth-child(2) > div:nth-child(2) > div {
  width: 100%
}
.roles-passport img {
  width: 192px;
  margin: 8px 0 8px 0
}
.roles-passport .title {
  text-align: center;
  border-radius: 16px 16px 0 0;
  flex: 0 2 0;
  box-shadow: 0 0 16px 4px rgba(0,0,0,0.7) inset;
}
.roles-passport .title a {
  color: #fff!important;
  width: 100%;
  display: inline-block;
  padding: 8px 0 8px 0;
  text-shadow: 1px 0 1px #000,0 1px 1px #000,-1px 0 1px #000,0 -1px 1px #000;
  border-radius: 16px 16px 0 0
}
.roles-passport .title a:hover {
  background-color: rgba(0,0,0,.2);
  box-shadow: 0 0 16px rgba(0,0,0,.2)
}
@media (orientation:portrait) {
  .roles-passport {
    width: 100%!important;
    max-width: 100%!important
  }
  .roles-passport div {
    width: 100%!important
  }
  .roles-passport > div:nth-child(2) {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    width: 100%
  }
  .roles-passport > div:nth-child(2) {
    display: flex;
    justify-content: center;
    align-items: center;
    flex-direction: column;
    width: 100%
  }
  .roles-passport > div:nth-child(2) > div:first-child {
    border-radius: 0 0 0 4px;
    display: flex;
    align-items: center;
    justify-content: center;
    border-right: 0;
    border-bottom: 1px solid grey;
    width: 208px;
    flex: 0 1 auto;
    width: 100%
  }
  .roles-passport > div:nth-child(2) > div:nth-child(2) {
    display: flex;
    justify-content: flex-start;
    padding: 16px;
    border-radius: 0 0 4px 4px;
    flex: 0 1 auto;
    width: 100%
  }
}
.comm {
  border: 2px solid #465298;
  background: repeating-linear-gradient(45deg,#606dbc,#606dbc 10px,#465298 10px,#465298 20px)
}
.sb {
  border: 2px solid #700000;
  background: repeating-linear-gradient(45deg,#8b0000,#8b0000 10px,#700000 10px,#700000 20px)!important
}
.med {
  border: 2px solid #304e8a;
  background: repeating-linear-gradient(45deg,#3c7dc7,#3c7dc7 10px,#304e8a 10px,#304e8a 20px)!important
}
.rnd {
  border: 2px solid #7a29a3;
  background: repeating-linear-gradient(45deg,#93c,#93c 10px,#7a29a3 10px,#7a29a3 20px)!important
}
.eng {
  border: 2px solid #ab8a2c;
  background: repeating-linear-gradient(45deg,#ab8a2c,#ab8a2c 10px,#b0a461 10px,#b0a461 20px)!important
}
.cargo {
  border: 2px solid #ad5313;
  background: repeating-linear-gradient(45deg,#ad5313,#ad5313 10px,#ad6d3e 10px,#ad6d3e 20px)!important
}
.just {
  border: 2px solid #490002;
  background: repeating-linear-gradient(45deg,#660004,#660004 10px,#490002 10px,#490002 20px)!important
}
.serv {
  border: 2px solid #39ab1d;
  background: repeating-linear-gradient(45deg,#56bd3c,#56bd3c 10px,#39ab1d 10px,#39ab1d 20px)!important
}
.antag {
  border: 2px solid #610000;
  background: repeating-linear-gradient(45deg,#a80000,#a80000 10px,#610000 10px,#610000 20px)!important
}
.ceco {
  border: 2px solid #29722e;
  background: repeating-linear-gradient(45deg,#488c40,#488c40 10px,#29722e 10px,#29722e 20px)!important
}
.sint {
  border: 2px solid #5a6e7a;
  background: repeating-linear-gradient(45deg,#738595,#738595 10px,#5a6e7a 10px,#5a6e7a 20px)!important
}
.sp {
  border: 2px solid #a6a6a6;
  background: repeating-linear-gradient(45deg,silver,silver 10px,#a6a6a6 10px,#a6a6a6 20px)!important
}
```