---
## Front matter
title: "Пятый этап индивидуального проекта"
subtitle: "Дисциплина: Операционные системы"
author: "Алиева Милена Арифовна"

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

Научиться добавлять на сайт записи для персональных проектов

# Задание

1. Сделать записи для персональных проектов
2. Сделать пост по прошедшей неделе
3. Добавить пост на тему по выбору: Языки научного программирования

# Выполнение лабораторной работы

1. Добавили на сайт свой проект в раздел с персональными проектами (рис. [-@fig:001])

![Добавление проекта](image/1.png){ #fig:001 width=70% }

2. Написали пост на тему: Языки научного программирования (рис. [-@fig:002])

![Пост](image/2.png){ #fig:002 width=70% }

Выгрузили с помощью команд git add, git commit, git push и hugo данные и убедились, что данные обновились (рис. [-@fig:003])

![Пост на сайте](image/3.png){ #fig:003 width=70% }

3. Также написали пост по прошедшей неделе (рис. [-@fig:004])

![Пост по прошедшей неделе](image/4.png){ #fig:004 width=70% }

Выгрузили с помощью команд git add, git commit, git push и hugo данные и увидели пост на своём сайте(рис. [-@fig:005])

![Пост по прошедшей неделе на сайте](image/5.png){ #fig:005 width=70% }

# Выводы

В ходе данной лабораторной работы я научилась добавлять на сайт записи для персональных проектов
