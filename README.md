Домашнее задание к лекции 4.«Tests»

Задача №1 unit-tests

Из курса «Python: программирование на каждый день и сверхбыстрое прототипирование» нужно написать тесты на любые 3 задания из Лекции 4. Необходимо использовать своё решение домашнего задания.

При написании тестов не забывайте использовать параметризацию.
Рекомендации по тестам.

Если у вас в функциях информация выводилась(print), то теперь её лучше возвращать(return) чтобы можно было протестировать.

Задача №2 Автотест API Яндекса

Проверим правильность работы Яндекс.Диск REST API. Написать тесты, проверяющий создание папки на Диске.
Используя библиотеку requests напишите unit-test на верный ответ и возможные отрицательные тесты на ответы с ошибкой

Пример положительных тестов:

Код ответа соответствует 200.
Результат создания папки - папка появилась в списке файлов.