# JavaDeveloper

Материалы для собеседования на позицию java developer.

<!--ts-->
<!--te-->

## Общие вопросы

#### Если нажать поиск в гугл, что происходит под капотом?
<details><summary markdown="span">Ответ</summary>

ToDo: развернутый большой ответ

</details>

---

#### Расскажите про клиент-серверную архитектуру
ToDo: небольшой ответ (поэтому без details)

---

#### Что такое xml, как он связан с xsd?
ToDo: небольшой ответ (поэтому без details)

---

#### Чем удобен json, есть ли у него инструменты для проведения валидации?
ToDo: ответ

---

#### Что такое сериализация и десериализация?
ToDo: ответ

---

#### Какие знаете http методы? какие из них персистентные?
ToDo: ответ

---

#### Зачем нужны куки?
ToDo: ответ

---

#### Чем аутентификация отличается от идентификации?
ToDo: ответ

---

#### REST vs SOAP
ToDo: ответ

---

#### RESTful api и JSON-pure api в чем отличие?
ToDo: ответ

---

#### Расскажите про CRUD
ToDo: ответ

---

#### Как согласно CAP теореме я должен выбирать элементы для фронт и бэк систем (Базы данных, системы резервирования и проч)?
ToDo: ответ

---

## Сервера приложений

#### Чем сервер приложений отличается от web сервера?
ToDo: ответ

---

#### Какие упрощения для приложения предоставляет app server?
ToDo: ответ

---

#### Вам нужно настроить TLS в вашем приложении. Какие есть способы реализации этого, если приложение установлено не standalone?
ToDo: ответ

---

#### Чем отличается jar от war?
ToDo: ответ

---

#### Зачем нужен в общем случае кластер WAS? могу ли я использовать кластер для распределения нагрузки?
ToDo: ответ

---

## Java EE

#### Назовите принципы ООП (с примерами)
ToDo: ответ

---

#### Расскажите про String пул
ToDo: ответ

---

#### Что будет если вызвать intern от сроки, которой еще нет в пуле?
ToDo: ответ

---

#### Что хранится в стеке, а что в хипе?
ToDo: ответ

---
#### Расскажите, как работает GC
ToDo: ответ

---

#### Назовите методы класса Object
ToDo: ответ

---

#### Расскажите про принципы happens before
ToDo: ответ

---

#### Как я могу создать поток?
ToDo: ответ

---

#### Что такое thread-safe?
ToDo: ответ

---

#### Будет ли ошибка, если вызвать wait не из блока synchronize?
ToDo: ответ

---

#### Использовали ли Вы что-то из пакета java.concurrent.atomic?
ToDo: ответ

---

#### Что такое оптимистичная блокировка?
ToDo: ответ

---

#### Расскажите про synchronize блоки и методы, чем отличаются? Что такое монитор?
ToDo: ответ

---

#### Как я могу пустить не один поток в синхронизированный блок, а например не больше пяти?
ToDo: ответ

---

#### Влияет ли как то volatile на оптимизации, выполняемые JVM?
ToDo: ответ

---

#### Назовите concurrent коллекцию. Как осущестляется расспаралеливание в ConcurrentHashMap?
ToDo: ответ

---

#### Что такое live lock и deadlock
ToDo: ответ

---

#### Расскажите про структуру исключений. Что значит обрабатываемые и необрабатываемые исключения?
ToDo: ответ

---

#### Могу ли я создавать свои исключения?
ToDo: ответ

---

#### Как в коде мне получить StackOverflow и OutOfMemory намеренно?
ToDo: ответ

---


## Коллекции

####  Какие существуют коллекции?
ToDo: ответ

---

#### Какую коллекцию мне нужно использовать для хранения отсортированного набора данных?
ToDo: ответ

---

#### Каким образом мы понимаем, в какой бакет положить элемент в HashMap?
ToDo: ответ

---

#### Что будет, если в один бакет попали элементы equals которых вернул true. Перезапишется ключ или значение? Останется старое value или новое?
ToDo: ответ

---

#### Что лучше ArrayList или LinkedList, если мне нужно будет в большой массив вставлять много элементов в середину?
ToDo: ответ

---

#### У array copy стоит нотация native, что значит эта нотация?
ToDo: ответ

---

#### Какие есть способы пройтись по коллекции?
ToDo: ответ

---

#### Что такое функциональный интерфейс? В чем его основное назначение?
ToDo: ответ

---

#### Сколько может быть терминальных операторов внутри стрима?
ToDo: ответ

---

#### Что внутри парралел стрима?
ToDo: ответ

---

#### Сколько тредов внутри парралел стрима по умолчанию? Могу ли я как-то сам задать их количество?
ToDo: ответ

---

## реактивное программирование
расскажите что такое проблема 10к и как реактивное программирование позволяет ее решить
почему получить ддос легче именно на реакте
можно ли анализировать ошибки по стектрейсу в реактивном приложении
у меня небольшой веб сервер со сложной логикой на бэке. запрос в среднем занимет 100мс.
При нагрузке 1к запросов в секунду есть ли мне смысл переписывать свое приложение под реакт?
какой есть у спринг модуль для реактива
что общего у SEDA архитектуры и AKKA

## паттерны разработки
какие существуют типы паттернов
чем отличается абстрактная фабрика от фабричного метода
почему синглтон считается антипаттерном
назовите примеры паттернов которые недавно использовали и какие были задачи
расскажите про паттерн сага
какие паттерны использует спринг?

## архитектура

DDD. Расскажите в чем основная суть подхода
принцип CQRS в чем состоит
Clean Architecture
onion architecture
screaming architecture
SOA архитектура
SEDA архитектура
монолиит, микросервисы и сервисмеш
SOLID
принцип KISS, DRY

spring
чем отличается DI от IoC
расскажите про propagation (распространение транзакций)
сколько существует уровней изоляции транзакций
скоупы бинов
опишите цикл жизни бина
выполнится предестрой у прототайп бина?
как я могу изменить бин перед помещением его в контейнер не изменяя код класса
где я могу ставить аннотацию autowired
в чем преимущество спринг для тестирования
чем мок отличается от spy

в чем преимущество spring boot

что будет результатом работы стартера?
чем лучше java 11 перед 8 для контейнеров
расскажите зачем применяется аннотация Conditional

работали ли с какими нибудь ORM?
расскажите сколько существует уровней кэширования?
могу как то я сказать JVM что этот объект нужно кэшировать?
какие знаете стратегии кэширования?
может быть с какими то сложными ошибками сталкивались в работе?
что такое уровни кэширования

## DevOps
#### Какими системами сборками пользовались?
ToDo: ответ

---

#### Отличие CI от CD
ToDo: ответ

---

#### Отличие Jenkins от Teamcity
ToDo: ответ

---

#### Что такое pipeline в jenkins
ToDo: ответ

---

#### Все ли груви фичи мне доступны в pipline дженкинса? могу ли я запретить опасные методы?
ToDo: ответ

---

#### Что такое Jenkins Node и как они используются
ToDo: ответ

---

#### Могу ли я скрипт сборки хранить в Git
ToDo: ответ

---

#### Про какие системы управления конфигурации слышал (ansible, puppet, chef)
ToDo: ответ

---

## Git
#### Зачем нужна система контроля версий?
ToDo: ответ

---

#### Какие есть основные операции в Git?
ToDo: ответ

---

#### Как появляются конфликты merge?
ToDo: ответ

---

#### Что такое gitflow?
ToDo: ответ

---


## Контейнеры и микросервисы
#### Зачем нужен Dockerfile
ToDo: ответ

---

#### Отличие виртуализации от контейнеризации
ToDo: ответ

---

#### Какие инструменты для оркестрации контейнеров использовали. Зачем они нужны?
ToDo: ответ

---

#### Сколько запускается рутовых процессов если я на linux-машине разворачиваю 3 контейнера?
ToDo: ответ

---

#### Что такое Istio и зачем он нужен?
ToDo: ответ

---

#### Что такое Service, Route, Pod?
ToDo: ответ

---

#### Зачем нужен replica set?
ToDo: ответ

---

#### У меня есть новая версия приложения, возможно с багами, я хочу только 10% нагрузки передать на новую версию, что мне делать?
ToDo: ответ

---

#### Мне нужно закрыть обмен между микросервисами tls. Как я могу это реализовать?
ToDo: ответ

---


## БД
#### Какие существуют нормальные формы?
ToDo: ответ

---

#### Какие существуют индексы?
ToDo: ответ

---

#### Почему нельзя перегружать таблицу индексами?
ToDo: ответ

---

#### Что такое транзакции?
ToDo: ответ

---

#### Какие существуют уровни изоляции транзакций?
ToDo: ответ

---

#### Что такое фантомное чтение?
ToDo: ответ

---


ToDo: нужно добавить что-то по нерелеационным бд

## Сети
#### Чем tcp отличается от udp?
ToDo: ответ

---

#### Чем отличается multicast от broadcast?
ToDo: ответ

---

#### Уровни модели OSI
ToDo: ответ

---

#### Балансировщик имеет маркировку L4 и L7, какой мне нужно использовать если я хочу терминировать ssl трафик через балансировщик?
ToDo: ответ

---

#### Расскажите про tcp back pressure
ToDo: ответ

---


## Linux
#### Что такое рут и почему опасно сидеть под ним?
ToDo: ответ

---

#### Как убить процесс?
ToDo: ответ

---

#### Как отобразить содержимое каталога?
ToDo: ответ

---

#### Что за команда nohup?
ToDo: ответ

---

#### В чем смысл команды chmod +x file и chmod 777 file?
ToDo: ответ

---

#### Нужно посмотреть какие коннекты открыты до определенного хоста в настоящий момент. Как это сделать?
ToDo: ответ

---

#### Что такое crontab и для чего используется?
ToDo: ответ

---


## MQ, kafka
расскажите про kafka. Что используется для управления кластером кафки
как я могу получить splitBrain в кафке?
расскажите про zero copy. Какие есть требования к передаваемым данным, что бы мы могли ускорить передачу с использованием zero copy
что произойдет если продьюсер отправит данные в топик, который в кластере не существует (с настройками по умолчанию).
в топике несколько партиций. продьюсер пишет сразу во все. Как будет читать данные консумер?

работали ли с MQ.
что такое кластерная очередь?
если из одной очереди читает сразу много потребителей, как я могу обеспечить корректную работу очереди?
потребитель не умеет работать с заголовками, а нам нужно заголовки сохранить и вернуть скоррелированный и обогащенный заголовками ответ. Могу ли я это сделать?
расскажите в чем роль брокера? какие я на нем действия могу сделать?
мне нужно на одном менеджере разграничить права для разных потребителей (разные наборы очередей) и закрыть все это тлс. Умеет ли это WebSphrere MQ?

## процесс
работали ли в эджайле? расскажите есть ли у вас негативный или наоборот позитивный опыт
что такое спринт, история, эпик, таска?
кто решает что в спринт берет команда?
что должно быть итогом спринта?
что такое планирование и демо?