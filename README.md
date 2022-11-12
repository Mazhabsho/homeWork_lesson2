# homeWork_lesson2
# STRING

In JavaScript, the textual data is stored as strings.Strings can be enclosed(закрытый) within either single quotes, double quotes or backticks:
1.let single = 'single-quoted';

2.let double = "double-quoted";

3.let backticks = `backticks`;

Single and double quotes are essentially the same. Backticks, however, allow us to embed any expression into the string, by wrapping it in ${…}:
Another advantage of using backticks is that they allow a string to span multiple lines:let guestList = `Guests:
 * John
 * Pete
 * Mary
 * 
### String length

    The length property has the string length.Please note that str.length is a numeric property (числовое свойство), not a function. There is no need to add parenthesis after it. Not .length(), but .length.
 
 ##### charAt()
    The charAt() method returns the character at a specified index (position) in a string.The index of the first character is 0, the second 1, ...
    Exp:let text = "HELLO SOFTCLUB";
     let letter = text.charAt(1);
     
##### indexOf()

    Метод indexOf() возвращает индекс первого вхождения указанного значения в строковый объект String, на котором он был вызван, начиная с индекса fromIndex. Возвращает -1, если значение не найдено.

###### Синтаксис:

    str.indexOf(searchValue, [fromIndex])
1.searchValue - Строка, представляющая искомое значение.

2.fromIndex - Необязательный параметр. Местоположение внутри строки, откуда начинать поиск. Если fromIndex >= str.length, метод вернёт -1, но только в том случае, если searchValue не равен пустой строке, в этом случае он вернёт str.length.

##### split()

Метод split() возвращает новый массив.

##### slice()

Определение и использование

Метод slice() извлекает часть строки.

Метод slice() возвращает извлеченную часть в новой строке.

Метод slice() не изменяет исходную строку.

Параметры start и end указывают часть строки для извлечения.

Первая позиция равна 0, вторая равна 1, ...

В конце строки выбирается отрицательное число.
Parameters
Parameter 	Description
start 	Required.
The start position.
(First character is 0).
end 	Optional.
The end position (up to, but not including).
Default is string length.

##### replace()

- replace() выполняет поиск значения или регулярного выражения в строке.

- replace() возвращает новую строку с замененными значениями.

- replace() не изменяет исходную строку.
- Если вы замените значение, будет заменен только первый экземпляр. Чтобы заменить все экземпляры, используйте регулярное выражение с установленным модификатором gi.

##### trim()

        Метод trim() удаляет пробелы с обеих сторон строки.trim() не изменяет исходную строку.Метод TrimEnd() удаляет пробелы из конца строки и TrimStart() удаляет пробелы из начала строки.

##### search()

        Метод search() сопоставляет строку с регулярным выражением ** search() возвращает индекс (позицию) первого совпадения.Метод возвращает значение -1, если совпадение не найдено.
 
##### repeat()

        Метод repeat() возвращает строку с количеством копий строки.Метод возвращает новую строку. Syntax
        string.repeat(count)

##### concet()

        Метод concat() объединяет две или более строк.concat() не изменяет существующие строки.Метод возвращает новую строку.Syntax
        string.concat(string1, string2, ..., stringX)

##### toUpperCase()

        Метод toUpperCase() возвращает значение строки, преобразованное в верхний регистр. Этот метод не влияет на значение самой строки, поскольку строки JavaScript неизменяемы.Syntax

        toUpperCase()

      and so on
