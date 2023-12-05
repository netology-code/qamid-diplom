# Дипломный проект по профессии «Инженер по тестированию»

* [Цели проекта](#цели-проекта)
* [Описание приложения](#описание-приложения)
* [Этапы выполнения:](#этапы-выполнения)
    * [Проверка приложения](#проверка-приложения)
    * [Автоматизация проверки приложения](#автоматизация-проверки-приложения)
        * [Настройка проекта перед написанием UI-тестов](#настройка-проекта-перед-написанием-ui-тестов)  
        * [Написание UI-тестов](#написание-ui-тестов) 
    * [Составление отчёта](#составление-отчета)
* [Правила сдачи дипломного проекта](#правила-сдачи-дипломного-проекта)
* [Критерии оценки](#критерии-оценки)
* [Как задавать вопросы руководителю по дипломной работе](#как-задавать-вопросы-руководителю-по-дипломной-работе)

---

## Цели проекта

Эта дипломная работа поможет закрепить знания и навыки по автоматизации тестирования мобильных приложений.   

В результате выполнения вы:
1. Проведёте ручное тестирование мобильного приложения «Мобильный хоспис».
2. Составите чек-лист для проверки приложения.
3. Распишите тест-кейсы для проверки приложения.
4. Автоматизируете проверку тест-кейсов по чек-листу.
5. Составите отчёты о тестировании.

## Описание приложения

Приложение даёт функционал по работе с претензиями хосписа и включает в себя:
- информацию о претензиях и функционал для работы с ними;
- новостную сводку хосписа;
- тематические цитаты.

![](pic/app.png)


---

## Этапы выполнения

### 1. Проверка приложения.

1. Скачайте [архив с приложением](https://drive.google.com/drive/folders/1zrL0XXgkMxpfF7tTNUrGAwQPvI7k8C69), откройте его в Android Studio и установите на устройство.   
Данные для авторизации:

- `login2`;
- `password2`.

2. Выполните проверку приложения по этапам: 
- планирование: определите «границы» приложения, реализованный функционал и заложите основу для тестов;
- типы тестирования: определите, что именно будет проверяться;
- чек-лист: составьте предварительный список проверок и дополняйте его;
- тест-кейсы: составьте предварительные тест-кейсы и дополняйте их. 

### 2. Автоматизация проверки приложения.

1. Настройка проекта перед написанием UI-тестов:
- добавьте необходимые библиотеки;  
- добавьте директорию для тестов;    
- настройте тестовый класс.

2. Написание UI-тестов.
Не забывайте, что каждое действие должно завершаться проверкой.

### 3. Составление отчёта.

1. Подключение Allure к проекту:
- добавьте необходимые зависимости; 
- добавьте необходимые права приложению.

2. Разметка тестов для отчёта:
- добавьте в тесты названия функциональностей; 
- описания тестов; 
- шаги;   
- прикрепление снимков экрана при падении.

3. Составление отчёта:
- выгрузите отчёты с мобильных устройств;  
- проверьте работоспособность;  
- запакуйте в архив.

---
## Правила сдачи дипломного проекта

1. В течение 7 дней после начала работы над проектом пришлите дипломному руководителю репозиторий с проектом, в корне которого созданы:

-  файл `Plan.md` с описанием плана по проверке и автоматизации приложения;
-  файл `Check` с чек-листом проекта и отметками о пройденых и непройденых тестах в формате xlsx, xls, csv (Разделение «;»);
-  таблица `Cases` с тест-кейсами в формате xlsx, xls, csv (Разделение «;»). Они должны содержать отметки, если такие есть, о покрытии с указанием причин, почему тест-кейс не может быть покрыт.

2. После того, как ваш дипломный руководитель проверил первый этап работы, приступайте к автоматизации и составлению отчёта.  
В корень репозитория вашего проекта добавьте:
-  файл `README.md` с описанием процедуры запуска авто-тестов;
-  `allure-results.zip` с отчётом о результатах прогона тестов (Allure);
-  файл `Result.md` с результатом сравнения времени проверки приложения по чек-листу руками и UI-тестами.

---
## Критерии оценки

1. Проект собирается, тесты запускаются без дополнительных манипуляций.
2. Проект работает на Android API 29.
3. В проекте есть UI-тесты.
4. Понятные названия тестов, методов и элементов. 
5. Нет явных изъянов в архитектуре, корректный code style.

---

## Как задавать вопросы руководителю по дипломной работе

1. Если у вас возник вопрос, попробуйте сначала самостоятельно найти ответ в интернете. Навык поиска информации пригодится вам в любой профессиональной деятельности. Если ответ не нашёлся, можно уточнить у руководителя по дипломной работе.
2. Если у вас набирается несколько вопросов, присылайте их в виде нумерованного списка. Так дипломному руководителю будет проще отвечать на каждый из них.
3. Для лучшего понимания контекста прикрепите к вопросу скриншоты и стрелкой укажите, что именно вызывает вопрос. Программу для создания скриншотов можно скачать [по ссылке](https://app.prntscr.com/ru/).
4. По возможности задавайте вопросы в комментариях к коду.
5. Формулируйте свои вопросы чётко, дополняя их деталями. На сообщения «Ничего не работает», «Всё сломалось» дипломный руководитель не сможет дать комментарии без дополнительных уточнений. Это затянет процесс получения ответа. 
6. Постарайтесь набраться терпения в ожидании ответа на свои вопросы. Дипломные руководители Нетологии – практикующие разработчики, поэтому они не всегда могут отвечать моментально. Зато их практика даёт возможность делиться с вами не только теорией, но и ценным прикладным опытом.  

Рекомендации по работе над дипломом:

1. Не откладывайте надолго начало работы над дипломом. В таком случае у вас останется больше времени на получение рекомендаций от руководителя и доработку диплома.
2. Разбейте работу над дипломом на части и выполняйте их поочерёдно. Вы будете успевать учитывать комментарии от руководителя и не терять мотивацию на полпути. 
