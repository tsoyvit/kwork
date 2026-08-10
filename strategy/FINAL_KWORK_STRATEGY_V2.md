# Kwork Launch Strategy — Research-backed v2

Дата среза: 2026-08-10.

Основание:

- **421 карточка** первой выдачи;
- **18 IT-сегментов**;
- **22 сильных продавца**;
- **14 deep-dives** конкретных кворков;
- live-срез Биржи проектов;
- визуальный анализ representative covers;
- base scope / extras / requirements / actual delivery patterns.

Сырые наблюдения находятся в `data/`, выводы — в `research/`, стандарты — в `specs/`.

---

# 1. Модель профиля

Не выбирать одну узкую нишу как единственную идентичность.

Рабочая модель:

**широкий технический профиль → много узких buyer intents → несколько ценовых слоёв → быстрое накопление reviews + рост среднего чека.**

Профиль продаёт способность решать прикладные IT-задачи. Конкретность обеспечивают отдельные кворки.

## Positioning

Рекомендуемая формула:

**Разработка и автоматизация: сайты, боты, API, CRM, скрипты, AI и веб-сервисы.**

Покупатель должен понимать, что можно прийти:

- с маленькой правкой;
- с интеграцией;
- с существующим сломанным проектом;
- с новым ботом/сервисом;
- с high-ticket бизнес-системой.

---

# 2. Три экономических слоя

## Layer A — acquisition

Ориентир base: **500–1 500 ₽**.

Задача слоя — дешёвый понятный вход, быстрые заказы, reviews, repeat work.

Примеры:

- WordPress fix;
- PHP/500 error;
- CSS/mobile fix;
- site → Telegram;
- Excel/VBA;
- Google Sheets;
- simple parser/script;
- small plugin setup;
- IT setup;
- small server issue.

Низкая base price допустима только при жёстком unit/scope.

## Layer B — core revenue

Ориентир: **1 500–10 000 ₽**.

Примеры:

- API/webhook;
- CRM integration;
- bot modification;
- n8n automation;
- PageSpeed;
- QA/audit;
- custom scripts/programs;
- deploy;
- plugin development.

## Layer C — price ceiling

Ориентир: **10 000–100 000+ ₽**.

Примеры:

- business bots;
- AI assistants;
- AI sales/support;
- Mini Apps;
- SaaS/MVP;
- admin/user cabinets;
- custom software;
- complex websites/integrations.

Профиль должен иметь Layer C с первого дня, иначе витрина закрепит позиционирование `мелкие правки`.

---

# 3. Главный закон карточки

**Один кворк = одна понятная причина покупки.**

Не:

`Full-stack разработчик PHP Python JS`.

А:

- `Ошибка 500 WordPress`;
- `Заявки с сайта в Bitrix24`;
- `Макрос VBA в Excel`;
- `Парсер → Excel`;
- `Ускорение WordPress`;
- `Тестирование сайта + bug-report`;
- `AI-ассистент для бизнеса`.

Полный стандарт: `specs/KWORK_CARD_SPEC.md`.

---

# 4. Стартовая витрина: 40 buyer intents

## Wave 1

`strategy/initial-20-kworks.md`

Покрывает:

- site fixes;
- WordPress/Bitrix;
- frontend;
- scripts/parsers;
- Sheets;
- server;
- API/CRM;
- bots;
- n8n;
- AI;
- MVP/SaaS.

## Wave 2

`strategy/second-wave-20-kworks.md`

Добавляет:

- PageSpeed;
- WordPress plugin development/fix;
- import/export;
- VBA;
- deeper Sheets automation;
- desktop software;
- QA;
- broken resources;
- unit tests;
- technical consultation;
- deploy;
- business AI.

## Правило

Не ждать, пока одна карточка «раскачается», прежде чем создавать соседние intents. Marketplace search — это площадь присутствия.

Но карточки не должны быть keyword duplicates. Каждая обязана соответствовать отдельной покупательской задаче.

---

# 5. Base scope

Низкая цена работает только вместе с измеримым unit.

Хорошие units из live Kwork:

- 1 проблема;
- 1 macro;
- 1 форма → 1 CRM;
- 1 сайт;
- 1 workflow;
- 1 endpoint;
- 1 audit/report;
- N fields;
- N records;
- 1 deploy;
- 1 assistant/prototype.

## Benchmark

Реальный кворк `Заявки с сайта в Bitrix24`:

- base 500 ₽;
- 1 форма;
- 1 простой HTML/CSS сайт;
- contact + deal в CRM.

WordPress/Bitrix, UTM, duplicate control, дополнительные формы — extras.

Это образцовая структура дешёвого входа.

---

# 6. Extras — основной механизм среднего чека

Extras проектируются **до публикации**, одновременно с base scope.

Типовые upsells:

- extra unit;
- urgent;
- CMS/custom source;
- API;
- DB;
- auth;
- payment;
- admin panel;
- deployment;
- server setup;
- extra workflow;
- data volume;
- mobile/browser/device;
- report/retest;
- support;
- privacy/non-portfolio;
- premium optimization.

## Наблюдаемые примеры

### Bitrix24 integration

500 ₽ base →

- WordPress/Bitrix +3 000 ₽;
- UTM +1 000 ₽;
- extra form +500 ₽;
- duplicate control +1 000 ₽.

### VBA macro

500 ₽ base →

- import/export +500 ₽;
- ribbon menu +500 ₽;
- >4 files +1 000 ₽;
- pivot automation +1 500 ₽.

### Desktop QA

5 000 ₽ base →

- mobile +4 000 ₽;
- target users +6 000 ₽;
- urgent +5 000 ₽.

Вывод: base price сама по себе почти ничего не говорит о revenue potential.

---

# 7. Pricing anchors

Медианы первой выдачи расширенного среза:

| Segment | Median entry |
|---|---:|
| Website error fixes | ~1 000 ₽ |
| Office / Excel | ~1 000 ₽ |
| IT help | ~1 000 ₽ |
| Website setup | ~1 500 ₽ |
| Plugins / themes | ~1 500 ₽ |
| Custom software | ~2 500 ₽ |
| Website speed | ~2 750 ₽ |
| QA / testing | ~3 500 ₽ |
| AI bots | ~10 000 ₽ |

Из первого batch:

- scripts ~1 000 ₽;
- parsers ~1 500 ₽;
- frontend fixes ~1 000 ₽;
- server ~1 500 ₽;
- bots ~3 000 ₽;
- AI automation ~5 000 ₽;
- Mini Apps ~10 000 ₽;
- website creation ~10 000 ₽.

Это anchors, не price rules.

Для нового профиля важнее:

`price + unit + proof + extras + speed`.

---

# 8. Covers

Исследование не подтверждает единственный «правильный дизайн».

Работают разные модели:

1. огромный symptom: `ОШИБКА 500`;
2. literal flow: `САЙТ → BITRIX24`;
3. artifact screenshot: dashboard/table/result;
4. simple product label: `VBA FOR EXCEL`;
5. illustration: QA/testing;
6. face/expert;
7. flashy AI creative;
8. product modules for high-ticket.

## Единственное устойчивое правило

**result/category должен считываться за 1–2 секунды.**

Сильный продавец может позволить себе посредственный cover благодаря reviews. Новый профиль — нет. Поэтому на старте ясность должна быть выше среднего.

---

# 9. Description

Не начинать с CV.

Порядок:

1. результат;
2. типовые ситуации;
3. base scope;
4. deliverable;
5. extras / exclusions;
6. requirements;
7. CTA.

## Для QA

Продавать artifact:

`PDF bug-report + screenshots + recommendations`.

## Для AI/high-ticket

Продавать business function:

- sales;
- support;
- leads;
- booking;
- document flow;
- CRM;
- analytics.

LLM/stack вторичны.

---

# 10. Requirements

Минимизировать friction.

Для microtask:

- URL;
- описание `сейчас / должно быть`;
- screenshot;
- доступ при необходимости.

Для integrations:

- access;
- API docs/keys;
- fields/events;
- desired flow.

Для risky website changes:

- admin/hosting;
- backup confirmation.

Для high-ticket AI:

1. цель;
2. канал;
3. integrations;
4. knowledge/data.

Не требовать формальное ТЗ там, где достаточно нормального человеческого описания задачи.

---

# 11. Delivery speed

Kwork показывает фактическое `обычно выполняет за ...`.

Это превращает скорость в social proof.

Live examples:

- PageSpeed: 5-day SLA, обычно 9 часов;
- VBA: 3-day SLA, обычно 23 часа;
- Bitrix integration: 3-day SLA, обычно 18 часов;
- QA: 5-day SLA, обычно 2 дня.

Правило:

**SLA ставить безопасный, actual delivery делать быстрее.**

Не обещать 1 день, если это создаёт риск late delivery.

---

# 12. Категория Kwork — отдельная переменная

Одинаковая задача может продаваться не там, где разработчик интуитивно ожидает.

Например `Заявки с сайта в Bitrix24` обнаружены в `Компьютерная и IT помощь`.

Перед публикацией каждого кворка:

1. найти похожие карточки;
2. посмотреть, где лежат сильные аналоги;
3. выбрать category по buyer discovery.

Это нужно включить в generator pipeline.

---

# 13. Профиль

Использовать `specs/PROFILE_SPEC.md`.

Профиль должен отвечать на вопрос:

**«можно ли этому человеку доверить техническую задачу?»**

Не повторять каждую карточку.

Не делать profile headline списком из 15 технологий.

До reviews trust строится через:

- avatar;
- понятный title;
- реальные portfolio screens;
- product cases;
- конкретные cards;
- быстрый ответ;
- грамотные questions.

---

# 14. Portfolio

Использовать `specs/PORTFOLIO_SPEC.md`.

Portfolio item = proof под buyer intent.

Один реальный продукт можно разложить на несколько proofs:

- admin panel;
- CRM flow;
- API integration;
- user cabinet;
- Windows client;
- real-time;
- bot;
- analytics.

Но кейс не должен выдумывать функционал, которого в реальном продукте не было.

---

# 15. Биржа проектов

На старте Биржа — главный outbound channel.

Live snapshot показывает большой spread proposals: от 0 до 70+.

Не использовать `много откликов` как запрет.

## Priority queue

### P0

- задача понятна;
- можем выполнить;
- есть похожий proof;
- buyer имеет историю покупок/hire;
- ответ можно подготовить быстро.

### P1

- нужен короткий technical research;
- API/docs/code нужно проверить.

### P2

- слабая экономика;
- много неопределённости;
- высокий risk.

P2 = lower priority, не автоматический отказ.

---

# 16. Отклик

`specs/RESPONSE_SPEC.md`.

Структура:

`понял задачу → как решу → proof → blocking questions → scope/price → CTA`.

Microtask — коротко.

Complex project — decomposition + первый milestone.

Не писать generic cover letter о себе.

---

# 17. Automation architecture

Цель — ускорять анализ и подготовку, а не превращать Kwork в spam automation.

```text
project/card idea
    ↓
classifier
    ↓
buyer intent / category
    ↓
scope unit
    ↓
price anchor
    ↓
portfolio matcher
    ↓
card/response generator
    ↓
human review
    ↓
publish/send
```

Knowledge base:

- `specs/KWORK_CARD_SPEC.md`;
- `specs/PROFILE_SPEC.md`;
- `specs/PORTFOLIO_SPEC.md`;
- `specs/RESPONSE_SPEC.md`;
- portfolio cases;
- pricing observations;
- completed-order learnings.

---

# 18. После каждого заказа

Каждый заказ должен увеличить скорость следующего.

Фиксировать:

1. actual scope;
2. actual time;
3. price;
4. extras;
5. buyer questions;
6. bugs/risks;
7. reusable code;
8. portfolio proof;
9. review;
10. related kwork ideas.

Это превращает исполнение в data flywheel.

---

# 19. Metrics

## Daily

- projects reviewed;
- responses sent;
- response time;
- replies;
- active dialogues;
- orders.

## Per kwork

- impressions/views;
- messages;
- orders;
- conversion;
- average order value;
- extras share;
- actual delivery time;
- review rate;
- repeat rate.

## Funnel

`view/response → message → dialogue → order → successful delivery → review → repeat`.

Оптимизировать completed paid orders и revenue, а не vanity traffic.

---

# 20. Operating plan

## Phase 0 — account readiness

1. seller onboarding;
2. photo/avatar;
3. profile text;
4. 5–8 strongest portfolio previews.

## Phase 1 — launch

1. Wave 1 cards;
2. Биржа с первого дня;
3. response templates;
4. daily metrics.

## Phase 2 — width

1. Wave 2 cards;
2. separate PageSpeed / QA / VBA / plugins / deploy / AI intents;
3. cross-category placement testing.

## Phase 3 — optimize

После первых собственных данных:

- views, no messages → title/cover/offer;
- messages, no orders → trust/price/scope;
- orders, low AOV → extras;
- repeat demand → dedicated card;
- repeated project type → reusable template/automation.

## Phase 4 — scale

- more cards around proven intents;
- higher price ceilings;
- repeat customers;
- faster delivery through reusable modules;
- stronger portfolio;
- own Kwork conversion data becomes more important than competitor research.

---

# 21. Что делать дальше

Исследования конкурентов уже достаточно, чтобы запускать production loop.

Следующий marginally valuable work:

1. подготовить финальные тексты первых 10–20 cards;
2. сделать cover briefs;
3. подобрать portfolio proof под каждую;
4. завершить seller onboarding;
5. публиковать;
6. отвечать на Биржу;
7. собирать собственные conversion data;
8. обновлять spec/strategy не по ощущению, а по результатам.

**Итог:** marketplace strategy строится не вокруг поиска «идеальной ниши», а вокруг системного покрытия buyer intents, ограниченного base scope, сильного proof, модульных extras, скорости и постоянного расширения того, что уже доказало спрос собственными заказами.
