# Star Wars: Rebellion — Digital Map (EN / UA)

**[English](#english) · [Українська](#українська)**

▶️ **Open the map / Відкрити мапу:** https://toxober.github.io/StarWars-Rebellion-Map-Tracker/

---

## English

A single-file digital map for the **Star Wars: Rebellion** board game. It opens in any browser on a phone, tablet, or PC. You don't need to install anything, create an account, or stay online, because the map image is embedded directly in the file.

**Version 2.2**

### Features

- All **32 systems** are labelled in English and Ukrainian. Large vector text is overlaid on the printed labels of the map scan.
- Each of the **24 populated systems** shows its build queue number, resource symbols, and allegiance.
- There are two ways to show allegiance, and you can switch between them in the menu:
  - **Planet colouring:** black for Empire, white for Rebels, dark grey for subjugated.
  - **Hexagon tokens** with emblems (Imperial crest, Rebel symbol, stormtrooper helmet). Planets are coloured in this mode too.
- Red crosses, sabotage markers, and enemy troop shading.
- **Production calculator** for both sides.
- Your own custom icons for allegiance tokens and ships.
- **Autosave:** the game state stays in the browser, even if you close the page mid-game.
- Works offline and supports fullscreen mode.

### How to use

| Action | Result |
|---|---|
| **Long press** on a planet or its name | Places a red cross. Long press again to remove it. Coruscant is always crossed. |
| **Tap** on a hexagon or planet | Cycles allegiance: empty → subjugated → Imperial → Rebel → empty. Coruscant is always Imperial. |
| **Tap** on the resource symbols | Places a sabotage marker. Tap again to remove it. |
| **Long press** on a system's area | Marks enemy troops. The whole system is shaded and a ship icon appears. This works only for systems with an allegiance; otherwise a hint is shown. |
| Pinch / **+ −** buttons | Zoom |
| Drag | Pan the map |

If fullscreen mode gets lost (for example, after a screen lock or an app switch), the first tap brings it back.

### Menu (⋮)

- **Calculate production** shows what each side builds in queues 1–3.
  - *Rebels:* all symbols of Rebel systems, plus the Rebel Base, which is always counted.
  - *Empire:* all symbols of Imperial systems and only the first symbol of subjugated ones.
  - Systems with sabotage or enemy troops are skipped and listed separately.
- **Custom icons** replace the allegiance tokens and ship icons with your own pictures. A plain background is removed automatically.
- **Allegiance style:** planet colouring or hexagons.
- **How to use** opens a short built-in guide.
- Fullscreen on/off, reset zoom, clear the map, switch language, exit.

The menu scrolls on small screens.

### Running locally

1. Download `index.html`.
2. Open it in a browser.

**Android tip.** If you open the file from a file manager, you may later see `ERR_FILE_NOT_FOUND`. This happens because the file manager gives the browser only temporary access to the file. To avoid it, use the online version or open the file directly in Chrome with `file:///sdcard/Download/<file_name>.html`.

**Saved games** are stored in the browser's `localStorage` and are tied to the page address. The online version and a local file therefore keep separate saves.

### License and feedback

The map is free to use and share. Feedback and corrections to the planet names are welcome. Please open an [Issue](../../issues).

*This is an unofficial fan-made tool. Star Wars: Rebellion is a trademark of its respective owners (Fantasy Flight Games, Lucasfilm). This project is not affiliated with them.*

---

## Українська

Однофайлова цифрова мапа для настільної гри **Star Wars: Rebellion**. Вона відкривається в будь-якому браузері на телефоні, планшеті чи ПК. Не потрібно нічого встановлювати, реєструватися чи бути онлайн, бо зображення мапи вже вбудоване в сам файл.

**Версія 2.2**

### Можливості

- Усі **32 системи** підписані англійською та українською мовами. Друковані назви на скані мапи перекриті великим векторним текстом.
- Біля кожної з **24 населених систем** показано номер черги виробництва, символи ресурсів і належність.
- Належність можна показувати двома способами, які перемикаються в меню:
  - **Зафарбовування планети:** чорна — Імперія, біла — Повстанці, темно-сіра — окупована.
  - **Шестикутні жетони** з емблемами (імперський герб, символ Повстанців, шолом штурмовика). У цьому режимі планети теж зафарбовуються.
- Червоні хрестики, жетони диверсії та затінення ворожих військ.
- **Калькулятор виробництва** для обох сторін.
- Власні значки для жетонів належності та кораблів.
- **Автозбереження:** стан гри залишається в браузері, навіть якщо закрити сторінку посеред партії.
- Працює офлайн і підтримує повноекранний режим.

### Як користуватися

| Дія | Результат |
|---|---|
| **Довге натискання** на планету або її назву | Ставить червоний хрестик. Повторне довге натискання видаляє його. На Корусанті хрестик стоїть завжди. |
| **Тап** по шестикутнику або планеті | Змінює належність: порожньо → окупована → Імперія → Повстанці → порожньо. Корусант завжди імперський. |
| **Тап** по символах ресурсів | Ставить жетон диверсії. Повторний тап знімає його. |
| **Довге натискання** на область системи | Позначає ворожі війська. Уся система затіняється, з'являється значок корабля. Працює лише для систем із належністю, інакше з'являється підказка. |
| Зведення пальців / кнопки **+ −** | Масштаб |
| Перетягування | Переміщення мапи |

Якщо повний екран злетів (наприклад, після блокування екрана чи перемикання застосунків), перший тап повертає його.

### Меню (⋮)

- **Порахувати виробництво** показує, що виробляє кожна сторона в чергах 1–3.
  - *Повстанці:* усі символи повстанських систем, плюс База повстанців, яка враховується завжди.
  - *Імперія:* усі символи імперських систем і лише перший символ окупованих.
  - Системи з диверсією або ворожими військами не враховуються і показані окремо.
- **Свої значки** замінюють жетони належності та значки кораблів власними картинками. Рівний фон прибирається автоматично.
- **Стиль належності:** зафарбовування планет або шестикутники.
- **Як користуватися** відкриває коротку вбудовану інструкцію.
- Повний екран (on/off), скидання масштабу, очищення мапи, перемикання мови, вихід.

На малих екранах меню прокручується.

### Запуск локально

1. Завантажте `index.html`.
2. Відкрийте його в браузері.

**Порада для Android.** Якщо відкрити файл через файловий менеджер, згодом може з'явитися помилка `ERR_FILE_NOT_FOUND`. Так стається тому, що менеджер дає браузеру лише тимчасовий доступ до файлу. Щоб цього уникнути, користуйтеся онлайн-версією або відкривайте файл напряму в Chrome за адресою `file:///sdcard/Download/<назва_файлу>.html`.

**Збереження** зберігаються в `localStorage` браузера і прив'язані до адреси сторінки. Тому онлайн-версія та локальний файл мають окремі збереження.

### Ліцензія та відгуки

Мапа повністю безкоштовна для використання та поширення. Відгуки, зауваження та виправлення щодо назв планет тільки вітаються. Створіть [Issue](../../issues).

*Це неофіційний фанатський інструмент. Star Wars: Rebellion є торговою маркою відповідних правовласників (Fantasy Flight Games, Lucasfilm). Проєкт із ними не пов'язаний.*
