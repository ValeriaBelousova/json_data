# String Functions Reference

| Function | Description | Syntax | Arguments | Example |
|----------|------------|--------|-----------|---------|
| ascii | Возвращает Unicode-код первого символа строки. | `ascii(string)` | string — строка | `ascii('Q') → 81` |
| char | Возвращает символ по его Unicode-коду. | `char(code)` | code — числовой Unicode-код | `char(81) → 'Q'` |
| concat | Объединяет несколько строк в одну. NULL преобразуется в пустую строку, другие типы — в строки. | `concat(string1,string2…)` | string — строка | `concat('sun','set') → 'sunset'` |
| format | Форматирует строку с использованием аргументов. | `format(string,arg1,arg2…)` | string — шаблон с %1, %2<br>arg — любое значение | `format('This %1 a %2','is','test') → 'This is a test'` |
| format_date | Форматирует дату/время в строку по заданному шаблону. | `format_date(datetime,format[,language])` | datetime — дата/время<br>format — шаблон<br>language — язык | `format_date('2012-05-15','dd.MM.yyyy') → '15.05.2012'` |
| format_number | Форматирует число с учётом локали и количества знаков. | `format_number(number[,places][,language][,omit_group_separators][,trim_trailing_zeroes])` | number — число<br>places — знаки после запятой | `format_number(10000000.332,2) → '10,000,000.33'` |
| left | Возвращает первые n символов строки. | `left(string,length)` | string — строка<br>length — длина | `left('Hello World',5) → 'Hello'` |
| length | Возвращает длину строки или геометрии. | `length(value)` | string/geometry — значение | `length('hello') → 5` |
| lower | Преобразует строку в нижний регистр. | `lower(string)` | string — строка | `lower('HELLO') → 'hello'` |
| lpad | Дополняет строку слева до заданной длины. | `lpad(string,width,fill)` | string — строка<br>width — длина<br>fill — символ | `lpad('Hello',10,'x') → 'xxxxxHello'` |
| ltrim | Удаляет указанные символы в начале строки. | `ltrim(string[,characters])` | string — строка<br>characters — символы | `ltrim(' hello ') → 'hello '` |
| replace | Заменяет подстроки или значения в строке. | `replace(string,before,after)` | string — строка<br>before/after — значения | `replace('QGIS SHOULD','SHOULD','DOES') → 'QGIS DOES'` |
| right | Возвращает последние n символов строки. | `right(string,length)` | string — строка<br>length — длина | `right('Hello World',5) → 'World'` |
| rpad | Дополняет строку справа до заданной длины. | `rpad(string,width,fill)` | string — строка<br>width — длина<br>fill — символ | `rpad('Hello',10,'x') → 'Helloxxxxx'` |
| rtrim | Удаляет указанные символы в конце строки. | `rtrim(string[,characters])` | string — строка<br>characters — символы | `rtrim(' hello ') → ' hello'` |
| strpos | Возвращает позицию первого вхождения подстроки. | `strpos(haystack,needle)` | haystack — строка<br>needle — подстрока | `strpos('HELLO WORLD','WORLD') → 7` |
| substr | Возвращает часть строки. | `substr(string,start[,length])` | string — строка<br>start — позиция<br>length — длина | `substr('HELLO WORLD',3,5) → 'LLO W'` |
| title | Преобразует строку в формат заголовка. | `title(string)` | string — строка | `title('hello world') → 'Hello World'` |
| to_string | Преобразует число в строку. | `to_string(number)` | number — число | `to_string(123) → '123'` |
| trim | Удаляет пробелы в начале и конце строки. | `trim(string)` | string — строка | `trim(' hello ') → 'hello'` |
| upper | Преобразует строку в верхний регистр. | `upper(string)` | string — строка | `upper('hello') → 'HELLO'` |
| wordwrap | Разбивает строку на строки заданной длины. | `wordwrap(string,wrap_length[,delimiter])` | string — строка<br>wrap_length — длина | `wordwrap('UNIVERSITY OF QGIS',13)` |