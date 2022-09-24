# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #1 выполнил(а):
- Деньщик Дарья Дмитриевна
- РИ-210950
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | # | 60 |
| Задание 2 | # | 20 |
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
- Задание 3.
- Код реализации выполнения задания. Визуализация результатов выполнения (если применимо).
- Выводы.
- ✨Magic ✨

## Цель работы
Ознакомиться с основными операторами зыка Python на примере реализации линейной регрессии.

## Задание 1
### Написать команды 'Hello World' на Python и Unity
Ход работы:
- Для Python в отчете привести скриншоты с демонстрацией сохранения документа google.colab на свой диск с запуском программы, выводящей сообщение 'Hello World'.
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192080501-390592d2-09b5-4b7e-bd7c-68b2e412b547.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192080504-45dae688-9535-44e3-bae3-02d995098982.png">
- Для Unity в отчете привести скриншот вывода сообщения 'Hello World' в консоль.

## Задание 2
### В разделе "Ход работы" пошагово выполнить каждый пункт с описанием и примером реализации задачи по теме лабораторной работы
Ход работы:
- Произвести подготовку данных для работы с алгоритмом линейной регрессии. 10 видов данных были установлены случайным образом, и данные находились в линейной зависимости. Данные проебразуются в формат массива, чтобы их можно было вычислить напрямую при использовании умножения и сложения.
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192080618-349dbcd5-2d42-49e8-9bba-dd9d3166feaf.png">

- Определите связанные функции. Функция модели: определяет модель линейной регрессии wx+b. Функция потерь: функция потерь среднеквадратичной ошибки. Функция оптимизации: метод градиентного спуска для нахождения частных производных w и b.
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192080826-d75793a6-2825-4e90-a531-0210ac278c07.png">

- Начать итерацию

- - Шаг 1. Инициализация и модель итеративной оптимизации
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192081041-604e7270-4056-4c97-93d4-ce430b18b24b.png">

- - Шаг 2. На второй итерации отображаются значения параметров, значения потерь и эффекты визуализации после итерации
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192081108-b42d661d-5ff6-4f93-8b4e-9df3f4faf042.png">

- - Шаг 3. Третья итерация показывает значения параметров, значения потерь и визуализацию после итерации
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192081131-f2e67f68-4f76-47ab-a088-f4246ee9efcc.png">

- - Шаг 4. На четвертой итерации отображаются значения параметров, значения потерь и эффекты визуализации
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192081147-f40872e8-bb2d-4b26-a1c3-eeb403b06650.png">

- - Шаг 5. Пятая итерация показывает значение параметра, значение потерь и эффект визуализации после итерации
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192081154-2457c7c6-873f-44d2-846e-fde5c2405d35.png">

- - Шаг 6. 10000-я итерация, показывающая занчения параметров, потери и визуализацию после итерации
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192081182-209fae10-a7da-46f9-9340-ecd68c2fc3dc.png">

## Задание 3
### Изучить код на Python и ответить на вопросы:

- Должна ли величина loss стремиться к нулю при изменении исходных данных? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ.

- - loss стремиться к нулю если разница между x[i] и y[i] стремится к нулю => Например сделаем x и y одинаковыми, в таком случае значение loss будет минимальным
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192081934-9b11ddbd-10fd-4a07-a9e9-6332af2b8501.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192082001-ccdbc592-45de-4844-925c-8c6f55791d40.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192082027-0ca1cbee-9615-444c-90de-97c10f975b12.png">
- - Но если разница между x[i] и y[i] будет большой => Например сделаем x и y одинаковыми, в таком случае значение loss будет минимальным


- Какова роль параметра Lr? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ. В качестве эксперимента можете изменить значение параметра.


## Выводы

Абзац умных слов о том, что было сделано и что было узнано.

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
