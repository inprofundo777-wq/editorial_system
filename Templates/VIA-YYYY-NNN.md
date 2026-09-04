# VIA-YYYY-NNN — Название материала

# Паспорт материала

| Поле | Значение |
|---|---|
| **VIA** | `VIA-YYYY-NNN` |
| **Рабочее название** | «Название материала» |
| **Lifecycle Status** | Active |
| **Source** | Указать источник |
| **Portfolio position** | Указать позицию или `Not applicable` |
| **Pilot** | Указать Pilot или `—` |
| **Координация** | Editorial Coach |
| **Дата открытия** | YYYY-MM-DD |
| **Дата закрытия** | — |
| **Template** | `VIA-YYYY-NNN v2.0-working` |
| **Protocol** | `VIA/README.md` |

> VIA работает по действующему протоколу `VIA/README.md`.
>
> Process Map является единственным canonical source of truth текущего состояния шагов.
>
> Память редакторской ветки не заменяет чтение актуального VIA.

---

# Карта процесса

| Блок | Шаг | Статус |
|---|---|:---:|
| **Formation** | Portfolio → VIA / Editorial Brief | `0` |
| **Draft** | Longform Draft | `-` |
| **Review** | Required Independent Reviews | `-` |
|  | Coach Integrated Review | `-` |
| **Revision** | Longform Revision | `-` |
| **Finalization** | Required Finalization | `-` |
| **Final Check** | Required Re-checks | `-` |
| **Publication** | Publication Preparation | `-` |
|  | Scheduled / Public Publication | `-` |
| **Close** | Preliminary / Final Close | `-` |
| **Observation** | VIA Observation | `-` |

В карте могут одновременно существовать несколько шагов `0`, если каждый из них имеет необходимые inputs и не зависит от ещё не завершённого обязательного шага.

Неиспользуемые в конкретном VIA capabilities не требуют создания пустых разделов.

---

# Source

## Portfolio / Source Handoff

**Тема**

Указать утверждённую тему.

**Центральный жизненный вопрос**

> Указать закрытый upstream question.

**Функция материала**

Указать ожидаемую функцию.

**Место в корпусе**

Указать связь с опубликованными или планируемыми материалами.

**Primary Human State / Context**

- ...

**Relevant Human States / Contexts**

- ...

**Search Question / External Language**

Указать, если существует и относится к материалу.

**Closed Upstream Decisions**

- ...
- ...

**Known Boundaries**

- ...
- ...

**Source References**

- ...
- ...

---

# Active Handoffs

## Portfolio → VIA / Editorial Brief

**Исполнитель**

Editorial Coach

**Inputs**

- настоящий VIA;
- Portfolio / Source Handoff;
- связанные материалы и решения;
- действующая документация Coach;
- только фактически необходимые дополнительные источники.

**Task**

Подготовить достаточный Editorial Brief для запуска материала.

Не повторять Candidate Selection, если Portfolio decision уже закрыт.

Не проектировать весь последующий VIA заранее.

**Expected Output**

Цельный раздел:

`# Coach Editorial Brief`

Brief должен содержать только необходимое для запуска следующей capability, включая:

- Formation Verdict;
- Working Function;
- Primary Audience;
- Relevant Audience;
- Human Entry;
- Central Movement;
- Reader Promise;
- biblical / theological axis, если применимо;
- Required Boundaries;
- Protected Ground;
- Closed Upstream Decisions;
- Longform Freedom;
- решение о необходимых Reviews;
- следующий article-specific handoff;
- точную необходимую Process Map transition.

**Transfer Requirement**

Результат вернуть одним внешним Markdown-блоком без вложенных triple-backtick fences.

---

# 1. Formation

После выполнения активного Formation сюда добавляется цельный:

`# Coach Editorial Brief`

Не создавать заранее пустые секции под Draft или Reviews.

---

# 2. Draft

Раздел добавляется после активации Longform.

Минимальная структура результата:

## Longform Editor — Draft

**Source**

Указать Editorial Brief и используемую версию материала.

**Draft**

Добавить один цельный Draft.

**Material Notes**

Добавлять только если существуют необходимые downstream notes или material deviation.

---

# 3. Review

Раздел создаётся только для фактически назначенных Review capabilities.

Независимые Reviews могут активироваться параллельно.

Каждый Review получает отдельный article-specific handoff и собственную строку в Process Map, если различение статусов необходимо для управления работой.

Пример возможной карты после Formation:

    | Блок | Шаг | Статус |
    |---|---|:---:|
    | Review | Theology Review | `0` |
    | Review | Reader Review | `0` |
    | Review | Literary Review | `-` |
    | Review | Coach Integrated Review | `-` |

Не добавлять Editor только ради полноты процесса.

После получения необходимых Reviews добавляется:

## Coach Integrated Review

Coach Integration:

- объединяет пересекающиеся findings;
- определяет required boundaries;
- сохраняет protected ground;
- отделяет optional suggestions;
- формирует Revision Assignment;
- определяет необходимые re-checks;
- не проектирует Revised Draft.

---

# 4. Revision

Раздел добавляется после активации Longform Revision.

## Longform Editor — Revised Draft

Добавить один цельный Revised Draft.

Longform:

- соблюдает required boundaries;
- сохраняет protected ground;
- самостоятельно выбирает литературную реализацию;
- не обязан механически выполнять optional suggestions;
- не переоткрывает закрытые решения без material deviation.

---

# 5. Finalization

Раздел создаётся только для фактически назначенной Finalization capability.

Finalization:

- работает с актуальным Revised Draft / Final Candidate;
- не повторяет полный Review;
- не переоткрывает архитектуру материала;
- возвращает PASS либо локально достаточные коррекции;
- поднимает Material Deviation, если локальная коррекция недостаточна.

Не создавать заранее секции для всех возможных Finalization Editors.

---

# 6. Final Check

Раздел создаётся только для назначенных selective re-checks.

Повторно вызывается только capability, если:

- Revision могла создать соответствующий material risk;
- ранее установленная граница требует подтверждения;
- Finalization обнаружила Material Deviation;
- Coach установил необходимость локальной проверки.

Полный Review не повторяется по умолчанию.

---

# 7. Publication

Раздел добавляется по мере появления фактических publication data.

## Publication Preparation

**Final Title**

...

**Final Text Reference**

...

**SEO Publication Package**

Добавить или указать ссылку, если требуется.

**Visual**

Добавить или указать route, если требуется.

**Blogger / Publication Fields**

- ...
- ...

## Publication Status

| Поле | Значение |
|---|---|
| **State** | Preparation / Scheduled / Published |
| **Scheduled Date** | — |
| **Published Date** | — |
| **Public URL** | — |
| **GitHub Reference** | — |
| **Rendering Check** | Pending / PASS / Deviation |
| **Material Deviation** | None / указать |

Publication data не дублируются в паспорте как Current Stage.

---

# 8. Close

Close может быть активирован после стабилизации Final Text и постановки материала в очередь.

## Close Status

| Поле | Значение |
|---|---|
| **State** | Preliminary / Final |
| **Publication** | Preparation / Scheduled / Published |
| **Final Condition** | Указать оставшееся условие или `Completed` |

## Material Close

**VIA**

`VIA-YYYY-NNN`

**Final Title**

...

**Published / Scheduled Date**

...

**Public URL**

...

**GitHub Reference**

...

**Cycle Result**

Кратко зафиксировать фактический результат редакционного цикла.

## Portfolio / Notion Update Package

Добавляется только необходимая информация:

- какой материал подготовлен или опубликован;
- publication status;
- какой Portfolio item становится следующим;
- какие durable content relations, Human States или questions следует вернуть в Notion;
- что не переносить, чтобы не создавать двойной учёт;
- какие Owner decisions действительно требуются.

Если update не требуется, отдельный пустой пакет не создаётся.

## Final Close Confirmation

Final Close подтверждает:

- выполнены установленные final conditions;
- публичный URL проверен, если материал опубликован;
- publication data зафиксированы;
- material deviation отсутствует либо маршрутизирована;
- Portfolio / Notion routing подготовлен, если требуется;
- блокирующих вопросов нет;
- Lifecycle Status может быть изменён `Active → Closed`.

---

# 9. Observation

Раздел создаётся или активируется только при наличии фактической задачи Observation либо material process evidence.

Observation может проводиться параллельно с другими блоками.

Фиксировать прежде всего:

- достаточность one-link handoff;
- необходимость дополнительных Owner explanations;
- ручную интеграцию Editors;
- неясность Process Map;
- конфликт статусов;
- непереносимый Output;
- потерю capability;
- material overlap;
- неясную authority boundary;
- значимую документационную недостаточность;
- работу Preliminary Close;
- readiness для будущей автоматизации.

Не фиксировать:

- полную историю нормальной работы;
- каждую техническую операцию;
- отсутствие ошибок;
- каждую локальную правку;
- ритуальное подтверждение соблюдения Protocol.

---

# 10. Learning Routing

Этот раздел добавляется только при наличии material signal, превышающего порог маршрутизации.

## Signal

- **Type:** Article | Content | Role | System
- **Signal:** краткое наблюдение
- **Evidence:** ссылка на точное место в VIA
- **Route:** VIA | Strategy | Role Backlog | Master / IDEAS
- **Reason:** почему signal требует маршрутизации

Правила:

- Article learning остаётся в VIA;
- Content learning передаётся Strategy;
- Role-specific pattern направляется в соответствующий Role Backlog;
- cross-role, VIA-wide или architectural signal направляется Master;
- один signal получает один primary destination;
- evidence не копируется полностью в несколько документов;
- Development не активируется автоматически из VIA Close;
- пустой Learning Routing section не сохраняется.

---

# 11. Owner Actions

Этот раздел добавляется только при наличии действий, которые Editor не может выполнить самостоятельно.

## 🔴 OWNER ACTION

**Target**

Указать точный файл, Notion database или внешний объект.

**Action**

Указать точное физическое действие.

**Update Mode**

Full Document Replacement / Complete Section Replacement / Status Update / External Action

**Replacement Boundary**

Указать точный раздел, если применимо.

**State Transition**

Указать точные изменения Process Map, если применимо.

**Expected Result**

Указать проверяемый результат.

**Next Route**

Указать следующего Editor, capability, документ или решение.

Owner Action не должен требовать от Owner повторного редакционного анализа или восстановления routing.

---

# 12. Handoff and Transfer Rule

Каждый переносимый результат возвращается:

- одним внешним Markdown-блоком;
- с одной зоной копирования;
- без вложенных triple-backtick fences;
- с сохранёнными Markdown headings, tables, lists и blockquotes;
- как полный документ либо полный цельный раздел;
- с точным target;
- с точной replacement boundary;
- с точной state transition;
- с ясным next route.

Если изменение нельзя безопасно передать одним цельным разделом, возвращается полный документ.

Редактор не должен возвращать набор разрозненных локальных исправлений, которые Owner обязан собирать вручную.

---

# 13. Validation Record

Этот раздел используется только в VIA, на котором проводится утверждённая Validation.

Проверить:

- был ли Process Map достаточным state authority;
- были ли активные `0` обоснованы inputs и dependencies;
- удалось ли работать параллельно без конфликта;
- смогли ли Editors начать работу по одной ссылке;
- потребовалось ли повторять VIA Protocol в handoff;
- был ли результат возвращён одним корректным Markdown-блоком;
- сколько отдельных ручных изменений потребовалось Owner;
- смог ли Coach подготовить Preliminary Close;
- удалось ли выполнить Learning Routing без архитектурного анализа;
- сохранился ли VIA как полноценный case file материала.

Validation не создаёт постоянное изменение автоматически.
