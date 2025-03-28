---
title: Языки научного программирования.
summary: Короткий рассказ о языках научного программирования.
date: 2024-11-16
authors:
  - admin
tags:
  - Markdown
  - РУДН
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com)'
---

# Языки научного программирования.

В компьютерном программированиинаучный язык программирования может относиться к двум уровням одной и той же концепции.

В широком смысле научный язык программирования — это язык программирования, который широко используется в вычислительной науке и вычислительной математике. В этом смысле C/C++ и Python можно считать научными языками программирования.

В более широком смысле научный язык программирования — это язык, разработанный и оптимизированный для использования математических формул и матриц.[1] Такие языки характеризуются не только наличием библиотек, выполняющих математические или научные функции, но и синтаксисом самого языка.[2] Например, ни в C++, ни в Python нет встроенных типов матриц или функций для матричной арифметики (сложения, умножения и т. д.); вместо этого эти функции доступны через стандартные библиотеки. К научным языкам программирования в более широком смысле относятся ALGOL, APL, Fortran, J, Julia, Maple, MATLAB, Octave и R.[3][4]

Научные языки программирования не следует путать с научным языком в целом, который в широком смысле относится к более высоким стандартам точности, корректности и лаконичности, ожидаемым от специалистов, использующих научный метод.

# Примеры

## Линейная алгебра

Научные языки программирования предоставляют возможности для работы с линейной алгеброй. Например, следующая программа на Julia решает систему линейных уравнений:

A = rand(20, 20)  # A — матрица 20x20
b = rand(20)      # b — вектор из 20 элементов
x = A\b           # x — решение уравнения A*x = b

Работа с большими векторами и матрицами является ключевой особенностью этих языков, поскольку линейная алгебра закладывает основу для математической оптимизации, которая, в свою очередь, позволяет использовать такие важные приложения, как глубокое обучение.

## Математическая оптимизация

В научном языке программирования мы можем вычислять оптимумы функций с помощью синтаксиса, близкого к математическому языку. Например, следующий код на Julia находит минимум полинома $ P(x,y)=x^{2}-3xy+5y^{2}-7y+3 $

используя Optim

P(x,y) = x^ 2 - 3x*y + 5y^ 2 - 7y + 3

z₀ = [ 0.0
       0.0 ]     # отправная точка для алгоритма оптимизации

optimize(z -> P(z...), z₀, Newton();
         autodiff = : вперед)

В этом примере используется метод Ньютона для минимизации. Современные языки научного программирования используют автоматическое дифференцирование для вычисления градиентов и матриц Гессе функции, заданной в качестве входных данных; см. дифференцируемое программирование. Здесь для этой задачи было выбрано автоматическое дифференцирование в прямом направлении. Более старые языки научного программирования, такие как почтенный Фортран, требовали от программиста передачи, помимо оптимизируемой функции, функции, вычисляющей градиент, и функции, вычисляющей матрицу Гессе.

Чем больше известно о минимизируемой функции, тем более эффективные алгоритмы можно использовать. Например, выпуклая оптимизация обеспечивает более быстрые вычисления, когда функция является выпуклой, квадратичное программирование обеспечивает более быстрые вычисления, когда функция является квадратичной по своим переменным, а линейное программирование — когда функция является линейной.