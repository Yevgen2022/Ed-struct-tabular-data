# Tabular Data Representation

A project focused on building a fully semantic HTML table structure to represent shopping data. The task emphasized proper use of table sections (caption, thead, tbody, tfoot), merged rows and columns, and use of `<colgroup>` for column-level styling or grouping.

## Live Demo
[Click here to view](https://structuring-tabular-data-f0b5ea.gitlab.io)

---

## Key Concepts Applied

- Created a semantic HTML table with `<caption>`, `<thead>`, `<tbody>`, and `<tfoot>`
- Used `<th scope="col">` for all column headers to improve accessibility and screen reader support
- Merged cells using `rowspan` and `colspan` to reflect proper data structure
- Grouped specific columns using `<colgroup>` and `<col>` for layout clarity
- Applied layout logic with `rowspan="2"` for the "Name" cell and `colspan="3"` for the "Purchases" label
- Added a "Total" row using `<tfoot>` and `colspan="2"` to summarize the data

---

## Technologies

- HTML5
- Tables: `<table>`, `<caption>`, `<thead>`, `<tbody>`, `<tfoot>`
- Column grouping: `<colgroup>`, `<col>`
- Row/column spanning (`rowspan`, `colspan`)
- GitLab Pages

---

## Task Instructions

See [REQUIREMENTS.md](./REQUIREMENTS.md) for the original task description used in this training challenge.
