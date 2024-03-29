---
author: Зорин Арсений Геннадьевич
title: Разработка системы обнаружения замаскированных лиц и потенциально опасных персон
date: 24.10.2019
---

## Описание проблемы

- Высокие затраты при масштабировании
- Человеческий фактор 

## Примеры успешного внедрения машинного обучения

### 
Система фиксации нарушений ПДД по видеоизображению

<img src="pics/pdd_olvia.jpg" alt="drawing" height="500"/>

### 

Система отслеживания нарушений правил безопасности с помощью видеоаналитики
![](pics/center2m.jpg)

###

Автоматическое обнаружение видимых дефектов на выпускаемой продукции

###

Интеллектуальное управление дорожным движением

![](pics/traffic.jpg)

::: notes

* Ольвия, ООО "Технологии распознавания"
* Центр2М
* Do not know
* axxonsoft
:::

## Имеющиеся на рынке решения

### Подходы

* Предсказание ключевых точек
* Поиск Haar-подобных характеристик
* HOG + Adaboost классификатор

###

![](pics/timeline2.jpg)

###

![](pics/timeline1.jpg)

## Предлагаемый подход

### Принцип действия

* Поиск лица
* Поиск частей лица
* Классификация лица (открытое/закрытое)

### Для поиска лица и частей лица используются сверточные нейронные сети
### Вывод о закрытости лица основывается на найденных частях лица

## Пример работы

### 

<img src="pics/results.png" alt="drawing" height="600"/>

###

![](pics/giphy.gif)

###

* Точность 83.42% 
* Ресурсоэффективный алгоритм
* Запущен на тестовом стенде

## Недостатки метода

### Закрытое лицо не всегда преступное

### Результат детектирования зависит от размеров лица

###

<img src="pics/graph.png" alt="drawing" height="600"/>

## Поведенческая модель

### Принцип работы

Сравнение выполняемых человеком действий со стандартными в данной ситуацией

###

Для построения поведенческой модели необходим анализ большого количества данных


## Возможные области применения 

* Отделения банков
* Транспортные хабы
* Общедоступные гос. учреждения
* Стадионы
* Места проведения массовых мероприятий

## План действий

### 

<img src="pics/roadmap.png" alt="drawing" height="600"/>

##

 **Разработка системы обнаружения замаскированных лиц**

* Первый этап:
  * Детектор замаскированных лиц
* Второй этап:
  * Детектор замаскированных лиц с улучшенным набором данных
  * Детектор девиантного поведения

## 
- E-mail: arseny.zorin@spbpu.com
- GitHub: https://github.com/ArsenyZorin
- GitLab: https://gitlab.com/ArsenyZorin

