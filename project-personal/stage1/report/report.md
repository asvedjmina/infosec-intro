---
## Front matter
title: "Лабораторная работа"
subtitle: "Индивидуальный проект. Шаг 1"
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

Установить kali linux, создать пользователя.

# Задание

Установить виртуальную машину и kali linux.

# Выполнение лабораторной работы

Я буду использовать Boxes федоры, поэтому скачиваю iso-файл.

![Скачивание](image/Screenshot from 2025-03-01 21-43-29.png){#fig:001 width=100%}

Открываю кали.

![Открытие kali](image/Screenshot from 2025-03-01 21-52-09.png){#fig:002 width=100%}

Настраиваю систему.

![Настройка](image/Screenshot from 2025-03-01 21-52-51.png){#fig:003 width=100%}

Захожу в систему.

![Вход в систему](image/Screenshot from 2025-03-01 22-22-34.png){#fig:004 width=100%}

Ура, всё работает!

![Рабочий стол](image/Screenshot from 2025-03-01 22-25-13.png){#fig:005 width=100%}

# Выводы

Устаовила новую ос и настроила.


