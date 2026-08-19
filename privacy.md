---
title: Privacy Policy
---

<a id="en"></a>

**English** · [Русский](#ru)

# Privacy Policy — UrgeKeeper

**Last updated: 17 August 2026**

UrgeKeeper is an app for noticing your own patterns. Everything you write in it stays on your device. This page describes exactly what the app does, without legal fog.

Developer: Artem Ryaboshapko. Contact: **aaertem040@gmail.com**

---

## In short

- No sign-up. No account. We don't know who you are.
- Your journal — check-ins, moods, thoughts, notes, onboarding answers, name and avatar — **never leaves your device**.
- The only thing sent out is anonymous usage statistics: the fact that a screen was opened or a check-in was saved. Never the content.
- We sell nothing, share nothing with advertisers, and don't track you across other apps.

---

## What stays on your device only

The app stores locally, in iOS protected storage, and never transmits:

- every check-in: mood, energy, stress, selected feelings, free-text notes, day marker;
- the full day-by-day history and everything built on it — charts, calendar, streak;
- the answers you gave on first launch, including the "who I want to be in 3 months" text;
- your name or nickname, chosen avatar, interface language, Face ID setting.

No copy of this exists with us or anyone else. If you erase it in the app or delete the app, it is gone for good. It cannot be recovered — that is the deliberate price of privacy, not an oversight.

## What is sent out

The app sends anonymous product analytics through **TelemetryDeck** (TelemetryDeck GmbH, Germany), so we can tell which features are used and which are not.

**Only event names are sent:**

| Event | Meaning |
|---|---|
| `Onboarding.stepViewed` | a first-launch screen was opened (the step name is included) |
| `Onboarding.remindersEnabled` | the "enable reminders" button was tapped |
| `Onboarding.completed` | first-launch flow finished |
| `CheckIn.completed` | a check-in was saved |
| `CheckIn.dayEdited` | a past day was edited |
| `Moment.opened` | the "Quick Help" screen was opened |
| `StreakResetNotice.shown` | the break notice was shown |

**Along with each event, technical device information is sent:** platform and iOS version, app version and build number, device model, CPU architecture, system language and region, SDK version.

**Identifier:** to tell "10 launches by one person" apart from "10 different people", a pseudonymous identifier is sent — an irreversible salted SHA-256 hash of the system `identifierForVendor`. It is not linked to your name, email or Apple ID, and it changes if you reinstall the app.

**Never sent:** the content of check-ins, moods, feelings, note text, your name, avatar, or any free text you typed.

Put plainly: we can see that someone saved a check-in. We cannot see — and have no way to see — what it says.

## What we don't do

- No advertising, and no data shared with ad networks.
- No tracking across apps and websites. The app does not ask for App Tracking Transparency permission, because it has nothing to track.
- No selling or sharing with data brokers.
- No advertising profiles and no automated decision-making about you.

## Face ID and passcode

If you enable Face ID on launch, iOS performs the check itself. The app receives only a yes or no. Biometric data never leaves the device's secure chip; the app never sees or stores it.

If no passcode is set on the device, the app opens without a check — otherwise you could be permanently locked out of your own notes.

## Reminders

The daily reminder is scheduled locally by iOS. No server knows about it and no server sends you anything. You can turn it on and off at any time under **Profile → Reminders**.

## How to delete your data

**Profile → Data → Delete all data.** This erases every entry, note, answer, your name and avatar, and returns the app to its first-launch state. It cannot be undone.

Deleting the app from your device has the same effect.

To stop analytics entirely, delete the app. If you want already-sent anonymous events removed on TelemetryDeck's side, write to us — but note that we physically cannot link those events to you, so it would require an identifier the app never shows you. The practical route is deleting the app: the new identifier will no longer be connected to the old events.

## Your rights

We hold no data that can identify you, so most requests (access, correction, portability) resolve to the fact that all of your data is already in your hands, on your device.

If you have a question about your rights under the GDPR or other applicable law, write to **aaertem040@gmail.com** and we will answer.

## Children

This app is not intended for children. We deliberately collect no data that could establish age, and do not ask for it.

## Data collected by Apple

Downloads, purchases and system-level analytics are handled by Apple under Apple's privacy policy, not this one. We receive only aggregate, anonymous download statistics from Apple.

## Changes

If this policy changes, we will update the date at the top of the page. Material changes will be noted in the App Store release notes.

## Contact

**aaertem040@gmail.com**

---
---

<a id="ru"></a>

[English](#en) · **Русский**

# Политика конфиденциальности — UrgeKeeper

**Обновлено: 17 августа 2026**

UrgeKeeper — приложение для наблюдения за собой. Всё, что вы в нём пишете, остаётся на вашем устройстве. Эта страница объясняет ровно то, что делает приложение, без юридического тумана.

Разработчик: Artem Ryaboshapko. Связь: **aaertem040@gmail.com**

---

## Коротко

- Регистрации нет. Аккаунта нет. Мы не знаем, кто вы.
- Дневник — чек-ины, настроения, мысли, заметки, ответы онбординга, имя и аватар — **никогда не покидает ваше устройство**.
- Наружу уходит только анонимная статистика использования: факт, что экран открыли или чек-ин сохранили. Без содержимого.
- Мы ничего не продаём, не передаём рекламодателям и не следим за вами в других приложениях.

---

## Что остаётся только на устройстве

Приложение хранит локально, в защищённом хранилище iOS, и никуда не передаёт:

- все чек-ины: настроение, энергия, стресс, отмеченные эмоции, свободные заметки, пометка дня;
- всю историю по дням и всё, что построено на ней — графики, календарь, серию дней;
- ответы, данные при первом запуске, включая текст «каким я хочу быть через 3 месяца»;
- имя или ник, выбранный аватар, язык интерфейса, настройку Face ID.

У этих данных нет копии ни у нас, ни у кого-либо ещё. Если вы удалите их в приложении или удалите само приложение — они исчезнут безвозвратно. Восстановить их невозможно: это осознанная цена приватности, а не недоработка.

## Что уходит наружу

Приложение отправляет анонимную продуктовую статистику через сервис **TelemetryDeck** (TelemetryDeck GmbH, Германия) — чтобы понимать, какими функциями пользуются, а какими нет.

**Передаются только названия событий:**

| Событие | Что означает |
|---|---|
| `Onboarding.stepViewed` | открыт экран первого запуска (передаётся название шага) |
| `Onboarding.remindersEnabled` | нажата кнопка включения напоминаний |
| `Onboarding.completed` | первый запуск пройден до конца |
| `CheckIn.completed` | чек-ин сохранён |
| `CheckIn.dayEdited` | день отредактирован задним числом |
| `Moment.opened` | открыт экран «Quick Help» |
| `StreakResetNotice.shown` | показано уведомление о перерыве |

**Вместе с событием передаётся техническая информация об устройстве:** платформа и версия iOS, версия и номер сборки приложения, модель устройства, архитектура процессора, язык и регион системы, версия SDK.

**Идентификатор:** чтобы отличать «10 запусков у одного человека» от «10 разных людей», передаётся псевдонимный идентификатор — необратимый хеш (SHA-256 с солью) от системного `identifierForVendor`. Это значение не связано ни с вашим именем, ни с почтой, ни с Apple ID, и меняется при переустановке приложения.

**Никогда не передаётся:** содержимое чек-инов, настроения, эмоции, тексты заметок, ваше имя, аватар и любой свободный текст, который вы вводили.

Другими словами: мы видим, что кто-то сохранил чек-ин. Мы не видим и не можем увидеть, что в нём написано.

## Чего мы не делаем

- Не показываем рекламу и не передаём данные рекламным сетям.
- Не отслеживаем вас между приложениями и сайтами. Разрешение App Tracking Transparency приложение не запрашивает, потому что ему нечего отслеживать.
- Не продаём и не передаём данные брокерам данных.
- Не строим профиль для рекламы и не принимаем автоматических решений о вас.

## Face ID и код-пароль

Если вы включили Face ID на запуск, проверку выполняет сама iOS. Приложение получает только ответ «да» или «нет». Биометрические данные не покидают защищённый чип устройства, приложение их не видит и не хранит.

Если на устройстве не задан код-пароль, приложение откроется без проверки — иначе вы могли бы навсегда потерять доступ к собственным записям.

## Напоминания

Ежедневное напоминание планируется локально, средствами iOS. Никакой сервер о нём не знает и никаких уведомлений вам не отправляет. Включить и выключить его можно в любой момент: **Профиль → Напоминания**.

## Как удалить свои данные

**Профиль → Данные → Удалить все данные.** Это стирает все записи, заметки, ответы, имя и аватар и возвращает приложение к состоянию первого запуска. Отменить нельзя.

Удаление приложения с устройства даёт тот же результат.

Чтобы прекратить отправку статистики, достаточно удалить приложение. Если вы хотите, чтобы уже отправленные анонимные события были удалены на стороне TelemetryDeck, напишите нам — но учтите, что мы физически не можем связать эти события с вами, поэтому потребуется идентификатор, который приложение вам не показывает. Практический способ — удалить приложение: новый идентификатор больше не будет связан со старыми событиями.

## Ваши права

Мы не храним данных, по которым вас можно опознать, поэтому большая часть запросов (доступ, исправление, перенос) сводится к тому, что все ваши данные уже находятся у вас в руках, на вашем устройстве.

Если у вас есть вопрос о ваших правах по GDPR или другому применимому закону — напишите на **aaertem040@gmail.com**, и мы ответим.

## Дети

Приложение не предназначено для детей. Мы сознательно не собираем данных, по которым можно определить возраст, и не запрашиваем их.

## Данные, которые собирает Apple

Загрузка приложения, покупки и системная аналитика находятся в ведении Apple и регулируются политикой конфиденциальности Apple, а не этой. Мы получаем от Apple только обезличенную статистику загрузок.

## Изменения

Если политика изменится, мы обновим дату вверху страницы. Существенные изменения будут отмечены в описании обновления в App Store.

## Связь

**aaertem040@gmail.com**
