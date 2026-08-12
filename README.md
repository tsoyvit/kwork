# Kwork Research & Launch

Практическая исследовательская база и launch-пакет для запуска и масштабирования профиля разработчика на Kwork.

## Цель

Максимизировать количество успешно выполненных оплачиваемых IT-заказов, положительных отзывов и выручку за минимально возможное время. Профиль не ограничивается одной технологией или нишей; отдельные кворки соответствуют конкретным покупательским задачам.

## Принцип

Сначала собраны наблюдаемые данные из реального интерфейса Kwork, затем выделены повторяющиеся паттерны. Конкуренция не используется как причина отказываться от услуги: она рассматривается только как контекст упаковки и порядка действий.

## Исследовательская база

Срез через авторизованную браузерную сессию Kwork:

- **421 карточка** в **18 сегментах**;
- **22 сильных продавца**;
- **14 deep-dives** конкретных карточек;
- live-срез Биржи проектов;
- анализ base scope, extras, requirements, covers и delivery patterns;
- спецификации профиля, карточки, портфолио и отклика;
- стратегия первых 40 buyer intents.

## Главное

**Широкий технический профиль → много конкретных buyer intents → дешёвые микро-заказы для acquisition + средние системные задачи + high-ticket продукты.**

На уровне карточки:

**один кворк = одна понятная причина покупки.**

---

# Launch package

Исследование уже переведено в материалы для реального запуска.

## Профиль

- `launch/profile/FINAL_PROFILE.md` — финальный buyer-facing текст профиля, positioning, skills и avatar requirements.

## Портфолио

- `launch/portfolio/PORTFOLIO_PLAN_V1.md` — первые 8 buyer-facing кейсов из Skillcue, RuviCRM, Rubikon и Telegram experience + требования к screenshots.

## Первые 20 кворков

- `launch/kworks/WAVE1_READY_01_10.md` — готовые карточки 1–10: title, price, scope, description, extras, requirements, exclusions, cover, portfolio.
- `launch/kworks/WAVE1_READY_11_20.md` — готовые карточки 11–20.
- `launch/COVER_BRIEFS_WAVE1.md` — визуальные briefs для всех 20 covers.

## Запуск

- `launch/LAUNCH_CHECKLIST.md` — последовательный checklist от seller onboarding до первых заказов и перехода к Wave 2.

---

# Research structure

## Методика и карта рынка

- `research/00_research_methodology.md`
- `research/market-map.md`
- `research/market-expansion-2026-08-10.md`

## Сырые данные

- `data/segments/` — CSV-срезы первой выдачи.
- `data/observed_cards_2026-08-10.csv` — исходная объединённая выборка первого batch.

Исследованы в том числе:
- website repair / errors / setup / speed / plugins;
- scripts / parsers / frontend;
- chat bots / AI agents / AI bots / mini apps;
- servers;
- website development;
- custom software;
- Office / Excel / Google Sheets automation;
- QA / usability / testing;
- computer & IT help.

## Продавцы и карточки

- `research/sellers/` — seller case studies.
- `research/cards/` — deep-dives конкретных кворков.
- `research/exchange/` — live Биржа.

## Спецификации

- `specs/KWORK_CARD_SPEC.md`
- `specs/PROFILE_SPEC.md`
- `specs/PORTFOLIO_SPEC.md`
- `specs/RESPONSE_SPEC.md`

## Стратегия

- `strategy/FINAL_KWORK_STRATEGY_V2.md`
- `strategy/initial-20-kworks.md`
- `strategy/second-wave-20-kworks.md`

---

# Текущий следующий шаг

1. Завершить seller onboarding.
2. Поставить avatar и заполнить профиль из `launch/profile/FINAL_PROFILE.md`.
3. Подготовить 5–8 portfolio screenshots/proofs.
4. Опубликовать Wave 1 из `launch/kworks/`.
5. Параллельно сразу работать с Биржей.
6. После первых заказов обновлять scopes, prices, portfolio и response templates по собственным conversion data.
7. После снятия стартового ограничения переходить к Wave 2 и дальнейшему масштабированию витрины.
