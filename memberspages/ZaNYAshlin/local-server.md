---
title: Запуск локального сервера
description: Развёртывание локалки билда WWDP
published: false
date: 2025-04-29T17:04:18.044Z
tags: 
editor: markdown
dateCreated: 2025-01-13T15:10:02.822Z
---

<!--
Ya yebal eto govno, suka blyat!!!
Muka soso
-->
<div id="windows" style="resize: none; overflow: none; display: inline;">
  <div class="header headtext">
    <div>>_ cmd - type local_server.txt</div>
    <div class="button">
      <div id="wrap">⎯</div>
      <div id="wrapWin">❐</div>
      <div id="closee">⤬</div>
    </div>
	</div>
  <div class="term">

  NT DOS [Version 6.1]
  (c) NanoTrasen Corporation. All rights reserved.
  N:\>cd guides
  N:\guides>cd contribution
  N:\guides\contribution>type local_server.txt
  <h1><center>Запуск локального сервера</center></h1>
  В этом руководстве вы научитесь развёртывать локальный сервер любого проекта с открытым билдом на базе Einstein Engines, в том числе WWDP.



  <h2><center>Cборка через скрипт</center></h2>
  Для облегчения работы были созданы скрипты. Приступим к сборке.

  Для начала установите компоненты, необходимые для сборки:
  - [Git](https://git-scm.com/downloads)
  - [.NET 9 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/9.0)

  Для работы с утилитами понадобится терминал:
  - Windows - [Windows Terminal](https://learn.microsoft.com/ru-ru/windows/terminal/)
  - GNU/Linux - встроенный в окружение рабочего стола/оконный менеджер или, например, [kitty](https://sw.kovidgoyal.net/kitty/)
  - macOS - встроенный, [iTerm2](https://iterm2.com/) или, например, [kitty](https://sw.kovidgoyal.net/kitty/)
  <p>Пользователям Windows можно устанавливать компоненты через пакетный менеджер <a href="https://learn.microsoft.com/ru-ru/windows/package-manager/winget/">winget</a> или установщики с официальных сайтов.</p> 
  <p>Пользователям дистрибутивов GNU/Linux рекомендуется устанавливать компоненты для сборки через встроенный пакетный менеджер.</p>
  <p>Пользователям macOS рекомендуется использовать пакетный менеджер <a href="https://brew.sh/">homebrew</a>, но можно использовать установщики с официальных сайтов.</p>
  <h3>Этапы:</h3>

  1. Откройте любую выбранную вами директорию в терминале:
    - Консольный способ - ```cd *нужная_директория*```
  - Или в проводнике нажмите ПКМ и выберите пункт ```"Открыть в Терминале"``` из выпадающего списка.

  2. Клонируем репозиторий через команду:
  ```
  git clone https://github.com/WWhiteDreamProject/wwdpublic/
  ```

  3. Переходим в папку репозитория в терминале (носит название последнего словосочетания в ссылке). В данном случае wwdpublic:
  ```
  cd wwdpublic
  ```

  4. Пропишите данную команду в консоль, чтобы скачать движок игры:
  ```
  git submodule update --init --recursive
  ```

  5. Соберите один из вариантов сервера и клиента через скрипт:

  5.1. Debug для разработки, содержит утилиты для отладки.
  - Windows - ```Scripts\bat\buildAllDebug.bat```
  - GNU/Linux & macOS - ```Scripts/sh/buildAllDebug.sh```

  5.2. Release для развёртывания на сервере или маппинга, содержит различные оптимизации.
  - Windows - ```Scripts\bat\buildAllRelease.bat```
  - GNU/Linux & macOS - ```Scripts/sh/buildAllRelease.sh```

  5.3. Tools для маппинга, содержит различные оптимизации.
  - Windows - ```Scripts\bat\buildAllTools.bat```
  - GNU/Linux & macOS - ```Scripts/sh/buildAllTools.sh```

  6. Запустите сервер и клиент через скрипт:

  - Windows - ```Scripts\bat\runQuickAll.bat```
  - GNU/Linux & macOS - ```Scripts/sh/runQuickAll.sh```

  7. Подключитесь через клиент к локальному серверу, нажав ```Прямое подключение``` в меню, и играйте.
  <div class="pentagon">
  <div class="ahui">N:\guides\contribution></div>
  <input id="enter" type="text">
  <div class="cursor"></div>
  </div>
  </div>
  </div>
</div>