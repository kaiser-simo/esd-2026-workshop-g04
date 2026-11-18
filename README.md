# GitHub Actions — Calculator CI hands-on

Browser-only exercise for the ESD workshop on **18 November 2026**. Students work in pairs, fork this repository, and observe automated tests passing, failing, and passing again.

**[Start the pair exercise](WORKSHOP_HANDS_ON.md)**

## Project files

- `site/calculator.js`: calculator addition function
- `tests/calculator.test.js`: four automated tests
- `.github/workflows/ci.yml`: GitHub Actions workflow running `npm test` on `main` pushes and pull requests

Local development is optional: run `npm test` with Node.js to execute the same tests.

## Presenter note

This default-branch exercise is separate from the live CI/CD demonstration on `feature/ci-cd-demo`. Do not merge the demo branch into `main` as part of this exercise.
hello
