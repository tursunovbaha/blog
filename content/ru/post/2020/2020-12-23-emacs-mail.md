---
title: "Emacs. Почта"
date: 2020-12-23T11:12:00+03:00
lastmod: 2021-01-10T20:09:00+03:00
categories: ["blog"]
draft: false
slug: "emacs-mail"
---

Чтение почты в Emacs.

<!--more-->

{{< toc >}}


## Почтовые клиенты Emacs {#почтовые-клиенты-emacs}


### Клиенты IMAP {#клиенты-imap}


#### Gnus {#gnus}

-   [Emacs. Почта. GNUS]({{< relref "2020-12-21-emacs-mail-gnus" >}})


#### WanderLust {#wanderlust}


### Индексаторы почты {#индексаторы-почты}

Индексаторы почты работают с локальными почтовыми
сообщениями. Получить их с сервера можно с помощью других средств.


#### NotMuch {#notmuch}

-   URL: <https://notmuchmail.org/>
-   Является интерфейсом для консольного клиента `notmuch`.
-   Интерфейс ориентирован на ярлыки.
-   Тегирование писем (теги локальные).
-   Хороший поиск.
-   Поиск работает поверх [xapian](https://xapian.org/).
-   В пользовательском интерфейсе сообщения сгруппированы по тегам.
-   Высокая производительность.
-   Изначально работает с одной учётной записью, несколько учётных записей объединяются в одну локальную.
-   Не поддерживает операции для работы с почтовым ящиком на сервере. На сервере ничего не изменяется.
-   Не рендерит html-почту.


#### mu4e {#mu4e}

-   [Emacs. Почта. Mu4e]({{< relref "2020-12-24-emacs-mail-mu4e" >}})
-   URL: <https://www.djcbsoftware.nl/code/mu/>
-   Является интерфейсом для консольного клиента `mu`.
-   Интерфейс ориентирован на папки.
-   Хорошая поддержка поиска.
-   Поиск работает поверх [xapian](https://xapian.org/).
-   Асинхронная работа (не блокирует emacs).
-   Поддерживает по умолчанию несколько учётных записей. Хранить их отдельно.
-   Хорошая интеграция с org-mode.
-   Автоматически вызывает программу синхронизации IMAP.
-   Поддерживает почтовые операции на сервере, такие как перемещение, удаление и т.д.
-   Содержимое html-письма рендерится с помощью Webkit в качестве бэкэнда и отображается как pdf.
-   Автозаполнение адресов на основе сообщений (нет необходимости в управлении адресными книгами).


## Backlinks {#backlinks}


### [Emacs]({{< relref "2020-12-24-emacs" >}}) {#emacs}

Работа с почтой (см. [Emacs. Почта]({{< relref "2020-12-23-emacs-mail" >}}))
