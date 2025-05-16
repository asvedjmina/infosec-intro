---
## Front matter
title: "Лабораторная работа 7" 
subtitle: "Элементы криптографии. Однократное гаммирование"
author: "Ведьмина Александра Сергеевна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Получение практических навыков работы в консоли с атрибутами файлов для групп пользователей

# Задание

Выполнить задания из файла в туисе.

# Выполнение лабораторной работы

Создаю пользователей guest и guest2.

![Создание пользователей](image/Screenshot from 2025-02-28 22-46-25.png{#fig:001 width=100%}

Добавляю пользователя guest2 в группу guest.

![Добавление в группу](image/Screenshot from 2025-02-28 22-47-06.png){#fig:002 width=100%}

Вхожу в пользователей с разных консолей.

![Вход](image/Screenshot from 2025-02-28 22-49-46.png){#fig:003 width=100%}

Смотрю директории с помощью pwd.

![Директория](image/Screenshot from 2025-02-28 22-54-55.png){#fig:004 width=100%}

Уточните имя вашего пользователя, его группу, кто входит в неё и к каким группам принадлежит он сам. Определите командами groups guest и groups guest2, в какие группы входят пользователи guest и guest2. Сравните вывод команды groups с выводом команд id -Gn и id -G.

![Id](image/Screenshot from 2025-02-28 22-55-33.png){#fig:005 width=100%}

![Groups](image/Screenshot from 2025-02-28 22-56-23.png){#fig:006 width=100%}

От имени пользователя guest2 выполняю регистрацию пользователя guest2 в группе guest.

![Регистрация guest2](image/Screenshot from 2025-02-28 22-58-32.png){#fig:007 width=100%}

От имени пользователя guest изменяю права директории /home/guest, разрешив все действия для пользователей группы.

![Изменение прав](image/Screenshot from 2025-02-28 22-59-15.png){#fig:008 width=100%}

Снимаю с директории /home/guest/dir1 все атрибуты командой.

![Снятие прав](image/Screenshot from 2025-02-28 23-00-42.png){#fig:009 width=100%}

![Проверка](image/Screenshot from 2025-02-28 23-01-12.png){#fig:010 width=100%}

# Выводы

В ходе лабораторной работы я получила практические навыки работы в консоли с атрибутами файлов для групп пользователей.


