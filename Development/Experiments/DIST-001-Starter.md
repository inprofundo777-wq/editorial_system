# DIST-001 — Distribution Experiment

## Статус

**Experimental / Active**

Первый рабочий цикл экспериментальной Distribution-модели In Profundo.

DIST-001 проверяет простой пакетный процесс превращения одной опубликованной статьи в недельные пакеты производных материалов для каналов.

Документ является одним живым рабочим артефактом цикла.

Он не является постоянным Template и не утверждает постоянную Distribution System.

---

# Source

```text
Source article:
Труд как место ученичества

Publication status:
PUBLISHED

Publication date:
15.08.2026

Canonical URL:
https://inprofundo777.blogspot.com/2026/08/trud-kak-mesto-uchenichestva.html

Related VIA:
VIA-2026-015

VIA source:
VIA/2026/VIA-2026-015.md

Portfolio source:
EXP-001 — Content Portfolio v1.0
```

Опубликованная статья является закрытым Source.

Distribution не переоткрывает:

- тему статьи;
- Editorial Brief;
- Draft;
- Review;
- Revision;
- Publication decisions.

---

# 1. Цель эксперимента

Проверить простой процесс:

```text
Published Article
        ↓
Coach Distribution Intake
        ↓
Reader Distribution Analysis
        ↓
SEO Distribution Analysis
        ↓
Coach Integration
        ↓
Distribution Brief
        ↓
Telegram Weekly Package
Facebook Weekly Package
Microformats Package
        ↓
Owner Polish + Publication
        ↓
Observation
        ↓
Close
```

Основная единица производства:

> **не отдельный пост, а пакет материалов для канала.**

DIST-001 не должен превращать публикацию каждого отдельного поста в самостоятельный редакционный цикл.

---

# 2. Process Map

| Блок | Шаг | Статус |
|---|---|:---:|
| **Source** | Published Article | + |
| **Intelligence** | Coach Distribution Intake | 0 |
| | Reader Distribution Analysis | - |
| | SEO Distribution Analysis | - |
| **Integration** | Coach Distribution Brief | - |
| **Production** | Telegram Weekly Package | - |
| | Facebook Weekly Package | - |
| | Microformats Package | - |
| **Publication** | Owner Polish + Publication | - |
| **Observation** | Distribution Observation | - |
| **Close** | Distribution Close | - |

### Статусы

```text
-  шаг ещё не открыт
0  шаг активен; соответствующий Editor может приступать
+  шаг завершён; результат добавлен в этот документ
```

---

# 3. Рабочий принцип

DIST-001 работает по одной ссылке.

Каждый участник:

1. физически открывает актуальную версию этого документа;
2. проверяет Process Map;
3. работает только с активным шагом `0`;
4. использует Source и уже завершённые результаты выше по процессу;
5. возвращает один цельный Markdown-блок;
6. не создаёт параллельный рабочий документ;
7. не повторяет шапку DIST-001;
8. не переоткрывает решения опубликованной статьи.

После получения результата Owner:

```text
1. вставляет цельный Markdown-блок в конец DIST-001;
2. меняет статус завершённого шага 0 → +;
3. открывает следующий шаг - → 0;
4. передаёт следующему Editor ту же ссылку.
```

Не создавать заранее пустые секции под будущие результаты.

---

# 4. Ownership — рабочая гипотеза

```text
Operational owner:
Coach
```

Coach не производит все Distribution Outputs самостоятельно.

Его функция:

```text
intake
→ route
→ integrate
→ formulate Distribution Brief
→ observe
→ close
```

Channel Editors отвечают за производство пакетов своих каналов.

Owner не должен становиться техническим диспетчером каждого отдельного поста.

---

# 5. Coach Distribution Intake

## Primary Task

Принять опубликованную статью как Source и сформулировать задачу Distribution-анализа.

Coach должен определить:

- что является центральным содержательным ядром Source;
- какие основные направления материала потенциально пригодны для дальнейшего раскрытия;
- какие вопросы Reader и SEO должны исследовать перед Production;
- какие существенные границы Source необходимо сохранить.

Coach **не должен на этом этапе**:

- составлять готовый список постов;
- писать Channel Tasks;
- определять точное количество публикаций;
- выполнять Reader Analysis;
- выполнять SEO Analysis;
- заранее решать, какие конкретные входы должны использовать TG/FB/Microformats.

## Output Contract

```markdown
# Coach Distribution Intake

## Source Core
[кратко]

## Distribution Opportunity
[что потенциально можно раскрывать дальше]

## Reader Assignment
[один цельный вопрос / задание]

## SEO Assignment
[один цельный вопрос / задание]

## Source Boundaries
[только существенные ограничения]
```

После добавления результата:

```text
Coach Distribution Intake | 0 → +
Reader Distribution Analysis | - → 0
```

---

# 6. Reader Distribution Analysis

## Function

Reader работает здесь шире, чем Reader на Article Review.

Его задача — посмотреть на уже опубликованную статью и найти **разные человеческие точки входа** в содержащиеся в ней идеи.

Reader может учитывать:

- разные жизненные состояния;
- ситуации;
- вопросы;
- напряжения;
- способы узнавания себя;
- аудитории, не являвшиеся основной аудиторией статьи;
- потенциальные риски восприятия.

Главный вопрос:

> Через какие реальные человеческие ситуации и вопросы разные читатели могут войти в содержание этой статьи?

Reader не пишет Telegram или Facebook посты.

Reader не обязан превращать каждый найденный вход в будущую публикацию.

## Output Contract

```markdown
# Reader Distribution Analysis

## Strong Human Entry Points

### 1.
**Situation / question:**  
**Why it matters:**  
**Reader risk if relevant:**  

### 2.
...

## Strongest Opportunities
[какие входы особенно перспективны и почему]

## Important Reader Boundaries
[только существенные]
```

Количество точек входа определяется материалом, а не квотой.

После результата:

```text
Reader Distribution Analysis | 0 → +
SEO Distribution Analysis | - → 0
```

---

# 7. SEO Distribution Analysis

## Function

SEO анализирует опубликованный Source уже не для SEO-подготовки самой статьи, а для расширения Distribution intelligence.

Главный вопрос:

> Через какие вопросы, формулировки и semantic entry points люди могут естественно входить в эту тему?

SEO может выявить:

- естественные поисковые формулировки;
- жизненные вопросы;
- язык, которым люди называют проблему;
- semantic variations;
- формулировки с хорошим потенциалом обнаруживаемости;
- возможные смысловые дубли;
- точки связи с опубликованным корпусом.

SEO не должен:

- повторно оптимизировать опубликованную статью;
- создавать Channel Outputs;
- определять стратегию всего корпуса;
- превращать Distribution в keyword production.

## Output Contract

```markdown
# SEO Distribution Analysis

## Search / Semantic Entry Points

### 1.
**Question / formulation:**  
**Underlying intent:**  
**Distribution relevance:**  

### 2.
...

## Language Opportunities
[полезные формулировки и варианты языка]

## Duplication / Search Risks
[только если обнаружено]

## Strongest Opportunities
[краткий приоритет]
```

После результата:

```text
SEO Distribution Analysis | 0 → +
Coach Distribution Brief | - → 0
```

---

# 8. Coach Distribution Brief

## Function

Coach интегрирует:

```text
Published Source
+
Reader Analysis
+
SEO Analysis
```

и формирует **один компактный Distribution Brief для производственных Editors**.

Coach:

- объединяет совпадающие точки входа;
- удаляет дубли;
- выбирает наиболее сильные направления;
- сохраняет разные человеческие и смысловые углы;
- определяет общие границы;
- не проектирует каждый будущий пост.

## Output Contract

```markdown
# Coach Distribution Brief

## Distribution Goal
[что должна сделать эта неделя Distribution]

## Priority Entry Points

### 1.
**Entry:**  
**Human question / tension:**  
**Useful language / semantic signal:**  

### 2.
...

## Diversity Requirement
[что важно не повторять во всех каналах]

## Boundaries
[общие существенные ограничения]

## Source Connection
[как производные материалы могут связываться с canonical article]

## Channel Assignment

### Telegram
[коротко: функция недельного пакета]

### Facebook
[коротко: функция недельного пакета]

### Microformats
[коротко: функция пакета]
```

Coach не должен заранее писать композицию каждого Channel Output.

После Integration одновременно могут быть открыты:

```text
Telegram Weekly Package | 0
Facebook Weekly Package | 0
Microformats Package | 0
```

Все три Production steps могут работать от одного Distribution Brief.

---

# 9. Telegram Weekly Package

## Function

Telegram Editor получает:

```text
Published Source
+
Coach Distribution Brief
```

и самостоятельно формирует **готовый недельный пакет Telegram** в логике своего канала.

Editor сам определяет:

- какие Entry Points использовать;
- сколько материалов действительно нужно;
- порядок;
- композицию;
- вопросы;
- где уместна ссылка на статью;
- какие идеи лучше не использовать в Telegram.

Не требуется отдельное согласование каждого поста с Coach.

## Output Contract

```markdown
# Telegram Weekly Package

[готовый недельный пакет Telegram в рабочем формате Editor]

## Editor Feedback
[только если обнаружен повторяющийся или существенный вопрос]
```

---

# 10. Facebook Weekly Package

## Function

Facebook Editor получает:

```text
Published Source
+
Coach Distribution Brief
```

и самостоятельно создаёт **готовый недельный пакет Facebook**.

Telegram Package не является обязательным Input.

Facebook Editor использует собственную логику канала.

Editor сам определяет:

- выбор Entry Points;
- количество материалов;
- композицию;
- poster thesis;
- вопросы;
- место canonical link;
- необходимое разнообразие публикаций.

## Output Contract

```markdown
# Facebook Weekly Package

[готовый недельный пакет Facebook в рабочем формате Editor]

## Editor Feedback
[только если обнаружен повторяющийся или существенный вопрос]
```

---

# 11. Microformats Package

## Function

Microformats Editor получает:

```text
Published Source
+
Coach Distribution Brief
```

и создаёт пакет коротких самостоятельных форматов.

При необходимости он может использовать уже готовые Telegram / Facebook Outputs как дополнительный материал, но это не является обязательным условием.

Editor самостоятельно определяет:

- количество;
- форму;
- длину;
- пригодность идеи для короткого формата;
- визуальный потенциал.

## Output Contract

```markdown
# Microformats Package

[готовый пакет Microformats]

## Editor Feedback
[только если обнаружен повторяющийся или существенный вопрос]
```

---

# 12. Owner Polish + Publication

После получения Channel Packages отдельный редакционный цикл для каждого поста не запускается.

Owner использует готовые пакеты как очередь публикации на неделю.

Рабочая логика:

```text
готовый Channel Package
        ↓
выбран следующий Output
        ↓
при необходимости:
быстрая финальная шлифовка
        ↓
publication
```

Локальная правка отдельного текста не требует отдельной Observation.

Различать:

```text
LOCAL TEXT ISSUE
→ Owner исправляет перед публикацией

REPEATING EDITOR PATTERN
→ Editor Feedback

CONTENT-INTELLIGENCE SIGNAL
→ Strategy / Notion

SYSTEM ISSUE
→ Master
```

---

# 13. Editor Feedback

Если Owner по ходу публикации замечает повторяющийся паттерн, например:

- однотипные вступления;
- чрезмерную абстрактность;
- слишком одинаковые вопросы;
- плохую адаптацию под канал;
- избыточную длину;
- потерю тона;
- повторение одной и той же идеи;

это фиксируется не как проблема конкретного поста, а как кандидат на развитие соответствующего Editor.

Не требуется документировать каждую мелкую правку.

---

# 14. Observation

После завершения недельного Distribution cycle Coach проводит короткую Observation.

Нужно проверить:

## Intelligence

- дали ли Reader и SEO действительно разные полезные точки входа;
- использовал ли Coach их без избыточного анализа;
- были ли найденные Entry Points реально полезны Production Editors.

## Production

- смогли ли TG / FB / Microformats работать от одного Brief;
- потребовались ли дополнительные объяснения Owner;
- насколько качественными оказались недельные пакеты;
- сколько пришлось шлифовать вручную.

## Workflow

- работала ли передача одной ссылкой;
- было ли достаточно пакетных статусов;
- возникла ли поштучная суета;
- нужен ли иной порядок или состав участников.

## Feedback Routing

Разделить новые findings:

```text
Editor-level
→ развитие конкретного Editor

Content-intelligence
→ Strategy
→ при необходимости Notion

System-level
→ Master
```

---

# 15. Close

DIST-001 закрывается после завершения выбранного недельного цикла.

Не требуется ждать статистической оценки долгосрочной эффективности всех опубликованных постов.

## Close Output

```markdown
# DIST-001 Close

**Cycle result:**  
SUCCESSFUL / PARTIAL / FAILED

## What worked
-

## What created unnecessary work
-

## Channel Editor Feedback
-

## Content-intelligence Feedback
-

## System Feedback
-

## Recommendation for DIST-002
-
```

---

# 16. Что проверяет DIST-001

Основные экспериментальные вопросы:

1. Достаточна ли цепочка:

   ```text
   Coach → Reader + SEO → Coach → Channel Editors
   ```

2. Дают ли Reader и SEO разные, действительно полезные типы intelligence?

3. Может ли Coach превратить их в один короткий Distribution Brief?

4. Могут ли Telegram, Facebook и Microformats создать недельные пакеты без поштучного управления?

5. Достаточно ли одной ссылки и одного живого документа?

6. Может ли Owner ограничиться:

   ```text
   получить пакет
   → слегка шлифовать по ходу недели
   → публиковать
   ```

7. Можно ли использовать возникающие проблемы прежде всего для развития Editors, а не для усложнения процесса?

---

# 17. Что DIST-001 не утверждает

DIST-001 не утверждает:

- постоянную Distribution System;
- постоянное ownership Coach;
- обязательность Reader;
- обязательность SEO;
- постоянный порядок аналитических ролей;
- постоянный состав Channel Editors;
- постоянное количество публикаций в неделю;
- постоянные Output Contracts;
- новый VIA template;
- отдельный Distribution College;
- обязательный Visual Stage;
- автоматизацию.

Это первый evidence cycle.

---

# 18. Активный шаг

```text
Active:
Coach Distribution Intake | 0
```

Следующее действие:

> Передать Coach только ссылку на актуальный `DIST-001`.

Coach должен физически открыть документ и выполнить исключительно активный шаг `Coach Distribution Intake`.

Предыдущие Coach / Reader / Integration outputs из старой версии DIST-001 не являются входом нового цикла.
