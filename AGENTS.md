# AGENTS: Repo Conventions, Scope, and Roadmap

This repository is a Markdown-native knowledge base for a sole proprietor (individual business owner) to reach Bookkeeping Grade 3 level understanding and to self-complete blue tax return (青色申告) bookkeeping. Content is designed for GitHub-first reading: concise, link-rich, with Mermaid diagrams and GitHub callouts.

## Authoring Conventions

- Content format: Markdown only. Viewable on GitHub without extra tooling.
- Diagrams: Prefer Mermaid for flows and relationships.
- Callouts: Use GitHub-style blocks `> [!NOTE]`, `> [!TIP]`, `> [!IMPORTANT]`.
- Tone: Concise, practical, actionable. Prioritize checklists, examples, and tables.
- Links: Always add relative links to related pages at the end of a file.
- Scope: Target is 個人事業主 with a path to 簿記3級 + 青色申告の実務。

## Directory Structure (Current)

- `overview/`
  - `bookkeeping-flow.md` — End-to-end accounting cycle with daily/monthly/yearly flows. [exists]

- `basics/`
  - `what-is-bookkeeping.md` — What is bookkeeping, core principles, cycle, ledgers. [exists]
  - `journal-entries.md` — Journal entry rules, accrual basis, three-part method (三分法), templates. [exists]
  - `accounting-equation.md` — A = L + E and profit linkage; adjusting concepts. [exists]

- `daily-activities/`
  - `daily-activities.md` — Daily tasks, evidence handling, quick checks. [exists]
  - `account.md` — Five elements (五要素), debit/credit rules, relationship diagrams. [exists]
  - `difference-between-balance-sheet-and-income-statement.md` — Balance sheet vs income statement overview. [exists]
  - `examples-of-daily-activities.md` — Practical cases: credit card, AR/AP, depreciation, sale/disposal. [exists]

- `what-to-do-every-month/` (aka monthly-operations)
  - `what-to-do-every-month.md` — Monthly checklist, flow, KPIs, reconciliation. [exists]
  - `trial-balance.md` — How to build and verify trial balance; AR/AP/Bank reconciliation. [exists]
  - `closing-checklist.md` — Month-end verification and common errors. [exists]

- `blue-tax-return/`
  - `types-of-accounting-books.md` — Required books for blue tax return and year-end. [exists]
  - `closing-entries.md` — Year-end adjustments for freelancers; depreciation, accruals, allocations. [exists]
  - `tax-return-timeline.md` — Dec–Mar workflow checklist. [exists]
  - `inventory-and-cogs.md` — Inventory count, COGS (期首+仕入−期末), 三分法総まとめ. [exists]
  - `blue-return-flow.md` — Blue return statements (P/L, B/S) preparation, e-Tax steps, retention. [exists]

- `consumption-tax/`
  - `README.md` — Section index and reading flow. [exists]
  - `overview.md` — Basics, scope, and obligation checks. [exists]
  - `taxable-vs-exempt.md` — Taxable vs exempt business rules. [exists]
  - `invoice-system.md` — Invoice system requirements and impact. [exists]
  - `calculation-methods.md` — Standard vs simplified, 2/10 special rule. [exists]
  - `journal-examples.md` — Tax-inclusive/exclusive journal examples. [exists]

- `reference/`
  - `chart-of-accounts.md` — Catalog of accounts + expense eligibility guide. [exists]
  - `document-management.md` — Evidence collection, naming, retention periods. [exists]
  - `glossary.md` — Key terms and definitions. (planned)

- `practice/`
  - `quiz-journal-entries.md` — Journal drills with answers. (planned)
  - `trial-balance-exercises.md` — Trial balance build/check problems with answers. (planned)
  - `adjusting-entries-exercises.md` — Year-end adjustments set with solutions. (planned)
  - `financial-statements-exercises.md` — Build P/L and B/S from a trial balance. (planned)

- `templates/`
  - `monthly-report-template.md` — KPI + commentary template. (planned)
  - `ap-ar-aging.md` — AR/AP aging worksheet. (planned)
  - `checklists.md` — Daily/Monthly/Yearly checklists consolidated. (planned)

## Content Style

- Lead with purpose → checklist → steps → examples → related links.
- Use tables for decision rules and templates; prefer concrete numbers in examples.
- Use Mermaid sparingly to visualize flows and relationships; add short captions.
- Keep repeated explanations in Basics; keep Daily/Monthly/Yearly pages focused on execution.

## Roadmap (Next Tasks)

High priority
1. Add `reference/glossary.md` — 用語集（売掛/買掛/未払/前払/控除/課税/免税 等）
2. Add `practice/quiz-journal-entries.md` — 20問（初級→3級）＋解答・解説
3. Add `practice/trial-balance-exercises.md` — 2セット（CSV/表）＋解答

Medium priority
4. Add `practice/adjusting-entries-exercises.md` — 決算整理1セット＋解答
5. Add `practice/financial-statements-exercises.md` — P/L・B/S作成問題＋解答
6. Add `templates/monthly-report-template.md` — 指標（売上、粗利、費用、利益、現金）と所感欄

Templates
7. Add `templates/ap-ar-aging.md` — 滞留日数・回転率を見える化
8. Add `templates/checklists.md` — 日次・月次・年次のチェックリスト総覧

Polish & Cross-linking
9. Add profitable asset sale example to `daily-activities/examples-of-daily-activities.md`.
10. Cross-link Basics ↔ Daily/Monthly/Yearly pages consistently.
11. Ensure all pages end with a Related Links section.

## Contribution Notes

- Keep changes minimal and focused; avoid large rewrites unless scoped.
- Match existing style (tables, callouts, Mermaid). Japanese as primary language.
- Validate numbers in accounting examples; prefer single-entry settlement for disposal/sale cases.

## Related Project (Planned Coordination)

The following app will be maintained alongside this repo. This knowledge base provides the “what is bookkeeping” foundation for users of that app, and future updates should keep terminology and examples aligned.

- https://github.com/shuji-bonji/e-shiwake
- https://shuji-bonji.github.io/e-shiwake/
