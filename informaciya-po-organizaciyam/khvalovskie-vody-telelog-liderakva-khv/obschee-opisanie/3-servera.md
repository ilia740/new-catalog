---
order: 3
title: 3. Сервера.
---

Требуется описание ОСР. Временная краткая запись для ОТП: сервер с 1С и общей папкой в офисе СБ, сервер телефонии в  ДЦ Даталайн (CDR Отдельно в ДЦ Прометей). Веб сервера в Даталайне. Даталайн изменил адрес системы сервис деска с [support@dtln.ru](mailto:support@dtln.ru) на [sd@rt-dc.ru](mailto:sd@rt-dc.ru). (заявка 93824)

Сервера Даталайн

-  **HV-Dataline-dev-site**

-  **HV-Dataline-Srv-Web6**

-  **HV-Dataline-Srv-Web7**

-  **HV-Dataline-Srv-Web8**

-  **HV-Dataline-Srv-Web9**

-  **HV-Dataline-Srv-Web10**

-  **HV-Dataline-Srv-Web11**

-  **HV-Dataline-Srv-Web-back2**

-  **HV-Dataline-Srv-Web-db2**

-  **HV-Dataline-Srv-Web-ftp2hw**

-  **HV-Dataline-Srv-Web-proxy**

**ДЦ Миран**

**ProLiant DL360 Gen9**

**Гипервизор VMWare ESXi –  7.0.3**  [**virt2.hvalwaters.ru**](http://virt2.hvalwaters.ru)

Домен-контроллер, ADDS сервер, DNS сервер.

**HV-SB-SRV-DC1 -** Windows 2019 (Server Standart)

Домен - hv.local

Пользователи распределены по отдела (Бухгалтерия, СПБ Менеджеры, МСК Менеджеры, Претензионный, Доставка)

В hosts указан  1С Сервер hwdb2.

Терминальный сервер

**HV-SB-SRV-Term** **\-** Windows 2019 (Server Standart)

Терминальный сервер для пользователей.

На дисках K-W находятся ЭЦП. Имеется файл с доступами к ЭЦП. Права распределяются группами AD.

Ключи водителей не копируем на диски. Выгружаем pfx и добавляем пользователям в реестр. Копии ключей храним на диске Backup G:\\КЛЮЧИ

Прямой проброс, защищен через RDP Defender.

**HV-Miran-SRV-Term2 -** подготовлен так как есть не устранимые проблемы с основным сервером, постепенный переезд всех пользователей будет.

Терминальный сервер Srv-Term02 - всех новых пользователей заводим на него, отдельный порт для сервера.

**HV-Miran-SRV-Bareos2 -** Система бэкапирование.

**HV-SB-SRV-WEB1C -** Web сервер для 1С  на ubuntu.

**HV-Miran-NET-Gate** Шлюз для всех ВМ.

**ProLiant DL360 Gen9**

**Гипервизор VMWare ESXi –** [**virt1.hvalwaters.ru**](http://virt1.hvalwaters.ru)

**HV-Miran-Srv-1C_2** Сервер 1С, был пересетаплен после падения рабочего (HV-Miran-Srv-1C)



1C Предприятие, 1С+MSSQL

Имя: hwdb2

Не входит в домен hv.local



**HV-Miran-SRV-Bareos** - Сервер бэкапирвоания