# itmo-web-task2
# Mission 2
## Part 0
https://disk.yandex.ru/d/Owb1swr3Ys9Mcg
## Part1

- Вопрос 1	 
> Ответ  
SSH нужен для безопасного удаленного доступа к серверам. Это протокол, который шифрует весь трафик. Позволяет получить удаленный доступ к нужному компьютеру/серверу

- Вопрос 2	 
> Ответ  
Чтобы Вася смог подключиться к терминалу, ему нужно свой ключ перенести в ssh и добавить в файл authorized keys. (.ssh/authorized_keys)

- Вопрос 3	 
> Ответ  
Long polling - метод взаимодействия с сервером, при котором информация остается открытой до момента обновления - то есть до отправки запроса. Если запрос есть - информация обновляется (например, каждые 30 секунд). Метод хорош можно использовать, если не нужны слишком частые обновления информации.

Webhook - работает непрерывно, то есть не нужно посылать запрос для обновления информации (получения нового сообщения) - она обновится автоматически сразу, как только придет ответ. То есть, бот ждет, и высылает ответ, когда он появится. Выглядит менее безопасным, но работает проще

- Вопрос 4	 
> Ответ  
Issues на GitHub - это инструмент для отслеживания и управления задачами и проблемами в проекте. Каждый issue представляет собой задачу или проблему, которую необходимо решить. Issues содержат информацию о названии проекта, теме, типе, приоритете, компонентах и содержании. Могут быть открытыми, закрытыми или находиться в других статусах

Примеры:
Issues в Mapbox (карты) на Android
https://github.com/mapbox/mapbox-maps-android/issues

Issues приложения Organic Maps (офлайн-карты на основе OSM для IOS и Android)
https://github.com/organicmaps/organicmaps/issues

- Вопрос 5	 
> Ответ
Директорию можно удалить перед коммитом. В директории нужно запустить команду rm -rf images.
Можно создать пустой файл .gitkeep внутри этой директории.
Можно изменить настройки git, чтобы он игнорировал определенные директории
