---
## Front matter
lang: ru-RU
title: Лабораторная работа №8
subtitle: Планировщики событий
author:
  - Акунаева Антонина Эрдниевна
institute:
  - Российский университет дружбы народов, Москва, Россия
  
date: 2025-12-20

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
---

# Информация

## Докладчик

:::::::::::::: {.columns align=center}
::: {.column width="70%"}

  * Акунаева Антонина Эрдниевна
  * студент ФФМиЕН, НПИбд-01-24
  * Российский университет дружбы народов
  * [1032240492@pfur.ru](mailto:1032240492@pfur.ru)
  * <https://github.com/Akuxee>

:::
::: {.column width="30%"}

![](./image/aeakunaeva.PNG)

:::
::::::::::::::

# Цели и задачи

- Получение навыков работы с планировщиками событий cron и at.

1. Выполните задания по планированию задач с помощью crond (см. раздел 8.4.1).
2. Выполните задания по планированию задач с помощью atd (см. раздел 8.4.2).

# Материалы и методы

- Linux (дистрибутив Rocky 9.6)
- Linux Fedora Sway (Markdown)
- Oracle VirtualBox

# Выполнение лабораторной работы

## 8.4.1. Планирование задач с помощью cron

```
su - 
systemctl status crond -l
cat /etc/crontab
```

![](image/1.PNG){#fig:001 width=60%}

## Отображение и изменение расписания в cron

```
crontab -l
crontab -e

*/1 * * * * logger This message is written from root cron
```

![](image/2.PNG){#fig:002 width=60%}

## Внесение изменений в cron

![](image/3.PNG){#fig:003 width=65%}

## Внесение задач в расписание cron

![](image/4.PNG){#fig:004 width=65%}

## Внесение новой записи в cron

```
0 */1 * * 1-5 logger This message is written from root cron
```

![](image/5.PNG){#fig:005 width=65%}

## Изменение файла сценария /etc/cron.hourly/eachhour

```
#!/bin/sh
logger This message is written at $(date)
```

![](image/6.PNG){#fig:006 width=65%}

## Изменение /etc/crond.d/eachhour

```
11 * * * * root logger This message is written from /etc/cron.d
```

![](image/7.PNG){#fig:007 width=65%}

## 8.4.2. Планирование заданий с помощью at

![](image/8.PNG){#fig:008 width=60%}

# Выводы

Я получила навыки работы с планировщиками событий cron и at.


