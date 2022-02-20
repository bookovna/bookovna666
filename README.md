## Проект по разработке автотестов для сайта [Goritskov.com](https://goritskov.com/ "goritskov's home")
### Технологический стек
________
<img src="images/logo/Java.svg" width="50" height="50"/> <img src="images/logo/Intelij_IDEA.svg" width="50" height="50"/> <img src="images/logo/Gradle.svg" width="50" height="50"/> <img src="images/logo/JUnit5.svg" width="50" height="50"/> <img src="images/logo/Selenide.svg" width="50" height="50"/> <img src="images/logo/GitHub.svg" width="50" height="50"/> <img src="images/logo/Jenkins.svg" width="50" height="50"/> <img src="images/logo/Selenoid.svg" width="50" height="50"/> <img src="images/logo/Allure_Report.svg" width="50" height="50"/> <img src="images/logo/Allure_TestOps.svg" width="50" height="50"/> <img src="images/logo/Telegram.svg" width="50" height="50"/>

-----
* Автотесты написаны на ``Java`` с использованием фреймворка ``Selenide``
* ``JUnit 5`` фреймворк для модульного тестирования
* ``Gradle`` используется для автоматизированной сборки проекта
* Тесты запускаются с помощью ``Jenkins``
* ``Selenoid`` запускает браузеры в контейнерах ``Docker``
* ``Allure Report`` формирует отчет о запуске тестов
* Автотесты интегрируются с тест-менеджмент системой ``Allure TestOps``
* В ``Telegram`` бот отправляет уведомления о результатах прохождения тестов

### ✅  Тест-кейсы
1. Проверка текста заголовка на главной странице
2. Проверка наличия ссылки на раздел "Обо мне" на странице

### 🚀 Запуск тестов из терминала
* Локально ``gradle clean test -DtypeEnv=locale``
* Удалённо ``gradle clean test -DtypeEnv=remote``

### <img src="images/logo/Jenkins.svg" width="40" height="40"/> Конфигурация Job в Jenkins 
🔴 Открыть сборку [Jenkins](https://jenkins.autotests.cloud/job/009_qaguru_j_unicorn_hw13v2/build?delay=0sec).  
🔴 Нажать **"Собрать с параметрами"**.  
🔴 Указать необходимые параметры.  
🔴 Нажать на кнопку **"Собрать"**.  

<img src="images/screenshots/Jenkins parameters.jpg" width="1000" height="700"/>  

🔴 Для формирования отчета о прохождении тестов в Allure Report необходимо нажать на ссылку/иконку **"Allure Report"**.  

<img src="images/screenshots/allure report1.jpg" width="1000" height="600"/>  

### <img src="images/logo/Selenoid.svg" width="40" height="40"/> Видео прохождения тестов в Selenoid  


<https://user-images.githubusercontent.com/93325839/148690769-79fc4059-f033-4f35-a7be-39214e0dc110.mp4>


### <img src="images/logo/Allure_Report.svg" width="30" height="30"/> Отчет о результатах тестирования в Allure Report

<details>
  <summary>Подробнее</summary>  

  
**1.** Страница «Overview»

<img src="images/screenshots/allure report2.jpg" width="800" height="400"/>  
  

    
  
**2.** Страница «Categories». 

Данная страница предоставляет информацию о распределении дефектов по их видам.

<img src="images/screenshots/allure report3.jpg" width="800" height="400"/>  

    
  
**3.** Страница «Suites»

На этой странице показано распределение выполнявшихся тестов по тестовым наборам или классам, в которых находятся тестовые методы

<img src="images/screenshots/allure report4.jpg" width="800" height="400"/>  

    
  
**4.** Страница «Graphs»

На этой странице — информация о тестовом прогоне в графическом виде: статус прогона, распределение тестов по их критичности, длительности прохождения, перезапусках, категориях, дефектах  

<img src="images/screenshots/allure report5.jpg" width="800" height="400"/>  

    
  
**5.** Страница «Timeline»

Эта страница визуализирует временные рамки прохождения каждого теста.  

<img src="images/screenshots/allure report6.jpg" width="800" height="400"/>  

</details>  

### <img src="images/logo/Allure_TestOps.svg" width="30" height="30"/> Интеграция тестов c тест-менеджмент системой [Allure TestOps](https://allure.autotests.cloud/project/862/dashboards)

<details>
  <summary>Подробнее</summary> 

  
📎 **Dashboards**  

<img src="images/screenshots/testops_dashboards.jpg" width="800" height="400"/>  
  
  

📎 **Test cases**  

<img src="images/screenshots/testops_testcases.jpg" width="800" height="400"/>  
  
  

📎 **Launches**  

<img src="images/screenshots/launches.jpg" width="800" height="400"/>  
  
  

</details>  
 

### <img src="images/logo/Telegram.svg" width="30" height="30"/> Уведомления о прохождении тестов в Telegram  

<img src="images/screenshots/telegram_bot.jpg" width="500" height="500"/>  
