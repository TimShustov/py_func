## Шаблон: python38

```
Python 3.8.6 
pip 19.3.1
```

Для корректной работы в функции должен быть скрипт `handlers/handler.py` с функцией `handler` принимающей на вход `flask.Request` и возвращающий текст ответа или любой набор значений, которые можно превратить в Response object используя `make_response <https://flask.palletsprojects.com/en/1.1.x/api/#flask.Flask.make_response>`.

### Подключение внешних зависимостей

Внешние зависимости могут быть определены в [`requirements.txt`](./requirements.txt) проекта функции.
