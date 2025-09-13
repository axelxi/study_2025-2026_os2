---
## Front matter
lang: ru-RU
title: Лабораторная работа №1
subtitle: Установка и конфигурация операционной системы на виртуальную машину
author:
  - Акунаева Антонина Эрдниевна
institute:
  - Российский университет дружбы народов, Москва, Россия
  
date: 2025-09-06

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

- Целью данной работы является приобретение практических навыков установки операционной системы на виртуальную машину, настройки минимально необходимых для дальнейшей работы сервисов.
- Выполнить домашнюю работу после выполнения лабораторной работы.

# Материалы и методы

- Linux (дистрибутив Rocky 9.6)
- Linux Fedora Workstation (Markdown)
- Oracle VirtualBox

# Выполнение лабораторной работы

## Создание ОС Rocky Linux

![](image/1.PNG){#fig:001 width=70%}

## Виртуальное оборудование Rocky Linux

![](image/2.PNG){#fig:002 width=70%}

## Виртуальный жёсткий диск Rocky Linux

![](image/3.PNG){#fig:003 width=70%}

## Окно установки Rocky Linux

![](image/4.PNG){#fig:004 width=70%}

## Окно установки Rocky Linux

![](image/5.PNG){#fig:005 width=70%}

## Настройка Rocky Linux: оборудование

![](image/6.PNG){#fig:006 width=70%}

## Настройка Rocky Linux: раскладка клавиатуры

![](image/7.PNG){#fig:007 width=70%}

## Настройка Rocky Linux: поддержка языков

![](image/8.PNG){#fig:008 width=70%}

## Настройка Rocky Linux: KDUMP

![](image/9.PNG){#fig:009 width=70%}

## Настройка Rocky Linux: настройка сети

![](image/10.PNG){#fig:010 width=70%}

## Настройка Rocky Linux: добавление пароля root

![](image/11.PNG){#fig:011 width=70%}

## Настройка Rocky Linux: добавление администратора

![](image/12.PNG){#fig:012 width=70%}

## Завершение настройки Rocky Linux

![](image/13.PNG){#fig:013 width=70%}

## Завершение установки Rocky Linux

![](image/14.PNG){#fig:014 width=70%}

## Подключение образа диска дополнений гостевой ОС

![](image/15.PNG){#fig:015 width=70%}


# Выполнение домашней работы

## Использование команды dmesg | less

```
dmesg | less
```

![](image/16.PNG){#fig:016 width=70%}

## Нахождение версии ядра Linux при помощи dmesg | grep -i

```
dmesg | grep -i "version"
```

![](image/17.PNG){#fig:017 width=70%}

## Нахождение частоты процессора при помощи dmesg | grep -i

```
dmesg | grep -i "processor"
```

![](image/18.PNG){#fig:018 width=70%}

## Нахождение модели процессора при помощи dmesg | grep -i

```
dmesg | grep -i "CPU0"
```

![](image/19.PNG){#fig:019 width=70%}

## Нахождение доступной оперативной памяти при помощи dmesg | grep -i

```
dmesg | grep -i "memory"
```

![](image/20.PNG){#fig:020 width=70%}

## Нахождение типа обнаруженного гипервизора при помощи dmesg | grep -i

```
dmesg | grep -i "hypervisor"
```

![](image/21.PNG){#fig:021 width=70%}

## Нахождение информации о файловых системах при помощи dmesg | grep -i

```
dmesg | grep -i "filesystem"
```

![](image/22.PNG){#fig:022 width=70%}


# Выводы

Я приобрела практические навыки установки операционной системы на виртуальную машину и настройки минимально необходимых для дальнейшей работы сервисов.


