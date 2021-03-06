---
## Front matter
lang: ru-RU
title: "Презентация по лабораторной работе 9"
author: "Елизавета Александровна Гайдамака"

## Formatting
toc: false
slide_level: 2
theme: metropolis
header-includes: 
 - \metroset{progressbar=frametitle,sectionpage=progressbar,numbering=fraction}
 - '\makeatletter'
 - '\beamer@ignorenonframefalse'
 - '\makeatother'
aspectratio: 43
section-titles: true
---

# Цель работы

Познакомиться с операционной системой Linux. Получить практические навыки работы с редактором Emacs.

# Задание

1. Открыть emacs.
2. Создать файл lab07.sh с помощью комбинации Ctrl-x Ctrl-f (C-x C-f).
3. Наберите текст
4. Сохранить файл с помощью комбинации Ctrl-x Ctrl-s (C-x C-s).
 Проделать с текстом стандартные процедуры редактирования, каждое действие должно осуществляться комбинацией клавиш.
  - 5.1. Вырезать одной командой целую строку (С-k).
  - 5.2. Вставить эту строку в конец файла (C-y).
  - 5.3. Выделить область текста (C-space).
  - 5.4. Скопировать область в буфер обмена (M-w).
  - 5.5. Вставить область в конец файла.
  - 5.6. Вновь выделить эту область и на этот раз вырезать её (C-w).
  - 5.7. Отмените последнее действие (C-/).

#

6. Научитесь использовать команды по перемещению курсора.
- 6.1. Переместите курсор в начало строки (C-a).
- 6.2. Переместите курсор в конец строки (C-e).
- 6.3. Переместите курсор в начало буфера (M-<).
- 6.4. Переместите курсор в конец буфера (M->).
7. Управление буферами.
- 7.1. Вывести список активных буферов на экран (C-x C-b).
- 7.2. Переместитесь во вновь открытое окно (C-x) o со списком открытых буферов
и переключитесь на другой буфер.
- 7.3. Закройте это окно (C-x 0).
- 7.4. Теперь вновь переключайтесь между буферами, но уже без вывода их списка на
экран (C-x b).

#

8. Управление окнами.
- 8.1. Поделите фрейм на 4 части: разделите фрейм на два окна по вертикали (C-x 3),
а затем каждое из этих окон на две части по горизонтали (C-x 2) (см. рис. 9.1).
- 8.2. В каждом из четырёх созданных окон откройте новый буфер (файл) и введите
несколько строк текста.
9. Режим поиска
- 9.1. Переключитесь в режим поиска (C-s) и найдите несколько слов, присутствующих
в тексте.

#

- 9.2. Переключайтесь между результатами поиска, нажимая C-s.
- 9.3. Выйдите из режима поиска, нажав C-g.
- 9.4. Перейдите в режим поиска и замены (M-%), введите текст, который следует найти
и заменить, нажмите Enter , затем введите текст для замены. После того как будут
подсвечены результаты поиска, нажмите ! для подтверждения замены.
- 9.5. Испробуйте другой режим поиска, нажав M-s o. Объясните, чем он отличается от
обычного режима?

# Теоретическое введение

1. Кратко охарактеризуйте редактор emacs.

Emacs представляет собой мощный экранный редактор текста, написанный на языке
высокого уровня Elisp.

2. Какие особенности данного редактора могут сделать его сложным для освоения новичком?

В emacs большую роль играет командная строка, это может быть сложно начинающим, т.к. они могут не знать команд.

#

3. Своими словами опишите, что такое буфер и окно в терминологии emacs’а.

Буфер это какой-то текст. Окно это часть фрейма, где отображается буфер.

4. Можно ли открыть больше 10 буферов в одном окне?

Да

#

5. Какие буферы создаются по умолчанию при запуске emacs?

`*GNU Emacs*`
`*scratch*`
`*Messages*`
`*Disabled Command*`

6. Какие клавиши вы нажмёте, чтобы ввести следующую комбинацию C-c | и C-c C-|?

Ctrl-c и |
Ctrl-c
Ctrl-|

7. Как поделить текущее окно на две части?

C-x 3

#

8. В каком файле хранятся настройки редактора emacs?

.emacs

9. Какую функцию выполняет клавиша `влево` и можно ли её переназначить?

Клавиша влево переместит курсор на один символ влево. 

10. Какой редактор вам показался удобнее в работе vi или emacs? Поясните почему.

Vi, потому что его быстрее открывать, и он лично мне понятнее.

# Выполнение лабораторной работы

Открываем emacs

![Рис.1](image\picture1.png)  

#

Создаем новый файл.

![Рис.2](image\picture2.png)  

#

Вбиваем текст.

![Рис.3](image\picture3.png) 

#

Вырезаем строку и вставляем в конец.

![Рис.4](image\picture4.png)  

#

Копируем, вставляем.

![Рис.5](image\picture5.png)  

#

Выделяем, вырезаем.

![Рис.6](image\picture6.png)  

#

Выводим все буферы.

![Рис.7](image\picture7.png)  

#

Открываем буфер.

![Рис.8](image\picture8.png)  

#

Закрываем второй буфер. Переключаемся на другой буфер.

![Рис.9](image\picture9.png)

#

Делим окно на 4 буфера.

![Рис.10](image\picture10.png)

#

Открываем новые буферы.

![Рис.11](image\picture11.png)

#

Производим поиск по фразе.

![Рис.12](image\picture12.png)  

#

Производим поиск по фразе другим способом.

![Рис.13](image\picture13.png)  

# Выводы

Благодаря данной работе я изучила идеологию и применение средств контроля версий и получила умения работы с git.
