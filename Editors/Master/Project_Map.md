# Publication Master — Publication System Map

## Паспорт

| Поле | Значение |
|---|---|
| Статус | v0.1 Candidate / Awaiting Validation |
| Функция | минимальная карта предметной области и интерфейсов роли |
| Не является | MASTER_ROADMAP, Project Overview map или полным Editorial lifecycle |

## 1. Граница системы

```text
EDITORIAL SYSTEM

Upstream editorial work
Idea → Draft → Review → Revision → Final Text approval
                              │
                              ▼
PUBLICATION SYSTEM
Final Preparation
→ Public Publication
→ Distribution
→ Publication Verification
→ Post-publication Handoff
```

## 2. Ownership

| Область | Owner capability |
|---|---|
| Постоянная архитектура и authority | Owner |
| Архитектурная связность Publication System | Publication Master |
| Конкретный VIA/DIST | Editorial Coach |
| Профильное содержание | Editors |
| Portfolio / Horizon / Notion | Strategist |
| Общепроектная карта и continuity | Project Overview |
| Research | Research System |
| Анализ downstream evidence | соответствующая Analytics / Strategy capability |

## 3. Основные интерфейсы

### Upstream → Publication System

Вход: утверждённый publish-ready Source, закрытые upstream decisions и понятный handoff.

### Publication Master → Coach

Выход: принятая рамка, разрешённая коррекция, experiment, threshold или цельный handoff. После передачи обычный цикл снова принадлежит Coach.

### Coach → Publication Master

Вход: Current Source, material deviation, evidence и системный вопрос.

### Publication System → downstream learning

Факты публикации маршрутизируются в Analytics, Strategy, Role Development или System Development. Publication Master не присваивает последующий анализ.

## 4. Граница завершения

Publication и Distribution имеют различимые состояния. Публикация может быть завершена, даже если Distribution ещё продолжается. Цикл Publication System выходит, когда факты проверены, состояния честно названы и evidence передано владельцу следующего анализа.
