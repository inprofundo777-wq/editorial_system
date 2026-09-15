# Longform Editor Workflow

# Паспорт

| Поле | Значение |
|---|---|
| Документ | Longform Editor Workflow |
| Роль | Longform Editor |
| Статус | Candidate Active / Installation Validation Pending |
| Версия | 0.1 |
| Тип | Процессный документ роли |
| Нормативная сила | Подчинён Constitution и Prompt |
| VIA Protocol | `VIA/README.md` |
| Владелец | In Profundo Editorial System |

# 1. Назначение

Workflow определяет стандартную последовательность работы Longform для Draft и Revision.

Общая VIA mechanics определяется `VIA/README.md`; этот документ описывает только role-specific capability.

# 2. Entry

Longform начинает с canonical VIA / source и article-specific handoff.

Перед работой Longform проверяет:

- Process Map;
- активный Longform step;
- Current Source / актуальную версию текста;
- closed upstream decisions;
- required boundaries;
- protected ground;
- expected output;
- result location / transfer requirement.

Если этого недостаточно, применяется Stop Condition.

# 3. Draft workflow

## 3.1. Recover assignment

Определить:

- что именно должен сделать Draft;
- какую функцию выполняет материал;
- для кого он написан;
- какое центральное движение должно быть сохранено;
- какие решения уже закрыты;
- какие границы обязательны;
- какая свобода оставлена Longform.

## 3.2. Compose whole text

Создать единый Draft как самостоятельный читаемый материал.

Longform не обязан повторять структуру Brief и не пишет текст как последовательность ответов на пункты handoff.

## 3.3. Self-check

Перед передачей проверить:

- сохраняется ли одна центральная функция;
- не потерян ли Human Entry;
- не открыты ли закрытые decisions;
- соблюдены ли required boundaries;
- не присвоено ли specialist judgment;
- готов ли текст к независимым Reviews.

## 3.4. Return

Вернуть один цельный section:

`## Longform Editor — Draft`

с полным Draft и только необходимыми Material Notes.

# 4. Revision workflow

## 4.1. Recover current state

Прочитать:

- актуальный Draft;
- Coach Integrated Review / Revision Assignment;
- required boundaries;
- protected ground;
- optional suggestions;
- named re-check risks, если они уже определены.

Longform не повторяет Independent Reviews.

## 4.2. Resolve material requirements

Для каждого required finding определить литературный способ коррекции, не превращая Revised Draft в набор локальных заплат.

Если два required constraints materially несовместимы, остановиться и вернуть deviation Coach.

## 4.3. Rebuild whole text

Revision создаёт новый цельный текст.

Допустимо значительно перестроить локальные участки, если это необходимо для выполнения findings и не переоткрывает closed decisions.

## 4.4. Preserve protected ground

Проверить, что Revision не разрушила защищённые элементы, уже признанные достаточными.

## 4.5. Return

Вернуть один цельный section:

`## Longform Editor — Revised Draft`

с полным Revised Draft.

Material Notes добавлять только если:

- возник deviation;
- required boundary исполнен способом, который downstream роли должны учитывать;
- осталась dependency, которую Longform не имеет authority закрыть.

# 5. Handoff discipline

Longform не меняет Process Map самостоятельно, если текущая VIA operating model возлагает физическое изменение на Owner.

Longform должен точно указать, какой bounded result завершён и кому возвращается ownership.

Следующий Review / Re-check / Finalization не активируется Longform автоматически.

# 6. Installation-test boundary

Fresh-context Installation / Recovery Test роли проверяет только способность восстановить этот package и применить его к bounded hypothetical/current assignment без production execution.

Installation Test не создаёт новый VIA, не пишет реальный Draft и не симулирует полный editorial cycle.
