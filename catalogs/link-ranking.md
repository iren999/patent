# Каталог: ссылочное ранжирование

Собран 20.09.2026. Источник: `search_patents` (Google Patents on BigQuery), assignee=google.
Дополнен 20.09.2026 запросами `authority`, `trust`, `nofollow`.

Запросы: `link`, `anchor`, `hyperlink`, `web graph`, `citation`, `PageRank`, `authority`,
`trust`, `nofollow`, `graph`, `spam`, `reputation`, `popularity` · Диапазон: 2000–2026 ·
Расход: ~378 ГБ.

> **Запрос `graph` обрезан лимитом** — вернул ровно 1000 строк и покрыл только
> 2022–2026. Период 2000–2022 по нему решено не добирать: проверка по 2524 уже
> собранным записям показала, что до 2022 года слово «graph» встречается всего
> в 6 US-патентах, и все шесть уже учтены (два в ядре — `web-link graph`, четыре
> отсеяны как `Trusted maps`). Графовые патенты по ранжированию почти всегда
> содержат «link» в названии, а этот термин отработан полностью за 2000–2026.
> Добор стоил бы 27 ГБ при близкой к нулю ожидаемой выгоде.

Предыдущая версия каталога собиралась из сохранённого CSV по одному термину `ranking`;
эта версия заменяет её полным прогоном и снимает прежнюю пометку о неполноте.

## Ядро темы

| № | Номер | Дата | Название | Ссылка |
|---|---|---|---|---|
| ⭐ | US-12511325-B2 | 30.12.2025 | Reranking documents based on graph representations of the documents | https://patents.google.com/patent/US12511325B2/en |
| ⭐ | US-2025103662-A1 | 27.03.2025 | Unifying transformers with link based ranking | https://patents.google.com/patent/US2025103662A1/en |
| ⭐ | US-10152520-B1 | 11.12.2018 | Ranking documents based on user behavior and/or feature data | https://patents.google.com/patent/US10152520B1/en |
| ⭐ | US-10268641-B1 | 23.04.2019 | Search result ranking based on trust | https://patents.google.com/patent/US10268641B1/en |
| ⭐ | US-9977816-B1 | 22.05.2018 | Link-based ranking of objects that do not include explicitly defined links | https://patents.google.com/patent/US9977816B1/en |
| ⭐ | US-9953049-B1 | 24.04.2018 | Producing a ranking for pages using distances in a web-link graph | https://patents.google.com/patent/US9953049B1/en |
| ⭐ | US-9165040-B1 | 20.10.2015 | Producing a ranking for pages using distances in a web-link graph | https://patents.google.com/patent/US9165040B1/en |
| ⭐ | US-8959093-B1 | 17.02.2015 | Ranking search results based on anchors | https://patents.google.com/patent/US8959093B1/en |
| ⭐ | US-8719276-B1 | 06.05.2014 | Ranking nodes in a linked database based on node independence | https://patents.google.com/patent/US8719276B1/en |
| ⭐ | US-8407231-B2 | 26.03.2013 | Document scoring based on link-based criteria | https://patents.google.com/patent/US8407231B2/en |
| ⭐ | US-8250114-B2 | 21.08.2012 | Method for detecting link spam in hyperlinked databases | https://patents.google.com/patent/US8250114B2/en |
| ⭐ | US-8127220-B1 | 28.02.2012 | Scoring links in a document | https://patents.google.com/patent/US8127220B1/en |
| ⭐ | US-7260573-B1 | 21.08.2007 | Personalizing anchor text scores in a search engine | https://patents.google.com/patent/US7260573B1/en |

## Ближний круг

| № | Номер | Дата | Название | Ссылка |
|---|---|---|---|---|
|  | US-2024250958-A1 | 25.07.2024 | Hybrid message passing neural network and personalized page ranking graph convolution network model | https://patents.google.com/patent/US2024250958A1/en |
|  | US-2023214425-A1 | 06.07.2023 | Node Embedding via Hash-Based Projection of Transformed Personalized PageRank | https://patents.google.com/patent/US2023214425A1/en |
|  | US-10152557-B2 | 11.12.2018 | Efficient similarity ranking for bipartite graphs | https://patents.google.com/patent/US10152557B2/en |
|  | US-9400849-B1 | 26.07.2016 | Scalable system for determining short paths within web link network | https://patents.google.com/patent/US9400849B1/en |
|  | US-9298777-B2 | 29.03.2016 | Personalization of web search results using term, category, and link-based user profiles | https://patents.google.com/patent/US9298777B2/en |
|  | US-9282092-B1 | 08.03.2016 | Systems and methods for determining trust when interacting with online resources | https://patents.google.com/patent/US9282092B1/en |
|  | US-9208229-B2 | 08.12.2015 | Anchor text summarization for corroboration | https://patents.google.com/patent/US9208229B2/en |
|  | US-9154491-B1 | 06.10.2015 | Trust modeling | https://patents.google.com/patent/US9154491B1/en |
|  | US-9098582-B1 | 04.08.2015 | Identifying relevant document languages through link context | https://patents.google.com/patent/US9098582B1/en |
|  | US-8892596-B1 | 18.11.2014 | Identifying related documents based on links in documents | https://patents.google.com/patent/US8892596B1/en |
|  | US-8825645-B1 | 02.09.2014 | Determining quality of linked documents | https://patents.google.com/patent/US8825645B1/en |
|  | US-8645396-B2 | 04.02.2014 | Reputation scoring of an author | https://patents.google.com/patent/US8645396B2/en |
|  | US-8615508-B2 | 24.12.2013 | Artificial anchor for a document | https://patents.google.com/patent/US8615508B2/en |
|  | US-8612411-B1 | 17.12.2013 | Clustering documents using citation patterns | https://patents.google.com/patent/US8612411B1/en |
|  | US-8595225-B1 | 26.11.2013 | Systems and methods for correlating document topicality and popularity | https://patents.google.com/patent/US8595225B1/en |
|  | US-8522128-B1 | 27.08.2013 | Systems and methods for modifying the order of links presented in a document | https://patents.google.com/patent/US8522128B1/en |
|  | US-8516357-B1 | 20.08.2013 | Link based clustering of hyperlinked documents | https://patents.google.com/patent/US8516357B1/en |
|  | US-8495483-B1 | 23.07.2013 | Using text surrounding hypertext links when indexing and generating page summaries | https://patents.google.com/patent/US8495483B1/en |
|  | US-8458196-B1 | 04.06.2013 | System and method for determining topic authority | https://patents.google.com/patent/US8458196B1/en |
|  | US-8452746-B2 | 28.05.2013 | Detecting spam search results for context processed search queries | https://patents.google.com/patent/US8452746B2/en |
|  | US-8150842-B2 | 03.04.2012 | Reputation of an author of online content | https://patents.google.com/patent/US8150842B2/en |
|  | US-8078629-B2 | 13.12.2011 | Detecting spam documents in a phrase based information retrieval system | https://patents.google.com/patent/US8078629B2/en |
|  | US-7590628-B2 | 15.09.2009 | Determining document subject by using title and anchor text of related documents | https://patents.google.com/patent/US7590628B2/en |
|  | US-7308643-B1 | 11.12.2007 | Anchor tag indexing in a web crawler system | https://patents.google.com/patent/US7308643B1/en |
|  | US-2005149851-A1 | 07.07.2005 | Generating hyperlinks and anchor text in HTML and non-HTML documents | https://patents.google.com/patent/US2005149851A1/en |
|  | US-6754873-B1 | 22.06.2004 | Techniques for finding related hyperlinked documents using link-based analysis | https://patents.google.com/patent/US6754873B1/en |

## Под вопросом — тему покажет только формула

| № | Номер | Дата | Название | Ссылка |
|---|---|---|---|---|
|  | US-12236322-B2 | 25.02.2025 | Training and/or utilizing a model for predicting measures reflecting both quality and popularity of content | https://patents.google.com/patent/US12236322B2/en |
|  | US-10970293-B2 | 06.04.2021 | Ranking search result documents | https://patents.google.com/patent/US10970293B2/en |
|  | US-10496652-B1 | 03.12.2019 | Methods and apparatus for ranking documents | https://patents.google.com/patent/US10496652B1/en |
|  | US-10482105-B1 | 19.11.2019 | External verification of content popularity | https://patents.google.com/patent/US10482105B1/en |
|  | US-10394832-B2 | 27.08.2019 | Ranking search results documents | https://patents.google.com/patent/US10394832B2/en |
|  | US-10268732-B2 | 23.04.2019 | Ranking native applications and native application deep links | https://patents.google.com/patent/US10268732B2/en |
|  | US-10055461-B1 | 21.08.2018 | Ranking documents based on large data sets | https://patents.google.com/patent/US10055461B1/en |
|  | US-9477714-B1 | 25.10.2016 | Methods and apparatus for ranking documents | https://patents.google.com/patent/US9477714B1/en |
|  | US-9448994-B1 | 20.09.2016 | Grammar extraction using anchor text | https://patents.google.com/patent/US9448994B1/en |
|  | US-9305099-B1 | 05.04.2016 | Ranking documents based on user behavior and/or feature data | https://patents.google.com/patent/US9305099B1/en |
|  | US-9195987-B2 | 24.11.2015 | Systems and methods of correlating business information to determine spam, closed businesses, and ranking signals | https://patents.google.com/patent/US9195987B2/en |
|  | US-9116976-B1 | 25.08.2015 | Ranking documents based on large data sets | https://patents.google.com/patent/US9116976B1/en |
|  | US-9083696-B1 | 14.07.2015 | Trusted peer-based information verification system | https://patents.google.com/patent/US9083696B1/en |
|  | US-8898800-B1 | 25.11.2014 | Mechanism for establishing the trust tree | https://patents.google.com/patent/US8898800B1/en |
|  | US-8812478-B1 | 19.08.2014 | Distributed crawling of hyperlinked documents | https://patents.google.com/patent/US8812478B1/en |
|  | US-8694374-B1 | 08.04.2014 | Detecting click spam | https://patents.google.com/patent/US8694374B1/en |
|  | US-2013282699-A1 | 24.10.2013 | Using Authority Website to Measure Accuracy of Business Information | https://patents.google.com/patent/US2013282699A1/en |
|  | US-7827052-B2 | 02.11.2010 | Systems and methods for reputation management | https://patents.google.com/patent/US7827052B2/en |
|  | US-7743045-B2 | 22.06.2010 | Detecting spam related and biased contexts for programmable search engines | https://patents.google.com/patent/US7743045B2/en |

## Родство семей

Оставлена US-версия; продолжения и повторные выдачи отмечены отдельно.

- `US-9165040-B1` → `US-9953049-B1` — продолжение, название одно.
- `US-9305099-B1` → `US-10152520-B1` — продолжение; вторая известна как Reasonable Surfer.
- `US-8732187-B1` (20.05.2014) → `US-9977816-B1` — продолжение.
- **Document scoring based on link-based criteria:** `US-2007094255-A1` → `US-2011022605-A1` → `US-8407231-B2`.
- **Anchor tag indexing in a web crawler system:** `US-7308643-B1` → `US-8484548-B1` (09.07.2013) → `US-9305091-B2` (05.04.2016) → `US-2016321252-A1` → `US-10210256-B2` (19.02.2019). Изобретатели — Dean, Ghemawat, Acharya.
- **Artificial anchor for a document:** `US-2009287698-A1` → `US-8595270-B2` (26.11.2013) → `US-8615508-B2`. Изобретатель — Krishna Bharat.
- **Method for detecting link spam:** `US-7509344-B1` → `US-7953763-B2` → `US-8250114-B2`.
- **Determining quality of linked documents:** `US-7783639-B1` → `US-8176056-B1` → `US-8825645-B1`.
- **Techniques for finding related hyperlinked documents:** `US-6754873-B1` → `US-7634716-B1`.
- **Link based clustering:** `US-7213198-B1` → `US-8516357-B1`.
- **Scalable system for short paths:** `US-8825646-B1` → `US-9400849-B1`.
- **Search result ranking based on trust:** `US-7603350-B1` (13.10.2009) → `US-8352467-B1`
  (08.01.2013) → `US-8818995-B1` (26.08.2014) → `US-10268641-B1`. Четыре публикации одной семьи.
- **Detecting spam documents in a phrase based IR system:** `US-7603345-B2` (13.10.2009)
  → `US-8078629-B2`. Изобретатель — Anna Lynn Patterson.
- **Systems and methods for detecting click spam:** `US-7933984-B1` (26.04.2011) →
  `US-8423640-B1` (16.04.2013); отдельно `US-8694374-B1` «Detecting click spam».
- **Репутация автора:** `US-8150842-B2` (Kamvar, Brougher) и `US-8645396-B2`
  (Bharat, Lawyer) — две линии одной идеи, к Agent Rank близки, но семьи разные.
- **External verification of content popularity:** `US-9465871-B1` (11.10.2016) →
  `US-10482105-B1`.
- **Модель качества и популярности:** `US-11551150-B2` (10.01.2023) → `US-12236322-B2`.
- **Reranking by graph representations:** `US-12511325-B2` — выданный патент; заявки `US-2026079992-A1`, `US-2025335486-A1`, `WO-2025226655-A1`.

## Отсеяно

**Телеком-шум по слову «link»** — 64 позиции из выдачи: uplink/downlink/sidelink,
link budget, link adaptation, radio link, backhaul, handover, оптические линки
(`Optical Link Diagnostic System`, `Reduce Link Repair Rate in Parallel Optical Links`),
peer-to-peer links, ultra-wideband links. К гиперссылкам отношения не имеют.

**Артефакт подстроки в запросе `citation`** — поиск сцепился со словом
ex**citation**: `Individual qubit excitation control`, `Antenna excitation through
laptop hinge`, `Modified Vivaldi antenna with dipole excitation mode`,
`Display module excitation for wireless communications`. Квантовые кубиты и антенны.

**Не тот «anchor»** — якоря в видео и AR, а не анкорный текст: `Video Anchors`,
`Video Timed Anchors`, `Anchors for live streams`, `Leveraging cloud anchors in
authentication`, `Anchoring virtual objects to physical locations`, `Establishment
anchoring with geolocated imagery`, `Multi-anchor bluetooth channel sounding`,
`Battery-Cell-to-Battery-Pouch Anchoring System`, `Anchor frame` (кодирование видео).

**Не тот «link» — интерфейс и приложения:** deep links в мобильные приложения,
sitelinks в выдаче и рекламе, `Invitation link for launching multi-user applications`,
`Automatic link based message verification`, `Click tracking using link styles`,
`Machine learning classification of an application link as broken or working`,
`Systems and methods for processing inoperative document links`, `Tracking links in
web browsers`, `Compressing hyperlinks in a hyperlink-based document`.

**Анкорный текст, но не ранжирование:** `Systems and methods for using anchor text as
parallel corpora for cross-language information retrieval` (`US-7146358-B1` →
`US-7814103-B1` → `US-7996402-B1` → `US-8190608-B1` → `US-8631010-B1`) — машинный
перевод; `Learning synonymous object names from anchor texts` (`US-8738643-B1`) —
текстовая оптимизация.

**Прочее ранжирование не по ссылкам:** геолокация (`Ranking of geographic
information`, `Discovery and ranking of locations`), анафора (`Using web ranking to
resolve anaphora`), `Document ranking based on entity frequency`, `Ranking a search
result document based on data usage`, `Ranking search result documents based on user
attributes`, `Adjusting search result rankings based on multiple user highlighting`,
`Modifying ranking data based on document changes`, `Ranking user generated web content`.

**Шум по запросу `trust`** — 227 позиций из 338: доверенные среды исполнения (TEE),
`Validating an untrusted native code module`, `Securing a wireless mesh network via a
chain of trust`, `Local trusted services manager for a contactless smart card`,
сертификаты, ключи, биометрия, платежи. Отдельно: `Trusted maps: updating map locations
using trust-based social graphs` — социальный граф карт, не веб-ссылки;
`Trust-based video content evaluation` и `Evaluating Merchant Trustworthiness` — оценка
контента и продавцов; `Trust agents` (семья из восьми публикаций) — агенты доверия
в рекламе.

**Шум по запросу `authority`** — 14 позиций из 16: `Central authority for certifying
unbonded access to a vehicle`, `System and method for delegating authority through
coupled devices`, `Verifying content distribution authority`, `Delegated authority
evaluation system` — делегирование прав и сертификация, не авторитетность документа.

**Шум по запросу `spam`** — 51 позиция из 63: почтовый спам (`Zero-minute virus and
spam detection`, `System for determining email spam by delivery path`, семья Postini),
спам в мультимедиа и соцсетях, `Map spam detection`, `Discovering spam merchants using
product feed similarity`, CAPTCHA, спам-аккаунты по IP и cookie.

**Шум по запросу `reputation`** — 30 позиций из 38: репутация отправителя почты
(`Electronic message source reputation information system` и вся её семья),
`Reputation Systems in Ride Share Platforms`, `User location reputation system`,
`Reputation based collaboration session`.

**Шум по запросу `popularity`** — 30 позиций из 36: `Recommending media programs based
on media program popularity` (семья из десяти публикаций), телевизионные рейтинги,
географическая популярность UGC, `Password popularity-based limiting of online account
creation requests`.

**Шум по запросу `graph`** — 636 позиций из 679 US: подавляющее большинство про
графический интерфейс, а не про граф. `Providing composite graphical assistant
interfaces`, `Presenting search results in a dynamically formatted graphical user
interface`, `Techniques for presenting graphical content in a search result`. Плюс
графовые нейросети (`Large-Scale Architecture Search in Graph Neural Networks`,
`Neural architecture search through a graph search space`) — машинное обучение,
не ранжирование документов.

**Проверено по формуле и отсеяно:** `US-9098551-B1` — популярность сущностей,
ссылок в формуле нет, карточка в `patents/other/`.

**Дубли семей не-US:** WO/EP/CN/CA/GB/JP/KR/TW-публикации перечисленных выше семей.

## Уже разобрано в карточки

- [[US-8407231]] — `patents/link-ranking/` · историко-данные, динамика ссылочного профиля
- [[US-8127220]] — `patents/link-ranking/` · оценка исходящих ссылок, Ларри Пейдж в авторах
- [[US-8719276]] — `patents/link-ranking/` · аффилированность, деление голоса на размер сетки
- [[US-8250114]] — `patents/link-ranking/` · линкспам через производную важности
- [[US-7260573]] — `patents/link-ranking/` · персонализированный вес анкора
- [[US-2025103662]] — `patents/link-ranking/` · статические сигналы в матрице внимания
- [[US-10268641]] — `patents/other/` · **не ссылочное**: ручные оценки доверия и аннотации
- [[US-12511325]] — `patents/other/` · **не ссылочное**: граф смыслов внутри документа, не веб-граф
- [[US-8959093]] — `patents/link-ranking/`
- [[US-9165040]] — `patents/link-ranking/`
- [[US-9953049]] — `patents/link-ranking/`
- [[US-10152520]] — `patents/link-ranking/`
- [[US-9977816]] — `patents/other/`
- [[US-9098551]] — `patents/other/`

## Ошибки классификации, найденные при разборе

Каталог собирался по заголовкам, карточки — по формулам. Расхождение оказалось
систематическим: из первых 34 разобранных патентов **14 не относятся к ссылочному
ранжированию** и вынесены в `patents/other/` или `patents/text-optimization/`.

| Патент | Что обещало название | Что в формуле |
|---|---|---|
| `US-10268641` | ранжирование по доверию | кнопка доверия в интерфейсе, аннотации |
| `US-12511325` | переранжирование по графу | граф смыслов внутри документа, не веб-граф |
| `US-8615508` | искусственный анкор | якорь в URL, а не анкорный текст |
| `US-9208229` | суммаризация анкорного текста | подтверждение фактов в хранилище |
| `US-10152557` | схожесть в графах | двудольный граф общего вида |
| `US-8150842` | репутация автора | рецензии коллег, проверка личности |
| `US-8645396` | репутация автора | взвешенное рецензирование |
| `US-8458196` | тематическая авторитетность | доля авторства × вес темы |
| `US-8452746` | детект спама в выдаче | фильтрация в Custom Search Engine |
| `US-8078629` | детект спам-документов | фразовая переоптимизация → `text-optimization` |
| `US-2024250958` | personalized page ranking | графовая нейросеть, классификация активов |
| `US-9154491` | trust modeling | права на трансляцию, авторские права |
| `US-9282092` | доверие к онлайн-ресурсам | TLS-сертификаты и удостоверяющие центры |

Закономерность: слова `trust`, `authority`, `graph`, `reputation` и `page ranking`
в заголовке почти ничего не гарантируют. Отбор по названию без проверки формулы
даёт примерно 40 процентов ложных попаданий.

## Заметки по методике

Три вещи, которые стоит учесть при следующем прогоне:

1. **`web graph` не находит ничего.** В названиях стоит «web-**link** graph», через
   дефис, а поиск идёт по подстроке. Рабочие варианты — `link graph` или просто `graph`.
2. **Лимит 500 обрезает по дате.** Запрос `link` с `limit: 500` вернул только
   2021–2026: выдача сортируется по дате убывающей, и вся классика 2004–2018
   осталась за бортом. Понадобился добор отдельным запросом по 2000–2021 с
   `limit: 1000` (вернулось 752 строки, потолок не достигнут).
3. **`citation` даёт ложные срабатывания** на ex**citation** — кубиты и антенны.
   Термин рабочий, но чистить выдачу нужно вручную.
4. **Составной термин со словом, которое уже гоняли, не даёт ничего нового.** Поиск
   идёт по подстроке, поэтому `link spam`, `link analysis`, `link quality`,
   `inbound link` и `web-link graph` целиком вложены в прогон по `link`. Проверено
   фильтрацией уже сохранённых выдач: новых патентов ноль. Перед новым запросом
   смотри, не является ли он подстрокой уже выполненного — это экономит ~27 ГБ за раз.
   В дополнении такая проверка сняла 5 запросов из 8 и сэкономила ~135 ГБ.
5. **`nofollow` не находит ничего.** У Google нет ни одного патента с этим словом
   в заголовке — атрибут описан в документации для вебмастеров, но не запатентован.
6. **`trust` и `authority` почти целиком про безопасность.** Из 338 строк по `trust`
   к ранжированию относятся четыре (одна семья), из 16 по `authority` — две.
   Термины рабочие, но требуют жёсткой чистки.
7. **`graph` — почти чистый шум и при этом дорогой.** Из 679 US-строк 636 про
   графический интерфейс: слово «graph» сидит внутри «graphical». Термин упёрся
   в лимит 1000 и покрыл только 2022–2026. Если возвращаться к нему, брать сразу
   `link graph` или `web-link graph`, а не голое `graph`.
8. **`spam`, `reputation`, `popularity` дают по 5–12 релевантных строк каждый.**
   Соотношение шума к делу примерно 5:1, но находки качественные: семья
   phrase-based spam (Anna Patterson), репутация автора (Bharat, Kamvar),
   `Correlating document topicality and popularity` (Singhal, Hölzle).
