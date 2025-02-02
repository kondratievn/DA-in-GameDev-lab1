# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Кондратьев Никита Алексеевич
- РИ-210949
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | # | 20 |

знак "*" - задание выполнено; знак "#" - задание не выполнено;

Работу проверили:
- к.т.н., доцент Денисов Д.В.
- к.э.н., доцент Панов М.А.
- ст. преп., Фадеев В.О.

[![N|Solid](https://cldup.com/dTxpPi9lDf.thumb.png)](https://nodesource.com/products/nsolid)

[![Build Status](https://travis-ci.org/joemccann/dillinger.svg?branch=master)](https://travis-ci.org/joemccann/dillinger)

Структура отчета

- Данные о работе: название работы, фио, группа, выполненные задания.
- Цель работы.
- Задание 1.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Задание 2.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Ознакомиться с основными операторами зыка Python на примере реализации линейной регрессии.

## Задание 1
### Пошагово выполнить каждый пункт раздела "ход работы" с описанием и примерами реализации задач
Ход работы: Написать программу с выводом 'Hello World' на Python и Unity.
На Python:

![2022-09-25_22-56-52](https://user-images.githubusercontent.com/113256538/192158618-7816e990-b159-4bf9-9cf0-bd7c495e457c.png)

На Unity:

![2022-09-25_12-32-37](https://user-images.githubusercontent.com/113256538/192158647-1311543b-20db-4a66-9f88-808e4c78d4b4.png)



## Задание 2
### В разделе "ход работы" пошагово выполнить каждый пункт с описанием и примером реализации задачи по теме лабораторной работы
1. Производим подготовку данных для работы с алгоритмом линейной регрессии. 10 видов данных были установлены случайным образом, и данные находились в линейной зависимости. Данные преобразуются в формат массива, чтобы их можно было вычислить напрямую при использовании умножения и сложения.

   ![2022-09-25_22-57-23](https://user-images.githubusercontent.com/113256538/192158752-12227bc2-4c7d-4c5d-99b6-d9c3dab10df4.png)
   
2. Определяем связанные функции. Функция модели: определяет модель линейной регрессии wx+b. Функция потерь: функция потерь среднеквадратичной ошибки. Функция оптимизации: метод градиентного спуска для нахождени частных производных w и b.

   ![2022-09-25_22-58-28](https://user-images.githubusercontent.com/113256538/192158832-922d3375-0820-454d-927e-79aed48bfb02.png)
   
3. Начинаем итерацию
   Шаг 1: инициализация и модель итеративной оптимизации
   
   ![2022-09-25_22-59-06](https://user-images.githubusercontent.com/113256538/192158890-61e7c446-6a47-49cd-b311-232875a9b16e.png)
   
   Шаг 2: на второй итерации отображаются значения параметров, значения потерь и эффекты визуализации после итерации
   
   ![2022-09-25_22-59-44](https://user-images.githubusercontent.com/113256538/192158973-1171d785-6f23-4822-8603-790c4a7a622e.png)
   
   Шаг 3: третья итерация показывает значения параметров, значения потерь и визуализацию после итерации
   
   ![2022-09-25_23-00-10](https://user-images.githubusercontent.com/113256538/192159013-aafd3a6f-362d-4aac-a8c2-6eeda0ce7fd0.png)
   
   Шаг 4: на четвертой итерации отображаются значения параметров, значения потерь и эффекты визуализации
   
   ![2022-09-25_23-00-26](https://user-images.githubusercontent.com/113256538/192159051-cb2b14de-8e01-436a-8e5c-6eb3a45700fc.png)
   
   Шаг 5: пятая итерация показывает значение параметра, значение потерь и эффект визуализации после итерации
   
   ![2022-09-25_23-00-47](https://user-images.githubusercontent.com/113256538/192159072-95497bbb-33d8-4abe-a4e9-b44eb01e11c9.png)
   
   Шаг 6: 10000-я итерация, показывающая значения параметров, потери и визуализацию после итерации
   
   ![2022-09-25_23-01-16](https://user-images.githubusercontent.com/113256538/192159098-70cd1061-d297-4961-87b2-b85323df2965.png)
   
   Вывод в консоль:
   
   ![2022-09-25_23-01-52](https://user-images.githubusercontent.com/113256538/192159650-d3a5adfb-dfee-4a17-bb45-be1d45e8e6f8.png)




## Выводы

В результате проделанной работы я ознакомился с основными операторами языка Python на примере реализации линейной регрессии. Вывел в консоль Unity и Python текст - "Hello World".

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| GitHub | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |

## Powered by

**BigDigital Team: Denisov | Fadeev | Panov**
