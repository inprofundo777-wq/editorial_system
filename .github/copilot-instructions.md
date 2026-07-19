# GitHub Copilot Instructions for Editorial System In Profundo

## General context

This repository contains the architecture, normative documents, workflows, policies, research frameworks, and historical records of Editorial System In Profundo.

The repository is primarily documentation-based. Changes should be interpreted as architectural, normative, procedural, historical, or editorial rather than as ordinary software changes.

## Commit messages

When suggesting a commit message:

- describe the actual architectural or documentary change;
- identify the main document or system component affected;
- distinguish between creating, revising, clarifying, restructuring, pausing, or archiving;
- avoid vague phrases such as "update files", "make changes", or "improve document";
- do not claim that a document was approved, adopted, or finalized unless the change explicitly records such a decision;
- do not describe conceptual drafts as normative documents;
- mention significant status changes, such as Draft, Review, Architectural Pause, Adopted, or Archived;
- use concise English in the commit title;
- use the extended description to explain the reason, scope, and architectural consequence of the change.

## Preferred commit title patterns

Use patterns such as:

- `Add [document or framework]`
- `Revise [document] to reflect [decision]`
- `Clarify [architectural distinction]`
- `Pause development of [document]`
- `Integrate [function] into [framework or workflow]`
- `Record [architectural decision]`
- `Archive [superseded document or version]`

## Extended descriptions

The extended description should state:

1. what changed;
2. why it changed;
3. which architectural decision or review caused the change;
4. whether the document's normative status changed;
5. what remains unresolved or deferred.

Do not invent motivations or decisions that are not present in the changed text.

## Documentation changes

When reviewing or describing Markdown changes:

- preserve the distinction between constitutional, foundational, policy, workflow, standard, working, and archival layers;
- do not treat every important document as constitutional or normative;
- flag possible duplication, mixed normative levels, hidden authority, or premature institutionalization;
- preserve document provenance and historical decisions;
- prefer minimal sufficient architecture over unnecessary new documents.

## Language

Repository documents may be written in Russian or English.

Commit titles should normally be in English.

Do not translate official document names unless the repository already uses an English name for them.
