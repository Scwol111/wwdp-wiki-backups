---
title: Пиздим у валерии 🍻
description: 
published: false
date: 2024-12-26T14:50:15.097Z
tags: 
editor: markdown
dateCreated: 2024-12-26T14:45:42.504Z
---

**Первый этап**, планирование:
- Выбрать страницу для переноса
- Подумать о путях в ссылках
**Второй этап**, перенос, часть 1:
- Откройте две вкладки, ваша страница и страница на старой вики
- Включите инструменты разработчика (ПКМ -> Просмотреть код)
<img src="https://i.ibb.co/J7c5k4T/image.png">
- Найдите в DOM блок BODY, затем блок MAIN, затем DIV с контентом страницы (Можете навестись на каждый и посмотреть подсвечивающуюся область)
<img src="https://i.ibb.co/JkCTMm8/image.png">
- Скопируйте блок на вашу страницу
**Третий этап**, перенос, часть 2:
- Для того, что бы перенести CSS, включите курсор-инспектор
<img src="https://i.ibb.co/4mP7rtG/image.png">
- Выберите любой блок с человеческим стилем на странице
<img src="https://i.ibb.co/kmZx4j0/image.png">
- Найдите местоположение стилей для страницы
<img src="https://i.ibb.co/9tNHSPC/image.png">
- Скопируйте стили к себе на страницу
**Четвертый этап**, исправление ошибок:
- Для временного исправления пропавших картинок, замените SRC подобного вида:

```
<img src="/main_page_icons/logo-tall-light-v2.png">
```
<img src="https://i.ibb.co/fH4QqX3/image.png">
- <br>На этот:

```
<img src="https://wiki.ss14.su/main_page_icons/logo-tall-light-v2.png">
```
<img src="https://i.ibb.co/NsYc7ng/image.png">

- Для исправления Giedi Prime, используйте этот сайт: http://web.archive.org/

<img src="https://i.ibb.co/bbRd0YT/image.png">

### Примечание
Желательно закинуть в хтмл-форматтер перед тем как вставить в статью. 
https://www.freeformatter.com/html-formatter.html