---
## Front matter
title: "Основы кибербезопасности" 
subtitle: "Этап 3"
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

Выполнить задания третьей части курса по кибербезопасности.

# Выполнение лабораторной работы

Два ключа - исходя из определения ассимитричного шифрования.

![Задание 1](image/Screenshot from 2025-05-13 19-30-21.png){#fig:001 width=100%}

По свойствам хэш-функции.

![Задание 2](image/Screenshot from 2025-05-13 19-31-21.png){#fig:002 width=100%}

Алгоритмы:

![Задание 3](image/Screenshot from 2025-05-13 19-31-57.png){#fig:003 width=100%}

Так как для шифровки и дешифровки используется один и тот же ключ.

![Задание 4](image/Screenshot from 2025-05-13 19-32-22.png){#fig:004 width=100%}

По определению этого алгоритма.

![Задание 5](image/Screenshot from 2025-05-13 19-32-56.png){#fig:005 width=100%}

Потому что используется ассиметричное шифрование.

![Задание 6](image/Screenshot from 2025-05-13 19-33-14.png){#fig:006 width=100%}

Подписанное сообщение проверяется открытым ключом.

![Задание 7](image/Screenshot from 2025-05-13 19-33-34.png){#fig:007 width=100%}

Она наоборот гарантирует, что можно определить, кто подписал.

![Задание 8](image/Screenshot from 2025-05-13 19-33-46.png){#fig:008 width=100%}

Так как в налоговую нужны юридически значимые документы.

![Задание 9](image/Screenshot from 2025-05-13 19-33-56.png){#fig:009 width=100%}

В сертифицированном центре.

![Задание 10](image/Screenshot from 2025-05-13 19-34-09.png){#fig:010 width=100%}

МИР и Mastercard всем известны.

![Задание 11](image/Screenshot from 2025-05-13 19-34-43.png){#fig:011 width=100%}

Отметила верные методы.

![Задание 12](image/Screenshot from 2025-05-13 19-35-05.png){#fig:012 width=100%}

Используется многофакторная аутентификация.

![Задание 13](image/Screenshot from 2025-05-13 19-35-21.png){#fig:013 width=100%}

Прообраз действительно сложно найти, поэтому она надёжна.

![Задание 14](image/Screenshot from 2025-05-13 19-35-44.png){#fig:014 width=100%}

По свойствам консенсуса.

![Задание 15](image/Screenshot from 2025-05-13 19-36-20.png){#fig:015 width=100%}

Они хранят цифровые подписи.

![Задание 16](image/Screenshot from 2025-05-13 19-36-33.png){#fig:016 width=100%}

Ура, я завершила курс!

![Задание 17](image/Screenshot from 2025-05-13 19-36-52.png){#fig:017 width=100%}

# Выводы

Все задания третьей части выполнены. Курс завершён.


