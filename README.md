# Strings

# Задание
Выполнить задания из прикреплённого файла.
Для решения задачи использовать только charAt(), length() и compareTo().

# Теоретическая справка
Для работы со строками в Java существует класс **String**. В данном классе уже существуют стандартные методы, которые позволяют облегчить нам работу со строками.

* Данный класс нельзя унаследовать и переопределить.
* При изменении строки создаётся абсолютно новая строка.

## объявление строки
String str;

## Примеры методов:
* charAt(int index) - позволяет вернуть элемент по индексу
* compareTo(String anotherString) - сравнивает лексикографически две строки
* equals(String anotherString) - сравнивает эквивалентность строк
* concat(String str) - добавляет к текущей строке - новую
* split(String regex) - разбивает строку на массивы с помощью разделителя regex
* length() - возвращает длину строки
* и т.д.
* Также класс String поддерживает математические операции!


