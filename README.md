## Регулярные выражения ##

В данном задании производилась "редакция" текста "Повесть временных лет" с использованием регулярных выражений.
* Для удаления всех пустых строк потребовалось два этапа. Сначала мы удаляем строки без пробелов, для этого используем регулярное выражение: \n\r, заменяем все вхождения \0. Второй этап - удаляем (которые начинаются с пробела). Использовалось регулярное выражение: \s\n\r, заменила все вхождения на \0
(фото)
* Для поиска князей и городов, чьи имена и названия заканчиваются на "слав" использовалось регулярное выражение: [А-я][a-я](сивол звезды)слав[a-я](символ звезды)
Всего упоминаний о князьях найдено: 592
Всего упоминаний о городах найдено:
(фото)
* Для поиска всех упоминаний Нвгорода в различных написаниях использовалось регулярное выражение: 
Всего упоминаний Новогорода найдено: 
