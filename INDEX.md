# INDEX — Роутер знаний

Карта навигации: при каком типе вопроса какой скилл нужно подгрузить.

> **Для Claude:** этот файл синхронизируется с Project Instructions проекта. Источник истины — здесь. При обновлении репозитория нужно обновлять зеркальную копию в Project Instructions.

---

## Принцип роутинга

1. По типу вопроса определяется **основной скилл**.
2. К нему почти всегда добавляются скиллы из `foundations/` (если затрагиваются базовые принципы — риба, гарар) и `kazakhstan/` (если речь о практическом применении в РК).
3. Если вопрос касается личных финансов пользователя — читается соответствующий файл из Project Knowledge.

---

## 1. Foundations (Фундамент фикха муамалят)

| Скилл | Триггеры | Статус |
|-------|----------|--------|
| `skills/foundations/riba.md` | "проценты", "ростовщичество", "риба", "займ под процент", "что не так с обычным кредитом" | планируется |
| `skills/foundations/gharar.md` | "гарар", "неопределённость", "спекуляция", "когда сделка недействительна" | планируется |
| `skills/foundations/maysir.md` | "майсир", "кимар", "азарт", "ставки", "лотерея" | планируется |
| `skills/foundations/halal-haram-categories.md` | "халяль", "харам", "макрух", "мубах", "категории дозволенного" | планируется |
| `skills/foundations/kawaid-fiqhiyya.md` | "общие принципы фикха муамалят", "кавáид", "правила выведения решений" | планируется |
| `skills/foundations/talfiq-rukhas.md` | "тальфик", "выбор удобного мнения", "можно ли смешивать мазхабы" | планируется |

---

## 2. Banking Contracts (Исламские контракты)

| Скилл | Триггеры | Статус |
|-------|----------|--------|
| `skills/banking-contracts/murabaha.md` | "мурабаха", "продажа с наценкой", "товарное финансирование" | планируется |
| `skills/banking-contracts/musharaka.md` | "мушарака", "партнёрство", "совместный бизнес", "убывающая мушарака" | планируется |
| `skills/banking-contracts/mudaraba.md` | "мудараба", "доверительное управление", "рабб аль-маль", "мудариб" | планируется |
| `skills/banking-contracts/ijara.md` | "иджара", "исламская аренда", "лизинг", "иджара мунтахийя биттамлик" | планируется |
| `skills/banking-contracts/istisna.md` | "истисна", "контракт на производство", "финансирование строительства" | планируется |
| `skills/banking-contracts/salam.md` | "салам", "форвардная продажа", "предоплата за будущий товар" | планируется |
| `skills/banking-contracts/qard-hasan.md` | "кард аль-хасан", "беспроцентный заём" | планируется |
| `skills/banking-contracts/takaful.md` | "такафул", "исламское страхование", "вакала", "взаимное страхование" | планируется |
| `skills/banking-contracts/wakala.md` | "вакала", "агентский договор", "доверительное представительство" | планируется |

---

## 3. Sukuk (Исламские облигации)

| Скилл | Триггеры | Статус |
|-------|----------|--------|
| `skills/sukuk/sukuk-fundamentals.md` | "сукук", "исламские облигации", "чем отличаются от облигаций" | планируется |
| `skills/sukuk/sukuk-structures.md` | "иджара-сукук", "мушарака-сукук", "мурабаха-сукук", "структуры сукук" | планируется |
| `skills/sukuk/sukuk-controversy-2008.md` | "критика сукук", "Усмани 2007 2008", "asset-backed vs asset-based" | планируется |

---

## 4. Equity Screening (Скрининг акций и фондов)

| Скилл | Триггеры | Статус |
|-------|----------|--------|
| `skills/equity-screening/qualitative-screening.md` | "отраслевой скрининг", "разрешённые сектора", "акции каких компаний можно" | планируется |
| `skills/equity-screening/quantitative-screening.md` | "финансовые пороги", "33% долг", "5% процентных доходов", "AAOIFI скрининг" | планируется |
| `skills/equity-screening/purification-tahleel.md` | "очищение дивидендов", "тахлиль", "очистительный расход" | планируется |
| `skills/equity-screening/islamic-indices.md` | "Dow Jones Islamic", "S&P Shariah", "MSCI Islamic", "индексы" | планируется |
| `skills/equity-screening/halal-funds-etfs.md` | "Wahed Invest", "Saturna", "SP Funds", "халяльные ETF" | планируется |

---

## 5. Personal Finance (Общая теория)

| Скилл | Триггеры | Статус |
|-------|----------|--------|
| `skills/personal-finance/islamic-mortgage.md` | "исламская ипотека", "халяльная ипотека", "три модели ипотеки" | планируется |
| `skills/personal-finance/auto-financing-halal.md` | "халяльное автофинансирование", "купить машину по шариату" | планируется |
| `skills/personal-finance/budgeting-principles.md` | "бюджет по исламу", "израф", "бухль", "управление деньгами" | планируется |
| `skills/personal-finance/debt-management.md` | "выплата долгов", "приоритет долгов", "долги в исламе" | планируется |

---

## 6. Zakat (Закят)

| Скилл | Триггеры | Статус |
|-------|----------|--------|
| `skills/zakat/zakat-fundamentals.md` | "закят", "что такое закят", "обязательность закята" | планируется |
| `skills/zakat/zakat-on-cash-gold.md` | "закят с денег", "закят с золота", "нисаб золота" | планируется |
| `skills/zakat/zakat-on-stocks.md` | "закят с акций", "закят с инвестиций", "рыночная стоимость или дивиденды" | планируется |
| `skills/zakat/zakat-on-crypto.md` | "закят с криптовалюты", "закят с биткоина" | планируется |
| `skills/zakat/zakat-on-business.md` | "закят с бизнеса", "торговый товар", "закят предпринимателя" | планируется |
| `skills/zakat/fitr-sadaqa.md` | "фитр-садака", "садакат-уль-фитр", "пожертвование за разговение" | планируется |

---

## 7. Crypto & Digital Assets

| Скилл | Триггеры | Статус |
|-------|----------|--------|
| `skills/crypto-digital/crypto-shariah-views.md` | "халяль ли биткоин", "крипта по шариату", "позиции учёных по криптовалютам" | планируется |
| `skills/crypto-digital/staking-lending-defi.md` | "стейкинг", "лендинг крипты", "DeFi по шариату", "yield farming" | планируется |
| `skills/crypto-digital/nft-shariah.md` | "NFT", "халяль ли NFT" | планируется |

---

## 8. Ethical Investing

| Скилл | Триггеры | Статус |
|-------|----------|--------|
| `skills/ethical-investing/esg-vs-islamic.md` | "ESG", "ESG vs ислам", "халяль ли ESG-фонды" | планируется |
| `skills/ethical-investing/socially-responsible-investing.md` | "SRI", "социально ответственные инвестиции" | планируется |

---

## 9. Waqf (Вакф)

| Скилл | Триггеры | Статус |
|-------|----------|--------|
| `skills/waqf/waqf-fundamentals.md` | "вакф", "что такое вакф", "благотворительный фонд по шариату" | планируется |
| `skills/waqf/cash-waqf.md` | "кэш-вакф", "денежный вакф" | планируется |
| `skills/waqf/corporate-waqf.md` | "корпоративный вакф" | планируется |

---

## 10. 🔵 Personal (Операционные скиллы)

> Эти скиллы Claude использует, когда пользователь обсуждает **свои** финансы. Личные данные берутся из Project Knowledge, методология — отсюда.

| Скилл | Триггеры | Статус |
|-------|----------|--------|
| `skills/personal/budget-framework.md` | "разбери мой бюджет", "помоги распределить доход", "сколько на что тратить" | планируется |
| `skills/personal/portfolio-review-checklist.md` | "проверь мой портфель", "халяль ли мои акции", "разбери мои инвестиции" | планируется |
| `skills/personal/zakat-calculation-workflow.md` | "посчитай мой закят", "помоги рассчитать закят", "когда платить закят" | планируется |
| `skills/personal/income-growth-halal.md` | "как увеличить доход", "халяльные способы заработка", "доп. источники дохода" | планируется |
| `skills/personal/financial-goals-islamic.md` | "финансовые цели", "копить на хадж", "приоритеты целей" | планируется |
| `skills/personal/emergency-fund.md` | "финансовая подушка", "резервный фонд", "сколько откладывать" | планируется |

---

## 11. 🔵 Kazakhstan (Локальный слой)

| Скилл | Триггеры | Статус |
|-------|----------|--------|
| `skills/kazakhstan/adcb-islamic-bank.md` | "ADCB Islamic", "Al Hilal", "исламский банк в Казахстане", "халяльный банк РК" | планируется |
| `skills/kazakhstan/aifc-instruments.md` | "AIFC", "МФЦА", "Astana International Financial Centre", "финансовые льготы" | планируется |
| `skills/kazakhstan/dumk-fatwas.md` | "ДУМК", "фетва ДУМК", "Духовное управление мусульман Казахстана" | планируется |
| `skills/kazakhstan/zakat-nisab-current.md` | "нисаб 2026", "актуальный нисаб", "сколько нисаб в тенге", "фитр-садака 2026" | планируется |
| `skills/kazakhstan/halal-screening-services.md` | "Sahih Invest", "Investlink", "как проверить акцию на халяль в РК" | планируется |
| `skills/kazakhstan/tax-context.md` | "налоги на инвестиции в РК", "ИПН", "льготы AIFC", "налогообложение" | планируется |
| `skills/kazakhstan/kase-halal-instruments.md` | "халяльные инструменты на KASE", "халяль на казахстанской бирже" | планируется |
| `skills/kazakhstan/halal-mortgage-products.md` | "халяльная ипотека в Казахстане", "иджара ипотека РК" | планируется |

---

## Типичные сценарии и какие скиллы подгружать

| Запрос пользователя | Скиллы для подгрузки |
|---------------------|----------------------|
| «Помоги посчитать мой закят» | `personal/zakat-calculation-workflow.md` + `kazakhstan/zakat-nisab-current.md` + `zakat/zakat-on-cash-gold.md` + `zakat/zakat-on-stocks.md` + Project Knowledge (`my-portfolio.md`) |
| «Стоит ли брать ипотеку в ADCB Islamic?» | `kazakhstan/adcb-islamic-bank.md` + `personal-finance/islamic-mortgage.md` + `banking-contracts/ijara.md` + `banking-contracts/murabaha.md` |
| «Проверь мой портфель на халяль» | `personal/portfolio-review-checklist.md` + `equity-screening/qualitative-screening.md` + `equity-screening/quantitative-screening.md` + `equity-screening/purification-tahleel.md` + Project Knowledge |
| «Халяль ли биткоин?» | `crypto-digital/crypto-shariah-views.md` + `foundations/gharar.md` |
| «Как халяльно увеличить доход?» | `personal/income-growth-halal.md` + соответствующие контракты (мушарака, мудараба) |
| «Разбери мой бюджет» | `personal/budget-framework.md` + `personal-finance/budgeting-principles.md` + Project Knowledge |
| «Какие у меня варианты для накоплений?» | `personal/financial-goals-islamic.md` + `kazakhstan/adcb-islamic-bank.md` + `kazakhstan/halal-screening-services.md` |

---

## Когда обновлять INDEX

INDEX обновляется при:

- Добавлении нового скилла → новая строка в соответствующей секции.
- Изменении статуса скилла (планируется → черновик → стабильный) → правка колонки «Статус».
- Изменении триггеров → правка соответствующей колонки.

После обновления INDEX **обязательно** синхронизировать Project Instructions в Claude Project (см. `docs/project-instructions.md`).
