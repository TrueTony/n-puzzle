# N-puzzle
Учебный проект Школы 21 по реализации алгоритма решения пятнашек с применением алгоритма A*

## О проекте
Цель проекта - написать программу для решений пятнашек использующую A* алгоритм или одну из его реализаций.
Вы начинаете с квадратного поля размером N*N клеток. Одна из клеток пустая, остальные заполнены цифрами начиная с 1 до N-1. Алгоритм поиска должен найти корректную последовательность ходов что бы достичь финальное состояние, оно же "улиточное решение", которое зависит от размера доски.

## Реализация
- Поиск решения занимает несколько секунд для пазла размера 3x3
- Реализация Манхэттенская  дистанции (A*)
- Реализация Евклидовой дистанции
- Реализация линейного конфликта
- Реализация Жадного поиска
- Использование Priorupy Queue

## Использование
[флаги] [путь до файла] <br>
*h* - помощь <br>
*e* - евклидова дистанция <br>
*m* - манхэттенская дистанция <br>
*l* - линейный конфликт <br>
Без использования флагов будем использоваться жадный поиск
