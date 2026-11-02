# Release Notes Style

Applies to every repository in this organisation unless a repository overrides it with its own `RELEASE_NOTES_STYLE.md`.

## Convention: GitHub's default, unedited

Use `gh release create --generate-notes` (or `release: { generate_release_notes: true }`) as the release body, unedited.

Write a good PR title; that title is the release note, there's no second draft.

## What NOT to do

- Don't hand-author root-cause/consequence paragraphs per change.
- Don't add a manual "edit the generated notes to match convention" step to a release pipeline.
- Don't mention user data, user counts or anything about individual users in a release note.
