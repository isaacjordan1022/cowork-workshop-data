# Pack 1 — Messy Folder (File Organization Task)

## What's here

One file: `messy-folder.zip`. Unzip it and you'll get a folder of ~35 files with realistic operator chaos — invoice PDFs, receipt screenshots, meeting notes, random "untitled folder.zip" junk, some stray .xlsx and .csv exports, and text notes.

## The prompt

Unzip `messy-folder.zip` into your Downloads (or anywhere). Then paste this into Claude Cowork:

```
I just unzipped messy-folder into my Downloads. Inside are ~35 files from
the last three months with ugly auto-generated names.

Do three things:
1. Group files by type into subfolders (documents, images, zips, other)
2. Rename every file so the date is at the front in YYYY-MM-DD format
3. Write a short summary of what you moved and why, saved as MOVES.md
   in the parent folder.

If you hit a file you're unsure about, leave it where it is and flag
it in the summary.
```

## What good output looks like

- A clean subfolder structure
- Files renamed with YYYY-MM-DD prefixes where inferable
- A `MOVES.md` that explains every decision
- Unfamiliar files left alone and flagged for you to review

## One-pattern, many-uses

The same prompt shape works for sorting resumes by seniority, contracts by expiration, invoices by vendor, design assets by dimension, campaigns by quarter, and so on. Pick your folder, describe the grouping rule, ask for a summary.
