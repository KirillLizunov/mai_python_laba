# Отчет по лабораторной работе N 9 по курсу
# "Фундаментальная информатика"

Студент группы: M8О-115Б, Лизунов Кирилл Романович\
Контакты: kirill89828@mail.ru \
Работа выполнена: 17.12.2023\
Преподаватель: Чеснов Илья Игоревич

## 1. Тема

Программирование на языке C

## 2. Цель работы

Написание простейшей программы на языке C

## 3. Задание

25. Треугольник с вершинами в точках (-10,0),(0,10),(-10,20)
![image](https://github.com/KirillLizunov/mai_python_laba/assets/75213389/b071f69f-471a-444e-bc6e-d993d722ee28)


## 4. Оборудование

Процессор: Intel Core i5-8265U @ 8x 3.9GH\
ОП: 7851 Мб\
НМД: 1024 Гб\
Монитор: 1920x1080

## 5. Программное обеспечение

Операционная система семейства: **linux (ubuntu)**, версия **18.10 cosmic**\
Интерпретатор команд: **bash**, версия **4.4.19**.\
Система программирования: **--**, версия **--**\
Редактор текстов: **emacs**, версия **25.2.2**\
Утилиты операционной системы: **--**\
Прикладные системы и программы: **--**\
Местонахождение и имена файлов программ и данных на домашнем компьютере: **--**

## 6. Идея, метод, алгоритм решения задачи

Прогонять цикл от 1 до 50, пока не найдем ответ


## 7. Сценарий выполнения работы

План:

Создать структуру для точки
Создать функции для минимума, максимума, и сигнума
Создать функции для расчета i, j, l
Создать функцию для проверки принадлежности точки треугольнику
Запустить цикл. На каждой итерации создаем новую структуру из п.1 с помощью функций из п.2 и п.3. И проверяем новую точку на принадлежность к треугольнику. Если не попали, продолжаем цикл, если попали - выводим ответ

## 8. Распечатка протокола

```
i:   5 j:   5, l:   0
i:   0 j:  -3, l:   0
i:  -3 j:   3, l:   0
i:   0 j:   4, l: -14
i:   0 j:   5, l:   8
i:  -1 j:  -2, l:   0
i:   0 j:   7, l:  -2

Отановилось на итерации: 8
Финальные значения i: -4, j: 8, k: 6
Success

```

## 9. Дневник отладки

| № | Лаб. или дом. | Дата       | Время     | Событие                                                | Действие по исправлению   | Примечание     |
|---|---------------|------------|-----------|--------------------------------------------------------|---------------------------|----------------|
|1  | Дом           | 30.10.2023 | 13:50     | Неправильно написал функцию sign, она возвращала мне не тот знак для 0| Стал для 0 возвращать 1  | Часто забываю про нули  |
|2  | Дом           | 31.10.2023 | 02:50     | Не смог найти функции min, max | Написал свои | До C таким не занимался                |

## 10. Замечания автора по существу работы

Интересная работа, сон сняло - как рукой...

## 11. Выводы

Мы научились отладке и составлению простейшей программы на языке С и получили результат в виде сообщения об итоге движения: попадание в заданную область плоскости не более чем за 50 шагов. Работа занимательная, сниться мне будет долго...

