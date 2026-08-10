# Kwork Launch Strategy — Research-backed v1

Дата среза: 2026-08-10.

## 0. Что исследовано

Эта стратегия основана не на общем гайде по фрилансу, а на живом Kwork через авторизованный browser session.

В репозитории собрано:
- карта всей категории `Разработка и IT`;
- **210 реальных карточек** из 9 IT-сегментов;
- **22 сильных продавца**;
- глубокий разбор 9 конкретных кворков;
- живые проекты Биржи с buyer/hire/proposals/budget metrics;
- отдельные спецификации карточки, профиля, портфолио и отклика.

Сырые URL сохранены в `data/`.

# 1. Главная стратегия

## Не искать одну нишу

Наша модель:

**широкий технический профиль → множество конкретных покупательских входов → быстрые микро-заказы + средние проекты + high-ticket продукты.**

Это подтверждается реальными продавцами:
- `rokoss21` — broad site/bot/AI/API/parsing profile, 92 заказа за сравнительно новый аккаунт;
- `anastasia_dev` прямо продаётся как `программист широкого профиля`;
- `alexwebdev_pro`, `LEOnidUKG`, `Constantinesx` совмещают несколько технических направлений;
- `ameganix`, `alexgah`, `modx_master` показывают, что один execution skill можно разложить на множество отдельных buyer intents.

**Конкуренция не является причиной отказываться от карточки или проекта.** Она может влиять на упаковку/скорость ответа, но не на доступ к рынку.

# 2. Экономическая модель

У нас должно быть 3 слоя одновременно.

## Layer A — acquisition / reviews

500–1 500 ₽ base:
- site fixes;
- WordPress;
- frontend;
- scripts;
- parsers;
- server issues;
- simple notifications/integrations.

Исследование первой выдачи показывает, что такие цены активно используют продавцы с сотнями и тысячами заказов. Это нормальная product strategy, а не только демпинг новичка.

## Layer B — core revenue

1 500–10 000 ₽:
- API/webhooks;
- CRM integrations;
- Telegram bots;
- automation;
- backend;
- data flows.

Это ближе всего к имеющемуся production experience и потенциально даёт repeat work.

## Layer C — price ceiling

5 000–100 000+ ₽:
- business bots;
- AI/LLM integration;
- Mini Apps;
- SaaS/MVP;
- CRM;
- admin/user cabinets;
- websites under key.

High-ticket слой нужен с первого дня, чтобы профиль не фиксировался только на `поправить кнопку`.

# 3. Что делать с текущим аккаунтом

На момент исследования профиль `tsoyvetal`:
- ещё не завершил seller onboarding;
- avatar — `T`;
- description отсутствует;
- active kworks отсутствуют;
- reviews отсутствуют.

## Порядок

1. Завершить `Стать продавцом`.
2. Поставить нормальный avatar/photo.
3. Заполнить profile по `specs/PROFILE_SPEC.md`.
4. Подготовить стартовые portfolio proofs.
5. Создать 20 стартовых kworks из `strategy/initial-20-kworks.md`.
6. Сразу параллельно работать с Биржей, не ждать organic traffic карточек.

# 4. Профиль

Профиль не должен быть резюме PHP-разработчика.

Buyer-facing positioning:

**Разработка и автоматизация: сайты, боты, API, CRM, скрипты и веб-сервисы.**

Первая мысль клиента:

> Можно прийти и с маленькой правкой, и с нестандартной технической задачей.

Внутри profile description:
- какие результаты делаем;
- production/product experience;
- как идёт работа;
- compact stack внизу;
- CTA `опишите задачу как есть`.

Codex не является основным selling point. Клиент покупает результат.

# 5. Стартовое портфолио

Не загружать всё резюме. Один проект превращается в buyer-facing proof.

## Skillcue

Приоритетные cases:
1. `SaaS-сервис: кабинет, админка и Windows-приложение`.
2. `Админ-панель и пользовательский кабинет`.
3. `Windows-приложение + backend synchronization`.
4. `Real-time система / WebSocket`.

## RuviCRM

5. `CRM для записи клиентов: расписание, сотрудники, услуги`.
6. `CRM / booking workflow для сервисного бизнеса`.

## Rubikon experience

Не `Компания Rubikon — список 30 продуктов`, а отдельные buyer proofs:
7. `CRM + online booking integration`.
8. `API/webhook automation между бизнес-сервисами`.
9. `CRM analytics / client metrics`.
10. `External service ↔ CRM synchronization`.

## Telegram

11. Отдельный bot case с реальным interface/flow/result.

Детальная структура: `specs/PORTFOLIO_SPEC.md`.

# 6. Первые 20 кворков

Полная таблица: `strategy/initial-20-kworks.md`.

Логика распределения:

### 12 acquisition cards
WordPress, website fixes, PHP errors, frontend, site→Telegram, Bitrix, Laravel/backend, Python script, parser, sheets automation, server problem.

### 5 standard system cards
API/webhook, CRM integration, bot modification, simple bot, n8n/Make/Zapier.

### 3 value-ceiling cards
business bot, AI/LLM integration, SaaS/MVP/admin.

После первого заказа не останавливаться на этих 20: строить десятки дополнительных problem/outcome cards.

# 7. Как должна быть оформлена карточка

Источник: `specs/KWORK_CARD_SPEC.md`.

Главные правила:

1. **Один buyer intent на карточку.**
2. Title = problem/outcome/product/platform+job.
3. Cover читается за 1–2 секунды.
4. Base scope измеримый и ограниченный.
5. Extras монетизируют complexity.
6. Description говорит о результате, а не о developer CV.
7. Requirements минимальны и помогают быстро начать.
8. Gallery/portfolio максимально похожи на услугу.

## Особенно важный вывод по cover

Исследование не показало, что всегда выигрывает «премиальный дизайн».

Сильные продавцы используют:
- простейший огромный текст проблемы (`Ошибка 500`);
- буквальный `Парсинг в Excel`;
- screenshot реального result;
- лицо + short promise;
- high-ticket product modules.

**Ясность > декоративность.**

# 8. Extras — обязательная часть экономики

Низкий base не должен означать низкий итоговый чек.

Повторяемые extras в реальных карточках:
- urgent;
- extra change/time;
- deployment;
- server setup;
- API;
- DB;
- admin panel;
- authorization;
- payment;
- styling;
- Telegram/email notifications;
- extra volume;
- file/image download;
- post-processing;
- support.

Например у business Telegram bot `rokoss21` на первом экране:
- deploy +2 500 ₽;
- external API +3 500 ₽;
- admin panel +4 500 ₽;
- DB +4 000 ₽.

Это правильная модель: cheap/clear entry + modular expansion.

# 9. Биржа проектов

Биржа должна быть главным outbound channel на старте.

В живом срезе одновременно были:
- project с **0 proposals**;
- 3–4;
- 15–27;
- 44–53;
- 72.

Наша политика:

**не фильтровать по количеству предложений**, а использовать его для очереди.

## P0
Понятно, можем быстро сделать, buyer нанимает, есть похожий case → отвечать сразу.

## P1
Нужно коротко изучить API/code/docs → отвечать после P0.

## P2
Много неизвестных / слабая экономика → отвечать позже при свободном ресурсе.

P2 ≠ запрет.

# 10. Что важно смотреть у заказчика

Kwork показывает полезные buyer signals:
- previous purchases;
- number of exchange projects;
- hire rate;
- open projects;
- proposals.

Они помогают решить **куда ответить первым**, а не кому вообще нельзя отвечать.

Особенно привлекательный pattern:
`buyer часто покупает + высокий hire rate + понятная небольшая задача`.

# 11. Отклик

Использовать `specs/RESPONSE_SPEC.md`.

Принцип:

`понял задачу → коротко как решу → похожий proof → только blocking questions → цена/scope → CTA`.

Microtask-response должен быть коротким. На задачу за 1 000 ₽ не нужен КП на страницу.

Для сложного project можно дать decomposition и proposed first milestone.

# 12. Скорость

Для нашей стратегии скорость — operating advantage.

Целевой процесс:

`новый проект → 1–3 мин analysis → matching case → draft → human check → send`.

Не потому, что первый всегда выигрывает, а потому что это увеличивает число качественных попыток и шанс попасть до того, как buyer уже ушёл в диалог с другим исполнителем.

# 13. Автоматизация

Целевая архитектура:

```text
Kwork official notification / user-opened project
        ↓
project data
        ↓
AI classifier
        ↓
size + risks + buyer metrics
        ↓
portfolio matcher
        ↓
response generator
        ↓
Telegram
[Send / Edit / Skip]
        ↓
manual action on Kwork
```

Автоматизировать сначала **анализ и подготовку**, а не массовое взаимодействие с сайтом.

Knowledge base для генератора должна брать:
- `specs/KWORK_CARD_SPEC.md`;
- `specs/PORTFOLIO_SPEC.md`;
- `specs/RESPONSE_SPEC.md`;
- portfolio cases;
- список services/prices;
- completed-order learnings.

# 14. После каждого заказа

Заказ должен создавать не только revenue.

Обновить:
1. review/status;
2. portfolio proof;
3. reusable code/template;
4. estimate library;
5. response blocks;
6. related kwork ideas;
7. known risks/questions.

То есть каждый заказ увеличивает скорость следующего.

# 15. Масштабирование витрины

После снятия стартового ограничения:

## WordPress/CMS cluster
- generic fix;
- Error 500;
- forms;
- emails;
- WooCommerce;
- plugins;
- speed;
- migration;
- API;
- Telegram notifications.

## Scripts cluster
- Python;
- PHP;
- JS;
- calculator;
- files/data;
- browser extension;
- scheduled automation.

## Parsing cluster
- site→Excel;
- supplier prices;
- products;
- images/files;
- Telegram;
- authenticated sources;
- scheduled parsing.

## Integration cluster
- generic API;
- webhook;
- amoCRM;
- Bitrix24;
- YCLIENTS/Altegio;
- МойСклад;
- GetCourse;
- Tilda;
- payment systems;
- Sheets.

## Bots cluster
- simple bot;
- fix bot;
- notification bot;
- CRM bot;
- payment bot;
- admin bot;
- AI bot;
- Mini App.

## Infrastructure cluster
- deploy;
- Docker;
- Nginx;
- SSL;
- VPS;
- database;
- migration;
- application deployment.

# 16. Метрики

## Daily
- new projects seen;
- responses sent;
- median response time;
- buyer replies;
- active dialogues;
- orders.

## Per kwork
- views;
- messages;
- orders;
- average order value;
- extras share;
- delivery time;
- reviews.

## Funnel

`response → reply → dialogue → order → successful delivery → review → repeat`.

Главная оптимизация — не vanity views, а деньги и completed orders.

# 17. План запуска

## Сегодня

1. Seller onboarding.
2. Avatar/profile.
3. Подготовить 5–8 strongest portfolio previews.
4. Опубликовать first acquisition kworks как можно быстрее.
5. Довести до 20 стартовых карточек.
6. Начать отвечать на Биржу в тот же день.

## Следующие 3 дня

- активно отвечать на весь выполнимый IT-flow;
- доделать portfolio;
- корректировать base scopes, если приходят не те expectations;
- фиксировать каждый response/order в analytics sheet;
- создавать reusable solution templates.

## Первая неделя

- максимальное число качественных попыток;
- первые reviews;
- анализ response→reply;
- анализ, какие kworks получают messages;
- после снятия лимита — expansion matrix;
- не ждать статистической значимости месяцами: менять явно слабую упаковку быстро, но не удалять demand category только из-за отсутствия мгновенной продажи.

# 18. Что ещё не доказано рынком

Нужно отдельно отличать факты от гипотез:

- мы не видим чужие winning proposals, поэтому RESPONSE_SPEC валидируется нашей статистикой;
- exact ranking formula Kwork не наблюдаема;
- accessibility layer браузера не показывает текст/alt многих portfolio thumbnails, поэтому PORTFOLIO_SPEC частично основан на card galleries и buyer logic;
- стартовые цены — benchmarks первой выдачи, не средний фактический чек.

Это не мешает запуску: дальше собственные conversion data должны стать главным источником оптимизации.

# 19. North Star

Не `стать лучшим PHP-разработчиком на Kwork`.

Не `найти категорию без конкурентов`.

North Star:

**максимизировать количество успешно завершённых оплачиваемых IT-заказов, положительных отзывов, repeat clients и выручку при минимальном времени от появления спроса до качественного предложения.**
