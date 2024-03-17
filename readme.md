# Задание 2.
## Магазин игрушек (Java)
### Информация о проекте:

_Необходимо написать проект, для розыгрыша в магазине игрушек. Функционал должен содержать добавление новых игрушек и задания веса для выпадения игрушек._

### Как сдавать проект:

_Для сдачи проекта необходимо создать отдельный общедоступный репозиторий (Github, gitlub, или Bitbucket).Разработку вести в этом репозитории, использовать пулреквесты на изменения. Программа должна запускаться и работать, ошибок при выполнении программы быть не должно. Программа,может использоваться в различных системах, поэтому необходимо разработать класс ввиде конструктора._

### Задание

Напишите класс - конструктор у которого принимает минимум 3 строки, содержащие три поля id и грушки, текстовое название и частоту выпадения игрушки
Из принятой строки id и частоты выпадения (веса) заполнить минимум три массива.
Используя API коллекцию: java.util.PriorityQueue, добавить элементы в коллекцию
Организовать общую очередь
Вызвать Get 10раз и записать результат в файл

***Подсказка:***

В метод put передаете последовательно несколько строк 12 конструктор; 22 робот; 36 кукла. Метод Get должен случайно вернуть либо “2”, либо “3” и в соответствии с весом. В 20% случаях выходит единица В 20% двойка И в 60% тройка. Критерии оценки Приложение должно запускаться, записывать значения в файл.