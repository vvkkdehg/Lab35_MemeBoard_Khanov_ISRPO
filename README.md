## Лабораторная работа №35. Подключаем фронтенд к API: доска мемов

### Как запустить:

1. Скопировать проект с GitHub
2. Открыть его в VS Code
3. Запустить backend в терминале через `dotnet run`
4. Запустить файл index.html через Live server

### Таблица

|Концепция|Где используется|
|---------|----------------|
|**fetch(url)**|GET-запрос к API|
|**fetch(url, { method, headers, body })**|POST и DELETE запросы|
|**response.ok**|Проверка успешности ответа|
|**response.json()**|Чтение JSON из ответа|
|**JSON.stringify(...)**|Объект JS → JSON-строка для отправки|
|**async / await**|Ожидание ответа от сервера|
|**try / catch / finally**|Обработка ошибок при fetch|
|**CORS**|Разрешение запросов между разными портами|
|**AddCors + UseCors**|Включение CORS в ASP.NET Core — два шага|