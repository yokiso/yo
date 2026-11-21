# Лабораторный практикум № 2

Интерфейсы, репозиторий и JSON. Решения рассчитаны на .NET SDK 10. Для HTTP-проверок нужен Python 3.

```powershell
dotnet run --project Interfaces/Interfaces.csproj
dotnet run --project Repository/Library.Demo/Library.Demo.csproj
dotnet run --project UserApi/UserApi.csproj
```

Чтобы прогнать автоматические HTTP-проверки, выполните `python UserApi/test_http.py`. Скрипт самостоятельно запускает сервис на свободном локальном порту с временной БД.

| Часть | Решение | Результат |
|---|---|---|
| 1 | `Interfaces` | 13 проверок |
| 2 | `Repository` | 16 проверок |
| 3 | `UserApi` | 26 HTTP-проверок и проверка схемы SQLite |

Фактические протоколы и скриншоты размещены в `evidence`. В отчетах Word есть формулировки заданий, результаты, схемы таблиц и листинги программ.
