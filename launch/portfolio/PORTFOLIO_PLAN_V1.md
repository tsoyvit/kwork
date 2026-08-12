# Launch Portfolio — план и готовые тексты v1

Основание: `specs/PORTFOLIO_SPEC.md` + известные данные по Skillcue, RuviCRM и Rubikon.

Цель стартового портфолио — не показать всю карьеру, а дать доказательства под разные buyer intents первых кворков.

> Важно: ниже нет придуманных цифр результата. Если для конкретного кейса нужны количественные показатели, добавлять только после подтверждения.

---

# 1. SaaS-сервис: кабинет, админка и Windows-приложение

**Источник:** Skillcue

## Buyer intent
SaaS / MVP / web application / user cabinet / admin panel / desktop integration.

## Результат одной строкой
Разработан полноценный программный продукт с пользовательским кабинетом, административной панелью, landing page и Windows-приложением, связанными с backend.

## Что реализовано
- пользовательский кабинет;
- административная панель;
- backend-логика;
- Windows-приложение;
- landing page;
- realtime-взаимодействие через WebSocket;
- чат и связанные модули.

## Главный screenshot
Самый сильный экран продукта: dashboard/кабинет, где сразу видно, что это законченный сервис.

## Дополнительные visuals
1. admin panel;
2. Windows application;
3. realtime/chat screen;
4. landing или общий flow.

## Короткая строка технологий
Backend • Web application • WebSocket • Windows application

## Усиливает кворки
- MVP / SaaS;
- admin panel;
- user cabinet;
- backend;
- realtime systems;
- desktop software.

---

# 2. Админ-панель и пользовательский кабинет

**Источник:** Skillcue

## Buyer intent
Admin panel / private account / business web application.

## Результат
Разработаны отдельные интерфейсы пользователя и администратора для управления функциями продукта и данными системы.

## Что показать
- user dashboard;
- admin dashboard;
- управление пользователями/сущностями;
- экран настроек или ключевого business workflow.

## Текст кейса
В рамках продукта реализованы пользовательский кабинет и отдельная административная часть. Пользователь работает с основными функциями через свой интерфейс, а администратор управляет системой через отдельную панель.

Подобный подход подходит для SaaS, внутренних сервисов, CRM, кабинетов клиентов, партнёрских систем и других web-продуктов.

## Усиливает
- admin panel;
- SaaS/MVP;
- CRM;
- custom backend/frontend.

---

# 3. Windows-приложение с синхронизацией с backend

**Источник:** Skillcue

## Buyer intent
Desktop software / existing backend integration / client application.

## Результат
Windows-приложение работает как часть единой системы и взаимодействует с backend и пользовательским аккаунтом.

## Visuals
1. главное окно Windows app;
2. экран авторизации/синхронизации;
3. связанный web cabinet;
4. схема `Windows app ↔ backend ↔ account`, если она поможет объяснить продукт.

## Усиливает
- программы на заказ;
- desktop integrations;
- API/backend;
- synchronization.

---

# 4. CRM для записи клиентов: расписание, сотрудники и услуги

**Источник:** RuviCRM

## Buyer intent
CRM / booking / service business / admin system.

## Результат одной строкой
Разработана CRM-система для сервисного бизнеса с клиентами, услугами, сотрудниками, расписанием и онлайн-записью.

## Что реализовано
- клиенты;
- услуги;
- сотрудники;
- расписание;
- онлайн-запись;
- административная и пользовательская бизнес-логика;
- backend на Laravel.

## Главный screenshot
Календарь/расписание или экран CRM, где одновременно видна прикладная ценность продукта.

## Дополнительные visuals
1. карточка клиента;
2. сотрудники/услуги;
3. booking flow;
4. admin screen.

## Усиливает
- CRM development;
- SaaS/MVP;
- booking system;
- Laravel backend;
- admin panel.

---

# 5. CRM + онлайн-запись: синхронизация бизнес-процесса

**Источник:** опыт Rubikon — YCLIENTS / Altegio / аналогичные booking integrations.

## Buyer intent
CRM integration / booking / API / synchronization.

## Результат
Интеграционные решения связывают CRM с системами онлайн-записи: данные о клиентах, визитах, сотрудниках, филиалах и статусах могут передаваться между системами без ручного дублирования.

## Что показать
Если исходные клиентские интерфейсы нельзя публично показывать:
- anonymized flow diagram;
- схема `CRM ↔ API ↔ booking system`;
- демонстрационный mockup полей и статусов;
- список реализованных workflow без клиентских данных.

## Возможные функции кейса
- получение доступных слотов;
- создание/перенос/отмена записи;
- синхронизация филиалов и сотрудников;
- передача статусов;
- работа из карточки CRM.

## Усиливает
- CRM integrations;
- API/webhook;
- YCLIENTS/Altegio-style integrations;
- business automation.

---

# 6. API/Webhook автоматизация между бизнес-сервисами

**Источник:** Rubikon experience.

## Buyer intent
API integration / webhook / automation / data sync.

## Результат
Разработка интеграционных сервисов, которые принимают события из одной системы, обрабатывают данные и автоматически выполняют действия в другой системе.

## Примеры задач из опыта
- формы/сайты → CRM;
- внешняя платформа → сделка/контакт;
- CRM → создание объекта во внешнем сервисе;
- синхронизация статусов;
- обработка webhook;
- поиск дублей и mapping полей.

## Visual
Лучше использовать чистую схему:
`SOURCE → WEBHOOK/API → BUSINESS LOGIC → CRM/SERVICE`

Дополнительно — anonymized лог обработки или screenshot UI/CRM, если допустимо.

## Усиливает
- API/webhook;
- CRM integration;
- site → CRM;
- automation;
- backend.

---

# 7. Интеграция заявок с сайта в CRM

**Источник:** Rubikon/Tilda/CRM integration experience.

## Buyer intent
Site form → amoCRM/Bitrix24/CRM.

## Результат
Заявка с сайта автоматически передаётся в CRM вместе с нужными полями и маркетинговыми данными, чтобы менеджеру не приходилось переносить данные вручную.

## Возможные функции
- создание/обновление контакта;
- создание сделки;
- mapping полей;
- UTM-метки;
- проверка дублей;
- дополнительные действия по событию.

## Почему отдельный кейс
На Kwork существует самостоятельный покупательский intent `заявки с сайта → CRM`; поэтому такой case должен быть отдельным и максимально буквальным.

## Усиливает
- CRM integration;
- WordPress/Tilda forms;
- API/webhook;
- amoCRM / Bitrix24.

---

# 8. Telegram-бот / автоматизация бизнес-процесса

**Источник:** существующие Telegram-проекты пользователя. Перед публикацией нужно выбрать самый визуально сильный реальный бот.

## Buyer intent
Telegram bot / business bot / notifications / API integration.

## Результат
Сделать отдельный кейс не про «бота вообще», а про конкретный workflow: например заявки, уведомления, меню, CRM/API, обработка данных или другой реализованный сценарий.

## Обязательные visuals
1. диалог/меню бота;
2. ключевой сценарий;
3. admin/backend/CRM side при наличии;
4. схема интеграции, если бот связан с API.

## Текстовая структура
- какую задачу решает бот;
- что пользователь делает в Telegram;
- что происходит автоматически;
- какие внешние сервисы подключены;
- какой результат получает бизнес.

## Усиливает
- bot fix;
- simple bot;
- business bot;
- Telegram + CRM/API;
- site → Telegram.

---

# Приоритет подготовки изображений

## P0 — сделать до публикации первых high-value кворков
1. Skillcue main SaaS screenshot.
2. Skillcue admin/user cabinet.
3. RuviCRM calendar/CRM.
4. API/CRM flow diagram.
5. Telegram bot screenshots.

## P1 — можно добавить в первые дни
6. Windows app.
7. Site → CRM flow.
8. Booking integration diagram.

## P2 — выращивать из Kwork-заказов
- WordPress before/after;
- Error 500 fix;
- parser output;
- Excel/Sheets automation result;
- VPS/deploy result;
- PageSpeed before/after;
- QA bug-report.

# Правило публикации

Не привязывать крупный SaaS-кейс к микрокворку только потому, что другого портфолио нет. Для micro-services лучше временно использовать нейтральное релевантное доказательство или быстро создать демонстрационный result, а затем заменить его первым реальным Kwork-case.
