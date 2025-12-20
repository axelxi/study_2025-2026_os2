---
## Front matter
lang: ru-RU
title: Лабораторная работа №7
subtitle: Установка и конфигурация операционной системы на виртуальную машину
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

Получить навыки работы с журналами мониторинга различных событий в системе.

1. Продемонстрируйте навыки работы с журналом мониторинга событий в реальном времени (см. раздел 7.4.1).
2. Продемонстрируйте навыки создания и настройки отдельного файла конфигурации мониторинга отслеживания событий веб-службы (см. раздел 7.4.2).
3. Продемонстрируйте навыки работы с journalctl (см. раздел 7.4.3).
4. Продемонстрируйте навыки работы с journald (см. раздел 7.4.4).

# Материалы и методы

- Linux (дистрибутив Rocky 9.6)
- Linux Fedora Sway (Markdown)
- Oracle VirtualBox

# Выполнение лабораторной работы

## 7.4.1. Мониторинг журнала системных событий в реальном времени

```
logger hello
```

![](image/1.PNG){#fig:001 width=65%}

## Журнал системных событий

```
tail -f /var/log/messages
```

![](image/2.PNG){#fig:002 width=65%}

## Журнал мониторинга сообщений безопасности

```
tail -n 20 /var/log/secure
```

![](image/3.PNG){#fig:003 width=65%}

## 7.4.2. Изменение правил rsyslog.conf

```
dnf -y install httpd
systemctl start httpd
systemctl enable httpd
```

![](image/4.PNG){#fig:004 width=60%}

## Журнал сообщений об ошибках веб-службы

```
tail -f /var/log/httpd/error_log
```

![](image/5.PNG){#fig:005 width=70%}

## Файл /etc/httpd/conf/httpd.conf

```
nano /etc/httpd/conf/httpd.conf
ErrorLog syslog:local1
```

![](image/6.PNG){#fig:006 width=65%}

## Создание файлов мониторинга и их редактирование

```
cd /etc/rsyslog.d
touch httpd.conf
cd /etc/rsyslog.d
touch debug.conf
echo "*.debug /var/log/messages-debug" > /etc/rsyslog.d/debug.conf
logger -p daemon.debug "Daemon Debug Message"
```

![](image/7.PNG){#fig:007 width=55%}

## Файл httpd.conf

```
local1.* -/var/log/httpd-error.log
```

![](image/8.PNG){#fig:008 width=65%}

## Перезагрузка веб-службы и конфигурации rsyslogd

```
systemctl restart rsyslog.service
systemctl restart httpd
```

![](image/9.PNG){#fig:009 width=60%}

## Журнал мониторинга отладочной информации

![](image/10.PNG){#fig:010 width=65%}

## 7.4.3. Использование journalctl

```
journalctl
```

![](image/11.PNG){#fig:011 width=65%}

## Журнал событий journald

![](image/12.PNG){#fig:012 width=65%}

## Журнал событий journald

![](image/13.PNG){#fig:013 width=65%}

## Журнал событий journald

![](image/14.PNG){#fig:014 width=65%}

## 7.4.4. Постоянный журнал journald

![](image/15.PNG){#fig:015 width=65%}

# Выводы

Я получила навыки работы с журналами мониторинга различных событий в системе.


