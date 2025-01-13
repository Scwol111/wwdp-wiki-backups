---
title: Запуск локального сервера
description: Развёртывание локалки билда WWDP и не только
published: true
date: 2025-01-13T15:10:02.822Z
tags: 
editor: markdown
dateCreated: 2025-01-13T15:10:02.822Z
---

# <center>Запуск локального сервера</center>
В этом руководстве вы научитесь развёртывать локальный сервер любого проекта с открытым билдом, в частности WWDP.
## <center>Собственная сборка</center>
Собственная сборка подразумевает собой поэтапный процесс с самого клонирования репозитория.

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
- Универсальный способ - <tt>cd *нужная директория*</tt>
- В проводнике нажмите ПКМ и выберите пункт "Открыть в Терминале" из выпадающего списка.

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

3. Переходим в папку репозитория (носит название последнего словосочетания в ссылке). В данном случае wwdpublic:
- Универсальный способ - <tt>cd wwdpublic</tt>
- В проводнике нажмите ПКМ по папке wwdpublic и выберите пункт "Открыть в Терминале" из выпадающего списка.

4. Устанавливаем зависимости для сборки через команду <tt>python ./RUN_THIS.py</tt>

5. Собираем сервер и клиент через команду