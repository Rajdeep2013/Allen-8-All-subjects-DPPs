# Daily Practice Pack — Guide

## What's included
The ZIP archive contains:
- `dpp_practice_app.html` — offline browser-based daily quiz app.
- `question_bank.json` — 35 auto-checked questions, each still marked for verification.
- `question_bank_TEMPLATE.json` — JSON import template for adding verified questions.
- `inventory.csv` — chapter, PDF page and DPP-sheet inventory.
- `extracted_text/` — extracted text for the 24 source PDFs.
- `scripts/` — parsing and candidate-building helpers.
- `PLAN.md` and `README.txt` — project notes and quick-start instructions.

## Source inventory
| Subject | PDF files | Pages | DPP sheets with solutions | Questions in app |
|---|---:|---:|---:|---:|
| Physics | 6 | 184 | 37 | 8 |
| Chemistry | 4 | 145 | 42 | 5 |
| Mathematics | 9 | 261 | 55 | 3 |
| Biology | 5 | 100 | 36 | 19 |
| **Total** | **24** | **690** | **170** | **35** |

## Run the app
1. Download and extract [DPP_Daily_Practice_Pack.zip](../DPP_Daily_Practice_Pack.zip).
2. Open `dpp_practice_app.html` in a modern browser.
3. Start today's set. The intended schedule is up to five questions per subject per day.
4. Use the revision queue for mistakes.
5. Import additional questions only after verifying the question, options, answer and explanation against the original PDF pages.

## Accuracy and completion status
The pack's own project plan states that automatic extraction can misalign question stems and answer keys. Therefore, only 35 questions passed the described consistency checks and are currently in the app; they remain labelled for user verification. The approximately 600 other candidate MCQs are not verified. The 170 DPP sheets and 24 PDFs are represented in the inventory. The app is functional, but the full question bank is not complete.

## Subject chapter index
- **Physics:** Electricity; Force and Laws of Motion; Gravitation; Magnetic Effects of Electric Current; Motion; Work, Energy and Power.
- **Chemistry:** Atoms and Molecules; Carbon and Its Compounds; Metals and Non-Metals; Structure of the Atom.
- **Mathematics:** Absolute Value Function; Circles; Coordinate Geometry; Linear Equations in Two Variables; Linear Inequality; Number System; Polynomials; Quadratic Equations; Trigonometry and Its Applications.
- **Biology:** Cell; Control and Coordination; Heredity; Reproduction in Human; Tissue.

## Progress storage
The app stores progress in the browser's local storage. It is local to that browser/device; clearing browser site data may erase it. The app can run offline after extraction.
