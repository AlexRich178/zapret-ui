<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/1eda3863-00dd-4fac-9e23-6426b6e180a4" /># Zapret UI

Простой однофайловый интерфейс для Windows поверх `Flowseal/zapret-discord-youtube`.

Интерфейс не заменяет `service.bat`, а только упрощает ручной запуск стратегий, переключение поддерживаемых настроек и просмотр статуса.

<img width="1920" height="1080" alt="image" src="https://github.com/user-attachments/assets/6cd9949f-070c-473e-8e83-b9b94f878fec" />


## Возможности

- выбор `.bat`-стратегии из папки zapret;
- запуск и остановка `winws.exe`;
- применение и перезапуск выбранной стратегии;
- отображение статуса `winws.exe`, `WinDivert` и службы `zapret`;
- управление поддерживаемыми настройками:
  - Game Filter;
  - IPSet Filter;
  - Auto-Update;
- сохранение логов в папку `logs`.

## Установка

1. Скачайте `zapret-ui.hta`.
2. Положите файл в корень папки `zapret-discord-youtube`, рядом с `service.bat`.
3. Запустите `zapret-ui.hta` двойным кликом.

Пример расположения:

```text
zapret-discord-youtube/
├── zapret-ui.hta
├── service.bat
├── general.bat
├── general (ALT).bat
├── bin/
├── lists/
└── utils/
