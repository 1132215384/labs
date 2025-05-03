---
## Front matter
##lang: ru-RU
title: "Лабораторная работа №13"
subtitle: "Задание для самостоятельного выполнения"
author:
  "- Герра Гарсия Максимиано"
institute:
  "- Российский университет дружбы народов, Москва, Россия"

## i18n babel
##babel-lang: russian
##babel-otherlangs: english

## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
	name: english

## Formatting pdf
#toc: false
#toc-title: Содержание
slide_level: 2
aspectratio: 169
section-titles: true
theme: metropolis
header-includes:
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
---

# Информация

## Постановка задачи

1. Используя теоретические методы анализа сетей Петри, провести анализ сети (с помощью построения дерева достижимости). Определить, является ли сеть безопасной, ограниченной, сохраняющей, имеются ли
тупики.
2. Промоделировать сеть Петри с помощью CPNTools.
3. Вычислить пространство состояний. Сформировать отчёт о пространстве состояний и проанализировать его.Построить граф пространства состояний.

## Описание модели

![Сеть для выполнения домашнего задания](image/1.png){#fig:001 width=40%}

## Анализ сети Петри

![Дерево достижимости](image/2.png){#fig:002 width=50%}

## Реализация модели в CPN Tools

![Модель задачи в CPN Tools](image/3.png){#fig:003 width=70%}

## Реализация модели в CPN Tools

![Задание деклараций](image/4.png){#fig:004 width=50%}

## Реализация модели в CPN Tools

![Запуск модели](image/5.png){#fig:005 width=70%}

## Пространство состояний

![Граф пространства состояний](image/6.png){#fig:006 width=70%}

## Пространство состояний

```
 Statistics
------------------------------------------------------------------------

  State Space
     Nodes:  5
     Arcs:   10
     Secs:   0
     Status: Full
```

## Выводы

В результате выполнения данной лабораторной работы я выполнил задание для самостоятельного выполнения, а именно провел анализ сети Петри, построил сеть в CPN Tools, построил граф состояний и провел его анализ.
