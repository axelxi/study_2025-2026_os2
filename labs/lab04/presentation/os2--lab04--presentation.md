---
## Front matter
lang: ru-RU
title: Лабораторная работа №4
subtitle: Работа с программными пакетами
author:
  - Акунаева Антонина Эрдниевна
institute:
  - Российский университет дружбы народов, Москва, Россия
  
date: 2025-09-27

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

- Получить навыки работы с репозиториями и менеджерами пакетов.

1. Изучите, как и в каких файлах подключаются репозитории для установки программного обеспечения; изучите основные возможности (поиск, установка, обновление, удаление пакета, работа с историей действий) команды dnf (см. раздел 4.4.1).
2. Изучите и повторите процесс установки/удаления определённого пакета с использованием возможностей dnf (см. раздел 4.4.1).
3. Изучите и повторите процесс установки/удаления определённого пакета с использованием возможностей rpm (см. раздел 4.4.2).

# Материалы и методы

- Linux (дистрибутив Rocky 9.6)
- Linux Fedora Sway (Markdown)
- Oracle VirtualBox

# Выполнение лабораторной работы

## Определение списка репозиториев

![](image/1.PNG){#fig:001 width=70%}

## Вывод списка репозиториев

```
dnf repolist
dnf search user
```

![](image/2.PNG){#fig:002 width=60%}

## Определение информации о nmap

![](image/3.PNG){#fig:003 width=70%}

## Установка nmap

![](image/4.PNG){#fig:004 width=70%}

## Установка nmap\*

![](image/5.PNG){#fig:005 width=70%}

## Удаление nmap

![](image/6.PNG){#fig:006 width=70%}

## Определение групп пакетов dnf

![](image/7.PNG){#fig:007 width=70%}

## Определение групп пакетов dnf

![](image/8.PNG){#fig:008 width=70%}

## Установка RPM DevTools

![](image/9.PNG){#fig:009 width=70%}

## Удаление RPM DevTools

![](image/10.PNG){#fig:010 width=70%}

## История использования dnf

![](image/11.PNG){#fig:011 width=70%}

## Установка rpm-пакета lynx

![](image/12.PNG){#fig:012 width=70%}

## Установка lynx из пакета и информация о нём

![](image/13.PNG){#fig:013 width=70%}

## Вывод списка файлов в пакете rpm

![](image/14.PNG){#fig:014 width=70%}

## Вывод списка файлов с документацией пакета

![](image/15.PNG){#fig:015 width=70%}

## Скрипты и удаление lynx

![](image/16.PNG){#fig:016 width=70%}

## Текстовый браузер lynx

![](image/17.PNG){#fig:017 width=70%}

## Установка dnsmasq

![](image/18.PNG){#fig:018 width=70%}

## Получение списков по dnsmasq

![](image/19.PNG){#fig:019 width=70%}

## Получение списков по dnsmasq

![](image/20.PNG){#fig:020 width=70%}

## Скрипты dnsmasq

![](image/21.PNG){#fig:021 width=70%}

## Скрипты и удаление dnsmasq

![](image/22.PNG){#fig:022 width=70%}


# Выводы

Я получила навыки работы с репозиториями и менеджерами пакетов.


