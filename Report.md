# Отчет о тестировании Precision.


## Краткое описание:

Создать приложение с использованием следующего кода и запустить его:
Проверить вывод итогового верного результата.
Итоговый результат сложения  = 0,9.

Код:
public class Main {
  public static void main(String[] args) {
    double regularBonus = 0.3;
    double specialBonus = 0.6;
    double totalBonus = regularBonus + specialBonus;
    System.out.println(totalBonus);
  }
}

*Описание проведенных тестов*:

1. Запуск программы с заранее подготовленным кодом.
2. Позитивное тестирование, использовализь валлидные данные и верные числовые значения.
Сложение данных:
        double regularBonus = 0.3;
        double specialBonus = 0.6;

3. Вывод итогово результа. (double totalBonus)
double totalBonus = regularBonus + specialBonus;


*Результаты*:

1. Успешных тестов не пройдено.
2. Сссылка на BugReport: Не верный подсчет итоговой суммы.
https://github.com/DimaVakarchuk/Home-Work-Java-1.2---Precision/issues/1#issue-690724599

*Общие рекомендации:*

Думаю стоит использовать тип Float вместо Double. Возможно с этим типом и связан такой более точный подсчет итоговой суммы, т.е данный тип может хранить больше значащих чисел.

 
*Тестирование производилось в следующем окружении*:

 - Openjdk version "11.0.8"
 - IntelliJ IDEA 2020
 - Windows 10 Pro (x64)