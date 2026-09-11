<!-- Template: replace every {{...}} placeholder, then delete this comment.
     Sections wrapped in OPTIONAL comment blocks stay hidden until they apply
     (Conventional Commits, a CI package matrix) — uncomment them then. -->

# Contributing to {{Project name}}

We really appreciate and value contributions to {{Project name}}. Please take 5' to review the
items listed below to make sure that your contributions are merged as soon as possible.

For ANY of the items below, if they seem too complicated or hard, you can always ask for help
from us. We love that you are helping us, and we would love to help you back!

## Opening an issue

Before starting development, please
[create an issue](https://github.com/OpenZeppelin/{{repo}}/issues/new/choose) to open the
discussion, validate that the change is wanted, and coordinate overall implementation details.

## Creating Pull Requests (PRs)

As a contributor, you are expected to fork this repository, work on your own fork and then
submit pull requests. The pull requests will be reviewed and eventually merged into the main
repo. See ["Fork-a-Repo"](https://help.github.com/articles/fork-a-repo/) for how this works.

## Code quality standards

Coding conventions live in [`GUIDELINES.md`](GUIDELINES.md) — the single source of truth for
naming, section ordering, idioms, testing and documentation — with the design rationale and
constraints in [`ARCHITECTURE.md`](ARCHITECTURE.md). Read both before opening a PR. The items
below are the hard gates your contribution must clear:

- **Test coverage**: minimum {{N}}% coverage required.
- **Linting**: all code must pass strict linting (`{{lint command}}`).
- **Conventions**: follow [`GUIDELINES.md`](GUIDELINES.md).
- **Documentation**: add inline documentation for every public API, formatted per
  [`GUIDELINES.md`](GUIDELINES.md).

## Commit and PR conventions

The single source of truth for how changes land — humans and agents follow the same rules:

- **Sign every commit.** Configure commit signing before your first contribution; unsigned
  commits will not be merged.
- **Never add a `Co-Authored-By` trailer for an AI assistant.** Add one only for a human
  co-author. You are accountable for what you submit and sign with your own name; an AI
  assistant is a tool, and a tool does not co-author.
- Keep the subject line short and imperative, and explain the *why* in the body when it is not
  obvious from the diff.
- Begin the PR body with "Fixes #123" or "Resolves #123" to link the PR to the issue it
  resolves.
- When you make a user-facing change, record it in [`CHANGELOG.md`](CHANGELOG.md) under
  `## Unreleased`, grouped by change type (`### Added` / `Changed` / `Fixed` / ...), following
  [Keep a Changelog](https://keepachangelog.com/), and reference the PR number.

<!-- OPTIONAL — uncomment if this repository adopts Conventional Commits. It is deliberately
     not a default: it is not currently mandated across OpenZeppelin ecosystem repos.

- Use [Conventional Commits](https://www.conventionalcommits.org/en/v1.0.0/) (`type(scope): summary`)
  for commit messages.

-->

<!-- OPTIONAL — uncomment once CI builds packages from an explicit matrix:

- When you add a new package, register it in the CI package matrix in the same PR. The matrix
  is the only thing that builds, lints and tests a package in CI; a package missing from it is
  silently never checked, so its tests do not gate merges.

-->

## AI-assisted contributions

Using an AI assistant to prepare a contribution is fine. What does not change is who is
answerable for the result:

- **You are responsible for the quality of everything you submit, whatever tools produced it.**
  Read, understand and test the code before opening a PR — if you cannot explain why a change
  is correct, it is not ready.
- **Respect reviewers' time.** Review bandwidth is the scarcest resource in this project, and
  an unreviewed generated diff spends it faster than anything else.
- **Do a local review pass before requesting a human one.** Run the tests, the linter and the
  repository's own quality command (see [`AGENTS.md`](AGENTS.md) for the agent setup) and act
  on what they report.

Low-quality submissions are closed without further explanation.

## A typical workflow

1. Make sure your fork is up to date with the main repository:

   ```sh
   cd {{repo}}
   git remote add upstream https://github.com/OpenZeppelin/{{repo}}.git
   git fetch upstream
   git pull --rebase upstream main
   ```

   > NOTE: The directory `{{repo}}` represents your fork's local copy.

2. Branch out from `main` into `fix/some-bug-short-description-#123`
   (ex: `fix/typos-in-docs-#123`):

   (Postfixing #123 will associate your PR with the issue #123 and make everyone's life
   easier =D)

   ```sh
   git checkout -b fix/some-bug-short-description-#123
   ```

3. Make your changes, add your files, update documentation, commit (signed) and push to your
   fork.

   ```sh
   git add .
   git commit -S -m "some bug short description #123"
   git push origin fix/some-bug-short-description-#123
   ```

4. Run the tests and the linter locally and make sure they pass. For external PRs, the checks
   on GitHub run once a maintainer approves them.

   ```sh
   {{build command}}
   {{test command}}
   {{coverage command}}
   {{lint command}}
   ```

5. Go to [OpenZeppelin/{{repo}}](https://github.com/OpenZeppelin/{{repo}}) in your web browser
   and issue a new pull request. _IMPORTANT_: read the PR template carefully and follow all of
   its instructions — they refer to conditions your PR must meet in order to be accepted, such
   as making sure that all PR checks pass.

6. Maintainers will review your code and possibly ask for changes before it is pulled into the
   main repository. We'll check that all tests pass, review the coding style, and check for
   general code correctness. If everything is OK, we'll merge your pull request and your code
   will be part of {{Project name}}.

   _IMPORTANT_: please pay attention to the maintainer's feedback, since it's a necessary step
   to keep up with the standards this project attains to.

## Tests

If you are introducing a new feature, please add a new test to ensure that it works as
expected. Unit tests are mandatory for each new feature. If you are unsure about whether to
write an integration test, you can wait for the maintainer's feedback.

## All set

If you have any questions, feel free to post them as an
[issue](https://github.com/OpenZeppelin/{{repo}}/issues).

Finally, if you're looking to collaborate and want to find easy tasks to start, look at the
issues we marked as
["Good first issue"](https://github.com/OpenZeppelin/{{repo}}/labels/good%20first%20issue).

Thanks for your time and code!
