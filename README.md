# Проект Mesto фронтенд + бэкенд

# Cтек: JavaScript / React.js / HTML / CSS / Node.js / MongoDB / Git / Figma
В этой проектной работе началась реализация бэкенда для приложения Mesto. Создано приложение на Express.

`/routes` — папка с файлами роутера  
`/controllers` — папка с файлами контроллеров пользователя и карточки   
`/models` — папка с файлами описания схем пользователя и карточки  

В проектной работе реализована возможность регистрации и авторизации. К схеме пользователя добавлены password и уникальный email. Доработан контроллер createUser. Создан контроллер login, который получает из запроса почту и пароль и проверяет их. Если почта и пароль правильные, контроллер создаtn JWT сроком на неделю, и записывает в в httpOnly куку. Созданы роуты для логина и регистрации. Создан мидлвэр auth для авторизации. Создан контроллер и роут для получения информации о пользователе. Защены авторизацией все маршруты, кроме страницы регистрации и логина. Реализована централизованная обработка ошибок. Настроена валидация приходящих на сервер запросов. Посредством регулярных выражений настроена валидация полей avatar и link на уровне схемы.
