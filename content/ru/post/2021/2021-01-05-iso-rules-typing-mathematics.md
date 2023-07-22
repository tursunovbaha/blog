---
title: "Правила ISO для набора математики"
date: 2021-01-05T14:59:00+03:00
lastmod: 2021-01-11T14:31:00+03:00
tags: ["science", "tex"]
categories: ["сиянс"]
draft: false
slug: "iso-rules-typing-mathematics"
---

При наборе математики следует придерживаться стандартов.

<!--more-->

{{< toc >}}


## Введение {#введение}

Нормы ISO представляют собой строгие правила набора математических
данных в областях физики и прикладных наук.

Стандарты:

-   ISO 31-11:1992.
    -   <https://en.wikipedia.org/wiki/ISO%5F31-11>
-   ISO 80000-2:2009
    -   <https://en.wikipedia.org/wiki/ISO/IEC%5F80000>
-   ISO 80000-2:2019


## Краткое описание {#краткое-описание}

Слово «количество» используется для обозначения любого физического
объекта, который может быть измерен в соответствии с
метрологической практикой, слово «переменная» используется для
обозначения математической сущности, представляющей переменные
данные.

-   Переменные обозначаются одной буквой, использование аббревиатур не
    допускается (в программировании идентификаторы называются
    переменными в том смысле, что они могут представлять переменные
    данные, но компьютерные программы - это не математика). К сожалению,
    некоторые аббревиатуры получили широкую популярность и широкое
    распространение, но они запрещены правилами ISO (например: CMRR
    часто используется для обозначения «коэффициента подавления
    синфазного сигнала», но это неправильное использование математики).
-   Все символы количества должны быть выделены курсивом, наклонный
    шрифт разрешён, но курсив с засечками должен быть предпочтительнее,
    если правила ISO не предписывают шрифт без засечек. Это означает,
    что символ дифференциала \\(\mathrm{d}\\) должен быть набран прямым шрифтом, чтобы
    избежать путаницы с физической величиной \\(d\\); число \\(\mathrm{e}\\) должно
    быть набрано прямым шрифтом, чтобы не путать с элементарным
    электрическим зарядом \\(e\\); мнимая единица \\(\mathrm{j}\\) в электротехнике (\\(\mathrm{i}\\) в
    других прикладных науках) должна быть записана прямым шрифтом,
    чтобы избежать путаницы с плотностью электрического тока \\(j\\) или
    электрическим током \\(i\\); трансцендентное число π =
    3,14159… следует отличать от угла π и т.д.
-   Все символы, которые не представляют количества, должны быть набраны
    прямым шрифтом, желательно шрифтом с засечками, за исключением
    случаев, когда правила ISO требуют шрифта без засечек. Это правило
    включает числа и их цифры, символы, представляющие постоянные
    числовые значения. Сопоставления не являются величинами или переменными:
    например, в выражении \\(V\_i\\) индекс \\(i\\) является переменной, потому что он
    представляет \\(i\\)-й элемент в последовательности, такой как \\(V\_0\\), \\(V\_1\\),
    \\(V\_2\\),… ; напротив, если нижний индекс является дополнением, например
    «i» означает «input», то он пишется в прямом начертании: \\(V\_\mathrm{i}\\).
-   Полужирным курсивом обозначаются матрицы; матрицы из одного столбца
    представляют собой векторы и должны
    рассматриваться как любая другая матрица. Как правило, многострочные
    и многоколоночные матрицы набираются прописными буквами, а строчные
    зарезервированы для векторов, но в некоторых науках векторы могут
    обозначаться заглавными буквами. Геометрические векторы, которые
    набираются с помощью курсивных букв верхнего или нижнего регистра
    со стрелкой наверху, не рассматриваются правилами ISO.
-   Надписи к геометрическим объектам, таким как точки, сегменты, углы
    (не их размеры), должны быть сделаны шрифтами без засечек. То же
    правило применяется к подписям, используемым в эскизах и чертежах,
    представляющих механизмы, электрические схемы и тому подобное, когда
    подпись относится к объекту, а не к его размеру.
-   Тензоры следует набирать наклонным полужирным шрифтом без засечек.


## Программное обеспечение {#программное-обеспечение}


### LaTeX {#latex}


#### pdfLaTeX {#pdflatex}

-   PM-ISOmath (The Poor Man ISO math bundle)
    -   <https://www.ctan.org/pkg/pm-isomath>
-   isomath – Mathematics style for science and technology
    -   <https://www.ctan.org/pkg/isomath>


#### XeLaTeX и LuaLaTeX {#xelatex-и-lualatex}

-   unicode-math – Unicode mathematics support for XeTeX and LuaTeX
    -   <https://ctan.org/pkg/unicode-math>