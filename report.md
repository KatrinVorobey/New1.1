# Отчёт о тестировании <Money Transfer>

09.11.2021 было проведено тестирование приложения "Money Transfer"

На тестирование затрачено: 15 минут

В результате тестирования выявлены следующие дефекты:
* Main -1794967296


В процессе тестирования выполнялись следующие шаги:


   1. В редакторе кода"Intellij IDEA" набрать код:
    public class Main {
    public static void main(String[] args) {
    int balance = 2_000_000_000;
    int transfer = 500_000_000;
    int total = balance + transfer;
    System.out.println(total);
    }
    }

    2. Осуществить запуск программы кликнув на кнопку “Run”

    3. Получаем результат: Main -1794967296

Ожидаемый результат: Total 2 500 000 000
Фактический результат: Main -1794967296

"C:\Program Files\Eclipse Foundation\jdk-11.0.12.7-hotspot\bin\java.exe" "-javaagent:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2021.2.3\lib\idea_rt.jar=53873:C:\Program Files\JetBrains\IntelliJ IDEA Community Edition 2021.2.3\bin" -Dfile.encoding=UTF-8 -classpath C:\Users\Kitten\IdeaProjects\New1.1\out\production\New1.1 Main
-1794967296
Process finished with exit code 0


 Тестирование производилось в следующем окружении: 

   - Система: Windows 10 Pro. Версия 21H1. Сборка ОС 19043.1288
   - "Редактор кода"Intellij IDEA Community Edition 2021.2.3"
