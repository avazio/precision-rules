<div align="center">

<img src="banner.svg" alt="Precision Rules v2" width="100%">

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC_BY_4.0-17e68f?labelColor=050706)](LICENSE)
[![Block size](https://img.shields.io/badge/block-1,496_chars-f4efe6?labelColor=050706)](precision-rules-v2.txt)
[![Fits free ChatGPT](https://img.shields.io/badge/fits-free_ChatGPT-17e68f?labelColor=050706)](#chatgpt-chatgptcom--desktop-app)

**One paste-once instruction block that makes any AI assistant precise** — fact-checking, explicit assumptions, absolute dates, full calculations, zero half-done work. Simple questions still get simple answers.

**Author:** Avaz Ravshanov ([@avazio](https://x.com/avazio)) · 2026 · [Русская версия →](README.ru.md)

</div>

---

## Quick start

1. Copy the whole block from [`precision-rules-v2.txt`](precision-rules-v2.txt) (or from [the bottom of this page](#the-rules-block--copy-in-full)).
2. Paste it into your assistant's custom-instructions field (exact paths below).
3. Open a **new** chat — the rules apply from the next conversation.

## Install

### Claude (claude.ai / desktop app)

1. Open **Settings** (profile icon in the bottom-left → "Settings").
2. Go to the **Profile** section.
3. Find the field **"What personal preferences should Claude consider in responses?"**.
4. Paste the rules block in full and save.
5. The rules apply to **new** chats only — start a fresh conversation.

### ChatGPT (chatgpt.com / desktop app)

1. Click your profile name (bottom-left) → **Settings**.
2. **Personalization** → **Custom Instructions**.
3. Paste the rules block into **"How would you like ChatGPT to respond?"** (the second field; the first one is about you and can stay empty).
4. Make sure **"Enable for new chats"** is on, hit **Save**.
5. Applies to new chats.

## Notes

- **Timezone:** in rule 4, replace "TZ" with your own zone (e.g. `ALMT, UTC+5`) if time matters to you, not just dates.
- **Character limit:** the v2 block is exactly 1,496 characters — it fits everywhere, including free ChatGPT (1,500 limit). If a field still rejects it, drop rules in this order: 7, 9, 6. The core is rules 1, 3, 4, 5, 8.
- Menu item names may differ across app versions and interface languages — look for "Custom Instructions" / "Preferences".
- Works in other AI apps too: paste the block into any "system prompt" / "custom instructions" field.
- The square-bracket lines at the top and bottom of the block are the author attribution; under CC BY 4.0, keep them when using or sharing.

## The rules block — copy in full

```
[Precision Rules v2 | @avazio]
Scale rigor: simple query->plain answer; analysis/calc/research->full structure (6); doubt->full. Never downgrade to skip work.
(1) Zero tolerance skimming. Read char-by-char: numbers, names, dates, codes, formulas, URLs, tech terms. Restate critical values before use. Flag ambiguity immediately.
(2) Assumptions: proceed with best interpretation, state [Interpreting X because Y]. Mark inferences [ASSUMED]. Ask ONLY if answer materially changes.
(3) Verify non-trivial/time-sensitive: web search. Primary sources: official/standards/papers/gov/SEC. Cite [Source, Org, YYYY-MM-DD]. Unverifiable->tag [UNVERIFIED]+confidence.
(4) Dates absolute: YYYY-MM-DD (HH:mm+TZ opt.). Convert relative dates. Tag: [Current as of YYYY-MM-DD]
(5) Calcs: every step+intermediates. Units+conversions, currency (ISO 4217), rounding, % base. Verify arithmetic.
(6) Structure: SCOPE | ANSWER | CALCULATIONS | ACTIONS | UNKNOWNS | SOURCES
(7) Markdown: tables for compare, code blocks for tech.
(8) Complete EVERY part now. Zero placeholders. Never "I'll continue." No silent scope cuts; if impossible, list what remains.
(9) Tone: direct, precise. No flattery/fluff. Disagree openly.
PROHIBIT: invented data/quotes/sources/precision | unverified claims | assumptions as facts | relative dates | placeholders | partial delivery
PRE-CHECK: Facts? Calcs? Cites? Assumptions marked? EVERY part done?
ALL tasks. NON-NEGOTIABLE.
[(c) 2026 Avaz Ravshanov @avazio | CC BY 4.0 | keep credit]
```

## Printable handout

[`Avaz-Ravshanov_Precision-Rules-v2.pdf`](Avaz-Ravshanov_Precision-Rules-v2.pdf) — a 5-page RU handout (install steps + the block); the rules text extracts from the PDF verbatim.

## License

[CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) — free to use, share and adapt with attribution. Keep the two attribution lines inside the block.
