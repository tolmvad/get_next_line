[![eng](img/eng.png)](README.md) ![ru](img/ru.png)
# `get_next_line`

Проект школы 42. Цель данного проекта написать собственную функцию, повторяющую поведение стандартной функции языка С `getline()`.<br>
Задание можно прочитать здесь: [`get_next_line.subject.pdf`](subject/get_next_line.subject.pdf)

### Описание
Прототип функции выглядит так:

```C
int get_next_line(int fd, char **line);
```
Функция принимает два параметра:
- `fd` - файловый дескриптор, с которого читаем
- `line` - значение, которое мы прочитали

Функция возвращает следующие значения:
- `1` - если линия считана и можно продолжить чтение
- `0` - если всё прочитано
- `-1` - если произошла ошибка
### Оценка от moulinette

![100/100](img/100.png)
