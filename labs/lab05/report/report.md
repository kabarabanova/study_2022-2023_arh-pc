---
## Front matter
title: "Отчёта по лабораторной работе №5"
author: "Барабанова Кристина Андреевна"

## Generic otions
lang: ru-RU
toc-title: "Содержание"

## Bibliography
bibliography: bib/cite.bib
csl: pandoc/csl/gost-r-7-0-5-2008-numeric.csl

## Pdf output format
toc: true # Table of contents
toc-depth: 2
lof: true # List of figures
lot: true # List of tables
fontsize: 12pt
linestretch: 1.5
papersize: a4
documentclass: scrreprt
## I18n polyglossia
polyglossia-lang:
  name: russian
  options:
	- spelling=modern
	- babelshorthands=true
polyglossia-otherlangs:
  name: english
## I18n babel
babel-lang: russian
babel-otherlangs: english
## Fonts
mainfont: PT Serif
romanfont: PT Serif
sansfont: PT Sans
monofont: PT Mono
mainfontoptions: Ligatures=TeX
romanfontoptions: Ligatures=TeX
sansfontoptions: Ligatures=TeX,Scale=MatchLowercase
monofontoptions: Scale=MatchLowercase,Scale=0.9
## Biblatex
biblatex: true
biblio-style: "gost-numeric"
biblatexoptions:
  - parentracker=true
  - backend=biber
  - hyperref=auto
  - language=auto
  - autolang=other*
  - citestyle=gost-numeric
## Pandoc-crossref LaTeX customization
figureTitle: "Рис."
tableTitle: "Таблица"
listingTitle: "Листинг"
lofTitle: "Список иллюстраций"
lotTitle: "Список таблиц"
lolTitle: "Листинги"
## Misc options
indent: true
header-includes:
  - \usepackage{indentfirst}
  - \usepackage{float} # keep figures where there are in the text
  - \floatplacement{figure}{H} # keep figures where there are in the text
---

# Цель работы

Освоение процедуры компиляции и сборки программ, написанных на ассемблере NASM.


# Выполнение лабораторной работы

1. Создала текстовый файл с именем hello.asm (рис. [-@fig:001])

![создание текстового файла](image/1.jpg){ #fig:001 width=70% }

2. Открыла этот файл с помощью текстового редактора gedit (рис. [-@fig:002])

![открытие файла с помощью тектового редактора gedit](image/2.jpg){ #fig:002 width=70% }

3. Ввела в него следующий текст: (рис. [-@fig:003])

![данный текст в редакторе gedit](image/3.jpg){ #fig:003 width=70% }

4. Скомпилировала приведённый выше текста программы «Hello World» (рис. [-@fig:004])

![компиляция программы](image/4.jpg){ #fig:004 width=70% }

5. Выполнила следующую команду, которая компилирует исходный файл hello.asm в obj.o (рис. [-@fig:005])

![компиляция исходного файла hello.asm в obj.o](image/5.jpg){ #fig:005 width=70% }

6. С помощью команды ls проверила, что файлы были созданы. (рис. [-@fig:006])

![проверка](image/6.jpg){ #fig:006 width=70% }

7. Передала объектный файл на обработку компоновщику (рис. [-@fig:007])

![передача объектного файла на обработку компоновщику](image/7.jpg){ #fig:007 width=70% }

8. Выполнила следующую команду (рис. [-@fig:008])

![выполнение следущей команды](image/8.jpg){ #fig:008 width=70% }

9. Запустила на выполнение созданный исполняемый файл, находящийся в
текущем каталоге (рис. [-@fig:009])

![запуск на выполнение созданный исполняемый файл](image/9.jpg){ #fig:009 width=70% }

10. С помощью команды cp создала копию файла hello.asm с именем lab5.asm (рис. [-@fig:010])

![создание копии файла hello.asm с именем lab5.asm](image/10.jpg){ #fig:010 width=70% }

11. С помощью текстового редактора внесла изменения в текст программы в файле lab5.asm так, чтобы вместо Hello world! на экран выводилась строка с моими фамилией и именем. Оттранслировала полученный текст программы lab5.asm в объектный файл. Выполнила компоновку объектного файла и запустила получившийся исполняемый файл (рис. [-@fig:011])

![трансляция полученного текста программы lab5.asm в объектный файл. Выполнение компоновки объектного файла и запуск получившегося исполняемого файла](image/11.jpg){ #fig:011 width=70% }



# Выводы

Я освоила процедуры компиляции и сборки программ, написанных на ассемблере NASM.


