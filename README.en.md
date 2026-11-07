# SWE5001 Open-Book Exam Study Materials

[中文](README.md) | English

Personal study materials for the NUS SWE5001 Architecting Scalable Systems final open-book exam (2026-11-03). They cover all three parts of the course: Architecting Software Solutions, Platform Engineering, and Cloud Native Solution Design. Most content is written in Chinese, with key exam sentences in English.

**Read online:** https://juiceless.cn/swe5001-exam-handbook/

## Contents

| Path | What it is |
|---|---|
| [`book/`](book/) | **Bilingual review book** (web): 13 chapters with a quiz at the end of each (answers are collapsed; click to reveal), a question-by-question walkthrough of the three sample papers, and appendices: a cloud-service map across three providers, a Chinese–English glossary, and points from the lecturers' sessions |
| [`handbook/`](handbook/) | **Exam handbook** (web): exam strategy → question-type cards T1–T17 → model answers for the three sample papers → English writing toolkit → study notes and common mistakes → reference data, glossary and index |
| [`mock/`](mock/) | **Mock papers 1–2** (web): two self-written bilingual mock papers with reference answers, explanations and diagram legends |
| `pdf/SWE5001_中英对照复习书.pdf` | Review book, print version (149 pages, all answers expanded) |
| `pdf/SWE5001_考场答题手册.pdf` | Exam handbook, print version (87 pages) |
| `pdf/模拟卷1-2_合订本（中英对照+答案+技巧+图例）.pdf` | Two self-written mock papers (GreenCharge charging platform, TixNow ticketing platform), bilingual, with reference answers, common mistakes and diagram legends |
| `sample-exams/` | The three sample papers released by the course (PAST, PAST2, PAST3) with their Appendix A case studies, and the official sample solution and marking scheme for PAST |

## How to use

1. **Learn:** read chapters 1–13 of the review book, do the quiz at the end of each chapter, then reveal the reference answers.
2. **Practise:** attempt the three sample papers and check them against chapters 14–17 of the review book; for PAST, also compare with the official solution.
3. **In the exam:** the handbook is organised by question type. Identify the type (T1–T17) from the wording of the question, use the card's answer skeleton and sentence patterns, then take the numbers and use cases from the case-study appendix.
4. **Mock exams:** do the two mock papers under time pressure before reading the answers in the booklet.

Printing: black and white, double-sided, A4.

## Notes

- This is a personal interpretation of the course slides, sample papers and lectures, and may contain mistakes. Where it differs from the course slides, the slides take precedence.
- Appendix C.1 of the review book ("What the Lecturers Said") is a Chinese paraphrase based on transcripts of lecture recordings, not verbatim quotes. For exam logistics, the official exam letter takes precedence.
- The papers and solution in `sample-exams/` are course materials; copyright belongs to the course provider. They are shared here for study purposes only.
- For copyright or other concerns, please contact bibi45gt@gmail.com and I will address them or take the material down promptly.

**If these materials help you, please follow me on GitHub ([@bibi45c](https://github.com/bibi45c)) and give this repository a ⭐ star!**

## Deployment

On every push to `main`, GitHub Actions (`.github/workflows/pages.yml`) publishes the landing page, `book/`, `handbook/`, `mock/`, `pdf/` and `sample-exams/` to GitHub Pages.
