# Legal Translation Quality Control

Legal Translation Quality Control is a publicly available, non-commercial skill for Chinese-English legal translation and review. It is designed for lawyers and legal teams working with PRC, US/UK common-law, Hong Kong, treaty, and mixed-law materials.

## What it does

This project controls the translation process rather than supplying a complete bilingual dictionary. It makes the translator identify the source legal system, direction, applicable-law date, and intended use; separate low-risk language from high-risk legal concepts; translate legal effect before polishing style; verify difficult points against source law; and run a release check before delivery.

The included `risk-anchors.md` is deliberately compact. It contains a small independently selected set of lawyer-reviewed triggers and contextual guardrails for concepts that commonly collide across systems. An anchor tells the translator what distinction to investigate. It is not a mandatory answer, does not cover every legal term, and does not make an absent term unsupported or untranslatable.

## What it does not do

It does not replace source-law research, an official translation, a project glossary, a qualified lawyer, or review by the intended court, tribunal, regulator, client, or supervising attorney. It does not contain a historical-law database. When the date or legal effect matters, verify the governing text directly.

## Install and use

Install the directory `legal-translation-quality-control` as a skill. Invoke it for Chinese-English translation, bilingual review, or legal-effect quality control. Specify the document, translation direction, source system, applicable-law date if known, intended use, and desired mode (Clean, Annotated, or Bilingual Review). If the document resolves those facts, do not repeat them as questions.

For routine text, let the workflow remain efficient. For Tier 1 concepts, use the anchors as prompts, create a project term sheet, verify the source law, and complete the release checklist. Keep project-specific terms and holdout test material outside the installed skill.

## Attribution and licence

Created and maintained by DL-Agenticlaw. This project is licensed under CC BY-NC 4.0: attribution is required; commercial use is prohibited; adaptations and derivatives are permitted on the same attribution and non-commercial basis. See [LICENSE](LICENSE) and [NOTICE.md](NOTICE.md).
