# Project Instructions

## Language

- Communicate with the user in German unless requested otherwise.
- Keep all application UI, code, documentation, filenames, tests, and Git history in English.
- Do not add new German application copy. Translate German requirements into natural English project content.

## Repository Context

- This repository currently contains the exported Walking Codex web preview rather than the maintainable application source.
- Prefer implementing future product changes in the source repository once it becomes available.
- If an urgent preview-only bundle change is required, document it and verify the published artifact carefully.
- Never commit `.codex-remote-attachments/`.

## Completion Gate

1. Inspect the current Git status and preserve unrelated user changes.
2. Validate modified JavaScript and check the relevant UI behavior.
3. Verify mobile layouts at 390 px and 320 px widths when UI changes.
4. Check browser warnings, errors, failed requests, overflow, and persistent navigation.
5. Update the relevant persistent project documentation.
6. Commit completed changes with an English commit message.
7. Push completed changes directly to `main` unless the user explicitly requests another workflow.
8. Wait for GitHub Pages to publish the new revision and verify the production application in a browser.

## Final Response

- Summarize the result, validation, documentation, commit, push, and deployment status in German.
- Always make the verified GitHub Pages URL the final item in the response:
  `https://nihansbu.github.io/walking-codex-preview/`
