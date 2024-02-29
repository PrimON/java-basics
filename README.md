# Материалы по курсу "Основы языка и платформы Java для анализа данных"

## Тема 1. Основы языка
- [Презентация](https://disk.yandex.ru/i/59AdRUKocrkXgg)
## Тема 2. Типы данных
- [Примеры кода](basics/src/main/java/ru/msu/vmk/Main.java)
- [Презентация](https://disk.yandex.ru/i/EZSzwSpcYPa0rw)
- Задание:
Дан следующий код, необходимо реализовать метод split.
```java
public class NumberSample {

    public static void main(String[] args) {
      // вызов split - проверка работы
    }

    public static BigDecimal[] split(BigDecimal amount, int n) {
        // разделить amount на n частей
        // если остается остаток, прибавить его к первому числу
        return null;
    }
}
```
- [Место для реализации](basics/src/main/java/ru/msu/vmk/NumberSample.java)
- [Тесты для проверки](basics/src/test/java/NumberSampleTests.java)

## Тема 3. Объектно ориентированное программирование
- [Примеры кода](object-oriented-programming/src/main/java/ru/msu/vmk)
- [Презентация](https://disk.yandex.ru/i/FvM8OJUHVnF0Gw)
- Задание:
По примеру класса [Money](object-oriented-programming/src/main/java/ru/msu/vmk/Money.java) реализовать класс Quantity:
- с поддержкой единиц измерения
- арифметических операций: add, subtract, multiply, divide
- реализовать операцию деления на N равных частей с добавлением остатка к первому значению (см. предыдущее задание)
- для проверки работы реализовать функцию main() или Unit-test по примеру

