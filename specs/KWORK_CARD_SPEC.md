# KWORK_CARD_SPEC

Спецификация основана на живом анализе **421 карточки Kwork в 18 сегментах** и **14 deep-dives**. Это рабочий стандарт для генерации новых кворков.

## 1. Выбрать покупательский intent

Каждый кворк должен отвечать **одной причине покупки**. Допустимые типы:

1. **Problem:** `Исправлю ошибку 500 WordPress`.
2. **Outcome:** `Настрою заявки с сайта в Telegram`.
3. **Product:** `Создам Telegram-бота с оплатой и CRM`.
4. **Platform + job:** `Доработаю сайт на WordPress`.
5. **Data flow:** `Парсер сайта → Excel/CSV`, `WB API → Google Sheets`.
6. **Audit / diagnostic:** `Протестирую сайт и подготовлю bug-report`, `Найду причину медленной загрузки`.
7. **Setup / deployment:** `Настрою готовый сервис на VPS`, `Установлю и настрою WordPress-плагин`.
8. **Consultation:** `Разберу интеграцию CRM/API и дам план реализации`.

Не создавать title в стиле `Я программист PHP/Python/JS` — это не покупательская задача.

## 2. Title

Формула:

`[действие/результат] + [объект/платформа] + [ключевой дифференциатор при необходимости]`

Примеры:
- `Исправлю ошибку PHP / 500 на сайте`;
- `Доработаю WordPress: ошибки, формы, функционал`;
- `Настрою уведомления с сайта в Telegram`;
- `Напишу Python-скрипт под вашу задачу`;
- `Сделаю парсер сайта с выгрузкой в Excel / CSV`;
- `Интегрирую API или webhook с вашим сайтом/CRM`;
- `Создам Telegram-бота: логика, API, CRM, оплата`;
- `Автоматизирую Excel: макрос VBA под вашу задачу`;
- `Протестирую сайт и подготовлю PDF bug-report`;
- `Ускорю WordPress по PageSpeed / Core Web Vitals`.

Title должен быть понятен без чтения description.

## 3. Cover

Картинка должна читаться в маленьком размере за 1–2 секунды.

Выбрать один подход:

### A. Problem cover
Большой текст симптома:
`ОШИБКА 500` / `НЕ РАБОТАЕТ ФОРМА` / `PHP BUG`.

### B. Outcome cover
`САЙТ → TELEGRAM`, `ПАРСИНГ → EXCEL`, `API → CRM`.

### C. Artifact cover
Скриншот реального конечного результата: dashboard, таблица, bot UI, admin panel, bug-report.

### D. Personal/expert cover
Лицо + 2–4 коротких результата/модуля. Подходит mid/high-ticket.

### E. Product architecture cover
Для дорогих продуктов: название продукта + 3–5 ключевых модулей (`CRM`, `оплата`, `админка`, `аналитика`).

### F. Literal product label
Для понятных utilitarian services допустим очень простой знак/текст: `VBA FOR EXCEL`, `WORDPRESS PLUGIN`, `UNIT TESTS`.

Не перегружать мелкими логотипами/текстом.

**Важно:** сильные продавцы с большим social proof иногда конвертируют даже с посредственной или очень простой обложкой. Новый профиль не должен рассчитывать на это преимущество. Пока нет отзывов, cover должен быть яснее среднего.

## 4. Первый экран description

Первые 2–4 предложения:

1. Что клиент получит.
2. В каких типовых ситуациях это подходит.
3. Что входит в базовую цену.

Пример структуры:

> Исправлю небольшую проблему на WordPress: ошибка, форма, блок, плагин или другая доработка. В базовый кворк входит до 2 небольших правок на одном сайте. Перед заказом можно прислать задачу — оценю, укладывается ли она в базовый объём.

Для audit/QA лучше сразу назвать deliverable:

> Протестирую основные сценарии сайта и передам bug-report со скриншотами, приоритетом ошибок и рекомендациями по исправлению.

Для high-ticket AI/business system сначала назвать business outcome, а не стек.

## 5. Base scope

Базовый кворк обязательно ограничить **измеримой единицей**.

Подходящие метрики:
- 1 проблема;
- до 2–3 правок;
- 1 сайт;
- 1 webhook/API endpoint;
- 1 форма → 1 CRM;
- 1 workflow;
- 1 macro;
- 1 plugin/module;
- 1 audit/report;
- до N полей/параметров;
- до N страниц/товаров/записей;
- до N минут/часов консультации;
- базовая bot logic;
- 1 deploy;
- 1 AI assistant / agreed prototype scope.

Это позволяет ставить низкую цену без риска продавать большой проект за 500–1 000 ₽.

### Хороший реальный паттерн

Кворк `Заявки с сайта в Bitrix24` продаёт за 500 ₽ строго **1 форму с 1 простого сайта**. WordPress/Bitrix, несколько форм, UTM, duplicate control и другие усложнения вынесены в extras.

## 6. Блок `Что могу сделать`

3–8 buyer-facing bullets. Не tech CV.

Плохо:
- Redis;
- RabbitMQ;
- PostgreSQL;
- REST.

Хорошо:
- исправлю ошибку;
- подключу форму;
- отправлю данные в CRM;
- добавлю Telegram notification;
- настрою import/export;
- подключу внешний API;
- найду ошибки и подготовлю отчёт;
- ускорю загрузку сайта.

Стек можно указать вторично.

## 7. Deliverable

У карточки должен быть понятный конечный артефакт.

Примеры:
- исправленный сайт;
- working macro;
- CSV/XLSX output;
- contact + deal in CRM;
- deployed bot/service;
- PDF bug-report;
- optimized PageSpeed result;
- plugin/module;
- integration workflow;
- configured AI assistant.

Особенно для консультации и QA deliverable нужно прописывать явно, иначе услуга выглядит как продажа времени.

## 8. Extras / upsell

Для каждого кворка продумать 3–7 дополнительных услуг.

Повторяющиеся паттерны Kwork:
- срочность;
- дополнительная правка/час;
- установка/deploy;
- server/hosting setup;
- API integration;
- DB;
- admin panel;
- authorization;
- payment;
- styling по дизайну;
- Telegram/email notifications;
- больший объём данных;
- скачивание файлов/изображений;
- post-processing;
- документация/instruction;
- support period;
- дополнительная форма/source;
- дополнительный browser/device;
- retest;
- privacy/non-portfolio option;
- premium package / deeper optimization.

Extras должны соответствовать естественному усложнению base scope.

### Экономика extras — наблюдаемые примеры

- base macro VBA: 500 ₽; import/export, ribbon UI, extra files и pivot table увеличивают заказ модульно;
- base site→Bitrix24: 500 ₽; WordPress/Bitrix implementation +3 000 ₽, UTM +1 000 ₽, duplicate control +1 000 ₽;
- QA desktop: 5 000 ₽; mobile audit +4 000 ₽, target-user testing +6 000 ₽, срочность +5 000 ₽;
- PageSpeed: 2 000 ₽; premium optimization packages +1 000/+2 000 ₽.

**Следствие:** extras проектируются одновременно с base scope, а не после написания карточки.

## 9. Requirements from buyer

Просить минимальный набор:
- URL/доступы, если нужны;
- краткое описание результата;
- что есть сейчас / что должно стать;
- reference/example;
- API documentation/keys при интеграции;
- input/output fields;
- formula/business rules;
- hosting/server access при deploy;
- исходные files/data для Office/data tasks;
- подтверждение backup перед рискованными изменениями сайта.

Фраза `ТЗ обязательно` не нужна для мелких заказов — можно просить описать задачу как есть.

Для high-ticket AI/business-system карточек requirements лучше формулировать бизнес-вопросами:

1. цель — sales / support / leads / internal automation;
2. канал — site / Telegram / CRM / phone;
3. integrations;
4. source knowledge/data.

## 10. Ограничения

В description явно указать, что **не входит** в base scope, если это предотвращает scope creep.

Пример:
- base включает 1 сайт / 1 endpoint / 2 правки;
- новый дизайн, дополнительная интеграция, deploy, импорт большого объёма — extras или индивидуальный заказ.

Для интеграций отдельно указывать, какой тип source/platform входит в дешёвый base. Например simple HTML form может стоить 500 ₽, а CMS/custom forms — отдельный scope.

## 11. Срок

Ставить срок с запасом, но внутри профиля стремиться делать быстрее заявленного. На сильных карточках Kwork отдельно показывает `обычно выполняет за ...`, и фактическая скорость становится social proof.

Наблюдаемые примеры:
- PageSpeed: срок 5 дней, обычно 9 часов;
- VBA macro: срок 3 дня, обычно 23 часа;
- Bitrix24 integration: срок 3 дня, обычно 18 часов;
- desktop QA: срок 5 дней, обычно 2 дня.

Не ставить нереальный SLA ради клика: late delivery ухудшает профиль сильнее, чем чуть более длинный заявленный срок.

## 12. CTA

Заканчивать конкретным следующим действием:

> Пришлите описание задачи и ссылку/скриншот. Я скажу, входит ли работа в базовый кворк и что нужно для старта.

Для high-ticket:

> Напишите цель, канал и нужные интеграции. Предложу архитектуру и границы первого этапа.

## 13. Portfolio / gallery

К карточке привязывать максимально похожее доказательство:
- screenshot результата;
- before/after;
- video demo;
- workflow/schema;
- таблица/output;
- admin/bot interface;
- sample bug-report;
- PageSpeed before/after;
- plugin settings screen.

Для high-ticket карточки — несколько экранов/примеров, а не один абстрактный логотип.

## 14. Цена

Цена не выбирается по принципу `чем ниже конкуренция, тем выше`.

Структура цены:
- дешёвый base scope для простого входа;
- monetization complexity через extras;
- отдельный mid/high-ticket кворк для полноценного продукта.

### Медианы входа в расширенной первой выдаче

Это **наблюдаемые median anchors**, а не обязательный прайс:

- website error fixes: **~1 000 ₽**;
- Office / Excel automation: **~1 000 ₽**;
- IT help: **~1 000 ₽**;
- website setup: **~1 500 ₽**;
- plugins/themes: **~1 500 ₽**;
- custom software: **~2 500 ₽**;
- website speed: **~2 750 ₽**;
- QA/testing: **~3 500 ₽**;
- AI bots: **~10 000 ₽**.

Ранее исследованные сегменты:
- scripts: ~1 000 ₽;
- parsers: ~1 500 ₽;
- frontend fixes: ~1 000 ₽;
- server tasks: ~1 500 ₽;
- ordinary bots: ~3 000 ₽;
- AI agents/automation: ~5 000 ₽;
- Mini Apps: ~10 000 ₽;
- website creation: ~10 000 ₽.

Внутри каждого сегмента разброс большой. Base price следует выбирать вместе с unit/scope и planned extras.

## 15. Категория размещения

Один и тот же technical intent может встречаться в неожиданной категории Kwork. Например `Заявки с сайта в Bitrix24` находится в `Компьютерная и IT помощь`, а не только в scripts/integrations.

Перед публикацией карточки:

1. найти 5–10 похожих успешных кворков;
2. проверить, где они размещены;
3. выбрать category по buyer discovery, а не по внутренней классификации разработчика.

## 16. Генератор кворка должен возвращать

Для каждой новой темы:
1. Intent.
2. Buyer problem/outcome.
3. 5 вариантов title.
4. Рекомендуемый title.
5. Recommended category/subcategory.
6. Base price.
7. Base scope unit.
8. Delivery time.
9. Deliverable.
10. Description.
11. Extras + prices.
12. Buyer requirements.
13. Scope exclusions.
14. FAQ.
15. Cover concept.
16. Text on cover.
17. Gallery/portfolio plan.
18. Related kworks, которые стоит создать рядом.

## 17. Проверка перед публикацией

Карточка готова только если на все вопросы ответ `да`:

- title понятен без description;
- buyer intent один;
- base scope измерим;
- deliverable понятен;
- complexity вынесена в extras;
- requirements не создают лишнее трение;
- cover читается в thumbnail;
- есть похожий proof или план gallery;
- category подтверждена похожими карточками;
- срок безопасен для SLA;
- цена соответствует scope, а не обещанию «сделаю всё».
