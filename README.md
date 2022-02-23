## Проект по разработке автотестов для сайта [Goritskov.com](https://goritskov.com/ "goritskov's home")
### Технологический стек
________
<img src="images/logo/Java.svg" width="50" height="50"/>   <img src="images/logo/Intelij_IDEA.svg" width="50" height="50"/>   <img src="images/logo/Gradle.svg" width="50" height="50"/>   <img src="images/logo/JUnit5.svg" width="50" height="50"/>   <img src="images/logo/Selenide.svg" width="50" height="50"/>   <img src="images/logo/GitHub.svg" width="50" height="50"/>   <img src="images/logo/Jenkins.svg" width="50" height="50"/>   <img src="images/logo/Selenoid.svg" width="50" height="50"/>   <img src="images/logo/Allure_Report.svg" width="50" height="50"/>   <img src="images/logo/Allure_TestOps.svg" width="50" height="50"/>   <img src="images/logo/Telegram.svg" width="50" height="50"/>

-----
* Автотесты написаны на ``Java`` с использованием фреймворка ``Selenide``
* ``JUnit 5`` фреймворк для модульного тестирования
* ``Gradle`` используется для автоматизированной сборки проекта
* Тесты запускаются с помощью ``Jenkins``
* ``Selenoid`` запускает браузеры в контейнерах ``Docker``
* ``Allure Report`` формирует отчет о запуске тестов
* Автотесты интегрируются с тест-менеджмент системой ``Allure TestOps``
* В ``Telegram`` бот отправляет уведомления о результатах прохождения тестов

###  Тест-кейсы
1. Проверка текста заголовка на главной странице
2. Проверка наличия ссылки на раздел "Обо мне" на странице

### 🚀 Запуск тестов из терминала
* Локально ``gradle clean test -DtypeEnv=locale``
* Удалённо ``gradle clean test -DtypeEnv=remote``

### <img src="images/logo/Jenkins.svg" width="40" height="40"/> Конфигурация Job в Jenkins 
✅ Открыть сборку [Jenkins](https://jenkins.autotests.cloud/job/bookovna-666/build?delay=0sec)  
✅ Кликнуть на **"Build with Parameters"**  
✅ Указать нужные параметры  
✅ Кликнуть на **"Build"** 

<img src="images/screenshots/job.png" width="80%" height="80%"/>  

✅ Чтобы увидеть отчёт о прохождении тестов в Allure Report, нужно кликнуть на иконку **"Allure Report"**  

<img src="images/logo/Allure_Report.svg" width="50" height="50"/>


### <img src="images/logo/Allure_Report.svg" width="30" height="30"/> Отчет о результатах тестирования в Allure Report

<details>
  <summary>Подробнее</summary>  

 <img src="images/screenshots/allure_report.png" width="80%" height="80%"/>  
  

</details>  

### <img src="images/logo/Allure_TestOps.svg" width="30" height="30"/> Интеграция тестов c тест-менеджмент системой [Allure TestOps](https://allure.autotests.cloud/launch/11113)

<details>
  <summary>Подробнее</summary> 

  
<img src="images/screenshots/allure_testops.png" width="80%" height="80%"/>  
  
  

</details>  

### <img src="images/logo/Selenoid.svg" width="40" height="40"/> Видео прохождения тестов в Selenoid  

<video>
 <source src="video/5e8b77b7342d9aaf.mp4">
<width=180/>
 

### <img src="images/logo/Telegram.svg" width="30" height="30"/> Уведомления о прохождении тестов в Telegram  

<img src="images/screenshots/telegram_bot.png" width="30%" height="30%" />  
