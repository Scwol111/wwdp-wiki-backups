---
title: Обновление таблицы ролей
description: 
published: false
date: 2024-12-26T21:00:14.303Z
tags: 
editor: markdown
dateCreated: 2024-12-26T14:37:23.458Z
---


## <center>Добавление на страничку роли
Во-первых, добавьте следующий скрипт в сценарий(свойства страницы, третья вкладка):

```
<script>
  async function insertContentAfterTable(url) {
    try {
      const response = await fetch(url);

      if (!response.ok) {
        throw new Error(`Ошибка загрузки: ${response.statusText}`);
      }

      const content = await response.text();

      const tableElement = document.querySelector('.table');

      if (tableElement) {
        const contentElement = document.createElement('div');
        contentElement.innerHTML = content;
        console.log(contentElement.querySelector(".title"));
        tableElement.insertAdjacentElement('afterend', contentElement);
      } else {
        console.log('Элемент с классом table не найден.');
      }
    } catch (error) {
      console.error('Произошла ошибка:', error);
    }
  }
  window.onload = function() {
    insertContentAfterTable('https://raw.githubusercontent.com/TokiJumper/wikijs-templates/refs/heads/main/role-table'); // Ссылка на таблицу ролей, чтобы заменить на английскую версию, добавьте "-en". role-table -> role-table-en //
  }

</script>
```
![screenshot_36.png](/guides/wiki/screenshot_36.png)

Затем, в самом конце самой страницы добавьте следующий элемент:

```
<div class="table"></div>
```
![screenshot_37.png](/guides/wiki/screenshot_37.png)

И тогда, при открытии страницы, на месте ```<div class="table"></div>``` должно получиться следующее:

<div class="table"></div>

<details>
   <summary>
      <center>Не забудьте добавить стили CSS</center>
   </summary>
<pre>
.roles-table {
  width: auto;
  display: flex;
  flex-wrap: wrap;
  margin: 1em auto 1em auto;
  padding: 5px;
  border-radius: 10px;
  border: solid #757575 1px
}
.roles-table > .title {
  width: 20%;
  display: flex;
  flex: min-content;
  flex-direction: column;
  justify-content: center;
  text-align: center;
  align-items: center
}
.roles-table > .wrapper {
  width: 80%;
  display: flex;
  flex: auto;
  flex-flow: row wrap
}
.roles-table > .wrapper > .dep-wrapper {
  width: 100%;
  display: flex;
  flex-direction: row;
  border: solid #212121 2px;
  border-radius: 10px
}
.roles-table > .wrapper > .dep-wrapper > .dep-title {
  display: flex;
  justify-content: center;
  text-align: center;
  align-items: center;
  padding: 0 3px;
  border-radius: 10px
}
.roles-table > .wrapper > .dep-wrapper > .dep-title > strong {
  font-size: 18px
}
.roles-table > .wrapper > .dep-wrapper > .roles > a:last-child:after {
  content: none
}
.roles-table > .wrapper > .dep-wrapper > .roles > a:after {
  content: "•";
  display: inline-block;
  color: #fff;
  margin: 0 0 0 4px
}
@media (orientation:portrait) {
  .roles-table {
    width: 100%
  }
  .roles-table > .wrapper > .dep-wrapper {
    flex-direction: column
  }
  .roles-table > .wrapper > .dep-wrapper > .roles {
    display: grid;
    padding: 5px 20px 5px 20px
  }
  .roles-table a:after {
    content: none!important
  }
}
@media (orientation:landscape) {
  .roles-table {
    width: 90%
  }
  .roles-table > .wrapper > .dep-wrapper > .dep-title {
    width: 20%
  }
  .roles-table > .wrapper > .dep-wrapper > .roles {
    width: 80%;
    display: inline;
    justify-content: center;
    padding: 5px 20px 5px 10px;
    gap: 0 10px
  }
  .roles-table > .wrapper > .dep-wrapper > .roles > .nomobile {
    display: inline;
    font-weight: 700
  }
}
.roles-table > .wrapper > .dep-wrapper > .roles > a {
  font-weight: 700
}
</pre>

![screenshot_53.png](/guides/wiki/screenshot_53.png)
</details>

# Изменение, дополнение и обновление таблицы ролей

1. У вас должен быть аккаунт на [**github**](https://github.com/).

2. Затем вам нужно перейти на страницу этого [**репозитория**](https://github.com/TokiJumper/wikijs-templates/tree/main).

3. Вас интересуют следующие файлы:
    * **role-table** — русская версия таблицы ролей.
    * **role-table-clown-ru** — особенная СмИшНаЯ таблица ролей для клоуна, русская (английской нет).
    * **role-table-en** — английская версия обычной таблицы ролей.

   Открываем нужный файл.

![screenshot_38.png](/guides/wiki/screenshot_38.png)

4. Редактирование. Нажмите на карандаш справа, с надписью при наведении <kbd>edit this file</kbd>.

![screenshot_39.png](/guides/wiki/screenshot_39.png)

5. После того, как вы внесли нужные изменения, нажмите кнопку <kbd>Commit changes</kbd>, и в открывшемся меню нажимаем <kbd>Propose changes</kbd>.

![screenshot_40.png](/guides/wiki/screenshot_40.png)
![screenshot_41.png](/guides/wiki/screenshot_41.png)

6. В <kbd>Add a title</kbd> и <kbd>Add a description</kbd> добавляем заголовок и описание ваших изменений (опционально).

7. Осталось создать пулреквест, нажмите кнопку <kbd>Create pull request</kbd>, далее ваши изменения должен принять Kutos или tokijumper.
![screenshot_42.png](/guides/wiki/screenshot_42.png)

## <center> Для слабых

Если вы не смогли создать ПР, тогда вы можете просто скинуть изменённый, например, в блокноте, html-файл.
  Скидывать можете kutos0 или tokijumper в дискорд, или в <a href="https://discord.com/channels/1274878892657741835/1305616260440264715.">этот тред</a> 

Получить файл, используемый в таблице ролей, легко: просто переходим по ссылке из скрипта. 
![screenshot_43.png](/guides/wiki/screenshot_43.png)
