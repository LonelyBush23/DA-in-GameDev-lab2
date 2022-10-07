# АНАЛИЗ ДАННЫХ И ИСКУССТВЕННЫЙ ИНТЕЛЛЕКТ [in GameDev]
Отчет по лабораторной работе #2 выполнил(а):
- Деньщик Дарья Дмитриевна
- РИ-210950
Отметка о выполнении заданий (заполняется студентом):

| Задание | Выполнение | Баллы |
| ------ | ------ | ------ |
| Задание 1 | * | 60 |
| Задание 2 | * | 20 |
| Задание 3 | * | 20 |

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
Познакомиться с программными средствами для организции передачи данных между инструментами google, Python и Unity

## Задание 1
### Реализовать совместную работу и передачу данных в связке Python - Google-Sheets – Unity. При выполнении задания используйте видео-материлы и исходные данные, предоставленные преподавателя курса.
Ход работы:
- В облачном сервисе google console подключить API для работы с google sheets и google drive.
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/194570191-fd6ba23e-7e3e-42bd-934b-1b5f5d40ac2a.png">

- Реализовать запись данных из скрипта на python в google-таблицу. Данные описывают изменение темпа инфляции на протяжении 11 отсчётных периодов, с учётом стоимости игрового объекта в каждый период.
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/194570312-4a5d37dc-8716-451b-ae6c-c58677aaabde.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/194570367-28daff36-e229-45f7-a1c3-9f2316536866.png">

- Создать новый проект на Unity, который будет получать данные из google-таблицы, в которую были записаны данные в предыдущем пункте.
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/194598058-d45f1605-3d90-41d4-b097-ae6144980117.png">

- Написать функционал на Unity, в котором будет воспризводиться аудио-файл в зависимости от значения данных из таблицы.
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/194598132-45faecf4-bcd0-4e1b-8056-2e64cc87cd6a.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/194598182-ad50efa8-d9bd-439f-bf9f-cddaa52390ac.png">

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

- - При изменении исходных данных величина loss не обязатеьно стремится к нулю, тк функция loss_function зависит не только от y[] и x[], но так же от a и b, значение которых случайно(в промежутке между 0 и 1) => Напимер, если мы изменим данные так, чтобы  y[] = x[], то loss может принимать значение многобольше нуля, так и значение близкое к ему
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192108304-878e63b3-faa8-43d7-a863-103bec308dcf.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192108721-855841ca-94f6-4021-b80d-2d96d5be29a0.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192108753-ad4ba61b-7f4a-4fe7-8184-eac9ec5405f3.png">

- Какова роль параметра Lr? Ответьте на вопрос, приведите пример выполнения кода, который подтверждает ваш ответ. В качестве эксперимента можете изменить значение параметра.
- - Параметр Lr отвечает за наклон прямой на графике, чем меньше значение, тем больше угол с осью OX
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192108830-f2d84775-3e6d-43af-8fd9-9477a6f0950b.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192108843-c5a60f37-b1d1-4fda-9eb7-fa162dbbb1a4.png">
<img width="960" alt="image" src="https://user-images.githubusercontent.com/104368430/192108876-22845a40-7a0e-493f-9793-3bd58f5ee45c.png">

## Выводы
В ходе работы я освоила базовые навыки для работы в таких программах как Python и Unity, написала код для работы с алгоритмом линейной регрессии и изучила его.
