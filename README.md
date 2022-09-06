![eng](img/eng.png) [![ru](img/ru.png)](README.ru.md)
# `get_next_line`

Project in school 42. The purpose of this project is to write own function that replicates the behaviour of the standard function С `getline()`.

### Discription
Prototype of the function looks like:
```C
int get_next_line(int fd, char **line);
```
The function take two parameters:
- `fd` - file discriptor for reading
- `line` - value of what has been read

The function can return next values:
- `1` - if line has been read and you can continue reading
- `0` - if reached EOF
- `-1` - if happened some error
### Evaluated by moulinette

![100/100](img/100.png)
