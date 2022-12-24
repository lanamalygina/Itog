## Итоговая проверочная работа.

### Описание решения

Программа решает задачу фильтрации массива целых чисел по критерию четности.

На вход подается массив целых чисел посредством ввода с клавиатуры. Кроме ручного ввода, предусмотрен тестовый режим с генерацией случайных чисел.

При запуске из консоли программа выводит приглашение с описанием работы.

Предусмотрено несколько команд:
 - Команда 1: начать ввод элементов массива
 - Команда 2: завершить ввод элементов массива и вывести результат
 - Команда 3: очистить массив
 - Команда 4: задать параметры генерации массива случайных чисел и вывести результат
 - Команда 5: выйти из приложения

Алгоритм функции фильтрации реализован при помощи промежуточного массива (ведерка), который накапливает четные числа и сливает результат в общий массив. При такой реализации, получается масштабируемый метод по потреблению памяти. Подобное поведение реализовано в стандартных коллекциях.

### Схема алгоритма функции filterEvens
![Схема](https://raw.githubusercontent.com/lanamalygina/ItogTest/master/algorithm-schema.drawio.svg "Схема алгоритма").

### Постановка задачи

Данная работа необходима для проверки ваших знаний и навыков по итогу прохождения первого блока обучения на программе разработчик. Мы должны убедиться что базовое знакомство с it прошло успешно.

### Задача: 

Написать программу, которая из имеющегося массива целых чисел формирует массив из четных чисел. Первоначальный массив можно ввести с клавиатуры, либо сгенерировать случайным образом. При решении не рекомендуется пользоваться коллекциями, лучше обойтись исключительно массивами.

### Примеры:

[1, 2, 3, 4] -> [2, 4]
[1, 3, 4, 5, 7, 1, 3] -> [4]
[2, -4, 6] -> [2, -4, 6]
[1, 3, 5] -> []

### Флоу выполнения:

Создать репозиторий на GitHub.
Нарисовать блок-схему алгоритма (можно обойтись блок-схемой основной содержательной части, если вы выделяете ее в отдельный метод).
Снабдить репозиторий оформленным текстовым описанием решения (файл README.md).
Написать программу, решающую поставленную задачу.
Использовать контроль версий в работе над этим небольшим проектом (не должно быть так, что все залито одним комитом, как минимум этапы 2, 3 и 4 должны быть расположены в разных комитах).