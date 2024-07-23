# CalculatorDateBot 
**CalculatorDateBot** – [telegram](https://telegram.org)-бот, помогающий запоминать события и указывать сколько до них осталось.

# Порядок установки и использования
1. Загрузить репозиторий. Распаковать.
2. Установить [Python](https://www.python.org/downloads/) версии 3.11 и выше. Рекомендуется добавить в PATH.
3. Установить пакеты при помощи следующей команды, выполненной из директории скрипта.

```
pip install -r requirements.txt
```
4. Настроить бота путём редактирования [_Settings.json_](#Settings).
5. Можно добавить команды в бота, для удобства работы [(бот будет работать и без этой настройки)](#AddCommands). 
6. Запустить файл _main.py_.
```
python main.py
``` 
7. Перейти в чат с ботом, токен которого указан в настройках, и следовать его инструкциям.

# Settings.json

<a name="Settings"></a> 

```JSON
"token": ""
```

Сюда необходимо занести токен бота Telegram (можно получить у [BotFather](https://t.me/BotFather)).

# Добавление команд 

<a name="AddCommands"></a> 

Можно указать в настройках бота в [BotFather](https://t.me/BotFather).

create - Создание события

list - просмотр событий

---

_Copyright © Dub Irina. 2024._
