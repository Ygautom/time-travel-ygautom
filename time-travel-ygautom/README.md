# Time-Travel Zine

I am learning disciplined Git workflows by making a small zine about a **time machine**.  
This repo demonstrates branches, issues, PRs, tags, and conflict resolution.

## Branch Strategy
- `author/idea-sprint`: Draft and iterate on content as the "Author".
- `editor/review`: Perform editorial passes and propose changes as the "Editor".

## .gitignore Rationale
- `target/` — Maven build outputs that should not be committed.
- `.DS_Store` — OS-specific metadata that doesn't belong in version control.

## Branching Workflow

- **main** – Finalized and stable content after all merges.  
- **author/idea-sprint** – Used for drafting and developing new zine ideas and early writing.  
- **editor/review** – Used for proofreading, formatting, and approving final versions before merging into `main`.  
- **feat/layout** – Adjusts formatting and structure of the zine.  
- **feat/content** – Adds or edits written sections.  
- **feat/polish** – Handles cleanup, grammar, and final polish before release.

