# Contributing

Thanks for helping. A few rules keep the history clean and the supply
chain trustworthy.

## Before you start

Open an issue for anything larger than a small fix, so the approach can be
agreed before you write the code.

## Commits

- Sign every commit (GPG, SSH or S/MIME). Unsigned commits cannot be
  merged.
- Add a Developer Certificate of Origin sign-off to every commit with
  `git commit -s`. It certifies you have the right to submit the change
  under the project licence (https://developercertificate.org).
- Use Conventional Commits: `type(scope): subject`, for example
  `fix(agent): retry the runner config fetch`.

## Pull requests

- One logical change per pull request.
- Write commit bodies and pull request descriptions the way Linux kernel
  commit messages are written: plain paragraphs wrapped at about 72
  columns, starting with the problem, then what the change does about
  it and the trade-offs. No headings, no restating the diff.
- CI must pass. New behaviour needs tests.

## Licence

Contributions are accepted under the Apache License, Version 2.0, the
licence of every hatchrun repository.
