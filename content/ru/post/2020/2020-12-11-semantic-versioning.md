---
title: "Семантическое версионирование"
date: 2020-12-11T19:17:00+03:00
lastmod: 2021-03-09T20:38:00+03:00
tags: ["programming"]
categories: ["sysadmin"]
draft: false
slug: "semantic-versioning"
---

Семантический подход в версионированию программного обеспечения.

<!--more-->

{{< toc >}}


## <span class="section-num">1</span> Краткое описание семантического версионирования {#краткое-описание-семантического-версионирования}

Семантическое версионирование описывается в [манифесте семантического версионирования](https://semver.org/lang/ru/).

Кратко его можно описать следующим образом:

-   Версия задаётся в виде кортежа `МАЖОРНАЯ_ВЕРСИЯ.МИНОРНАЯ_ВЕРСИЯ.ПАТЧ`.
-   Номер версии следует увеличивать:
    -   МАЖОРНУЮ версию, когда сделаны обратно несовместимые изменения API.
    -   МИНОРНУЮ версию, когда вы добавляете новую функциональность, не нарушая обратной совместимости.
    -   ПАТЧ-версию, когда вы делаете обратно совместимые исправления.
-   Дополнительные обозначения для предрелизных и билд-метаданных
    возможны как дополнения к МАЖОРНАЯ.МИНОРНАЯ.ПАТЧ формату.


## <span class="section-num">2</span> Программное обеспечение {#программное-обеспечение}

Для реализации семантического версионирования создано несколько
программных продуктов. При этом лучше всего использовать комплексные
продукты, которые используют информацию из коммитов системы
версионирования. Естественно, коммиты должны иметь стандартизованный
вид. Поэтому в семантическое версионирование применяется вместе с _общепринятыми коммитами_ (см. [Общепринятые коммиты]({{< relref "2020-12-11-conventional-commits" >}})).


### <span class="section-num">2.1</span> Пакет Semantic-release {#пакет-semantic-release}

Пакет [Semantic-release]({{< relref "2021-01-15-semantic-versioning-semantic-release" >}})
автоматизирует весь рабочий процесс выпуска программного пакета.


### <span class="section-num">2.2</span> Пакет Conventional Changelog {#пакет-conventional-changelog}

Пакет [Conventional Changelog]({{< relref "2021-01-16-semantic-versioning-conventional-changelog" >}}) является комплексным решением по управлению коммитами и генерации журнала изменений.
Он содержит набор утилит, которые можно использовать по-отдельности.


## <span class="section-num">3</span> Backlinks {#backlinks}

-   [Система контроля версий git]({{< relref "2020-12-07-git-cvs" >}})

<!--listend-->

-   [Общепринятые коммиты]({{< relref "2020-12-11-conventional-commits" >}})

<!--listend-->

-   [Практический сценарий использования git]({{< relref "2021-01-17-git-practical-use-case" >}})
