---
## Front matter
lang: ru-RU
title: Лабораторная работа 2
subtitle: "Дискреционное
разграничение прав в Linux. Основные
атрибуты"
author:
  - Ведьмина Александра Сергеевна
institute:
  - Российский университет дружбы народов, Москва, Россия

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Ведьмина Александра Сергеевна
  * студентка
  * Российский университет дружбы народов
  * [1132236003@rudn.ru](mailto:1132236003@rudn.ru)
  * <https://asvedjmina.github.io/ru/>

:::
::: {.column width="30%"}

![](./image/admin.jpg)

:::
::::::::::::::

# Вводная часть

## Цели и задачи

Получение практических навыков работы в консоли с атрибутами файлов, закрепление теоретических основ дискреционного разграничения доступа в современных системах с открытым кодом на базе ОС Linux1.

# Выполнение лабораторной работы

Создаю нового пользователя guest командами useradd guest, ставлю пароль, вхожу в систему как guest

![](image/Screenshot from 2025-02-28 22-23-15.png){#fig:001 width=100%}

## Выполнение лабораторной работы

Определяю директорию, в которой нахожусь. Она домашняя.

![](image/Screenshot from 2025-02-28 22-26-50.png){#fig:002 width=100%}

## Выполнение лабораторной работы

Смотрю id.

![](image/Screenshot from 2025-02-28 22-27-06.png){#fig:003 width=100%}

## Выполнение лабораторной работы

Смотрю groups. Информацию об имени пользователя совпадает с данными,
выводимыми в приглашении командной строки.

![](image/Screenshot from 2025-02-28 22-27-28.png){#fig:004 width=100%}

## Выполнение лабораторной работы

Смотрю файл /etc/passwd командой cat /etc/passwd. Нахожу в нём свою учётную запись.

![](image/Screenshot from 2025-02-28 22-30-44.png){#fig:005 width=100%}

## Выполнение лабораторной работы

Вывожу список директорий с их правами.

![](image/Screenshot from 2025-02-28 22-35-25.png){#fig:006 width=100%}

## Выполнение лабораторной работы

Не могу посмотреть расширенные атрибуты lsattr /home.

![](image/Screenshot from 2025-02-28 22-35-53.png){#fig:007 width=100%}

## Выполнение лабораторной работы

Создаю директорию dir1 и смотрю права доступа.

![](image/Screenshot from 2025-02-28 22-36-35.png){#fig:008 width=100%}

## Выполнение лабораторной работы

Снимаю их все.

![](image/Screenshot from 2025-02-28 22-37-04.png){#fig:009 width=100%}

## Выполнение лабораторной работы

Создаю в директории dir1 файл file1 командой echo "test" > /home/guest/dir1/file1, но получаю ошибку.

![](image/Screenshot from 2025-02-28 22-39-03.png){#fig:010 width=100%}

# Выводы

Получила навыки работы в консоли с атрибутами файлов.
