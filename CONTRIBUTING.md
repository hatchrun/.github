# Contributing

Thanks for helping. A few rules keep the history clean and the supply
chain trustworthy.

## Issues, not pull requests

Only collaborators can open pull requests in hatchrun repositories. A
pull request from a fork runs code from an unknown author next to the
project's CI and release pipeline, and hatchrun builds the images and
binaries that run other people's jobs, so the project does not accept
that risk.

To report a bug or propose a change, open an issue. Describe what you
saw, what you expected and how to reproduce it, or the problem a
feature would solve. A maintainer writes the change. Security problems
go through the private process in [SECURITY.md](SECURITY.md) instead.

The rest of this document applies to collaborators.

## Commits

- Sign every commit (GPG, SSH or S/MIME). Unsigned commits cannot be
  merged.
- Add a Developer Certificate of Origin sign-off to every commit with
  `git commit -s`. It certifies you have the right to submit the change
  under the project licence (https://developercertificate.org). The
  `dco` check fails a pull request with any commit missing a sign-off
  that matches its author; fix it with `git rebase --signoff -S main`
  and force-push.
- Use Conventional Commits: `type(scope): subject`, for example
  `fix(agent): retry the runner config fetch`.

## Pull requests

- Open an issue for anything larger than a small fix, so the approach
  can be agreed before you write the code.
- One logical change per pull request.
- Write commit bodies and pull request descriptions the way Linux kernel
  commit messages are written: plain paragraphs wrapped at about 72
  columns, starting with the problem, then what the change does about
  it and the trade-offs. No headings, no restating the diff.
- CI must pass. New behaviour needs tests.

## Licence

Contributions are accepted under the Apache License, Version 2.0, the
licence of every hatchrun repository.
