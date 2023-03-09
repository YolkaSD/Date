# Даты и время.

* java.util.Date 
* LocalDate 
* LocalTime 
* LocalDateTime 
* System.currentTimeMills() и т.д.

В основном дата и/или время приходит просто в обычной строке.
По этому основной нюанс при работе с датами это как именно превратить строку в дату.
Для этого существует такое понятие как формат даты или маска даты.

## Задачи:

1. Написать метод, который будет принимать дату рождения в строке и возвращать количество дней в формате *int*, которые прошли с этого дня.

2. Написать метод, который будет принимать дату в формате *LocalDate* и возвращать тоже *LocalDate*, для конвертации даты из формата *"dd/mm/yyyy"* в формат *"yyyy-mm-dd"*.

3. Написать метод, который будет конвертировать время из одной временной зоны в другую, используя стандартную библиотеку Java.

4. Разработать функционал, который определяет время, прошедшее с момента запуска приложения до момента его завершения.

5. Создать метод, который принимает на вход лист строк (которые должны содержать даты) и с помощью *StreamAPI* вернуть самую большую дату из этого списка в формате *LocalDateTime*

6. В методе *main* вызывать методы класса *LocalData* и использовать этот функционал для наглядности выводя результаты работы отдельных методов в консоль.