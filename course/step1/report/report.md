---
## Front matter
title: "Основы кибербезопасности" 
subtitle: "Этап 1"
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

Выполнить задания первой части курса по кибербезопасности.

# Выполнение лабораторной работы

UPD, TCP, IP - протоколы других уровней.

![Задание 1](image/Screenshot from 2025-05-13 19-20-27.png){#fig:001 width=100%}

TCP вне всяких сомнений transmission - транспортный уровень.

![Задание 2](image/Screenshot from 2025-05-13 19-20-30.png){#fig:002 width=100%}

В ip число между точками не больше 255.

![Задание 3](image/Screenshot from 2025-05-13 19-20-34.png){#fig:003 width=100%}

DNS сервер преобразует имена в адреса.

![Задание 4](image/Screenshot from 2025-05-13 19-20-40.png){#fig:004 width=100%}

Протоколы действительно распределены по уровням, идущим в таком порядке.

![Задание 5](image/Screenshot from 2025-05-13 19-20-44.png){#fig:005 width=100%}

В http данные в открытом виде, в https - в закрытом.

![Задание 6](image/Screenshot from 2025-05-13 19-20-47.png){#fig:006 width=100%}

HTTPS включает две фазы - рукопожатие и передачу данных.

![Задание 7](image/Screenshot from 2025-05-13 19-20-50.png){#fig:007 width=100%}

Это согласовывается клиентом и сервером.

![Задание 8](image/Screenshot from 2025-05-13 19-20-53.png){#fig:008 width=100%}

Шифрования данных нет врукопожатии.

![Задание 9](image/Screenshot from 2025-05-13 19-20-56.png){#fig:009 width=100%}

Куки используются для персонализации контента, им не нужны пароли и ip.

![Задание 10](image/Screenshot from 2025-05-13 19-21-17.png){#fig:010 width=100%}

Как отмечено ранее, у куки другие цели.

![Задание 11](image/Screenshot from 2025-05-13 19-21-23.png){#fig:011 width=100%}

Сервер создает куки.

![Задание 12](image/Screenshot from 2025-05-13 19-21-27.png){#fig:012 width=100%}

Сессионные куки очищаются после завершения сессии.

![Задание 13](image/Screenshot from 2025-05-13 19-21-31.png){#fig:013 width=100%}

Всего три узла - входной, промежуточный, выходной.

![Задание 14](image/Screenshot from 2025-05-13 19-21-37.png){#fig:014 width=100%}

IP скрыт от охранного и промежуточного узла.

![Задание 15](image/Screenshot from 2025-05-13 19-21-41.png){#fig:015 width=100%}

Общий ключ создается со всеми узлами.

![Задание 16](image/Screenshot from 2025-05-13 19-21-44.png){#fig:016 width=100%}

Это необязательно.

![Задание 17](image/Screenshot from 2025-05-13 19-21-47.png){#fig:017 width=100%}

По определению:

![Задание 18](image/Screenshot from 2025-05-13 19-21-57.png){#fig:018 width=100%}

Канальный, обеспечивает доступ в сеть.

![Задание 19](image/Screenshot from 2025-05-13 19-22-00.png){#fig:019 width=100%}

Устаревший протокол, легко взломать.

![Задание 20](image/Screenshot from 2025-05-13 19-22-03.png){#fig:020 width=100%}

Сначала аутентифицируют, потом передают данные.

![Задание 21](image/Screenshot from 2025-05-13 19-22-06.png){#fig:021 width=100%}

Из названия понятно, что personal для личного пользования.

![Задание 22](image/Screenshot from 2025-05-13 19-22-09.png){#fig:022 width=100%}



# Выводы

Все задания выполнены.


