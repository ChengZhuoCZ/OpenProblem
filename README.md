# OpenProblem

This repository stores problem sets and related metadata.

## Structure

- `question-sets/`: Question set files, grouped by subject, grade, exam, or topic.
- `templates/`: Reusable templates for new question sets.
- `metadata/`: Shared metadata definitions and notes.

## Current Collections

- `question-sets/open-problems/`: Research-style mathematical open problems imported from `problem_markdown_archive(2).zip`.

For open problems, each problem is maintained as a directory:

```text
problem-001/
  problem.md
  progress.md
```

- `problem.md` stores the problem statement and mathematical formulation.
- `progress.md` stores the current progress, open clarifications, next actions, and work log.

## Suggested File Naming

Use clear, sortable names:

```text
subject-grade-topic-version.md
math-grade-9-quadratic-equations-v1.md
english-cet4-reading-2026-01.md
```

## Question Set Workflow

1. Copy `templates/question-set.md`.
2. Rename it using the naming convention above.
3. Fill in metadata, questions, answers, and scoring notes.
4. Commit related changes together.

## Open Problem Workflow

1. Add or update the problem statement in `problem.md`.
2. Record current research state in `progress.md`.
3. Update `question-sets/open-problems/index.md` when adding a new problem or changing status.
4. Commit problem and progress changes together.
