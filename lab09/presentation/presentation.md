---
## Front matter
lang: ru-RU
title: Лабораторная работа №9
subtitle: Модель «Накорми студентов»
author:
  - Герра Максимиано
institute:
  - Российский университет дружбы народов, Москва, Россия

## i18n babel
babel-lang: russian
babel-otherlangs: english

## Formatting pdf
toc: false
toc-title: Содержание
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

## Введение

**Цель работы**

Реализовать модель "Накорми студентов" в CPN Tools.

**Задание**

- Реализовать модель "Накорми студентов" в CPN Tools;
- Вычислить пространство состояний, сформировать отчет о нем и построить граф.

## Выполнение лабораторной работы

Рассмотрим пример студентов, обедающих пирогами. Голодный студент становится сытым после того, как съедает пирог.

Таким образом, имеем:

- два типа фишек: «пироги» и «студенты»;
- три позиции: «голодный студент», «пирожки», «сытый студент»;
- один переход: «съесть пирожок».

## Выполнение лабораторной работы

![Граф сети модели «Накорми студентов»](image/1.png){#fig:001 width=70%}

## Выполнение лабораторной работы

![Декларации модели «Накорми студентов»](image/2.png){#fig:002 width=70%}

## Выполнение лабораторной работы

![Модель «Накорми студентов»](image/3.png){#fig:003 width=50%}

## Выполнение лабораторной работы

![Запуск модели «Накорми студентов»](image/4.png){#fig:004 width=70%}

## Упражнение

```
 Statistics
------------------------------------------------------------------------
  State Space
     Nodes:  4
     Arcs:   3
     Secs:   0
     Status: Full

  Scc Graph
     Nodes:  4
     Arcs:   3
     Secs:   0
```

## Упражнение

```
 Boundedness Properties
------------------------------------------------------------------------
  Best Integer Bounds
                             Upper      Lower
     nakormi_studenta'food 1 5          2
     nakormi_studenta'hungry_student 1
                             3          0
     nakormi_studenta'satisfied_student 1
                             3          0
```

## Упражнение

![ Пространство состояний для модели «Накорми студентов»](image/5.png){#fig:005 width=50%}

## Выводы

В процессе выполнения данной лабораторной работы я реализовал модель "Накорми студентов" в CPN Tools.
