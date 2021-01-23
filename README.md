__Discord Auto Poster - Скрипт для автоматизации отправки сообщений в заданый канал дискорда.__ 
-------------
Вы задаете сообщение, задержку, и канал куда необходимо отправлять сообщение, скрипт успешно отправляет ваши сообщения каждые X минут/часов/дней
![](https://i.imgur.com/OjJ5cAd.png)

*Примечание. Данный софт не ворует ваши аккаунты, обфускация нужна только для защиты кода.*

----------
# Инструкция по установке
### Шаг 1 Получение токена пользователя
1) Зайдите через браузер в [Discord](https://discordapp.com)
2) Войдите в аккаунт
3) Нажмите CTRL + Shift + I
4) Откройте вкладку "Network"
5) В Filter надо написать "/api/v6" (без ковычек)
6) Нажмите Ctrl + R
*. Появится куча вкладок, типа science, выберите её или любую другую.*
7) Листайте список справа пока не дойдёте до надписи "authorization", если её нет - берите другую вкладку.
8) Справа от authorization будет написан ваш токен (authorization: ************************.******.*******_********_**********) 
9) Копируете его
10) Сохраните токен на будущее и затем вставьте в программу (Внимание! Никому не показывайте свой токен, иначе вас взломают)
### Шаг 2 Получение ID канала в который нужно отправлять сообщение
1) Переходим в настройки [Discord](https://discordapp.com), вкладка "Внешний вид" "Расширенные" и включаем Режим разработчика
2) Заходим на нужный сервер дискорда и кликаем правой кнопкой мыши на канал в который необходимо отправлять сообщения
3) Нажмите "Копировать ID" это и есть id нашего канала, вставьте его в программу.
### Шаг 3 Запустить скрипта
#### Пример запуска в консоли:
```python
python discordautoposter.py
```
# Требования
Все требуемые модули указаны в файле requirements.txt  
Для установки запустите команду:
```python
python pip install -r requirements.txt
```

