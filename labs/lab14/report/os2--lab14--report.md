---
## Front matter
title: "Отчёт по лабораторной работе №15"
subtitle: "Управление логическими томами"
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

Получить навыки управления логическими томами. [@TUIS-lab15]

# Задание

1. Продемонстрировать навыки создания физических томов на LVM (см. раздел 15.4.1).
2. Продемонстрировать навыки создания группы томов и логических томов на LVM (см. раздел 15.4.2).
3. Продемонстрировать навыки изменения размера логических томов на LVM (см. раздел 15.4.3).
4. Выполнить задание для самостоятельной работы (см. раздел 15.5).

# Выполнение лабораторной работы

**15.4.1. Создание физического тома**

 ([рис. @fig:001]):

![](image/1.PNG){#fig:001 width=70%}

**15.4.2. Создание группы томов и логических томов**

 ([рис. @fig:001]):

![](image/1.PNG){#fig:001 width=70%}

**15.4.3. Изменение размера логических томов**

 ([рис. @fig:001]):

![](image/1.PNG){#fig:001 width=70%}

**15.5. Самостоятельная работа**

 ([рис. @fig:001]):

![](image/1.PNG){#fig:001 width=70%}

# Контрольные вопросы

**1. **

 ([рис. @fig:0]):

![Контрольный вопрос №1](image/q1.PNG){#fig:0 width=70%}

**2. **

 ([рис. @fig:0]):

![Контрольный вопрос №2](image/q2.PNG){#fig:0 width=70%}

**3. **

 ([рис. @fig:0]):

![Контрольный вопрос №3](image/q3.PNG){#fig:0 width=70%}

**4. **

 ([рис. @fig:0]):

![Контрольный вопрос №4](image/q4.PNG){#fig:0 width=70%}

**5. **

 ([рис. @fig:0]):

![Контрольный вопрос №5](image/q5.PNG){#fig:0 width=70%}

**6. **

 ([рис. @fig:0]):

![Контрольный вопрос №6](image/q6.PNG){#fig:0 width=70%}

**7. **

 ([рис. @fig:0]):

![Контрольный вопрос №7](image/q7.PNG){#fig:0 width=70%}

**8. **

 ([рис. @fig:0]):

![Контрольный вопрос №1](image/q8.PNG){#fig:0 width=70%}

**9. **

 ([рис. @fig:0]):

![Контрольный вопрос №1](image/q9.PNG){#fig:0 width=70%}

# Выводы

Я получила навыки управления логическими томами.

# Список литературы{.unnumbered}

::: {#refs}
:::
