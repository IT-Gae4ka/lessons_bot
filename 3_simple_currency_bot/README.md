## Не добавляем ничего принципильано нового, но расширяем текущий функционал за счет более сложных возможностей.

Бот распилен на несколько файлов, разделены логика и настройки.
Закрепляем на практике умение разделять код на несколько файлов, лежащих в разных местах, и подключать их друг к другу.

Добавлена возможность ответа на команды
```bash
/start 
/country rb или uk 

/курс <аббревиатура валюты> 
например
/курс usd
```

### Подготовка и запуск
pip install requests

```bash
python telegram_bot.py

```
или

```bash
python3 telegram_bot.py
```