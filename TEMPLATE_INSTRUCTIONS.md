# Setting up a new subteam repo

**Delete this file when setup is done.**

## Setup checklist

1. Create the repo with **Use this template -> Create a new repository** (owner: AguaClara). Do not fork.
2. Name it in `kebab-case` (i.e. all lowercase and spaces replaced with hyphens) matching the team name, and add a one-line description in the repo's "About" box.
3. Edit [`README.md`](README.md): replace every `[BRACKET]`, fill in the current technical advisor, subteam lead, and team roster.
4. Copy the example semester folder [`YY-N-SS`](YY-N-SS/) and rename it to the current semester (see below).
5. Delete this file.

## Semester folder naming

**Format:** `YY-N-SS`

| Season | N | Example |
| --- | --- | --- |
| Spring | 1 | `2026-1-SP` |
| Summer | 2 | `2026-2-SU` |
| Fall | 3 | `2026-3-FA` |

This sorts chronologically in GitHub's file listing.

## Every new semester

1. Copy the example semester folder [`YY-N-SS`](YY-N-SS/) and rename it.
2. Update the "Contact Information" section in the main [`README.md`](README.md).
3. Add a new section at the **top** of the "Semesters" list in [`README.md`](README.md). Do not remove old semesters.
4. Throughout the semester, upload reports and presentations (PDF plus editable version) and update the [`README.md`](README.md) links.

## Deliverable file naming

`YYYYSS-Team-Document.ext`, where SS is SP, SU, or FA. Examples:

- `2026SP-UASB-Final-Report.pdf` and `2026SP-UASB-Final-Report.docx`
- `2026SP-UASB-Symposium.pdf` and `2026SP-UASB-Symposium.pptx`

Use hyphens in place of spaces.

## Commit messages

Simple upload: one line describing the file, e.g. `Add Spring 2026 final report`.

Larger changes:

```
A brief one-line description of the changes made

- A bulleted list of details about the changes (leave the blank line above!)
- More information about the changes
```

## What not to commit

- Files over 100 MB (GitHub rejects them). Link large videos or datasets from the README instead.
- Personal information beyond what team members have agreed to list in the README.
