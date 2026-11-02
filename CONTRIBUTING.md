# Contributing

Thanks for considering it. These guidelines apply to every repository in this
organisation unless a repository overrides them with its own
`CONTRIBUTING.md`.

## Health data comes first

Ebbwise handles personal health data. Whatever you change:

- Never put real health data in an issue, pull request, test fixture or log.
  Use made-up values.
- Never log or store a health value in plaintext. Each repository's
  `AGENTS.md` lists the invariants that protect this.
- User-facing wording describes patterns in a person's own data. It never
  diagnoses, predicts flares, scores disease activity or gives treatment
  advice.

## You don't need to write code

Much of what the project needs is lived experience, not programming:

- Telling us where logging is too much work on a bad day
- Checking that wording reads as neutral and supportive
- Reporting a pattern the app shows that doesn't match what you know

Open an issue describing what you noticed.

## Pull requests

1. Branch from the default branch.
2. Keep a pull request to one concern.
3. Use Conventional Commits for the PR title (`feat: ...`, `fix: ...`); it
   becomes the squash-merge commit and the release note.
4. Describe what you changed and how you verified it.

## Licensing

The repositories are private and not yet licensed for reuse. Contributions
are accepted on the understanding that they become part of the project
under whichever licence it later adopts.
