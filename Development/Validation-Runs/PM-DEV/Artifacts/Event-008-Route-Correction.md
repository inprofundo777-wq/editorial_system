# PM-DEV — Event 008 Route Correction

## Owner Correction

`Event 007 — Editorial Coach Validation Activation` сохраняется как исторически выданное назначение и не переписывается.

Однако его execution **DEFERRED**. Coach Installation / fresh-context Validation не должен выполняться до завершения documentation/package readiness для Editorial Coach и Longform Editor.

Причина коррекции: Event 007 преждевременно объединил documentation readiness и последующий installation validation. Intended Publication Role Readiness route требует сначала подготовить и принять installation-ready packages, а уже затем проверять fresh-context recovery соответствующих ролей.

## Corrected Publication Role Readiness Route

1. `Publication Master Installation / Recovery` — COMPLETE / PASS (`PM-DEV-001`).
2. `Editorial Coach Documentation Readiness` — Review и Targeted Stabilization выполнены; Publication Master должен формально подтвердить Package Acceptance / `READY FOR INSTALLATION TEST`.
3. `Longform Editor Package Formation / Documentation Readiness` — Publication Master проводит bounded Review существующей capability и durable documentation; при необходимости собирает/стабилизирует минимальный Installation Package; затем подтверждает Package Acceptance / `READY FOR INSTALLATION TEST`.
4. Только после одновременного `Coach Documentation Readiness: PASS` и `Longform Documentation Readiness: PASS` активируются role-specific fresh-context Installation Tests.
5. `Editorial Coach Fresh-context Installation Test` — выполняется отдельной Coach branch по assignment, сформированному Publication Master через canonical Run Record.
6. `Longform Editor Fresh-context Installation Test` — выполняется отдельной Longform branch по assignment, сформированному Publication Master через canonical Run Record.
7. `Publication Master Final Validation Close` — сводит evidence Master + Coach + Longform и даёт итоговый Publication Role Readiness verdict.
8. Только после этого разрешается первый real-work validation: `Closed Content Portfolio 02 → Coach → new VIA → required Editors → Publication System`.

## Current Gate Correction

**Event 007 status:** `DEFERRED — DO NOT EXECUTE YET`.

**Current owner:** Owner → Publication Master for continuation of documentation readiness route.

**Current next gate:** `PUBLICATION MASTER — Coach Package Acceptance / Documentation Readiness`, затем `Longform Editor Package Formation / Documentation Readiness`.

Editorial Coach branch сейчас не должна выполнять Event 007.

Longform Editor branch сейчас не активирована как исполнитель validation test. Работа с Longform package сначала принадлежит Publication Master как bounded system-level package Review / formation task.

## Master Continuation Authority

Publication Master получает authority продолжить оставшуюся Publication Role Readiness chain в пределах указанной карты без возврата Owner после каждого технического микрошагa, если следующий шаг уже однозначно разрешён маршрутом.

Publication Master должен остановиться и вернуть Owner только при:

- material authority decision;
- material architecture change;
- blocker;
- необходимости активировать отдельную role branch через Owner;
- завершении Publication Role Readiness.

Publication Master не выполняет за Coach или Longform их future fresh-context Installation Tests. Он готовит packages, формирует bounded assignments и управляет handoff через canonical Run Record.

## Run Record Discipline

`PM-DEV.md` остаётся canonical handoff point. Этот artifact фиксирует Owner-approved route correction и должен быть связан с canonical Run Record новым append-only Event; предыдущий Event 007 не удаляется и не переписывается.

Process Map / Current State после синхронизации должны отражать только corrected verified route: Coach validation deferred; ownership возвращено Publication Master для package-readiness work.

## Language Learning — defer to Final Close

Во время активного validation Run Record не пересобирать ради языка. При Final Validation Close зафиксировать durable documentation principle:

> Technical language may remain English: filenames, identifiers, role/process names, statuses, field names, commands and established technical terms. Semantic project content — explanations, rationale, findings, decisions and working instructions — should by default be written in Russian.

Это не blocker текущего validation route.