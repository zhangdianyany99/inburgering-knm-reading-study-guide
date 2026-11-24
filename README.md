# Dutch Inburgering (A2 / B1) KNM & Reading Study Guide

Open study notes, exam format specifications, and a lightweight JSON schema for practicing the Dutch Civic Integration (*Inburgering*) exams administered by **DUO**.

> Live reference implementation & free 10-question diagnostic: **[InburgeringMock](https://inburgeringmock.com/)**

## Exam Structure Overview

| Module | Items | Duration | Scope | Reference |
| :--- | :---: | :---: | :--- | :--- |
| **KNM** (*Kennis van de Nederlandse Maatschappij*) | 40 | 45 min | Work & income (UWV), healthcare (*huisarts*, *eigen risico*), housing, Dutch law & history | [KNM Practice Exam](https://inburgeringmock.com/knm-practice-exam) |
| **Lezen A2** (Reading A2) | 25 | 65 min | Official letters, municipal notices, workplace instructions | [Reading A2 Practice Exam](https://inburgeringmock.com/reading-a2-practice-exam) |
| **DUO 2026 Rules** | — | — | *Wet inburgering 2021* (B1 default / Z-route / Onderwijsroute) vs. A2 naturalization path | [DUO 2026 Rules Guide](https://inburgeringmock.com/guide/duo-2026-rules) |

## Bilingual Question Schema (Dutch Prompt + English Rationale)

```json
{
  "id": "knm-uwv-01",
  "module": "knm",
  "cefr": "A2",
  "stemNl": "Samira verliest haar baan omdat het bedrijf dichtgaat. Waar vraagt zij een WW-uitkering aan?",
  "options": [
    { "id": "A", "textNl": "Bij de gemeente" },
    { "id": "B", "textNl": "Bij het UWV" },
    { "id": "C", "textNl": "Bij de Belastingdienst" },
    { "id": "D", "textNl": "Bij DUO" }
  ],
  "correctId": "B"
}
```

## Official Primary Sources
- [DUO Inburgeren](https://www.inburgeren.nl/)
- [Rijksoverheid — Civic Integration](https://www.government.nl/topics/integration-in-the-netherlands)
