# История изменений — telegram-zapret

- Тег пакета по `releasetag.txt`: **1.10.4**.
- 
- Файлы исходной сборки и сценарии оставлены без модификации.

## Изменения, перечисленные в исходных release-заметках

- Отправление фейков на неизвестные TCP протоколы (для GameFilter TCP)
- Это может как помочь с восстановлением работы сервисов/игр с включённым GameFilter TCP, так и сломать то, что до этого работало. Как всегда используйте GameFilter с осторожностью
- Обновлены все стратегии `SIMPLE FAKE`, `EXP` и `ALT1` in Flowseal/zapret-discord-youtube@1b8bbb
- Новые фиксы
- Обновлен IPSet
- service.bat: добавлена очистка кэша Discord Canary и Discord Development
- @Zzazazaza27 made their first contribution in Flowseal/zapret-discord-youtube#16169

## Примечание о версиях

В исходных release-заметках указан upstream-диапазон `1.10.0...1.10.1`. Он приводится как справочная информация из исходного архива и не выдаётся за полный changelog между всеми тегами этой сборки.
