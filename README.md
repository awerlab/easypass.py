# EasyPass
Модуль для простой генерации паролей и почтовых ящиков
## Оглавление
1. Установка
2. Функции и классы
  3. Аргументы
4. Генерация пароля
5. Генерация почтового ящика
6. Исключения
## Установка
Установка осуществляется командой в терминале:
```
pip install easypass
```
## Функции и классы
В модуле есть два класса — ```Password``` и ```Email```. У них есть 3 функции. Это конечно же ```__init__()```, в котором создаётся пароль/почта, ```print()``` для вывода пароля или почты в консоль и  ```save()``` для сохранения в файл.
## Аргументы
В таблице указаны имя параметра, его значение по умолчанию и то, за что он отвечает.

### Password
| Параметр | Значение | Описание |
|:----------------:|:---------:|:----------------:|
| lenght | 8 | Длина пароля |
| lower | True | Наличие нижнего регистра |
| upper | True | Наличие верхнего регистра |
| numbers | True | Наличие цифр |
| symbols | False | Наличие специальных знаков |
### Password.print()
Нет никаких параметров, функция просто выводит пароль в консоль
### Password.save()
| Параметр | Значение | Описание |
|:----------------:|:---------:|:----------------:|
| path | None | Путь к файлу |

### Password
| Параметр | Значение | Описание |
|:----------------:|:---------:|:----------------:|
| lenght | 8 | Длина пароля |
| lower | True | Наличие нижнего регистра |
| upper | True | Наличие верхнего регистра |
| numbers | True | Наличие цифр |
| symbols | False | Наличие специальных знаков |
### Password.print()
Нет никаких параметров, функция просто выводит пароль в консоль
### Password.save()
| Параметр | Значение | Описание |
|:----------------:|:---------:|:----------------:|
| path | None | Путь к файлу |
