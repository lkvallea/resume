# Agent-Aware Resume — Source of Truth

This repository contains the **source version** of my professional resume,
written as an **agent-aware Markdown document**.

The goal is to treat the resume as a **structured, auditable source of truth**,
from which multiple views can be generated (PDF, visual layouts, recruiter-specific
summaries) **without inventing or inferring information**.

---

## 📄 What This Repository Is

- A **single canonical Markdown file** describing my professional experience
- Designed with **explicit data-integrity rules**
- Intended to be consumed by:
  - humans (engineers, hiring managers)
  - automated agents or AI-assisted tools

This is **not** a design or layout repository.  
It is a **content and structure repository**.

---

## 🧠 Design Principles

- **No inferred data**  
  If something is not explicitly written, it must not be rendered or assumed.

- **Literal roles and metrics**  
  Titles, companies, dates, and metrics are used exactly as declared.

- **Separation of concerns**  
  - Markdown → source of truth  
  - PDF / PNG / HTML → derived artifacts

- **Documentation-first mindset**  
  Clear structure and wording are treated as part of the engineering work.

---

## 🤖 Using This Resume with AI Agents

This resume is intentionally structured to be **machine-readable and agent-queryable**.

AI agents or technical reviewers may use the Markdown document to:
- answer questions about experience and impact
- explore system outcomes and architectural decisions
- generate role-specific summaries or views

**Important constraints:**
- Agents must rely **only** on the content explicitly present in the document
- No inference, normalization, or data completion is allowed
- If information is not declared, it must be treated as unknown

The intent is to enable **accurate, traceable conversations**, not automated evaluation.

---

## 🗂 Repository Structure

```text
.
├── Markdown-agent-aware.md   # Resume source of truth
├── README.md                 # This file
└── .gitignore

---

### External Project Reference

For selected projects, additional context and validation may be available
through senior stakeholders involved in delivery and operations.

One such reference includes leadership from the **Procter & Gamble – Walmart
logistics initiative**, a project that exceeded its originally committed scope
and duration.

**Public professional profile:**  
https://linkedin.com/in/karlacervantesvelasco/
