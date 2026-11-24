# Contributing to Osun EduOS

Thank you for helping build better education infrastructure for Osun State. You don't need to write code to contribute: feedback from teachers, school heads, Ministry officers and parents is just as valuable.

This guide applies to every repository in the [Osun-eduos](https://github.com/Osun-eduos) organisation. A repository's own README may add setup steps for that codebase.

## Where to contribute

| Repository | Contribute here for |
| --- | --- |
| [osun-eduos](https://github.com/Osun-eduos/osun-eduos) | Architecture, roadmap, project-wide proposals and questions |
| [eduos-web](https://github.com/Osun-eduos/eduos-web) | Screens, workflows and the web prototype |
| [eduos-api](https://github.com/Osun-eduos/eduos-api) | API, database, sync and notifications |
| [eduos-android](https://github.com/Osun-eduos/eduos-android) | The offline Android app |
| [eduos-ios](https://github.com/Osun-eduos/eduos-ios) | The offline iOS app |

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
- **Changes that cross repositories** (for example a new field that touches the API, web, Android and iOS apps) start as an issue in **osun-eduos** so the design is agreed once.

## Pull request process

1. Fork the repository and create a branch from `main` (for example `fix/attendance-save` or `feat/yoruba-labels`).
2. Make your change and test it.
3. Open a pull request using the template. Link the issue it addresses and add screenshots for visual changes.
4. A maintainer will review it. Please respond to feedback; we may ask for changes before merging.

## Licensing of contributions

By submitting a contribution you agree that it is licensed under the licence of the repository you contribute to (GNU Affero General Public License v3.0 unless stated otherwise), and that you have the right to submit it.

## Conduct

Everyone taking part is expected to follow the [Code of Conduct](CODE_OF_CONDUCT.md).
