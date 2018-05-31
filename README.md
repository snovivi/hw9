## Регулярные выражения ##

В данном задании производилась "редакция" текста "Повесть временных лет" с использованием регулярных выражений.

**_Ссылка на файл с текстом, который получился после обработки:_**

[result.txt.link](https://github.com/snovivi/hw9/blob/master/result.txt)

**_задание 1_**

Для удаления всех пустых строк потребовалось два этапа.
* Сначала мы удаляем строки без пробелов, для этого используем регулярное выражение: \n\r, заменяем все вхождения \0.
* Второй этап - удаляем строки, которые начинаются с пробела. Использовалось регулярное выражение: \s\n\r, заменила все вхождения на \0. 

![](https://github.com/snovivi/hw9/blob/master/Снимок%20экрана%202018-05-25%20в%2022.42.01.png)
![](https://github.com/snovivi/hw9/blob/master/Снимок%20экрана%202018-05-25%20в%2022.42.30.png)

**_задание 2_**

* Для поиска князей и городов, чьи имена и названия заканчиваются на "слав" использовалось регулярное выражение: [А-я][a-я](символ звезды)слав[a-я](символ звезды)
* Всего упоминаний о князьях и городах найдено: 592

![](https://github.com/snovivi/hw9/blob/master/Снимок%20экрана%202018-05-25%20в%2022.45.56.png)
![](https://github.com/snovivi/hw9/blob/master/Снимок%20экрана%202018-05-25%20в%2022.48.39.png)

**_задание 3_**

* Для поиска всех упоминаний Нвгорода в различных написаниях использовалось регулярное выражение: Нов.гор
* Всего упоминаний Новогорода найдено: 57

![](https://github.com/snovivi/hw9/blob/master/Снимок%20экрана%202018-05-25%20в%2022.54.46.png)

**_Бонусное задание_**

Для того, чтобы поставить после каждого знака припинания пробел использовалось следубщее регулярное выражение: [(-+)!?".,:;]
Заменила все на: $&

![](https://github.com/snovivi/hw9/blob/master/Снимок%20экрана%202018-05-31%20в%2022.28.36.png)
