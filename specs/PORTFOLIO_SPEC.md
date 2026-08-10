# PORTFOLIO_SPEC

Рабочая спецификация продающего IT-кейса для Kwork.

## Что реально подтверждено исследованием

Из живого интерфейса видно:
- сильные продавцы используют portfolio/galleries как отдельный слой social proof;
- high-ticket карточка 1С-Битрикс у `max_volkov` имела очень большую галерею — интерфейс показывал `1 из 102`;
- `ameganix` прямо ведёт на video demonstrations примеров;
- `YuriCoder` ставит на cover скриншот конечной таблицы, а не абстрактную картинку;
- отзывы привязаны к конкретным кворкам/результатам;
- у профилей portfolio разбито по рубрикам.

Accessibility-представление Kwork не отдаёт текстовые названия многих portfolio thumbnails, поэтому конкретную структуру каждого portfolio item нельзя честно восстановить только из DOM. Ниже — спецификация, основанная на наблюдаемой витрине, card galleries и buyer logic; её нужно валидировать после загрузки первых наших кейсов по просмотрам/заказам.

## Главный принцип

Портфолио — не архив проектов и не резюме. Его задача:

> Клиент должен за 10–20 секунд увидеть: «этот человек уже делал что-то похожее на мою задачу».

## 1. Один кейс = один покупательский доказательный тезис

Большой проект можно разбивать на несколько buyer-facing cases, если каждый доказывает разную услугу.

Например Skillcue может дать:
- `SaaS-сервис с личным кабинетом и админкой`;
- `Windows-приложение + синхронизация с backend`;
- `Real-time система на WebSocket`;
- `Административная панель для управления пользователями`.

Это не дублирование ради количества: разные кворки требуют разных доказательств.

## 2. Название кейса

Не название внутреннего проекта без контекста.

Плохо:
`Skillcue`

Лучше:
`SaaS-сервис: личный кабинет, админка и Windows-приложение`

Плохо:
`RuviCRM`

Лучше:
`CRM для записи клиентов: расписание, сотрудники и услуги`

Название должно работать даже для человека, который никогда не слышал бренд проекта.

## 3. Preview

Выбрать **самый доказательный экран**:
- dashboard;
- admin panel;
- user cabinet;
- bot conversation;
- table/result;
- booking calendar;
- before/after;
- API flow diagram, если UI отсутствует.

Не ставить в качестве основного preview скрин кода.

## 4. Внутренняя структура кейса

### A. Результат одной строкой

`Разработан сервис, в котором пользователь работает через кабинет и Windows-приложение, а администратор управляет системой через отдельную панель.`

### B. Что было нужно

1–3 предложения о задаче клиента/продукта.

### C. Что реализовано

3–7 функций на языке результата:
- авторизация и роли;
- управление клиентами;
- запись/расписание;
- realtime updates;
- notifications;
- payments/integrations;
- admin tools.

### D. Visual proof

2–6 экранов:
1. общий результат;
2. ключевой workflow;
3. admin/client side;
4. сложный модуль;
5. mobile/desktop/realtime при необходимости.

### E. Технологии

Короткой строкой в конце, если повышает доверие:
`Laravel • JS • WebSocket • PostgreSQL`.

Стек не должен быть главным содержанием case.

### F. Связанные услуги

В конце можно подсказать buyer intent:
`Могу сделать похожий личный кабинет / CRM / admin panel / integration.`

## 5. Какие кейсы подготовить из текущей базы опыта

### Skillcue

1. Полноценный SaaS/product case.
2. Admin panel + user cabinet.
3. Windows application + backend synchronization.
4. Real-time/WebSocket workflow.

### RuviCRM

5. CRM for service business / client booking.
6. Schedule + employees + services.
7. Laravel business backend / API (только если нужен technical-oriented case).

### Rubikon experience

Не делать один кейс `Работал в Rubikon`.

Переупаковывать по задачам:
8. CRM + online booking integration.
9. API/webhook business automation.
10. CRM analytics / customer metrics.
11. External service ↔ CRM synchronization.
12. Messenger/lead automation.

### Telegram bots

13. Отдельный visual bot case, желательно с диалогом/flow/admin/result.

## 6. Матчинг кейса к кворку

У каждого kwork должна быть одна primary portfolio proof и 1–2 secondary.

Примеры:
- `Telegram bot + CRM` → bot case + Rubikon integration case;
- `CRM/API integration` → Rubikon/YCLIENTS-style case + RuviCRM;
- `Admin panel` → Skillcue admin;
- `SaaS/MVP` → Skillcue + RuviCRM;
- `WordPress microfix` → после первых заказов добавлять before/after именно по WordPress, потому что крупный SaaS-case здесь хуже совпадает с intent.

## 7. Портфолио должно расти из выполненных Kwork-заказов

После каждого заказа проверять:
- можно ли сделать screenshot;
- можно ли показать before/after;
- можно ли сделать anonymized case;
- какой kwork он усиливает.

Так портфолио постепенно становится всё ближе к реальному спросу Kwork.

## 8. Что не делать

- 10 экранов без пояснения, что на них;
- скриншоты IDE как главное доказательство;
- огромный stack list;
- один общий `CRM` case на все услуги;
- портфолио только из красивых landing pages, если продаются integrations/backend;
- технические детали без понятного конечного результата.

## Выход генератора portfolio case

1. Buyer intent.
2. Case title.
3. One-line result.
4. Problem/context.
5. What was implemented.
6. Recommended main screenshot.
7. Additional 2–5 visuals.
8. Short stack line.
9. Related kworks.
10. CTA/related services.
