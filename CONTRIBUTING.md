# Contributing to Loomux

Thanks for looking. Loomux is pre-alpha and maintained by one person, so
reviews and answers are best effort. This is the default guide for
every Loomux repository; a repository with its own `CONTRIBUTING.md`
(such as [loomux/server](https://github.com/loomux/server/blob/main/CONTRIBUTING.md))
adds its specifics there.

## Which repository

- [loomux/server](https://github.com/loomux/server): the server, its
  API, the agent and plugin images, and most bugs.
- [loomux/web](https://github.com/loomux/web): the browser client.
- [loomux/tui](https://github.com/loomux/tui): the terminal client.

If you aren't sure, open the issue on loomux/server.

## What's welcome before 1.0

- **Bug reports** with what you ran, what happened and how to make it
  happen again.
- **Fixes** for bugs, with a test that fails without the fix.
- **Docs** that were wrong, unclear or missing when you set Loomux up.

Please **open an issue before you write a feature** or anything that
changes the API: a short issue saves you a pull request that can't be
merged. Loomux is single-user by design for now.

## Security problems

Don't report a vulnerability in a public issue, pull request or
discussion. Follow the repository's `SECURITY.md`.

## Making a change

- Each repository's README says how to build it, and its CI workflows
  (`.github/workflows/`) show the checks a pull request must pass. Keep
  them green: every merge to `main` is released.
- **One change per pull request**, small enough to review in one
  sitting. Say what it fixes or adds and how you tested it.
- A change users would notice adds a changelog fragment,
  `changes/<slug>.md`, where the repository has a `changes/` directory,
  instead of editing `CHANGELOG.md`.

## Licence, CLA and DCO

Loomux is under the MIT licence, and your contribution is accepted under
the same licence. There is **no CLA** to sign. A
[Developer Certificate of Origin](https://developercertificate.org/)
sign-off (`git commit -s`) is welcome but not required.
