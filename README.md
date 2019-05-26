﻿# Требования к проекту
---

# Содержание

1. [Введение](#intro)  
1.1. [Назначение](#appointment)  
1.2. [Бизнес-требования](#business)  
1.2.1. [Исходные данные](#data)  
2. [Требования пользователя](#requirements)  
2.1. [Программные интерфейсы](#interfaces)  
2.2. [Интерфейс пользователя](#ui)  
2.3. [Характеристики пользователей](#users)  
2.4. [Предположения и зависимости](#dependence)  
3. [Системные требования](#systemreq)  
3.1. [Функциональные требования](#functionalreq)  
3.2. [Нефункциональные требования](#nonfunctionalreq)  
3.2.1. [Атрибуты качества](#qa)  
3.2.2. [Требования к безопасности](#security)  


<a name = "intro"/>

# 1 Введение

Тип приложения: нативное мобильное веб-приложение

Название продукта: чат-мессенджер для Android 


<a name = "appointment"/>

## 1.1. Назначение

В данном документе описываются требования для mobile-приложения мессенджер для Android. Этот документ ориентирован на людей, которые будут заниматься разработкой и последующим тестированием данного приложения. Данный вариант документа является первой редакцией.


<a name = "business"/>

## 1.2. Бизнес требования


<a name = "data"/>

### 1.2.1. Исходные данные

Внедрение чат-мессенджера позволит клиентам общаться между собой путем обмена сообщениями.


<a name = "requirements"/>

# 2. Требования пользователя


<a name = "interfaces"/>

## 2.1 Программные интерфейсы

* Приложение должно предоставлять пользователю возможность отправки и получения сообщений другим пользователям.
* Приложение должно оповещать пользователя о входящем сообщении от другого пользователя.
* Приложение должно предоставлять возможность просмотра списка контактов пользователя


<a name = "ui"/>

## 2.2. Интерфейс пользователя


<a name = "users"/>

## 2.3. Характеристики пользователей

Разбиения на классы пользователей не предполагается. Все пользователи равны в своих правах и возможностях.


<a name = "dependence"/>

## 2.4. Предположения и зависимости

* Приложение будет некорректно работать на устройстве, версия Android которого ниже, чем минимальная поддерживаемая версия, для которой осуществлялась разработка приложения.
* Приложение не будет приостанавливать свою работу, а также некорректно её завершать. 
* Приложению требуется доступ к интернету для отправки и получения сообщений.

<a name = "systemreq"/>

# 3. Системные требования

Приложение может работать под упралением семейства операционных систем Android (вер. 5.0 и выше).


<a name = "functionalreq"/>

## 3.1. Функциональные требования

| Функция | Требование |
| :------: | :-------: |
 

<a name = "nonfunctionalreq"/>

## 3.2. Нефункциональные требования


<a name = "qa"/>

### 3.2.1. Атрибуты качества

Атрибуты, важные для пользователей:
1. Доступность. Приложение должно быть доступно для пользователей круглосуточно.
2. Удобство и простота использования.
3. 

Атрибуты, важные для разработчиков:

4. Легкость в эксплуатации
5. Тестируемость. Максимальная цикломатическая сложность модуля (количество логических ответвлений в модуле исходного кода) не должна превышать 50.


<a name = "security"/>

### 3.2.2. Требования к безопасности

Надежное функционирование автоматизированной системы должно быть обеспечено выполнением организационно-технических мероприятий, таких как:

- использование лицензионного программного обеспечения;
- организация бесперебойного питания путем использования блоков бесперебойного питания;

Загрузка и отображение основного окна программы не должны превышать 5 секунд. 
