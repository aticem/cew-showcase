# CEW — Construction Engineering Workflow

> 🔒 **Showcase repository.** The source code lives in a private repo; this page explains what the
> platform does and how it is built. Code walkthrough available on request — [LinkedIn](https://www.linkedin.com/in/acsamiloglu/).

The umbrella platform for utility-scale solar / BESS construction: **progress tracking**, **QA/QC**,
and an **AI assistant** that answers questions over a project's own documents. It ties together the
site's GIS layout, the daily field data and the document control so that "where are we, and is it
right?" can be answered in one place.

**Why:** on site, progress, quality records and the paperwork that proves them all live in separate
tools and spreadsheets. CEW brings them under one roof and lets you ask questions directly against
the project's documents instead of hunting through folders.

---

## ✨ Features

### Construction progress tracking
- Map-based progress per work package, built on the site's own GIS (GeoJSON) layout.
- Click / lasso items on the layout to mark them done; daily logs, progress stats, history and export.

### QA/QC
- Inspection and test records tied to the physical assets on the site layout.
- Status and completion rolled up so quality progress is visible alongside construction progress.

### AI document assistant
- Ask natural-language questions over project documents — **RAG with OCR** so scanned PDFs are searchable.
- Answers stay grounded in the source documents rather than guessing.
- An **evaluation harness** scores answer quality so the assistant can be tuned and trusted.

---

## 🧰 Tech stack
Next.js · TypeScript · Supabase · Python AI service · Vertex AI / Gemini · Docker

---
<sub>More projects on my [GitHub profile](https://github.com/aticem).</sub>
