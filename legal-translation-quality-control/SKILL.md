---
name: legal-translation-quality-control
description: Apply a legal translation quality-control workflow to Chinese-English legal translation, review, and bilingual comparison across PRC, US/UK common-law, Hong Kong, international, and mixed-law materials. Use it for contracts, pleadings, judgments, legislation, opinions, arbitration materials, and other legal documents when legal effect, cross-system terminology, source verification, or release quality matters.
---

# Legal Translation Quality Control

Use this skill to control the translation decision process, not to supply a complete bilingual dictionary or a guaranteed answer key. Translate efficiently when risk is low; slow down only where a wording choice can change legal meaning.

## 1. Preflight: resolve four axes

Determine, from the document and context where possible:

1. Source legal system: PRC, US/UK common law, Hong Kong, treaty/international, or mixed.
2. Direction: Chinese→English or English→Chinese. Do not infer direction from legal system.
3. Applicable-law date: identify the law in force when the transaction, conduct, or proceeding occurred. If the date is unresolved and changes the wording, ask; otherwise proceed and state the assumption.
4. Use and readers: internal understanding, client work, court/arbitration filing, legislation comparison, transaction signing, or academic work.

Do not ask questions already resolved by the text. Ask only when the missing axis would materially change the translation.

## 2. Classify risk and choose the mode

- Tier 1: a mistake may change a party, legal status, element, procedure, remedy, priority, burden, or liability. Verify source law and legal effect before release.
- Tier 2: a definition, institution, document name, repeated term, or cross-document expression that must remain consistent. Lock it in a project term sheet.
- Tier 3: ordinary wording that does not carry an independent legal effect. Translate efficiently and review for completeness.

Choose one output mode:

- Clean: deliver only the target-language text; do not leak annotations, alternatives, or source-language notes.
- Annotated: deliver the translation plus concise notes on Tier 1 choices, unresolved assumptions, and verification points.
- Bilingual Review: place source and translation side by side and identify terminology, legal-effect, and drafting issues for lawyer review.

## 3. Translate in two passes

First produce a legal-structure draft. Preserve actors, acts, rights, duties, permissions, conditions, exceptions, negation, degree, time, quantity, procedure, remedy, causation, and legal effect. Do not merge or soften a rule for fluency.

Then produce the target-language legal style draft. Select wording by target jurisdiction, document function, and house style. Do not impose a universal rule such as always using `shall`; choose among `shall`, `must`, `may`, the present tense, or another form deliberately.

Use `references/risk-anchors.md` only when a trigger appears. It supplies contextual guardrails and questions, not binding answers. When a source term appears in the file, consult the relevant row before release; do not load the entire file for ordinary translations. A term absent from it remains translatable: analyze the sentence and law, then verify when risk warrants.

## 4. Route by source system and direction

- PRC source: identify the Chinese legal concept and its effect first; verify the current or historical source law and any authoritative parallel text for Tier 1 terms.
- US/UK source: identify the target common-law jurisdiction and preserve its institutional and procedural distinctions; do not substitute PRC concepts because a Chinese gloss looks familiar.
- Hong Kong source: use local court, institution, statute, and drafting conventions; do not transplant a Hong Kong name into another jurisdiction.
- Treaty or mixed source: separate concepts by source system and use the treaty or institution's authoritative text where one exists.

For historical law, verify the text directly if the compact anchors do not cover the date. This lite skill contains no historical-law database.

## 5. Verify and release

For each Tier 1 item, compare the candidate wording against the source-law elements and effects, then perform a target-reader reverse check: would the wording import an extra element, remedy, defence, or procedural consequence? Record the chosen term and rejected alternatives in the project term sheet.

Do not fabricate case names, docket numbers, parties, source descriptions, citations, links, or legal history. Do not call a wording official or standard without a source. Run the release checklist in `references/quality-control-protocol.md`; use `references/validation-protocol.md` for holdout and round-trip testing when changing this workflow or testing a high-risk document. Apply `references/document-controls.md` for document-specific style and formatting controls.

Before release, confirm that the translation preserves legal propositions, scope, timing, exceptions, responsibility, procedure, and remedies; uses locked terms consistently; states material uncertainties in Annotated/Bilingual Review mode; and contains no internal notes in Clean mode.
