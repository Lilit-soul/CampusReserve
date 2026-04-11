# Кампус-Бронь

Сервис для бронирования аудиторий в НГТУ (на данный момент расчет на 7й корпус).
Студенты и преподаватели могут смотреть расписание занятости аудиторий и бронировать свободные аудитории через простой web-интерфейс.

Это должно облегчить студентам и преподавателям огранизовывать мероприятия, тратя меньше времени на согласование времени, что позволить уделить больше внимания уделить организации и планировке самого мероприятия.

---

## Стек

| Слой/Задача | Применяемые инструменты |
|-------------|-------------------------|
| Backend/API | GoLang + Gin |
| DataBase | PostgreSQL |
| ORM | GORM |
| Инфраструктура | Docker, docker-compose, Nginx |
| Frontend | React |

---

## Структура
### Структура репозитория
```
/
|— frontend/            # web-интерфейс
|— backend/             # API и другая логика
|— db/                  # миграции и схемы баз данных
|— infra/               # docker-compose, nginx, envs
|— .github/             # 
   |— workflows/        # CI/CD
   |— ISSUE_TEMPLATE/   # 
```

---

## Локальный запуск
<!-- Пока пусто, через docker-compose дело проходить будет -->

---

## Работа

Перед началом изучить [CONTRIBUTING.md](./CONTRIBUTING.md) — тут лежат правила оформления веток, коммитов, и запросов на слияние

Добовлять задачи/баги в issues — [GitHub Issues](https://github.com/VixurHD/CampusReserve/issues)

Доска с взятыми/открытыми, взятыми на рассмотрение/рассмотреными задачами — [GitHub Projects](https://github.com/VixurHD/CampusReserve/projects)

---

## Команда
| Имя — Username | Роль/Задачи |
|----------------|-------------|
| Денис — [@VixurHD](https://github.com/VixurHD) | Maintain, DevOps |
| Ирина — [@Lilit-soul](https://github.com/Lilit-soul) | Дизайн, Frontend |
| Дмитрий — [@EJIEKTRICK](https://github.com/EJIEKTRICK) | Backend, API |
| Азат — [@unfiltered-feed](https://github.com/unfiltered-feed) | Базы данных |

