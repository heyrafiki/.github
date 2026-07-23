# Contributing

Thank you for contributing to Heyrafiki.

## Before you start

Read the repository README for its purpose, setup instructions, licence, and checks. Report security issues through the process in `SECURITY.md`, not through a public issue.

For a substantial change, open an issue first so the scope and approach can be agreed before implementation.

## Working on a change

1. Create a branch named `work/<short-description>`.
2. Keep the change focused on one problem.
3. Add or update tests for changed behaviour.
4. Run every check documented by the repository.
5. Remove debug output, temporary files, and unrelated changes.

## Two things we hold firmly

**User-facing words are reviewed line by line.** Labels, errors, empty states
and documentation are part of the product, and a maintainer will edit them.
That is not a comment on your writing; it is how we keep one voice.

**Nothing may weaken the separation between identity data and clinical data.**
A change that makes it easier to join the two, or that widens who can reach
clinical content, needs to say so plainly in the pull request. It may still be
right. It will not be merged quietly.

## Commit messages

Write complete sentences saying what changed and why. We do not use
Conventional Commits: this history is a public artifact, and `fix(ui): tweak`
tells a reader nothing.

## Pull requests

A pull request should explain what changed, why it changed, how it was verified, and any compatibility or security considerations.

Maintainers review contributions for correctness, safety, accessibility, interoperability, and fit with the repository's scope. A maintainer may ask for changes or close a proposal that does not fit that scope.

By contributing, you agree that your contribution is licensed under the repository's licence.
