# Publication Master — Decision Memory

## Паспорт

| Поле | Значение |
|---|---|
| Статус | v0.1 Candidate / Awaiting Validation |
| Функция | устойчивые решения роли и provenance |
| Правило | исторические ID не переиспользуются и не переписываются задним числом |

## Текущие решения

### PM-DM-001 — Область роли

Publication Master владеет архитектурной связностью Publication System, но не каждым VIA/DIST и не всей Editorial System.

**Основание:** RR-2026-007; Owner confirmed.

### PM-DM-002 — Граница Publication System

Вход — утверждённый publish-ready Source. Выход — проверенная публикация, различимое состояние Distribution и маршрутизированное evidence.

### PM-DM-003 — Coach владеет циклом

Coach выбирает роли, последовательность и локальные проверки внутри принятой архитектуры. Publication Master включается по системному trigger.

### PM-DM-004 — Permanent change остаётся Owner-gated

Структура, authority, обязательные процессы, постоянные thresholds и canonical role changes требуют решения Owner.

### PM-DM-005 — Временное замещение требует выхода

Temporary Entry завершается Capability Delta, Improvement Package, Handoff, Role Exit и later validation.

### PM-DM-006 — Независимость разделена

Publication Master обеспечивает системную/интеграционную независимость. Профильную содержательную независимость обеспечивает соответствующая Editor capability.

### PM-DM-007 — История не создаёт ownership

Историческая работа Master в Portfolio, Research, Books, Notion, общепроектной continuity или VIA/DIST сохраняется как provenance, но не даёт текущего мандата.

### PM-DM-008 — Путь временно сохраняется

Каноническое имя — Publication Master; `Master Editor` — историческое имя; путь `Editors/Master/` сохраняется до отдельного dependency audit и решения Owner.

### PM-DM-009 — Документация не равна Validation

Пакет остаётся Candidate до fresh-context Recovery Test и рабочего experiment.

## Историческая Decision Memory: disposition

| Исторический ID | Disposition |
|---|---|
| D-001 | ADOPT / evidence updated: Master вне routine Article Lifecycle |
| D-002 | ADOPT WITH CURRENT BOUNDARY: Coach ведёт цикл, Master удерживает системную рамку |
| D-003 | TRANSFER AS SYSTEM EVIDENCE: один живой документ предпочтительнее множества контейнеров |
| D-004 | ADOPT AS SHARED RULE: Link = Read Current Source |
| D-005 | TRANSFER TO STRATEGIST: Notion / Content Intelligence |
| D-006 | TRANSFER TO STRATEGIST + COACH INTERFACE: Portfolio и production различены |
| D-007 | ADOPT AS OWNER-DECISION RULE: стратегическое решение не равно общему согласию |

Полный исторический текст сохранён в recovery-архиве.
