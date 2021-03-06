
## Проект по автоматизации тестирования для сайта QA.GURU ☀️️

### <a target="_blank" href="https://qa.guru/">Перейти на сайт школы инженеров по автоматизации тестирования</a>

### 💎Содержание:

- <a href="#технологии-и-инструменты">Технологии и инструменты</a>
- <a href="#реализованные-проверки">Реализованные проверки</a>
- <a href="#сборка-в-jenkins">Сборка в Jenkins</a>
- <a href="#запуск-из-терминала">Запуск из терминала</a>
- <a href="#allure-отчет">Allure отчет</a>
- <a href="#видео-примеры-прохождения-тест-кейсов">Видео примеры прохождения тест-кейсов</a>
- <a href="#отчет-в-telegram">Отчет в Telegram</a>

### 💎[Технологии и инструменты](#технологии-и-инструменты)
<p align="center">
<img width="6%" title="IntelliJ IDEA" src="logo/Intelij_IDEA.svg">
<img width="6%" title="Java" src="logo/Java.svg">
<img width="6%" title="Selenide" src="logo/Selenide.svg">
<img width="6%" title="Selenoid" src="logo/Selenoid.svg">
<img width="6%" title="Allure Report" src="logo/Allure_Report.svg">
<img width="6%" title="Gradle" src="logo/Gradle.svg">
<img width="6%" title="JUnit5" src="logo/JUnit5.svg">
<img width="6%" title="GitHub" src="logo/GitHub.svg">
<img width="6%" title="Jenkins" src="logo/Jenkins.svg">
<img width="6%" title="Telegram" src="logo/Telegram.svg">
</p>

### 💎[Реализованные проверки](#реализованные-проверки)
* Тест на открытие главной страницы сайта qa.guru.
* Тест на открытие программы обучения.
* Тест на проверку перехода в ВК.
* Тест на авторизацию с невалидными кредами.
* Тест на авторизацию с валидными кредами.

### 💎[Сборка в Jenkins](#сборка-в-jenkins)
#### <a target="_blank" href="https://jenkins.autotests.cloud/job/qa.guru-hm13-smallProject/">Перейти на сборку</a>

### 💎[Запуск из терминала](#запуск-из-терминала)
* #### Локальный запуск тест-кейсов
**gradle clean test**

* #### Удаленный запуск тест-кейсов
**clean test**  
-DpropertyBrowser=${PROPERTYBROWSER}  
-DpropertyVersion=${PROPERTYVERSION}  
-DpropertyBrowserSize=${PROPERTYBROWSERSIZE}, где  
**propertyBrowser** - браузер, по умолчанию Chrome;  
**propertyVersion** - версия браузера, по умолчанию 100;  
**propertyBrowserSize** - размер окна браузера, по умолчанию 1920x1080.


### 💎[Allure отчет](#allure-отчет)
#### Сводные данные
![Img1](logo/mainreport.jpg)

#### Тест-кейсы
![Img2](logo/tests.jpg)

* ##### **Пример успешного прохождения тест-кейса**
![Img3](logo/success.jpg)

* ##### **Пример неуспешного прохождения тест-кейса**
Неуспешный тест-кейс добавлен в проект для наглядности. Для его успешного прохождения необходимо добавить переменные -  
(email адрес и пароль) в переменные окружения.
![Img4](logo/failed.jpg)

#### Графики
![Img5](logo/graphs.jpg)

#### Выводы
Подключение Allure Report к проекту позволяет выявить в короткие сроки причины неуспешных тест-кейсов.
Статистика прохождения тест-кейсов представлена наглядно и доступно.

### 💎[Видео примеры прохождения тест-кейсов](#видео-примеры-прохождения-тест-кейсов)
К каждому тест-кейсу прилагается запись прохождения теста. Одно из таких видео представлено ниже.
<p align="center">
<img title="video1" src="video1.gif" width="750" height="440"  alt="video">
</p>

### 💎[Отчет в Telegram](#отчет-в-telegram)
Для быстрого реагирования на результаты прохождения тест-кейсов, на проекте настроены быстрые уведомления в Telegram.
Уведомления выглядят следующим образом:

![Img6](logo/tg.jpg)

❤️ <a target="_blank" href="https://qa.guru">qa.guru</a><br/>
💙 <a target="_blank" href="https://t.me/qa_guru_chat">t.me/qa_guru_chat</a>
