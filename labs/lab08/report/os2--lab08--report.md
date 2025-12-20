---
## Front matter
title: "Отчёт по лабораторной работе №8"
subtitle: "Планировщики событий"
author: "Акунаева Антонина Эрдниевна"

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
mainfont: IBM Plex Serif
romanfont: IBM Plex Serif
sansfont: IBM Plex Sans
monofont: IBM Plex Mono
mathfont: STIX Two Math
mainfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
romanfontoptions: Ligatures=Common,Ligatures=TeX,Scale=0.94
sansfontoptions: Ligatures=Common,Ligatures=TeX,Scale=MatchLowercase,Scale=0.94
monofontoptions: Scale=MatchLowercase,Scale=0.94,FakeStretch=0.9
mathfontoptions:
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

Получение навыков работы с планировщиками событий cron и at. [@TUIS-lab8]

# Задание

1. Выполните задания по планированию задач с помощью crond (см. раздел 8.4.1).
2. Выполните задания по планированию задач с помощью atd (см. раздел 8.4.2).

# Выполнение лабораторной работы

**8.4.1. Планирование задач с помощью cron**

 ([рис. @fig:001]).

![](image/1.PNG){#fig:001 width=70%}

**8.4.2. Планирование заданий с помощью at**

 ([рис. @fig:001]).

![](image/1.PNG){#fig:001 width=70%}

# Контрольные вопросы

**1. Как настроить задание cron, чтобы оно выполнялось раз в 2 недели?**

 ([рис. @fig:001]).

![](image/1.PNG){#fig:001 width=70%}

**2. Как настроить задание cron, чтобы оно выполнялось 1-го и 15-го числа каждого месяца в 2 часа ночи?**

 ([рис. @fig:001]).

![](image/1.PNG){#fig:001 width=70%}

**3. Как настроить задание cron, чтобы оно выполнялось каждые 2 минуты каждый день?**

 ([рис. @fig:001]).

![](image/1.PNG){#fig:001 width=70%}

**4. Как настроить задание cron, чтобы оно выполнялось 19 сентября ежегодно?**

 ([рис. @fig:001]).

![](image/1.PNG){#fig:001 width=70%}

**5. Как настроить задание cron, чтобы оно выполнялось каждый четверг сентября ежегодно?**

 ([рис. @fig:001]).

![](image/1.PNG){#fig:001 width=70%}

**6. Какая команда позволяет вам назначить задание cron для пользователя alice? Приведите подтверждающий пример.**

```

``` ([рис. @fig:001]).

![](image/1.PNG){#fig:001 width=70%}

**7. Как указать, что пользователю bob никогда не разрешено назначать задания через cron? Приведите подтверждающий пример.**

 ([рис. @fig:001]).

![](image/1.PNG){#fig:001 width=70%}

**8. Вам нужно убедиться, что задание выполняется каждый день, даже если сервер во время выполнения временно недоступен. Как это сделать?**

 ([рис. @fig:001]).

![](image/1.PNG){#fig:001 width=70%}

**9. Какая команда позволяет узнать, запланированы ли какие-либо задания на выполнение планировщиком atd?**

```

``` ([рис. @fig:001]).

![](image/1.PNG){#fig:001 width=70%}

# Выводы

Я получила навыки работы с планировщиками событий cron и at.

# Список литературы{.unnumbered}

::: {#refs}
:::
