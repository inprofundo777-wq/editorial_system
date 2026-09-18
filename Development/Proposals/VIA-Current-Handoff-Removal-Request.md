# Master Change Request — Remove Standalone Current Handoff from VIA

## Request Status

`SUBMITTED TO MASTER / DECISION REQUIRED`

## Request Owner

Editorial Coach

## Decision Authority

Master Editor proposes system-level disposition. Permanent template/protocol change remains Owner-gated under the existing Editorial System authority model.

## Requested Change

Remove the standalone `# Current Handoff` section from:

1. `Templates/VIA-YYYY-NNN.md`;
2. the corresponding normative instructions in `VIA/README.md`;
3. future VIA creation practice.

Preserve its useful operational content inside the section of the active stage.

## Problem

The current VIA structure contains two locations that can appear to describe active state:

1. Process Map — defined as the canonical source of truth;
2. Current Handoff — a repeated task-and-status block.

This duplication creates drift risk without adding a distinct authority function.

## Evidence

### Evidence 1 — VIA-2026-021 status divergence

After Longform Editor completed the Draft:

- Process Map correctly showed `Longform Draft: +`;
- Current Handoff still showed `Longform Draft: 0`;
- the document therefore presented two incompatible readings of the same step.

The Draft itself was intact. The defect was created by redundant routing state.

### Evidence 2 — VIA-2026-020 section-boundary failure

The Current Handoff contained the literal target heading `# SEO Publication Package` inside its instructions.

During replacement, an editor/tool matched that earlier textual occurrence instead of the actual section heading. This removed the intervening Source, Reviews, Revised Draft and Final Text structure. The document had to be restored from the previous intact commit.

The failure was technical, but the duplicated heading reference inside Current Handoff increased the ambiguity of replacement boundaries.

### Evidence 3 — Open Portfolio 2 VIA files

VIA-2026-021–024 can retain one-link execution without standalone Current Handoff:

- Process Map identifies the active step;
- the same-named stage section contains the article-specific assignment;
- Owner Actions contains only an actual Owner transfer/action when needed;
- `VIA/README.md` holds generic process rules.

The standalone Current Handoff was removed locally from these four working VIA files without loss of required task information.

## Proposed Operating Model

### 1. Process Map

The only canonical state authority.

It answers:

- what is complete;
- what is active;
- what is not yet activated;
- which independent steps may run in parallel.

### 2. Same-named stage section

Contains the complete article-specific assignment:

- executor;
- inputs;
- task;
- expected output;
- replacement boundary;
- permitted status transition;
- next route.

Example:

```markdown
# Theology Review

## Assignment — `0`

**Executor:** Theology Editor  
**Input:** Longform Draft + Editorial Brief  
**Task:** article-specific review scope  
**Expected output:** 0–3 material findings  
**Replacement boundary:** full section `# Theology Review`
```

After execution, the result replaces the Assignment inside the same stage section.

### 3. Owner Actions

Used only when an action cannot be performed by the assigned Editor or Coach:

- external publication;
- Notion write;
- Owner-gated decision;
- manual transfer where technically necessary.

Owner Actions must not duplicate the full active assignment by default.

### 4. VIA README

Holds generic execution and transfer rules. These are not repeated in each VIA.

## Required Template Changes

If Master recommends adoption, the template should:

1. remove `# Active Handoffs` / standalone `# Current Handoff`;
2. place the initial Formation assignment inside `# 1. Formation`;
3. define a standard `## Assignment — 0` block for an active stage;
4. require the completed result to replace that assignment within the same stage section;
5. keep Process Map as the only status authority;
6. reserve Owner Actions for genuine Owner-only operations;
7. prohibit literal target headings in prose when they could be mistaken for replacement boundaries, or require anchored-heading semantics;
8. retain one-link execution: an Editor must still be able to open one VIA, read the Process Map and find the same-named active section.

## Required README Changes

If adopted, `VIA/README.md` should clarify:

- Editors locate active work through Process Map;
- each `0` maps to one same-named section;
- the stage section contains the complete current assignment;
- assignments do not become a second status source;
- completed results replace their stage assignment;
- multiple `0` steps are permitted when dependencies are satisfied;
- Owner Actions is not a general routing mirror.

## Acceptance Criteria

The change is successful if a fresh-context Editor can:

1. identify its active step from Process Map;
2. locate exactly one corresponding stage section;
3. recover the full task without chat history;
4. identify an unambiguous replacement boundary;
5. complete the step without updating a separate routing block;
6. leave no stale task/status duplicate after completion;
7. preserve the one-link workflow.

## Non-goals

This request does not propose:

- removing Process Map;
- reducing article-specific assignments;
- moving production state into Notion;
- changing role authority;
- redesigning the full VIA lifecycle;
- changing previously closed VIA files;
- automatically adopting a permanent architecture from one local correction.

## Current Local Disposition

- VIA-2026-021–024: standalone Current Handoff removed;
- stage-specific assignment retained in the appropriate stage section or the completed result already occupies it;
- template and `VIA/README.md`: unchanged pending Master/Owner decision.

## Requested Master Output

Return one of:

- `ADOPT` — with exact template and README replacement scope;
- `ADOPT WITH REVISION` — with a corrected operating model;
- `TEST FURTHER` — with one bounded validation case and explicit success criteria;
- `REJECT` — with the distinct function that requires Current Handoff to remain.

Do not edit the template or protocol as part of review unless separately authorized by Owner.

---

`MASTER CHANGE REQUEST: SUBMITTED`
