<div align="center">
  <img width="325" height="281" src="https://github.com/goavengers/go-interview/blob/master/img/go-inter.jpeg">
  <h1>Вопросы и ответы для собеседования Back-end/Golang разработчика и не только</h1>
  <h5>Вместе мы разберемся!</h5>
</div>

Здесь собирается большая коллекция вопросов и ответов на них, необходимых не только для прохождения собеседований, но и для комплексного развития кругозора

## Содержание

0. [Разогрев](docs/what_is_going_on)
1. [Общие вопросы](docs/common)
    - [В чем отличие протоколов TCP и UDP? В каком случае UDP предпочтительнее?](docs/common#1-в-чем-отличие-протоколов-tcp-и-udp-в-каком-случае-udp-предпочтительнее)
    - [Что такое NAT?](docs/common#2-что-такое-nat)
    - [Что такое HTTP и HTTPS, в чем их отличия?](docs/common#3-что-такое-http-и-https-в-чем-их-отличия)
    - [Что такое SSL и TLS, есть ли между ними отличия?](docs/common#4-что-такое-ssl-и-tls-есть-ли-между-ними-отличия)
    - coming soon
2. [Вопросы по шаблонам проектирования](docs/design_patterns)
    - С какими паттернами проектирования знакомы?
    - Расскажите про паттерны Builder(Строитель), Factory(Фабрика), Closer(Доводчик), Singleton(Одиночка)
    - Расскажите, какой паттерн использовали в продукте/своем коде?
    - Знакомы ли с концепцией [12FA](https://12factor.net/ru/) для проектирования SaaS приложений? 
3. [Вопросы про микросервисы](docs/microservices)
    - [Что такое микросервисная архитектура? (кратко)](docs/microservices/README.md#что-такое-микросервисная-архитектура-кратко)
    - [Чем отличается микросервис от монолита?](docs/microservices/README.md#чем-отличается-микросервис-от-монолита)
    - [Опишите плюсы и минусы двух концепций](docs/microservices/README.md#опишите-плюсы-и-минусы-двух-концепций)
4. [Вопросы про инфраструктуру и деплой](docs/infrastructure_and_deploy)
    - [Что такое сине-зеленый деплой(blue-green deployment)?](docs/infrastructure_and_deploy/README.md#что-такое-сине-зеленый-деплойblue-green-deployment)
    - [Что такое Canary (канареечные развертывания)?](docs/infrastructure_and_deploy/README.md#2-что-такое-canary-канареечные-развертывания)
    - [Что такое Dark (скрытые) или А/В-развертывания?](docs/infrastructure_and_deploy/README.md#что-такое-dark-скрытые-или-ав-развертывания)
    - [Что такое SLA, SLO, SLI?](docs/infrastructure_and_deploy/README.md#что-такое-sla-slo-sli)
    - [Какие инструменты CI/CD вам известны?](docs/infrastructure_and_deploy/README.md#какие-инструменты-cicd-вам-известны)
    - [Как обеспечить непрерывность и стабильность деплоя приложения?](docs/infrastructure_and_deploy/README.md#как-обеспечить-непрерывность-и-стабильность-деплоя-приложения)
    - [С какими проблемами при деплое продукта вы сталкивались, как митигировали?](docs/infrastructure_and_deploy/README.md#с-какими-проблемами-при-деплое-продукта-вы-сталкивались-как-митигировали)
5. [Вопросы про кеширование и базам данных](docs/cache_and_db)
    - [Что такое индексы в MySQL, как и для чего их использовать и создавать?](docs/cache_and_db/README.md#что-такое-индексы-в-mysql-как-и-для-чего-их-использовать-и-создавать)
    - [Что такое составной индекс, как и для чего их использовать и создавать?](docs/cache_and_db/README.md#что-такое-составной-индекс-как-и-для-чего-их-использовать-и-создавать)
    - [Как использовать индексы в JOIN запросах Mysql?](docs/cache_and_db/README.md#как-использовать-индексы-в-join-запросах-mysql)
    - [Что такое частичные индексы, как и для чего их использовать и создавать?](docs/cache_and_db/README.md#что-такое-частичные-индексы-как-и-для-чего-их-использовать-и-создавать)
    - [В чем отличия InnoDB и MyISAM?](docs/cache_and_db/README.md#в-чем-отличия-innodb-и-myisam)
    - [Возможен ли JOIN со вложенными запросами, как?](docs/cache_and_db/README.md#возможен-ли-join-со-вложенными-запросами-как)
    - [Что такое дедлоки (deadlock), почему возникают, как можно недопускать?](docs/cache_and_db/README.md#что-такое-дедлоки-deadlock-почему-возникают-как-можно-недопускать)
    - [Что такое HAVING, что он делает как и зачем его использовать?](docs/cache_and_db/README.md#что-такое-having-что-он-делает-как-и-зачем-его-использовать)
    - [Разница между WHERE и HAVING и можно ли использовать HAVING без группировки данных?](docs/cache_and_db/README.md#разница-между-where-и-having-и-можно-ли-использовать-having-без-группировки-данных)
    - [Что такое EXPLAIN?](docs/cache_and_db/README.md#что-такое-explain)
    - [Как узнать версию Mysql?](docs/cache_and_db/README.md#как-узнать-версию-mysql)
    - [Как можно оптимизировать ORDER BY RAND()?](docs/cache_and_db/README.md#как-можно-оптимизировать-order-by-rand)
    - Как правильно выбрать тип данных в Mysql, когда нужны:
      - [NULL значения, когда лучше использовать?](docs/cache_and_db/README.md#null-значения-когда-лучше-использовать)
      - [Целые числа (TINYINT, SMALLINT, INT, BIGINT) и UNSIGNED, длинна числовых типов?](docs/cache_and_db/README.md#целые-числа-tinyint-smallint-int-bigint-и-unsigned-длинна-числовых-типов)
      - [Большие числа: demical, что это и как работает?](docs/cache_and_db/README.md#большие-числа-demical-что-это-и-как-работает)
      - [Float | Double VS Demical, в чем разница, что и как использовать?](docs/cache_and_db/README.md#float--double-vs-demical-в-чем-разница-что-и-как-использовать)
      - [Строки VARCHAR и CHAR, отличия когда лучше использовать?](docs/cache_and_db/README.md#строки-varchar-и-char-отличия-когда-лучше-использовать)
      - [BLOB / TEXT, чем отличаются, как выполнять сортировку по полям данного типа?](docs/cache_and_db/README.md#blob--text-чем-отличаются-как-выполнять-сортировку-по-полям-данного-типа)
      - [ENUM, когда может пригодится?](docs/cache_and_db/README.md#enum-когда-может-пригодится)
      - [DATETIME / TIMESTAMP, в чем их разница, какие максимальные значения?](docs/cache_and_db/README.md#datetime--timestamp-в-чем-их-разница-какие-максимальные-значения)
    - [Когда и зачем может пригодиться денормализация данных?](docs/cache_and_db/README.md#когда-и-зачем-может-пригодиться-денормализация-данных)
    - [Что такое шардинг и репликация?](docs/cache_and_db/README.md#что-такое-шардинг-и-репликация)
    - [В чем отличие синхронной репликации от асинхронной? Какая подходит лучше для какого кейса?](docs/cache_and_db/README.md#в-чем-отличие-синхронной-репликации-от-асинхронной-какая-подходит-лучше-для-какого-кейса)
    - [Если индекс создан для 2-х колонок и запрос содержит только одну из них - будет ли он работать?](docs/cache_and_db/README.md#если-индекс-создан-для-2-х-колонок-и-запрос-содержит-только-одну-из-них---будет-ли-он-работать)
6. [Вопросы по языку Golang](docs/golang)
    - [Что из себя представляет тип данных string в языке Golang? Можно ли изменить определенный символ в строке? Что происходит при склеивании строк?](docs/golang#1)
    - [Вытекающий вопрос — как эффективно склеивать множество строк?](docs/golang#2)
    - Что будет происходить при конкурентной записи в map? Как можно решить эту проблему?
    - Расскажите о ООП в Golang.#1
    - [Какое будет значение у переменной x после выполнения программы?](docs/golang#12)
    - [Какое значение примет выражение (true && false) || (false && true) || !(false && false)?](docs/golang#13)
    - [Мы знаем, что в десятичной системе самое большое число из одной цифры - это 9, а из двух - 99. В бинарной системе самое большое число из двух цифр это 11 (3), самое большое число из трех цифр это 111 (7) и самое большое число из 4 цифр это 1111 (15). Вопрос: каково самое большое число из 8 цифр? (Подсказка: 101-1=9 и 102-1=99)](docs/golang#14)
    - [Что выведет следующая программа?](docs/golang#15)
    - [Что выведет следующая программа?](docs/golang#16)
    - [Как работает Garbage Collection в Go?](docs/golang#17)
    - Что такое interface, как они работают в Go?
    - Что такое slice, как устроены и чем отличаются от массивов?
    - Что такое len и capacity в slice Go?
    - Возможно ли предугадать, что GC отработает за константное время N?
    - Что будет, если создать канал и отправить туда запись, но у него нет читателей?
    - По какому алгоритму растет slice? (если знаете старую и новую формулу - круто)
    - Сколько весят такие структуры данных, как слайс, мапа, пустая строка, число в байтах?
    - В какой момент инициализированное значение переменной передается в defer? Как это связано с именованием функции?
7. [Вопросы о распределённых системах](docs/distributed_systems)
    - Как тестировать распределённую систему?
    - Знакомы ли с lock-free концепцией? Можете описать принцип работы?
8. [Вопросы по организации кода](docs/code_design)
    - Как тесты и TDD влияют на организацию кода?
    - В чём разница между сцеплением и связанностью?
    - Почему в TDD тесты пишутся прежде кода?
    - Если у вашего кода плохая организация, как вы это поймёте?
9. [Вопросы от Данила Подольского на позицию Senior Golang Backend Developer в компанию Evrone](docs/podolsky/)
    - [Go — императивный или декларативный? А в чем разница?](docs/podolsky#1)
    - [Что такое type switch?](docs/podolsky#2)
    - [Как сообщить компилятору, что наш тип реализует интерфейс?](docs/podolsky#3)
    - [Как работает append?](docs/podolsky#4)
    - [Какое у slice zero value? Какие операции над ним возможны?](docs/podolsky#5)
    - [Как устроен тип map?](docs/podolsky#6)
    - [Каков порядок перебора map?](docs/podolsky#7)
    - [Что будет, если читать из закрытого канала?](docs/podolsky#8)
    - [Что будет, если писать в закрытый канал?](docs/podolsky#9)
    - [Как вы отсортируете массив структур по алфавиту по полю Name?](docs/podolsky#10)
    - [Что такое сериализация? Зачем она нужна?](docs/podolsky#11)
    - [Сколько времени в минутах займет у вас написание процедуры обращения односвязного списка?](docs/podolsky#12)
    - [Где следует поместить описание интерфейса: в пакете с реализацией или в пакете, где этот интерфейс используется? Почему?](docs/podolsky#13)
    - [Предположим, ваша функция должна возвращать детализированные Recoverable и Fatal ошибки. Как это реализовано в пакете net? Как это надо делать в современном Go?](docs/podolsky#14)
    - [Главный недостаток стандартного логгера?](docs/podolsky#15)
    - [Есть ли для Go хороший orm? Ответ обоснуйте.](docs/podolsky#16)
    - [Какой у вас любимый линтер?](docs/podolsky#17)
    - [Можно ли использовать один и тот же буфер []byte в нескольких горутинах?](docs/podolsky#18)
    - [Какие типы мьютексов предоставляет stdlib?](docs/podolsky#19)
    - [Что такое lock-free структуры данных, и есть ли в Go такие?](docs/podolsky#20)
    - [Способы поиска проблем производительности на проде?](docs/podolsky#21)
    - [Стандартный набор метрик prometheus в Go -программе?](docs/podolsky#22)
    - [Как встроить стандартный профайлер в свое приложение?](docs/podolsky#23)
    - [Overhead от стандартного профайлера?](docs/podolsky#24)
    - [Почему встраивание — не наследование?](docs/podolsky#25)
    - [Какие средства обобщенного программирования есть в Go?](docs/podolsky#26)
    - [Какие технологические преимущества языка Go вы можете назвать?](docs/podolsky#27)
    - [Какие технологические недостатки языка Go вы можете назвать?](docs/podolsky#28)
10. [Популярные задачи на собеседованиях](docs/popular_tasks)
    - [На вход подаются два неупорядоченных слайса любой длины. Надо написать функцию, которая возвращает их пересечение](docs/popular_tasks#1)
    - [Написать генератор случайных чисел](docs/popular_tasks#2)
    - [Слить N каналов в один](docs/popular_tasks#3)
    - [Сделать конвейер чисел](docs/popular_tasks#4)
    - [Написать WorkerPool с заданной функцией](docs/popular_tasks#5)
    - [Сделать кастомную waitGroup на семафоре](docs/popular_tasks#6)
    - [Что выведет код?](docs/popular_tasks#7)
    - [Какая есть проблема в коде?](docs/popular_tasks#8)
    - [Что выведет код?](docs/popular_tasks#9)
    - [Что выведет код?](docs/popular_tasks#10)

<details>
  <summary>Ответ</summary>
  <br />
  
  Тут ответ
</details>

# Надо будет отсортировать!

Быстрый экскурс по вопросам Go. Будет дополняться

- [ ] практические задачи по темам
- [ ] дополнительные материалы
- [ ] просто практические задачки по Go

### Начнем! (Чисто для себя)



### Мапы:

1. Что такое Map? Как устроен в Go? Желательно приблизительно понимать структуру (type hmap struct) и его поля
<details>
  <summary>Ответ</summary>
`map` в Go — это встроенный тип данных, представляющий собой ассоциативный массив или хеш-таблицу. Он позволяет хранить пары "ключ-значение", где каждый ключ уникален.

## Основные характеристики `map` в Go:

1. **Неупорядоченность**: Элементы в `map` не имеют фиксированного порядка.
2. **Уникальность ключей**: Каждый ключ в `map` должен быть уникальным. Если вы попытаетесь добавить значение с уже существующим ключом, старое значение будет перезаписано.
3. **Динамическое выделение памяти**: Размер `map` может изменяться динамически, когда вы добавляете или удаляете элементы.

## Структура `map` в Go

Внутренняя структура `map` в Go представлена типом `hmap`. Хотя точная реализация может варьироваться в зависимости от версии Go, общая структура выглядит примерно так:

```go
type hmap struct {
    count     int // количество элементов в map
    flags     uint8 // флаги, указывающие на состояние
    B         uint8 // степень хеш-функции (размер таблицы)
    noverflow uint16 // количество переполнений
    hash0     uint32 // случайное значение для хеширования
    buckets   unsafe.Pointer // указатель на массив "ведер" (buckets)
    oldbuckets unsafe.Pointer // указатель на старые "ведра" (при увеличении размера)
    nevacuate uintptr // индекс, до которого выполнена эвакуация
    extra     *mapextra // дополнительные данные
}
```
<br />
	
</details>
3. Что такое хеш-функция?
4. Почему нельзя брать ссылку на значение, хранящееся по ключу в map?
5. Что такое эвакуация, и в каком случае она будет происходить?
6. Какие есть особенности синтаксиса получения и записи значений в map?
7. Как происходит поиск по ключу в map?
8. Каков порядок перебора map?
9. Что будет происходить при конкуррентной записи в map? Как можно решить эту проблему?
10. Как защититься от ошибки во время конкурентной записи в map?

**полезные материалы:**

- https://www.youtube.com/watch?v=P_SXTUiA-9Y
- https://www.youtube.com/watch?v=0UX4MIfOMEs

### Каналы в Go:

1. Что такое канал? Чем отличается буферизированный канал от небуферизированного?
2. Как создать канал? Как закрыть канал?
3. Как читать из канала и писать в канал?
4. Зачем нужны в целом каналы?
5. Что будет, если читать из закрытого канала?
6. Что будет, если писать в закрытый канал?
7. Что будет если закрыть закрытый канал?
8. Что такое nil канал и что будет если писать и читать от туда?

**полезные материалы:**

- https://www.youtube.com/watch?v=ZTJcaP4G4JM


### Типы данных в Go:

1. Какие бывают типы в Go? Целочисленные, дробные, комплексные, структуы, интерфесы, время и дополнить.
2. Отличие uint от int?
3. Что такое обычный int и какие есть нюансы его реализации?
4. Как преобразовать строку в int и наоборот? Можно ли сделать int(string) и string(int) соответственно?
5. Сколько в памяти занимают реализации int32 и int64?
6. Какие предельные значения int32 и int64?
7. Какой результат получим если разделить int на 0 и float на 0?
8. Что такое константы и можно ли их изменять?
9. Что такое iota?
10. Что такое структура (stuct) в Go? Зачем они нужны?
11. Что такое метод? Как они выглядят?
12. Как осуществляется наследование в Go?
13. Что такое тип rune? Зачем их использовать?
14. Что такое тип byte?
15. Что такое goto?
16. Какие циклы есть в Go?

### Интерфейсы в Go:

1. Что такое интерфейсы в Go? Чем отличается от интерфейсов в дпугих языказ, например, Java, PHP. Что такое утиная типизация?
2. Внутренее устройство интерфейса, какое оно (структура iface, itab)?
3. Сделать интерфейс для вычисления площади круга и квадрата, реализовать их в структурах cicle и square.
4. Что такое пустой интерфейс?
5. Что такое nil интерфейс?
6. Что такое type switch? 
7. Как определить тип интерфейса?
8. Как преобразовать интерфейс к другому типу?
9. Где следует поместить описание интерфейса: в пакете с реализацией или в пакете, где этот интерфейс используется? Почему?

**полезные ресурсы:**

- https://www.youtube.com/watch?v=eYHCCht8eX4

### Вопросы по Go:

1. Зачем используется ключевое слово defer в Go?
2. Каков порядок возврата при использовании несколько функций с defer в рамках одной внешней функции?
3. Как передаются значения в функции, перед которыми указано ключевое слово defer? Пример:

```go
func main() {
	nums := 1 << 5 // 32

	defer fmt.Println(nums) // туть как?

	nums = nums >> 1 //16

	fmt.Println("done")
}
```

4. Какие бывают способоы синхронизации данных в Go? (про каналы тоже не забываем)
5. Что такое mutex, какие они бывают и как их использовать?
6. Что такое atomics, какие бывают и как и когда их лучше использовать?
7. Что такое sync.Map?
8. Что такое lock-free структуры данных, и есть ли в Go такие? Если интересно.
9. Как можно обработать панику с помощью defer и recovery?
10. Что такое context в Go? Какие бывают context в Go? Когда их нужно использовать и зачем?
11. Что такое указатели? Как передаются параметры в функцию по указателю или по значению? Какие типы неявно передаются как указатель? Как передать по указателю?
12. Что такое пакеты (package) в Go? Как их создавать и импортировать?
13. Можно ли реализовать sync.Mutex и sync.WaitGroup на каналах? Как?

### Вопросы по Runtime Go:

1. Что такое runtime (планировщик sheduler)? Как он устроен в Go?
2. Что такое Gorutine (горутина)?
3. В чем отличие горутины от потока?
4. Как устроены горутины, сколько памяти они занимают в стеке?
5. Кто управляет горутинами? Какой тип многозадачности используется в Go и какой был до версии Go 1.15?
6. Что такое GC (garbadge collector/сборщик мусора)?
7. Как работает сборщик мусора в Go?
8. Как проверить тип переменной в среде выполнения?

**полезные материалы:**

- https://www.youtube.com/watch?v=ZTJcaP4G4JM (тут про каналы, но еще рассказывает про рантайм и горутины, планировщик и тп)

### Вопросы по тестированию

1. Что такое unit тесты?
2. Что такое интеграционные тесты?
3. Как в Go пишут unit тесты со стандартным пакетом testing? Какие есть библиотеки, например, testify?
4. Что такое моки (mocks)?

### Вопросы по CI/CD:

0. Что такое CI/CD?
1. Что такое линтеры (linters) зачем они нужны и как их использовать?
2. Как можно измерить использование памяти в Go? Что такое pprof?
3. Что такое Prometheus и Grafana? Зачем они нужны?

### Практическая часть по всем вопросам: 

- 

### Полезные ссылки:

- https://nuancesprog.ru/p/12333/
- https://github.com/goavengers/go-interview
   
## Как мне добавить свой вопрос-ответ?

- [Ознакомьтесь с шаблоном составления](TEMPLATE.md)

### Maintainers

<table>
<tr>
<td align="center">
<img src="https://avatars1.githubusercontent.com/u/23422968?s=460&u=668229465690637b50f6581df0fa9918d7fb6c1e&v=4" width="100px;" alt=""/>
<br /><sub><b>zikwall</b></sub></a><br />
</td>
<td align="center">
<img src="https://avatars.githubusercontent.com/u/2690403?v=4" width="100px;" alt=""/>
<br /><sub><b>dreddsa5dies</b></sub></a><br />
</td>
<td align="center">
<img src="https://avatars.githubusercontent.com/u/35832930?v=4" width="100px;" alt=""/>
<br /><sub><b>gonnafaraway (kj22k0m)</b></sub></a><br />
</td>
<td align="center">
<img src="https://avatars.githubusercontent.com/u/64461997?v=4" width="100px;" alt=""/>
<br /><sub><b>screamo-boop</b></sub></a><br />
</td>
</tr>
</table>
