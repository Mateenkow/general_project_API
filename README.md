# Дипломный проект по автоматизации тестирования API на [reqres.in](https://reqres.in/)
![img.png](picture/img.png)

---

### ✏️ Описание проекта 
Проект по автоматизации тестирования Api с использованием платформы открытого доступа [reqres.in](https://reqres.in/)
Проект разработан для локального и удаленного  развертывания и запуска api авто-тестов. 

Проект находится в открытом доступе, поэтому вы можете его скачать, доработать, кастомизировать или использовать как шаблон для ваших целей.

---

### 🧰 Используемые технологии и инструменты:

| Java                                                                                                      | IntelliJ Idea                                                                                                                 | GitHub                                                                                                     | JUnit 5                                                                                                           | Gradle                                                                                                     | Jenkins                                                                                                           |
|:----------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------|------------------------------------------------------------------------------------------------------------|-------------------------------------------------------------------------------------------------------------------:|
| <a href="https://www.java.com/"><img alt="Java" height="50" src="picture/Java.svg" width="50"/></a>  | <a id ="tech" href="https://www.jetbrains.com/idea/"><img alt="IDEA" height="50" src="picture/Idea.svg" width="50"/></a> | <a href="https://github.com/"><img alt="Github" height="50" src="picture/GitHub.svg" width="50"/></a> | <a href="https://junit.org/junit5/"><img alt="JUnit 5" height="50" src="picture/Junit5.svg" width="50"/></a> | <a href="https://gradle.org/"><img alt="Gradle" height="50" src="picture/Gradle.svg" width="50"/></a>  |   <a href="https://www.jenkins.io/"><img alt="Jenkins" height="50" src="picture/Jenkins.svg" width="50"/></a> |


| Allure                                                                                                                     |
|----------------------------------------------------------------------------------------------------------------------------|
| <a href="https://github.com/allure-framework"><img alt="Allure" height="50" src="picture/Allure.svg" width="50"/></a> |



### 💻 Запуск тестов из терминала :

`gradle clean test`

---

### Удаленный запуск тестов через [Jenkins:](https://jenkins.autotests.cloud/job/C27-mateenkov-General-Api/)

Запустить авто-тесты можно по кнопке ```Build with parameters```

![img.png](notifications/startbuild.png)

### Allure-отчетность:

По кнопке со значком ![img.png](notifications/iconAllure.png) Allure можно увидеть всю отчетность:

![img.png](notifications/owerViewAllure.png)
![img.png](notifications/AllureReport.png)

### Отчетность в Telegram:

После прохождения всех тестов приходит уведомление в Telegram с небольшим отчетом

![img_1.png](notifications/telegramReport.png)
