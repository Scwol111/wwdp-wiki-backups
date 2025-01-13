---
title: Запуск локального сервера
description: Развёртывание локалки билда WWDP и не только
published: false
date: 2025-01-13T16:51:46.006Z
tags: 
editor: markdown
dateCreated: 2025-01-13T15:10:02.822Z
---

# <center>Запуск локального сервера</center>
В этом руководстве вы научитесь развёртывать локальный сервер любого проекта с открытым билдом на базе Einstein Engines, в том числе WWDP.
## <center>Cборка через скрипт</center>
Для облегчения работы, были созданы скрипты. Приступим к сборке.

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

### Этапы:
1. Откройте любую выбранную вами директорию в терминале:
- Консольный способ - <tt>cd *нужная директория*</tt>
- Или в проводнике нажмите ПКМ и выберите пункт "Открыть в Терминале" из выпадающего списка.

2. Клонируем репозиторий через команду:
<tt>git clone https://github.com/WWhiteDreamProject/wwdpublic/</tt>

3. Переходим в папку репозитория в терминале (носит название последнего словосочетания в ссылке). В данном случае wwdpublic:
<tt>cd wwdpublic</tt>

4. Пропишите команду <tt>git submodule update --init --recursive</tt> в консоль, чтобы скачать движок игры.

5. Соберите один из вариантов сервера:

5.1. Debug для разработки, содержит утилиты для отладки.
- Windows - <tt>Scripts/bat/buildAllDebug.bat</tt>
- GNU/Linux & macOS - <tt>Scripts/sh/buildAllDebug.sh</tt>

5.2. Release для развёртывания на сервере или маппинга, содержит различные оптимизации.
- Windows - <tt>Scripts/bat/buildAllRelease.bat</tt>
- GNU/Linux & macOS - <tt>Scripts/sh/buildAllRelease.sh</tt>

5.3. Tools для маппинга, содержит ещё больше оптимизаций.
- Windows - <tt>Scripts/bat/buildAllTools.bat</tt>
- GNU/Linux & macOS - <tt>Scripts/sh/buildAllTools.sh</tt>

6. Запустите сервер:

- Windows - <tt>Scripts\bat\runQuickAll.bat</tt>
- GNU/Linux & macOS - <tt>Scripts/sh/runQuickAll.sh</tt>

7. Подключитесь к локальному серверу, нажав <tt>Direct Connect To Server...</tt> в меню, и играйте