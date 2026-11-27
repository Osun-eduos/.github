# Contributing to Osun EduOS

Thank you for helping build better education infrastructure for Osun State. You don't need to write code to contribute: feedback from teachers, school heads, Ministry officers and parents is just as valuable.

This guide applies to every repository in the [Osun-eduos](https://github.com/Osun-eduos) organisation. A repository's own README may add setup steps for that codebase.

## Where to contribute

| Repository | Contribute here for |
| --- | --- |
| [osun-eduos](https://github.com/Osun-eduos/osun-eduos) | Architecture, roadmap, project-wide proposals and questions |
| [eduos-web](https://github.com/Osun-eduos/eduos-web) | Screens, workflows and the web prototype |
| [eduos-api](https://github.com/Osun-eduos/eduos-api) | API, database and notifications |
| [eduos-mobile](https://github.com/Osun-eduos/eduos-mobile) | The offline Android and iOS app (Flutter) |
| [eduos-sync](https://github.com/Osun-eduos/eduos-sync) | The sync service the mobile app talks to (Go) |

If you're not sure, open an issue in **osun-eduos**.

## Ways to contribute

- **Report a bug.** Open an issue using the *Bug report* template. Include the screen, what you did, what you expected and what happened.
- **Suggest a feature or workflow change.** Use the *Feature request* template. Explain who it helps (teacher, principal, Ministry officer, parent) and the problem it solves.
- **Improve the documentation.** Fixes to READMEs and docs are always welcome.
- **Write code.** Pick an issue labelled `good first issue` or `help wanted`, or open an issue first to discuss anything large.

## Guidelines

- **Keep it working offline and on low-end phones.** Many schools have weak connectivity and older Android devices. Avoid heavy libraries and large assets.
- **Never commit real personal data.** Use only fictional sample data. No real student, teacher or parent names, phone numbers or results.
- **Accessibility matters.** Label form controls, keep keyboard navigation working, and keep colour contrast readable in light and dark mode.
- **Plain language.** Write interface text the way a teacher or parent would say it.
- **Small pull requests.** One change per pull request is easier to review.
- **Changes that cross repositories** (for example a new field that touches the API, the web app and the mobile app) start as an issue in **osun-eduos** so the design is agreed once.

## Pull request process

The `main` branch of every repository is protected: changes reach it through pull requests, not direct pushes.

1. Fork the repository and create a branch from `main` (for example `fix/attendance-save` or `feat/yoruba-labels`).
2. Make your change and test it. Run the same checks CI runs (each README lists them).
3. Open a pull request against `main` using the template. Link the issue it addresses and add screenshots for visual changes.
4. If this is your first contribution, a maintainer approves the CI run before it starts. That is a safety step for pull requests from forks, not a judgement on your change.
5. Before a pull request can merge:
   - the required CI checks must pass;
   - a code owner must approve it (new commits after an approval need a fresh review);
   - every review conversation must be resolved.
6. A maintainer merges it with **Squash and merge**, so each pull request becomes one commit on `main`. Write a clear pull request title: it becomes the commit message. The branch is deleted after merging.

If `main` moves on while your pull request is open, use the **Update branch** button or rebase your branch on `main`.

Dependency updates are opened automatically by Dependabot and go through the same review.

## Licensing of contributions

By submitting a contribution you agree that it is licensed under the licence of the repository you contribute to (GNU Affero General Public License v3.0 unless stated otherwise), and that you have the right to submit it.

## Conduct

Everyone taking part is expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
