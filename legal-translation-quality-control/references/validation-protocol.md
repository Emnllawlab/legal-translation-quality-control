# Validation Protocol

Use this file to test the method after a workflow or anchor change and for high-risk projects. Do not make ordinary translation wait for a full research audit.

## Holdout design

Select real, publicly accessible legal text not used to write or tune the current anchors. Keep the source, answer, and issue list outside the installed skill. Prefer continuous passages with several propositions over isolated terms.

Include samples that test conditions, exceptions, scope, procedural posture, remedy, priority, responsibility, and historical or cross-system collisions. Do not reveal the expected answer to the translator or the independent reviewer.

## Forward translation

1. Extract a proposition list before translating: actors, conduct, conditions, exceptions, scope, procedure, remedy, and effect.
2. Run the current skill in the intended mode.
3. Record Tier 1 choices, assumptions, and verification points.
4. Do not preserve Chinese syntax merely to make later back-translation easier.

## Blind round trip

Have a fresh context translate the English back into Chinese without seeing the original, answer, anchor file, or prior review. For Tier 1 passages, use two independent back-translations where practical. Compare legal propositions, not wording.

Check:

| Area | Question |
|---|---|
| Actors | Are the same persons or institutions acting or protected? |
| Relations | Are rights, duties, powers, defences, and liabilities unchanged? |
| Elements | Are conditions, thresholds, presumptions, exceptions, and negation preserved? |
| Scope | Are partial/whole, included/limited, relative/absolute distinctions intact? |
| Time | Are dates, sequence, duration, maturity, and historical law preserved? |
| Procedure | Is the posture, application, appeal, retrial, recognition, or enforcement accurate? |
| Remedy | Are the result, damages, priority, and third-party effects accurate? |
| Target reading | Does the English import a foreign-law element or consequence? |

## Regression propositions

Retain these abstract propositions in the holdout set after relevant revisions:

- A proposition expressing inability to satisfy a debt must not be weakened to mere nonpayment or an outstanding status; do not add a maturity condition without a stated or legally supported basis.
- When the supplied date selects historical law, historical terminology must not be silently modernized or replaced by a generic near-synonym.

## Error grading

- H: changes actor, element, condition, right, duty, procedure, remedy, priority, or legal effect.
- T: a system or context term is wrong but the proposition remains recoverable.
- S: meaning survives but drafting is unsuitable.
- P: an acceptable stylistic preference.

Release a revised Tier 1 sample only when H=0 and material T issues are resolved. A back-translation difference alone is not an error: first determine whether the English permits the original legal meaning.

## Maintenance rule

When a holdout exposes a repeatable problem, add the smallest self-authored guardrail or trigger that would prevent it. Do not add the whole source passage, a case narrative, or a long glossary. Re-test with a fresh holdout after each material change. Keep a project test record outside the skill with source, date, proposition list, outputs, errors, cause, revision, and re-test result.
