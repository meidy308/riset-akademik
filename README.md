# 🎓 Riset Akademik: LLM-Powered Research Wiki

A structured, AI-maintained knowledge base for academic research, built in Obsidian. This repository serves as a centralized hub for ingesting, synthesizing, and querying academic literature, frameworks, and methodologies.

## 🌟 Overview

The **Riset Akademik** (Academic Research) wiki uses a semi-automated workflow where a human researcher provides raw sources, and an AI assistant (LLM) maintains the systematic organization of knowledge. The goal is to create a high-fidelity, cross-referenced web of concepts, entities, and summaries.

## 📂 Repository Structure

The repository is organized following a strict schema to ensure data integrity and ease of navigation:

| Directory | Description |
| :--- | :--- |
| `raw/` | **Immutable Source Documents.** Contains PDFs, transcripts, and raw notes. *Excluded from Git.* |
| `wiki/` | **The Knowledge Base.** Contains all AI-generated and maintained markdown files. |
| ∟ `concepts/` | Definitions and mechanics of specific research frameworks or theories. |
| ∟ `entities/` | Profiles of researchers, tools, and organizations. |
| ∟ `summaries/` | Structured breakdowns of individual raw sources. |
| ∟ `syntheses/` | Comparative analyses and cross-cutting frameworks. |
| ∟ `journal/` | Session logs and research progress notes. |
| ∟ `index.md` | The central Table of Contents. |
| ∟ `log.md` | Audit trail of all wiki modifications. |

## 🛠 Workflow

1. **Adding Sources**: New research or sources are added to the `raw/` folder.
2. **Ingestion**: The AI assistant reads the source, discusses key takeaways, creates summary, concept, entity, and synthesis pages, and interlinks them using `[[wiki-links]]`.
3. **Tracking**: All changes are tracked in the `wiki/index.md` and `wiki/log.md`.
4. **Analysis & QA**: The user can ask questions, and the AI will synthesize answers, citing specific wiki pages and sources.

---
## 📝 Guidelines for Use

- **Obsidian Support:** This repository is optimized for [Obsidian](https://obsidian.md/). Use `[[wiki-links]]` for navigation.

## Disclaimer
The files in the `raw/` folder, `.obsidian/` folder, and other specific user resources are excluded via `.gitignore` to maintain a clean repository specifically focused on the curated wiki content.


