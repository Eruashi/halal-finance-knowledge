# SOURCES REGISTRY — Реестр источников

Централизованный каталог всех внешних источников, на которые ссылаются скиллы. Каждый источник имеет уникальный **ID**, который используется в frontmatter скиллов и в тексте.

---

## Формат записи

```
### [ID]
- **Название:** ...
- **Автор / Орган:** ...
- **Тип:** standard | fatwa | book | article | report | website
- **Год:** YYYY
- **URL:** https://...
- **Язык:** ar / en / ru / kk
- **Краткое описание:** ...
- **Применимость:** где используется (тематически или по юрисдикции)
```

---

## ID-naming convention

- `AAOIFI-SS-XX` — AAOIFI Shariah Standard номер XX.
- `AAOIFI-FAS-XX` — AAOIFI Financial Accounting Standard.
- `IFSB-XX` — IFSB Standard номер XX.
- `IIFA-RES-XXX` — Islamic Fiqh Academy Resolution.
- `DUMK-FATWA-XXX` — фетва ДУМК с внутренним ID (см. `dumk-fatwa-archive.md`).
- `USMANI-INTRO-CHX` — Mufti Taqi Usmani, "An Introduction to Islamic Finance", глава X.
- `USMANI-SUKUK-2008` — известное эссе Усмани о сукук.
- `QARADAWI-FIQH-ZAKAT` — "Фикх аз-закят" Юсуфа аль-Карадави.
- `AIFC-IF-REPORT-2024` — отчёт AIFC по исламским финансам в РК.
- При добавлении новых типов — расширять документацию здесь же.

---

## 1. Международные стандарты

### AAOIFI (Бахрейн)

> Накопительный реестр Shariah Standards AAOIFI. Заполняется по мере включения скиллов, использующих конкретные стандарты.

#### [AAOIFI-SS-08]
- **Название:** Shariah Standard № 8 — Murabaha
- **Орган:** AAOIFI
- **Тип:** standard
- **URL:** https://aaoifi.com/shariaa-standards/?lang=en
- **Язык:** en / ar
- **Краткое описание:** Стандарт по контракту мурабаха, включая мурабаху для заказчика на покупку.
- **Применимость:** banking-contracts/murabaha

#### [AAOIFI-SS-09]
- **Название:** Shariah Standard № 9 — Ijarah and Ijarah Muntahia Bittamleek
- **Орган:** AAOIFI
- **Тип:** standard
- **URL:** https://aaoifi.com/shariaa-standards/?lang=en
- **Язык:** en / ar
- **Краткое описание:** Стандарт по аренде и аренде с правом выкупа.
- **Применимость:** banking-contracts/ijara, personal-finance/islamic-mortgage

#### [AAOIFI-SS-12]
- **Название:** Shariah Standard № 12 — Sharika (Musharaka) and Modern Corporations
- **Орган:** AAOIFI
- **Тип:** standard
- **URL:** https://aaoifi.com/shariaa-standards/?lang=en
- **Язык:** en / ar
- **Краткое описание:** Партнёрство и современные корпоративные структуры.
- **Применимость:** banking-contracts/musharaka, equity-screening

#### [AAOIFI-SS-13]
- **Название:** Shariah Standard № 13 — Mudaraba
- **Орган:** AAOIFI
- **Тип:** standard
- **URL:** https://aaoifi.com/shariaa-standards/?lang=en
- **Язык:** en / ar
- **Краткое описание:** Контракт мудараба.
- **Применимость:** banking-contracts/mudaraba

#### [AAOIFI-SS-17]
- **Название:** Shariah Standard № 17 — Investment Sukuk
- **Орган:** AAOIFI
- **Тип:** standard
- **URL:** https://aaoifi.com/shariaa-standards/?lang=en
- **Язык:** en / ar
- **Краткое описание:** Стандарт по инвестиционным сукук.
- **Применимость:** sukuk/*

#### [AAOIFI-SS-21]
- **Название:** Shariah Standard № 21 — Financial Paper (Shares and Bonds)
- **Орган:** AAOIFI
- **Тип:** standard
- **URL:** https://aaoifi.com/shariaa-standards/?lang=en
- **Язык:** en / ar
- **Краткое описание:** Скрининг акций, методология качественного и количественного отбора.
- **Применимость:** equity-screening/*

#### [AAOIFI-SS-26]
- **Название:** Shariah Standard № 26 — Islamic Insurance (Takaful)
- **Орган:** AAOIFI
- **Тип:** standard
- **URL:** https://aaoifi.com/shariaa-standards/?lang=en
- **Язык:** en / ar
- **Краткое описание:** Исламское страхование.
- **Применимость:** banking-contracts/takaful

> *Полный список AAOIFI Shariah Standards: 60+ документов. Добавляются по мере необходимости в скиллах.*

---

### IFSB (Малайзия)

#### [IFSB-1]
- **Название:** Guiding Principles of Risk Management for Institutions Offering Islamic Financial Services
- **Орган:** IFSB
- **Тип:** standard
- **Год:** 2005
- **URL:** https://www.ifsb.org/published-standards/
- **Язык:** en
- **Краткое описание:** Принципы риск-менеджмента для исламских финансовых институтов.
- **Применимость:** общие риск-вопросы

> *Полный список стандартов IFSB на их сайте. Добавляются по мере необходимости.*

---

### Islamic Fiqh Academy (OIC)

#### [IIFA-RES-XXX]
- *Шаблон. Резолюции IIFA добавляются по мере включения в скиллы.*
- **URL:** http://www.iifa-aifi.org/

---

## 2. Локальные источники — Казахстан

### ДУМК (Духовное управление мусульман Казахстана)

> Конкретные фетвы ДУМК с детальными выписками — в отдельном файле `dumk-fatwa-archive.md`. Здесь только обобщённые ссылки.

#### [DUMK-WEB]
- **Название:** Официальный сайт ДУМК
- **Орган:** Духовное управление мусульман Казахстана
- **Тип:** website
- **URL:** https://www.muftyat.kz/ru/
- **Язык:** ru / kk
- **Краткое описание:** Источник официальных фетв, разъяснений по фикху, ежегодных значений нисаба и фитр-садака.
- **Применимость:** все скиллы с локальной привязкой

#### [DUMK-ZEKET]
- **Название:** Фонд закят ДУМК / онлайн-калькулятор
- **Орган:** ДУМК
- **Тип:** website
- **URL:** https://zeket.online (или раздел на muftyat.kz)
- **Язык:** ru / kk
- **Краткое описание:** Официальная методика расчёта закята, актуальные значения нисаба.
- **Применимость:** zakat/*, kazakhstan/zakat-nisab-current

#### [DUMK-NISAB-METHODOLOGY]
- **Название:** Методика определения размера нисаба ДУМК
- **Орган:** ДУМК
- **Тип:** methodology
- **URL:** https://www.muftyat.kz/ru/qa/oraza/2024-01-16/43634-kak-opredeliaetsia-razmer-nisaba/
- **Язык:** ru
- **Краткое описание:** Разъяснение, как ДУМК ежегодно определяет нисаб (через золото, серебро, по разным видам имущества). Ханафитский подход (закят со скота можно выплатить и в денежном эквиваленте и т.д.).
- **Применимость:** zakat/*

---

### AIFC / МФЦА

#### [AIFC-IF-REPORT-2024]
- **Название:** Исламское финансирование: анализ рынка Казахстана
- **Орган:** AIFC
- **Тип:** report
- **Год:** 2024
- **URL:** https://aifc.kz/wp-content/uploads/2024/05/islamic-finance-kazakhstan-market-analysis-final_rus.pdf
- **Язык:** ru
- **Краткое описание:** Аналитический отчёт по рынку исламских финансов в РК, оценка спроса по сегментам (исламская ипотека, автофинансирование, сукук и т.д.).
- **Применимость:** kazakhstan/*

#### [AIFC-WEB]
- **Название:** Официальный сайт AIFC
- **Орган:** AIFC
- **Тип:** website
- **URL:** https://aifc.kz/
- **Язык:** ru / en
- **Применимость:** kazakhstan/aifc-instruments

---

### ADCB Islamic Bank (бывший Al Hilal)

#### [ADCB-ISLAMIC-WEB]
- **Название:** Официальный сайт ADCB Islamic Bank Kazakhstan
- **Орган:** ADCB Islamic Bank JSC
- **Тип:** website
- **URL:** https://www.adcb.com/ru/kazakhstan/business/
- **Язык:** ru / en / kk
- **Краткое описание:** Официальная информация о продуктах исламского банка в Казахстане. Ребрендинг с Al Hilal произведён 21.10.2024.
- **Применимость:** kazakhstan/adcb-islamic-bank

---

### Сервисы скрининга акций (русскоязычные)

#### [SAHIH-INVEST]
- **Название:** Sahih Invest
- **Орган:** Sahih Invest
- **Тип:** website / service
- **URL:** https://sahihinvest.com/
- **Язык:** ru
- **Краткое описание:** Скрининг акций по нормам ислама, методология AAOIFI, шариатский совет с участием сертифицированных AAOIFI-аудиторов.
- **Применимость:** equity-screening, kazakhstan/halal-screening-services

#### [INVESTLINK]
- **Название:** Investlink (раздел "Халяль инвестиции")
- **Орган:** Investlink
- **Тип:** website / service
- **URL:** https://investlink.kz/halal-investing/
- **Язык:** ru
- **Краткое описание:** Скрининг акций и ETF на соответствие нормам AAOIFI, интегрированы данные Zoya.Finance.
- **Применимость:** kazakhstan/halal-screening-services

---

## 3. Современные академические источники

### Таки Усмани

#### [USMANI-INTRO]
- **Название:** An Introduction to Islamic Finance
- **Автор:** Mufti Muhammad Taqi Usmani
- **Тип:** book
- **Год:** 2002 (первое издание)
- **Издательство:** Idaratul Ma'arif, Karachi
- **Язык:** en (есть русские переводы)
- **Краткое описание:** Базовый академический источник по исламским финансам с ханафитской перспективы.
- **Применимость:** все основные скиллы

#### [USMANI-SUKUK-2007]
- **Название:** Sukuk and their Contemporary Applications
- **Автор:** Mufti Muhammad Taqi Usmani
- **Тип:** article
- **Год:** 2007
- **Язык:** en
- **Краткое описание:** Известное эссе с критикой соответствия большинства сукук шариату.
- **Применимость:** sukuk/sukuk-controversy-2008

---

### Юсуф аль-Карадави

#### [QARADAWI-FIQH-ZAKAT]
- **Название:** Фикх аз-закят (فقه الزكاة)
- **Автор:** Юсуф аль-Карадави
- **Тип:** book
- **Год:** 1969 (первое издание)
- **Язык:** ar (есть переводы)
- **Краткое описание:** Фундаментальный труд по фикху закята, включая закят на современные виды имущества.
- **Применимость:** zakat/*

---

### Низамуддин Шами

> *Заполняется по мере включения цитат в скиллы.*

---

## 4. Образовательные и аналитические ресурсы

#### [IIBI-WEB]
- **Название:** Institute of Islamic Banking and Insurance
- **Тип:** website / educational
- **URL:** https://www.islamic-banking.com/
- **Язык:** en
- **Применимость:** общие ссылки

#### [IFN]
- **Название:** Islamic Finance News
- **Тип:** website / news
- **URL:** https://www.islamicfinancenews.com/
- **Язык:** en
- **Применимость:** новости отрасли

---

## Как добавлять источники

1. Открой этот файл.
2. Найди подходящий раздел (или создай новый).
3. Сгенерируй уникальный ID по конвенции.
4. Заполни все поля шаблона.
5. Используй ID в frontmatter скиллов в поле `key-sources`.

Если источник используется только в одном скилле и не претендует на цитирование где-то ещё — всё равно добавь его сюда. Это страхует от дублирования и потери ссылок.

---

*Реестр обновляется по мере наполнения репозитория скиллами.*
