---
title: "Курс МОЗИиИБ. Основные понятия информационной безопасности"
date: 2021-02-24T12:49:00+03:00
lastmod: 2021-03-15T17:11:00+03:00
draft: false
weight: 101
toc: true
type: "book"
summary: "Основные понятия информационной безопасности"
slug: "course-mathsec-basic-concepts"
menu:
  mathsec:
    identifier: "курс-мозиииб-dot-основные-понятия-информационной-безопасности"
    parent: "mathsec-lections"
    weight: 101
---

Лекция. Основные понятия информационной безопасности

<!--more-->


## <span class="section-num">1</span> Цели информационной безопасности {#цели-информационной-безопасности}


### <span class="section-num">1.1</span> Основные цели информационной безопасности {#основные-цели-информационной-безопасности}

-   Конфиденциальность
-   Целостность
-   Работоспособность


### <span class="section-num">1.2</span> Конфиденциальность {#конфиденциальность}

-   Самый общий аспект информационной безопасности.
-   Необходимо защитить нашу конфиденциальную информацию.
-   В военных организациях важно сохранение секретности важной информации.
-   В промышленности важно сохранение информации от конкурентов.
-   Необходимо сохраняться секретность учётных записей клиентов.
-   Необходима при хранении информации.
-   Необходима при передаче информации.


### <span class="section-num">1.3</span> Целостность {#целостность}

-   Информация изменяется постоянно.
-   Изменения должны быть сделаны только разрешёнными объектами и с помощью разрешённых механизмов.
-   Нарушение целостности --- не обязательно результат злонамеренного действия.


### <span class="section-num">1.4</span> Работоспособность {#работоспособность}

-   Информация должна быть доступна разрешённым объектам.
-   Информация бесполезна, если она не доступна.


## <span class="section-num">2</span> Виды атак на информацию {#виды-атак-на-информацию}


### <span class="section-num">2.1</span> Атаки, угрожающие конфиденциальности {#атаки-угрожающие-конфиденциальности}


#### <span class="section-num">2.1.1</span> Вмешательство {#вмешательство}

-   Неправомочный доступ или перехват данных.
-   Для предотвращения вмешательства данные должны быть представлены так, что перехвативший не сможет понять их.
-   Использование шифрования для предотвращения вмешательства.


#### <span class="section-num">2.1.2</span> Наблюдение за трафиком и его анализ {#наблюдение-за-трафиком-и-его-анализ}

-   Анализируя сетевой трафик, можно получить дополнительную информацию.
-   Часть информации открыта.
-   Статистические данные, связанные с перехватываемой информацией.


### <span class="section-num">2.2</span> Атаки, угрожающие целостности {#атаки-угрожающие-целостности}


#### <span class="section-num">2.2.1</span> Модификация {#модификация}

-   После прерывания или доступа к информации атакующий изменяет информацию.


#### <span class="section-num">2.2.2</span> Имитация источника (spoofing) {#имитация-источника--spoofing}

-   Имитация кого-то, кто имеет право на производимые действия.
-   Имитация приёмника.


#### <span class="section-num">2.2.3</span> Повторная передача информации (атака воспроизведения) {#повторная-передача-информации--атака-воспроизведения}

-   Атакующий получает копию сообщения и передает эту копию с целью дезорганизации процесса или попытки повторить его.


#### <span class="section-num">2.2.4</span> Отказ от сообщения {#отказ-от-сообщения}

-   Передатчик сообщения может отрицать факт передачи.
-   Приёмник сообщения может отрицать, что он получил сообщение.


### <span class="section-num">2.3</span> Атаки, угрожающие работоспособности {#атаки-угрожающие-работоспособности}


#### <span class="section-num">2.3.1</span> Отказ в обслуживании (Denial of Service --- DoS) {#отказ-в-обслуживании--denial-of-service-dos}

-   Атака на сервер.
    -   Перегрузка сервера фиктивными запросами.
    -   Прерывание запросов клиента. Клиент увеличивает количество запросов.
-   Атака на клиент.
    -   Удаление ответа сервера. Клиент считает, что сервер не отвечает.
    -   Прерывание запросов клиента. Клиент считает, что сервер не отвечает.


### <span class="section-num">2.4</span> Типы атак {#типы-атак}


#### <span class="section-num">2.4.1</span> Пассивные атаки {#пассивные-атаки}

-   Цель атакующего состоит в том, чтобы только получить информацию.


#### <span class="section-num">2.4.2</span> Активные атаки {#активные-атаки}

-   Изменяют данные или повреждают систему.


### <span class="section-num">2.5</span> Классификация атак {#классификация-атак}

| Атака                         | Тип атаки | Угроза             |
|-------------------------------|-----------|--------------------|
| Вмешательство                 | Пассивная | Конфиденциальности |
| Анализ трафика                | Пассивная | Конфиденциальности |
| Модификация                   | Активная  | Целостности        |
| Имитация источника            | Активная  | Целостности        |
| Повторная передача информации | Активная  | Целостности        |
| Отказ от сообщения            | Активная  | Целостности        |
| Отказ в обслуживании          | Активная  | Работоспособности  |


## <span class="section-num">3</span> Услуги информационной безопасности {#услуги-информационной-безопасности}


### <span class="section-num">3.1</span> Услуги информационной безопасности ITU-T {#услуги-информационной-безопасности-itu-t}

ITU-T (X.800) определил пять услуг, связанных с целями информационной безопасности.

-   Конфиденциальность данных
-   Целостность данных
-   Установление подлинности (аутентификация)
-   Исключение отказа от сообщений
-   Управление доступом


### <span class="section-num">3.2</span> Конфиденциальность данных {#конфиденциальность-данных}

-   Защита данные от попытки их раскрытия.
-   Охватывает:
    -   конфиденциальность целого сообщения;
    -   конфиденциальность части сообщения;
    -   защищает от наблюдения за трафиком и анализа трафика.


### <span class="section-num">3.3</span> Целостность данных {#целостность-данных}

-   Защита данных от
    -   модификации,
    -   вставки,
    -   удаления,
    -   повторной передачи.
-   Может защищать целое сообщение или часть сообщения.


### <span class="section-num">3.4</span> Установление подлинности (аутентификация) {#установление-подлинности--аутентификация}

-   Установление подлинности (аутентификацию) оператора на другом конце линии.
-   Установление подлинности передатчика или приёмника в течение установления соединения (установление подлинности объектов равного уровня).
-   Установление подлинности источника данных (установление подлинности происхождения данных).


### <span class="section-num">3.5</span> Исключение отказа от сообщений {#исключение-отказа-от-сообщений}

-   Защищает от отказа от сообщения передатчиком или приёмником данных.
-   Приёмник может доказать происхождение сообщения, используя идентификатор передатчика.
-   Передатчик для доказательства использует подтверждение доставки.


### <span class="section-num">3.6</span> Управление доступом {#управление-доступом}

-   Защита против неправомочного доступа к данным.
-   Доступ включает в себя:
    -   чтение,
    -   запись,
    -   изменение данных,
    -   запуск на выполнение,
    -   и др.


## <span class="section-num">4</span> Механизмы информационной безопасности {#механизмы-информационной-безопасности}


### <span class="section-num">4.1</span> Механизмы безопасности {#механизмы-безопасности}

-   Шифрование
-   Целостность данных
-   Цифровая подпись
-   Обмен сообщениями для опознавания
-   Заполнение трафика
-   Управление маршрутизацией
-   Доверенность
-   Управление доступом


### <span class="section-num">4.2</span> Шифрование {#шифрование}

-   Гарантирует конфиденциальность.
-   Два **метода**: криптография и стеганография.


### <span class="section-num">4.3</span> Целостность данных {#целостность-данных}

-   Добавка в конце данных короткий контрольный признак (check value).
-   Контрольный признак создаётся отдельно от данных.
-   Приёмник получает данные и контрольный признак:
    -   создаёт новый контрольный признак;
    -   сравнивает только что созданный контрольный признак с полученным;
    -   если эти два контрольных признака совпадают, целостность данных была сохранена.


### <span class="section-num">4.4</span> Цифровая подпись {#цифровая-подпись}

-   Отправитель может подписать данные.
-   Приёмник может проверить подпись.


### <span class="section-num">4.5</span> Обмен сообщениями для опознавания {#обмен-сообщениями-для-опознавания}

-   Два объекта обмениваются некоторыми сообщениями, чтобы доказать, что эти объекты известны друг другу.


### <span class="section-num">4.6</span> Заполнение трафика {#заполнение-трафика}

-   Возможность вставлять в трафик данных некоторые фиктивные данные, чтобы сорвать попытки злоумышленников использовать его для анализа.


### <span class="section-num">4.7</span> Управление маршрутизацией {#управление-маршрутизацией}

-   Выбор и непрерывное изменение различных доступных маршрутов между отправителем и приёмником для того, чтобы препятствовать противнику в перехвате информации на определённом маршруте.


### <span class="section-num">4.8</span> Доверенность {#доверенность}

-   Выбор третьей стороны с целью доверить ей контроль обменом между двумя объектами.


### <span class="section-num">4.9</span> Управление доступом {#управление-доступом}

-   Доказывает, что пользователь имеет право доступа к данным:
    -   пароль,
    -   PIN-код,
    -   и др.


### <span class="section-num">4.10</span> Соотношение между услугами и механизмами {#соотношение-между-услугами-и-механизмами}

| Услуга безопасности            | Механизм обеспечения безопасности                                     |
|--------------------------------|-----------------------------------------------------------------------|
| Конфиденциальность данных      | Шифрование и управление маршрутизацией                                |
| Целостность данных             | Шифрование, цифровая подпись, контрольные признаки целостности данных |
| Проверка полномочий            | Шифрование, цифровая подпись, установление правомочности изменений    |
| Исключение отказа от сообщений | Цифровая подпись, целостность данных и доверенность                   |
| Управление доступом            | Механизм управления доступом                                          |


## <span class="section-num">5</span> Методы информационной безопасности {#методы-информационной-безопасности}


### <span class="section-num">5.1</span> Шифрование {#шифрование}


#### <span class="section-num">5.1.1</span> Два метода шифрования для реализации механизма безопасности: {#два-метода-шифрования-для-реализации-механизма-безопасности}

-   Криптография
-   Стеганография


### <span class="section-num">5.2</span> Криптография {#криптография}


#### <span class="section-num">5.2.1</span> Значение термина {#значение-термина}

-   Криптография  (от греч. κρυπτός «скрытый» + γράφω «пишу»).


#### <span class="section-num">5.2.2</span> Механизмы криптографии {#механизмы-криптографии}

-   Совокупность трёх механизмов:
    -   шифрование симметричными ключами,
    -   шифрование асимметричными ключами,
    -   хеширование.


#### <span class="section-num">5.2.3</span> Шифрование симметричными ключами {#шифрование-симметричными-ключами}

-   Шифрование c секретным ключом (криптография с секретным ключом).
-   Применяется единственный ключ засекречивания и для шифрования, и для расшифровки.


#### <span class="section-num">5.2.4</span> Шифрование асимметричными ключами {#шифрование-асимметричными-ключами}

-   Шифрование асимметричными ключами (шифрование с открытыми ключами, криптография с открытыми ключами).
-   Два ключа вместо одного:
    -   открытый ключ (public key),
    -   индивидуальный или секретный (private key).


#### <span class="section-num">5.2.5</span> Хеширование {#хеширование}

-   Из сообщения переменной длины может быть создан дайджест фиксированной длины (обычно намного меньшего размера, чем исходное сообщение).


### <span class="section-num">5.3</span> Стеганография {#стеганография}


#### <span class="section-num">5.3.1</span> Значение термина {#значение-термина}

-   Стеганография (от греч. στεγανός «скрытый» + γράφω «пишу»; букв. «тайнопись»).


#### <span class="section-num">5.3.2</span> Криптография vs. стеганография {#криптография-vs-dot-стеганография}

-   Криптография защищает содержание сообщения.
-   Стеганография защищает сам факт наличия каких-либо скрытых посланий.


## <span class="section-num">6</span> Резюме {#резюме}


### <span class="section-num">6.1</span> Резюме {#резюме}

-   Для информационной безопасности были определены три главные цели:
    -   конфиденциальность,
    -   целостность,
    -   работоспособность.

-   Конфиденциальности информации угрожают два типа атак:
    -   вмешательство,
    -   анализ трафика.

-   Целостности информации угрожают четыре типа атак:
    -   модификация,
    -   имитация источника,
    -   повторная передача информации,
    -   отказ от сообщения.

-   Работоспособности информации угрожает атака:
    -   прекращение обслуживания запроса.

-   ITU-T определил несколько услуг информационной безопасности:
    -   конфиденциальность данных,
    -   целостность данных,
    -   установление подлинности,
    -   исключение отказа от сообщений,
    -   управление доступом.

-   ITU-T рекомендует механизмы обеспечения безопасности:
    -   шифрование,
    -   целостность данных,
    -   цифровая подпись,
    -   установление правомочности изменений,
    -   заполнение трафика,
    -   управление маршрутизацией,
    -   доверенность,
    -   управление доступом.

-   Два метода защиты информации:
    -   криптография,
    -   стеганография.


## <span class="section-num">7</span> Контрольные вопросы {#контрольные-вопросы}


### <span class="section-num">7.1</span> Контрольные вопросы {#контрольные-вопросы}

1.  Определите три цели безопасности.
2.  Укажите различие между пассивными и активными атаками на секретную информацию.
3.  Назовите некоторые пассивные атаки.
4.  Назовите некоторые активные атаки.
5.  Перечислите и определите пять служб безопасности.
6.  Перечислите и определите восемь механизмов безопасности.
7.  Укажите различие между шифрованием и стеганографией.


## <span class="section-num">8</span> Видео к лекции {#видео-к-лекции}


### <span class="section-num">8.1</span> Цели информационной безопасности {#цели-информационной-безопасности}

{{< youtube lCDWTC3cFZ4 >}}


### <span class="section-num">8.2</span> Услуги и механизмы информационной безопасности {#услуги-и-механизмы-информационной-безопасности}

{{< youtube bRFw1RRD0DE >}}


## <span class="section-num">9</span> Backlinks {#backlinks}

-   [Курс МОЗИиИБ. Лекции]({{< relref "2021-03-11-course-mathsec-lections" >}})