# 🧠 Application Map – Modular Logic Guide

This document outlines how the Modular Project Planner application is structured inside `/src`.

This guide will help you get up and running with the Modular Project Planner project as quickly and seamlessly as possible and how the Modular Project Planner application will be structured inside `/src`.

---

## 🔗 Exclusive Entry Point (Current Version)

### `app.md`
- Provides Information
- Lists different paths to choose from. No active functions are associated.

---

## 🔗 Next List of Releases that Will Be Available


### 🔗 Core Entry Point

### `app.py`
- Main orchestration layer
- Imports, chains, and triggers modules
- Coordinates between planning logic and API outputs (Flowise, Notion, etc.)

### 🔧 Subdirectories

### `functions/`
Reusable logic blocks:
- `date_utils.py` – cleans or validates date fields
- `validator.py` – applies sanity rules to parsed project data
- `logic_engine.py` – routes flags, contradictions, or access failures

#### `modules/`
Future-ready folders for:
- `timeline_builder.py`
- `checklist_generator.py`
- `micro_project_launcher.py`

#### `parsers/`
If you're pulling structured data (e.g., PDFs, form entries):
- Each parser can handle specific source types or input formats

---

## ⚙️ Logic Flow (example)

1. `app.py` pulls user input or pre-filled template
2. Validates w/ `validator.py`
3. Passes to `logic_engine.py`
4. Feeds result to appropriate generator (`checklist`, `timeline`, etc.)

---

## ✨ Next Milestone

MPP will route a micro-project intake through:
- Validation → Flagging → Optional Suggestion → JSON export

---

## 1. What's already done

1. Reviewed the README

2. Downloaded the zipfile for this repo.

If you haven't done that... 

## 2. Step??? 

Refer to Docs/phases.md for guidance on outlining your project’s major phases or milestones. Use that document to map out how you’ll move from planning to deployment.

## 3. Step????
Use ProjectTemplate.md (found in your template library) and the information from Docs/phases.md to assemble your README.md. This will serve as the main project overview, including:

---

## 4. Further Reading, Optimization & References

[....]

## 5. Coming Soon

[....]

---

© 2025 Missa.
Last updated: June 5, 2025