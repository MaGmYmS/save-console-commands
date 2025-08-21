# Виртуальное окружение

### Посмотреть все версии питона
```
py -0
```

### Создать окружение определенной версии 
```
py -3.10 -m venv venv3.10
```

### Активация виртуального окружения 
```
venv3.10\Scripts\activate
```

### Активация виртуального окружения в линуксе
```
source venv\Scripts\activate
```

### Установка зависимостей из коренной папки
```
pip install -r requirements.txt
```

### Установка зависимостей из определенной папки
```
pip install -r "path_to_file_requitements.txt"
```

### Создание файла requirements.txt
```
pip freeze > requirements.txt
```

### Удаление всех зависимостей
```
### pip freeze | xargs pip uninstall -y
```

### Просмотр всех установленных пакетов
```
### pip list --format=columns
```

### Ссылка, по которой pip устанавливает все зависимости
```
https://pypi.org/simple/tensorflow/
```