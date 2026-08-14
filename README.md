<!-- Copy -->
<h1 align="center">.github</h1>

<h4 align="center">Community health files, issue templates, and canonical license texts shared across every @willtheorangeguy repository.</h4>

<!-- Badges -->
<div align="center">
  <img alt="GitHub Issues" src="https://img.shields.io/github/issues/willtheorangeguy/.github">
  <img alt="GitHub Pull Requests" src="https://img.shields.io/github/issues-pr/willtheorangeguy/.github">
  <img alt="License" src="https://img.shields.io/github/license/willtheorangeguy/.github">
</div>

<!-- Navigation -->
<p align="center">
  <a href="#key-features">Key Features</a> •
  <a href="#how-it-works">How It Works</a> •
  <a href="#usage">Usage</a> •
  <a href="#support">Support</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#license">License</a>
</p>

## Key Features

* Code of Conduct, Contributing Guide, and Security Policy inherited by every repository that does not define its own.
* Issue forms for bug reports, feature requests, and questions, with required fields and structured output.
* Pull request template with a change-type and review checklist.
* Canonical MIT and CC BY 4.0 license texts, plus the one approved copyright line.
* Shared image assets for every repository, served from `icons/`.
* GitHub Sponsors and funding configuration.

## How It Works

GitHub treats a repository named `.github` as the account's default source for community health files. Any repository under [@willtheorangeguy](https://github.com/willtheorangeguy) that does **not** contain its own copy of a file below automatically inherits the one here — nothing needs to be copied.

```text
├── ISSUE_TEMPLATE
|   ├── bug-report.yml
|   ├── config.yml
|   ├── feature-request.yml
|   └── question.yml
├── icons
|   └── <repository>/...
├── licenses
|   ├── CC-BY-4.0.md
|   ├── MIT.md
|   └── README.md
├── CODE_OF_CONDUCT.md
├── CONTRIBUTING.md
├── FUNDING.yml
├── PULL_REQUEST_TEMPLATE.md
└── SECURITY.md
```

Two things are **not** inherited and must live in each repository:

| File | Why |
| ---- | --- |
| `LICENSE.md` | GitHub only detects a license from the repository it sits in. Write it out from [`licenses/`](licenses/). |
| `.github/dependabot.yml` | Dependabot configuration is never inherited from the `.github` repository. |

## Usage

Images are referenced by absolute URL rather than copied into each repository, so a logo is updated once and changes everywhere:

```text
https://raw.githubusercontent.com/willtheorangeguy/.github/main/icons/<repository>/logo.png
```

This repository must stay **public** for those URLs to resolve.

To reuse these files in your own account, [fork the repository](https://github.com/willtheorangeguy/.github/fork) or [download it](https://github.com/willtheorangeguy/.github/archive/refs/heads/main.zip), rename it to `.github`, and edit each file to match your community.

## Support

Open a [GitHub Discussion](https://github.com/willtheorangeguy/.github/discussions/new) or file an [issue](https://github.com/willtheorangeguy/.github/issues/new/choose).

## Contributing

Contributions welcome. See the [Contributing Guide](CONTRIBUTING.md) and [Code of Conduct](CODE_OF_CONDUCT.md).

## License

MIT — see [`LICENSE.md`](LICENSE.md).
