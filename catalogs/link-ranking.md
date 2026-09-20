# Каталог: ссылочное ранжирование

Собран 20.09.2026. Источник: `google_link_ranking_2015_2026.csv` — сохранённая выгрузка
`search_patents` (assignee=google, 2015–2026, 60 строк). Расход BigQuery: **0 ГБ**.

> ⚠️ **Каталог неполный, это рабочая версия.** Выгрузка сделана по одному термину
> в заголовке — `ranking`. Патенты по теме, в названии которых нет слова «ranking»
> (а таких много — «link», «anchor», «hyperlink», «web graph», «citation»,
> «PageRank»), сюда не попали в принципе. Полный прогон по шести синонимам не
> выполнен: BigQuery отдаёт 403 на уровне проекта, см. «Что не сделано» внизу.

## Ядро и ближний круг

| № | Номер | Дата | Название | Ссылка |
|---|---|---|---|---|
| ⭐ | US-8959093-B1 | 17.02.2015 | Ranking search results based on anchors | https://patents.google.com/patent/US8959093B1/en |
| ⭐ | US-9165040-B1 | 20.10.2015 | Producing a ranking for pages using distances in a web-link graph | https://patents.google.com/patent/US9165040B1/en |
| ⭐ | US-9953049-B1 | 24.04.2018 | Producing a ranking for pages using distances in a web-link graph | https://patents.google.com/patent/US9953049B1/en |
| ⭐ | US-9977816-B1 | 22.05.2018 | Link-based ranking of objects that do not include explicitly defined links | https://patents.google.com/patent/US9977816B1/en |
| ⭐ | US-10152520-B1 | 11.12.2018 | Ranking documents based on user behavior and/or feature data | https://patents.google.com/patent/US10152520B1/en |
| ⭐ | US-12511325-B2 | 30.12.2025 | Reranking documents based on graph representations of the documents | https://patents.google.com/patent/US12511325B2/en |
| ⭐ | US-2025103662-A1 | 27.03.2025 | Unifying transformers with link based ranking | https://patents.google.com/patent/US20250103662A1/en |
| | US-9305099-B1 | 05.04.2016 | Ranking documents based on user behavior and/or feature data | https://patents.google.com/patent/US9305099B1/en |
| | US-10152557-B2 | 11.12.2018 | Efficient similarity ranking for bipartite graphs | https://patents.google.com/patent/US10152557B2/en |
| | US-2024250958-A1 | 25.07.2024 | Hybrid message passing neural network and personalized page ranking graph convolution network model | https://patents.google.com/patent/US20240250958A1/en |

**Родство внутри таблицы:**

- `US-9165040-B1` → `US-9953049-B1` — продолжение той же семьи, одно название.
- `US-9305099-B1` → `US-10152520-B1` — продолжение; вторая публикация известна как Reasonable Surfer.
- `US-12511325-B2` — выданный патент; в семье также заявки `US-2026079992-A1`,
  `US-2025335486-A1`, `WO-2025226655-A1` (то же название).
- `US-2024250958-A1` — пока только заявка US; в семье `EP-4226284-A1`, `WO-2023129124-A1`,
  `CA-3185202-A1`, `CN-116671065-A`.

## Под вопросом — название общее, тему покажет только формула

| Номер | Дата | Название | Ссылка |
|---|---|---|---|
| US-10970293-B2 | 06.04.2021 | Ranking search result documents | https://patents.google.com/patent/US10970293B2/en |
| US-10394832-B2 | 27.08.2019 | Ranking search results documents | https://patents.google.com/patent/US10394832B2/en |
| US-10496652-B1 | 03.12.2019 | Methods and apparatus for ranking documents | https://patents.google.com/patent/US10496652B1/en |
| US-9477714-B1 | 25.10.2016 | Methods and apparatus for ranking documents | https://patents.google.com/patent/US9477714B1/en |
| US-10055461-B1 | 21.08.2018 | Ranking documents based on large data sets | https://patents.google.com/patent/US10055461B1/en |
| US-9116976-B1 | 25.08.2015 | Ranking documents based on large data sets | https://patents.google.com/patent/US9116976B1/en |
| US-10268732-B2 | 23.04.2019 | Ranking native applications and native application deep links | https://patents.google.com/patent/US10268732B2/en |

`deep links` в последней строке — ссылки внутрь мобильных приложений, а не веб-ссылки;
оставлен только потому, что механизм отбора может оказаться общим.

## Отсеяно

**Не по теме — геолокация:** `US-12435984-B2`, `US-11941009-B1`, `US-10360228-B1`,
`US-9690805-B1`, `US-9684727-B1`, `US-2024037109-A1`, `US-2021270621-A1`,
`EP-4340403-A1`, `EP-3782381-A1/B1`, `WO-2020131136-A1` — ранжирование мест
для геоприложений.

**Не по теме — прочее ранжирование:**

- `US-10083226-B1`, `US-9542441-B1`, `US-9183257-B1` — разрешение анафоры, NLP.
- `US-9679018-B1` — частота сущностей в документе, текстовая оптимизация.
- `US-9672253-B1`, `US-9201929-B1` — вес страницы в байтах при загрузке.
- `US-9436742-B1` — персонализация по атрибутам пользователя.
- `US-9244891-B2` — выделение текста пользователями, поведенческое.
- `US-9002867-B1` — изменения документа во времени.
- `US-8965883-B2`, `EP-2494464-A4`, `TW-I501096-B` — пользовательский контент.
- `US-9098551-B1` — популярность сущностей; проверено по формуле, ссылок в ней
  нет, карточка лежит в `patents/other/`.

**Дубли семей (оставлена US-версия):** `WO-2024226614-A2/A3`, `WO-2018080673-A1`,
`CN-107977398-A`, `CN-115803732-A`, `GB-2556676-A`, `GB-201715602-D0`,
`US-2018113866-A1`, `US-2019377741-A1`, `US-2016378761-A1`, `WO-2017003742-A1`,
`US-2015220530-A1`, `EP-4226284-A1`, `WO-2023129124-A1`, `CA-3185202-A1`,
`CN-116671065-A`, `US-2026079992-A1`, `US-2025335486-A1`, `WO-2025226655-A1`.

## Уже разобрано в карточки

- [[US-8959093]] — `patents/link-ranking/`
- [[US-9165040]] — `patents/link-ranking/`
- [[US-9953049]] — `patents/link-ranking/`
- [[US-10152520]] — `patents/link-ranking/`
- [[US-9977816]] — `patents/other/`
- [[US-9098551]] — `patents/other/`

## Что не сделано

Прогон по синонимам `link`, `anchor`, `hyperlink`, `web graph`, `citation`,
`PageRank` (6 запросов, ~162 ГБ). BigQuery отклоняет любой вызов с HTTP 403 на
уровне проекта `project-e2f6fedd-652c-4730-9bf`. Проверено: API включён, биллинг
активен, токен валиден, право `bigquery.jobs.create` выдано — 403 приходит
HTML-страницей от фронтенда Google на все эндпоинты BigQuery, тогда как тот же
токен получает 200 от Cloud Resource Manager. Похоже на ограничение уровня
организации (VPC Service Controls или политика доступа), а не на проблему скилла.
