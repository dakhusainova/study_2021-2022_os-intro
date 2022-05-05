---
## Front matter
title: "Индивидуальный проект"
subtitle: "Первый этап Размещение на Github pages заготовки для персонального сайта."
author: "Хусаинова Динара Айратовна"

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

Разместить на Github pages заготовки для персонального сайта.

# Задание

- Установить необходимое программное обеспечение.
- Скачать шаблон темы сайта.
- Разместить его на хостинге git.
- Установить параметр для URLs сайта.
- Разместить заготовку сайта на Github pages.


# Выполнение лабораторной работы

1. Скачиваем исполняемый файл для hugo(рис. [-@fig:001])

![Качаем файл](image/1.jpg){ #fig:001 width=70% }

2. Создаем папку bin и перемещаем туда исполняемый файл (рис. [-@fig:002])

![Помещаем в нужную папку](image/2.jpg){ #fig:002 width=70% }

3. Переходим в репозиторий starter-hugo-academic и создаем по его шаблону репозиторий blog (рис. [-@fig:003],[-@fig:004] )

![Создаем новый репозиторий1](image/3.jpg){ #fig:003 width=70% }

![Создаем новый репозиторий2](image/4.jpg){ #fig:004 width=70% }

4. Клонируем этот репозиторий к себе (рис. [-@fig:005], [-@fig:006])

![Клонирование1](image/5.jpg){ #fig:005 width=70% }

![Клонирование2](image/6.jpg){ #fig:006 width=70% }

5. Устанавливаем golang (рис. [-@fig:008]).

![Установка](image/8.jpg){ #fig:008 width=70% }

6. В папке blog замечаем каталог public, затем его удаляем на время (рис. [-@fig:009],[-@fig:010])

![Видим public](image/9.jpg){ #fig:009 width=70% }

![Удаляем](image/10.jpg){ #fig:010 width=70% }

7. Выполняем hugo server, копируем ссылку в конце сообщения и проходим на наш сайт с заготовками( рис. [-@fig:011],[-@fig:012],[-@fig:013]).

![Выполняем команду](image/11.jpg){ #fig:011 width=70% }

![Проходим по ссылке](image/12.jpg){ #fig:012 width=70% }

![Открываем сайт](image/13.jpg){ #fig:013 width=70% }

8. Удаляем определенный сайт для того, чтобы избавиться от предупреждения в начале нашего сайта (рис. [-@fig:014]).

![Удаление файла](image/14.jpg){ #fig:014 width=70% }

9. Создаем новый репозиторий, клонируем его к себе, создаем в нем файл README.md и загружаем все в GitHub(рис. [-@fig:015],[-@fig:016], [-@fig:017], [-@fig:018]).

![Создание](image/15.jpg){ #fig:015 width=70% }

![Клонируем](image/16.jpg){ #fig:016 width=70% }

![Отправляем все на сайт](image/17.jpg){ #fig:017 width=70% }

![Наблюдаем наше обновление](image/18.jpg){ #fig:018 width=70% }

10. Помещаем все файлы для сайта в каталог public, потом комментируем public в файле gitignore (рис. [-@fig:019], [-@fig:020], [-@fig:021]).

![Пытаемся все переместить](image/19.jpg){ #fig:019 width=70% }

![Редактирование](image/20.jpg){ #fig:020 width=70% }

![Загружаем все в public](image/21.jpg){ #fig:021 width=70% }

11. Выполняем hugo и проверяем связь нашего репозитория с public (рис. [-@fig:022], [-@fig:023]).

![Выполнение](image/22.jpg){ #fig:022 width=70% }

![Проверяем](image/23.jpg){ #fig:023 width=70% }

12. Клонируем весь каталог public (рис. [-@fig:024]).

![Клонируем](image/24.jpg){ #fig:024 width=70% }

13. Открываем сайт и видим наши заготовки (рис. [-@fig:025]).

![Открытие сайта](image/25.jpg){ #fig:025 width=70% }

# Выводы

Разместили на Github pages заготовки для персонального сайта.

::: {#refs}
:::