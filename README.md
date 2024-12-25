Данный проект полезен тем, кто не хочет платить за дорогостоящие контроллеры автоматического полива.

Для реализации автоматического полива необходимо заказать готовую недорогую плату на Alixpress, Ozon  или другом магазине (пример платы на фото в проекте) , купить распределительную коробку, соленоиды, трубки и форсунки для полива.
Файл "firmware.bin" для загрузки для купленной платы в ESP32.

В проекте реализован полив 2 раза в сутки для каждой из 4-х зон по времени в указанные дни недели. 
Возможность задать таймера полива. Автоматическая синхронизация времени. 
Удаленное управление со встроенного Web интерфейса по IP адресу или HostName.
Доступна настройка управления по MQTT.

Загрузить проект в новую плату можно через USB TTL адаптер, для дальнейших обновлений и загрузок прошивки реализована загрузка через WiFi по адресу: IP платы:8080/update



