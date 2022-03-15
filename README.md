# Дипломный проект профессии «Инженер по тестированию»

* [Цели проекта](#цели-проекта)
* [Описание приложения](#описание-приложения)
* [Этапы выполнения:](#этапы-выполнения)
    * [Проверка приложения](#проверка-приложения)
    * [Автоматизация проверки приложения](#автоматизация-проверки-приложения)
        * [Настройка проекта](#настройка-проекта)
        * [Написание ui-тестов](#написание-ui-тестов)
    * [Составление отчета](#составление-отчета)
* [Требования к сдаче дипломного проекта](#требования-к-сдаче-дипломного-проекта)
* [Критерии оценки:](#критерии-оценки)
* [Как правильно задавать вопросы дипломному руководителю?](#как-правильно-задавать-вопросы-дипломному-руководителю)

---

## Цели проекта

Это дипломное задание позволит закрепить знания и навыки по автоматизации тестирования мобильных приложений.   
В результаты выполнения вы:
1. Проведете ручное тестирование мобильного приложения "Мобильный хоспис".
2. Составите чек-лист для проверки приложения.
3. Распишете тест-кейсы для проверки приложения.
4. Автоматизируете проверку тест-кейсов по чек-листу.
5. Составите отчеты от тестировании


## Описание приложения

Приложение предоставляет функционал по работе с претензиями хосписа и включает в себя:
1. Информацию о претензиях и функционал для работы с ними.
2. Новостную сводку хосписа.
3. Тематические цитаты.

![](pic/app.png)



---

## Этапы выполнения

### 1. Проверка приложения

1. Скачайте архив с приложением, откройте его в Android Studio и установите на устройство - [приложение](fmh-android.zip).   
Данные для авторизации:
`login2`
`password2`
3. Выполните проверку приложения, следуя этапам ниже: 
- Планирование: определите "границы" приложения, реализованный функционал и заложите основу для тестов;
- Типы тестирования: определите, что именно будет проверяться;
- Чек-лист: составьте предварительный список проверок и дополняйте его;
- Тест-кейсы: составьте предварительные тест-кейсы и дополняйте их. 

### 2. Автоматизация проверки приложения

1. Настройка проекта перед написанием ui-тестов:
- Добавьте необходимые библиотеки, 
- Добавьте директорию для тестов, 
- Настройте тестовый класс.

2. Написание ui-тестов.
Не забывайте, что каждое действие должно завершаться проверкой.

### 3. Составление отчета

1. Подключение Allure к проекту:
- Добавьте необходимые зависимости,
- Добавьте необходимые права приложению.

2. Разметка тестов для отчета:
- Добавьте в тесты названия функциональностей,
- Описания тестов,
- Шаги, 
- Прикрепление снимков экрана при падении.

3. Сбор отчета:
- Выгрузите отчеты с мобильных устройств,
- Проверьте работоспособность,
- Запакуйте в архив.

---
## Требования к сдаче дипломного проекта

1. Репозиторий с проектом.
2. План по проверке и автоматизации приложения описан в `Plan.md` в корне вашего проекта.
3. Файл с чек-листом проекта и отметками о пройденых и непройденых тестах в формате xlsx, xls, csv (Разделение ";") и именем `Check` в корне вашего проекта;
4. Таблица с тест-кейсами в формате xlsx, xls, csv (Разделение ";") и именем `Cases`, в корне вашего проекта, должны содержать отметки о покрытии с указанием причин почему тест-кейс не может быть покрыт (если такие имеются).
5. Наличие ui-тестов в проекте
6. В файле `README.md` должна быть описана процедура запуска авто-тестов
7. Отчет с результатом прогона тестов (Allure) в `allure-results.zip`
8. Результат сравнения времени проверки приложения по чек-листу руками и ui-тестами в `Result.md`

---
## Критерии оценки

- Проект собирается, тесты запускаются без дополнительных манипуляций
- Работает на Android API 29
- Понятные названия тестов, методов и элементов 
- Нет явных изъянов в архитектуре, корректный code style


---
## Как правильно задавать вопросы дипломному руководителю?

Что поможет успешно справиться с дипломным заданием:

1. Попробуйте найти ответ сначала самостоятельно в интернете или в материалах курса и ДЗ и только после этого спрашивайте у дипломного 
  руководителя. Скилл поиска ответов пригодится вам в профессиональной деятельности.
2. Если вопросов больше одного, то присылайте их в виде нумерованного списка. Так дипломному руководителю будет проще отвечать на каждый из них.
3. Как правильно оформлять вопросы:
    - публикуйте самую последнюю версию вашего кода на GitHub
    - включайте в репозитории Issues
    - заводите новое Issue с описанием проблемы, скриншотами.
4. Начинайте работу над дипломом как можно раньше, чтобы было больше времени на правки. 
5. Делайте диплом по частям.
6. Все материалы (документы, авто-тесты, открытые issue, отчёты и т.д.) размещайте  в одном публичном репозитории, ссылку на который вы и будете отправлять дипломному руководителю.

Что может стать источником проблем:

1. Вопросы вида «Ничего не работает. Не запускается. Всё сломалось». Дипломный руководитель не сможет ответить на такой вопрос без дополнительных уточнений. Цените своё время и время других.
2. Откладывание выполнения курсового проекта на последний момент.
3. Ожидание моментального ответа на свой вопрос. Дипломные руководители работающие разработчики, которые занимаются, кроме преподавания, 
  своими проектами. Их время ограничено, поэтому постарайтесь задавать правильные вопросы, чтобы получать быстрые ответы :)

