---
applyTo: "assignments/**/*.md"
---

# Assignment Markdown Structure Guidelines

All assignment markdown files should follow these guidelines:

## 1. Template Usage

- Assignment markdown files must follow the structure in [`templates/assignment-template.md`](../../templates/assignment-template.md).
- The assignment must be created as a `README.md` file
- Do not remove or skip required sections from the template.

## 2. Section Guidance

The section headers should reflect the structure in the template, including the exact icon usage.

- **Title**: Replace `[Assignment Title]` with a short, descriptive name (e.g., `Python Basics`, `Loops and Conditionals`, `Functions and Modules`).
- **Objective**: Write 1-2 sentences summarizing what the student will learn or accomplish. Focus on the main skills or concepts.
- **Tasks**: For each task:
   - Use a specific, action-oriented task name
   - In the Description, clearly state what the student must do.
   - In Requirements, use bullet points to list the expected outcomes or features. Be specific and measurable
   - Provide example input/output in code blocks if helpful.

Do not include extra sections unless explicitly specified.

# Assignment Folder Instructions

## Purpose
This file provides guidelines for creating and maintaining assignment folders in this repository.

## Folder Structure
- Each assignment should have its own subfolder under `assignments/`.
- Each assignment folder should include:
  - `README.md`: Assignment description, objectives, and instructions for students.
  - `starter-code.py` (or relevant starter file): Starter code for students to begin their work.
  - Any required data files (e.g., `data.csv`).

## Naming Conventions
- Use descriptive, lowercase, hyphen-separated names for assignment folders (e.g., `data-analysis`).
- File names should be clear and indicate their purpose.

## Content Guidelines
- Ensure all instructions are clear and student-friendly.
- Include learning objectives and expected outcomes.
- Provide sample input/output if relevant.
- Avoid ambiguous or overly complex language.

## Example Assignment Folder
```
assignments/
  data-analysis/
    README.md
    starter-code.py
    data.csv
```

## Review Process
- Review new assignments for clarity, completeness, and alignment with educational standards before adding them to the repository.
