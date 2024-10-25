# Shop-Research

## Опис проекту
**Shop-Research** — це Java-додаток для аналізу показників діяльності магазину протягом п'яти днів. Кожен день фіксується найбільш продаваний товар та загальна сума продажів за день.

### Основні класи
1. **Main.java** — основний клас програми, який відповідає за ініціалізацію та виведення оброблених даних щодо продуктів і сум продажів.
2. **DataProvider.java** — клас, що надає вихідні дані у вигляді масивів продуктів та сум продажів.
3. **DataHandler.java** — клас, що реалізує узагальнений метод для обробки даних різного типу, формуючи підсумковий текстовий результат для виведення.

### Як працює програма
1. Клас `DataProvider` надає дані про продукти та суми продажів у вигляді масивів.
2. Клас `DataHandler` обробляє отримані дані, формуючи текстовий формат для зручного відображення результатів.
3. Основний клас `Main` ініціалізує процес обробки та виводить результати в консоль.

### Вимоги до системи
- Java 8 або вище
- Будь-яке середовище розробки для Java (VSCode, IntelliJ IDEA, Eclipse)
