---
title: Запуск локального сервера
description: Развёртывание локалки билда WWDP и не только
published: true
date: 2025-01-13T15:48:20.186Z
tags: 
editor: markdown
dateCreated: 2025-01-13T15:10:02.822Z
---

# <center>Запуск локального сервера</center>
В этом руководстве вы научитесь развёртывать локальный сервер любого проекта с открытым билдом, в частности WWDP.
## <center>Собственноручная сборка</center>
Собственноручная сборка подразумевает собой поэтапный процесс с самого клонирования репозитория.

Для начала установите компоненты, необходимые для сборки:
- [Git](https://git-scm.com/downloads)
- [.NET 9 SDK](https://dotnet.microsoft.com/en-us/download/dotnet/9.0)
- [Python 3.7+](https://www.python.org/downloads)

Для работы с утилитами понадобится терминал:
- Windows - [Windows Terminal](https://learn.microsoft.com/ru-ru/windows/terminal/)
- GNU/Linux - встроенный в окружение рабочего стола/оконный менеджер или, например, [kitty](https://sw.kovidgoyal.net/kitty/)
- macOS - встроенный, [iTerm2](https://iterm2.com/) или, например, [kitty](https://sw.kovidgoyal.net/kitty/)
<p>Пользователям Windows можно устанавливать компоненты через пакетный менеджер <a href="https://learn.microsoft.com/ru-ru/windows/package-manager/winget/">winget</a> или установщики с официальных сайтов.</p> 
<p>Пользователям дистрибутивов GNU/Linux рекомендуется устанавливать компоненты для сборки через встроенный пакетный менеджер.</p>
<p>Пользователям macOS рекомендуется использовать пакетный менеджер <a href="https://brew.sh/">homebrew</a>, но можно использовать установщики с официальных сайтов.</p>

Этапы:
1. Откройте любую выбранную вами директорию в терминале:
- Консольный способ - <tt>cd *нужная директория*</tt>
- Или в проводнике нажмите ПКМ и выберите пункт "Открыть в Терминале" из выпадающего списка.

2. Клонируем нужный вам репозиторий через команду <tt>git clone *ссылка*</tt>
Вместо *ссылки* вставьте нужный вам репозиторий. Вот некоторые из существующих на свете:
- WWDP - https://github.com/WWhiteDreamProject/wwdpublic
- Einstein Engines - https://github.com/Simple-Station/Einstein-Engines
- Backmen & Ataraxia - https://github.com/Rxup/space-station-14
- Corvax - https://github.com/space-syndicate/space-station-14
- Corvax Next - https://github.com/space-syndicate/space-station-14-next
- Wizard's Den - https://github.com/space-wizards/space-station-14
<p>Получившаяся команда будет иметь примерно такой вид:</p>
<tt>git clone https://github.com/WWhiteDreamProject/wwdpublic/</tt>

3. Переходим в папку репозитория в терминале (носит название последнего словосочетания в ссылке). В данном случае wwdpublic:
- Консольный способ через команду <tt>cd wwdpublic</tt>
- Или в проводнике нажмите ПКМ по папке wwdpublic и выберите пункт "Открыть в Терминале" из выпадающего списка.

4. Устанавливаем зависимости для сборки через команду <tt>python ./RUN_THIS.py</tt>

5. Собираем сервер и клиент через команду <tt>dotnet build</tt> или <tt>dotnet build --configuration *конфигурация*</tt>
Вместо *конфигурация* впишите нужную:
- <tt>Release</tt> - обычная сборка, используемая на серверах;
- <tt>Tools</tt> - отладка, оптимизированная для маппинга;
- <tt>Debug</tt> - отладка;
- <tt>DebugOpt</tt> - оптимизированная отладка;

### <center>Обновление версии</center>

1. Переходим в папку репозитория в терминале (носит название последнего словосочетания в ссылке):
- Универсальный способ через команду <tt>cd *путь до репозитория*</tt>
- Или в проводнике нажмите ПКМ по папке репозитория и выберите пункт "Открыть в Терминале" из выпадающего списка.

2. Пропишите команды <tt>git pull</tt> и <tt>git submodule update --init --recursive</tt> в консоль.
3. В той же командной строке введите команду <tt>dotnet build</tt>

### <center>Запуск</center>
#### Вручную:
1. Запускаем сервер:

- Windows - запустите исполняемый файл <tt>Content.Server.exe</tt> по пути <tt>..\\*ИМЯ РЕПОЗИТОРИЯ*\bin\Content.Server (не путать с Robust.Server.exe)</tt>
- GNU/Linux & macOS - <tt>dotnet run --project Content.Client --no-build</tt>

2. Запускаем клиент:

- Windows - запустите исполняемый файл <tt>Content.Client.exe</tt> по пути <tt>..\\*ИМЯ РЕПОЗИТОРИЯ*\bin\Content.MapRenderer (не путать с Robust.Client.exe)</tt>
- GNU/Linux & macOS - <tt>dotnet run --project Content.Client --no-build</tt>

#### Через скрипт:
- Windows - <tt>..\\*ИМЯ РЕПОЗИТОРИЯ*\Scripts\bat\runQuickAll.bat</tt>
- GNU/Linux & macOS - <tt>../*ИМЯ РЕПОЗИТОРИЯ*/Scripts/sh/runQuickAll.sh</tt>