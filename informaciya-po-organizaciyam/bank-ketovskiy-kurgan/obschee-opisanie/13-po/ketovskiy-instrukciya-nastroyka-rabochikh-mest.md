---
order: 1
title: Кетовский. Инструкция. Настройка рабочих мест.
---

### **1) Подключение сетевого диска:**

-  Подключаем под **буквой W**

-  \\\\192.168.100.3\\ForVoronin

-  Логин/Пароль есть в КП: Кетовский-коммерческий-банк-(Курган-банк)>Кетовский сетевой диск W пользователям

### **2) Настройка доступов к сайтам:**

\*\*\*\*\*Свои логины\\пароли пользователи должны знать, если нет, то оправляем в Курган или к руководителю -- **мы не занимаемся выдачей доступов в банковские программы**.

\*\*\*\*\*\*А также если есть проблемы внутри банковского ПО, им надо обращаться в Курган.

-  *(\*; \*\*)Золотая корона(ЗК):* <https://www.perevod-korona.com/arm>

   -  В настройках браузера где подключена ЗК, указываем путь загрузки W:\\ZKout\\Omega

-  (\*) Юнистрим: [\*https://ok.unistream.com/user/login \*](https://ok.unistream.com/user/login)

   -  Необходимо установить сертификат для сайта, он находится на \\\\192.168.100.3\\ForVoronin\\IKR\\unistream

      -  Сайт будет ругаться на сертификат(что устанавливали на шаг выше не ssl), просто игнорируете и  заходите на сайт - в данный момент решения нет.

-  (\*) Корпоративная почта: [*http://mail.bank-45.ru*](http://mail.bank-45.ru)

-  (необязательно)Валюты мира: [*https://base.icpress.ru/ru/*](https://base.icpress.ru/ru/) +

   -  Логин: ketovsky,

      1. Пароль: lui45krycs18

         -  Данные одни для всех пользователей.

-  (необязательно)Service Desk Юнистрим: <https://sd.unistream.ru/>

   -  Необходимо установить ssl сертификат для доступа на сайт. Находиться \\\\192.168.100.3\\ForVoronin\\IKR\\unistream\\sdunistream

-  Сервисы МВД [https://xn--b1aew.xn--p1ai/сервисы-гувм](https://xn--xnb1aew-316c.xn--xnp1ai-4g0c/сервисы-гувм)

### **3) Настройка банковских программ.**

**Омега:**

-  Дистрибутив находиться: \\\\192.68.100.3\\forvoronin\\@ОМЕГА

   1. Папку @ОМЕГА копируем в корень локального системного диска.

   2. Выводим ярлык на рабочий стол.

   3. Настраиваем: Запускаем Омегу>вкладка «дополнительно»>«Параметры соединения»> вводим: 192.168.100.220, порт 211>во вкладке «приложения» выбираем ETALON







Один важный момент, для сохраннее настроек нужно, что бы пользователь авторизовался до закрытия программы. А иначе придется повторить пункт 3.

**Spark(необязательно)(\*;\*\*)**

-  Установочник находиться: \\\\192.68.100.3\\forvoronin\\IKR

   -  Выбираем версию 2.6.3

   -  Устанавливаем из-под админа.