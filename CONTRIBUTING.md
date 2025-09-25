# Contributing to OpenStateStack

We’re excited that you’re interested in contributing to **OpenStateStack**, the Operating System for Digital Sovereignty.
This document outlines how you can contribute and the rules you must follow.

## 📌 Before You Start

* By contributing, you agree to the [OpenStateStack Contribution and Restricted Use License (OSRUL)](./LICENSE).
* Contributions are **owned and controlled** by [OpenStateStack Limited](https://openstatestack.io).
* Unauthorized production or commercial use of OpenStateStack, forks, or derivatives is strictly prohibited.

## 🚀 How to Contribute

### 1. Reporting Issues

* Use the GitHub [Issues](./issues) tab to report bugs, vulnerabilities, or documentation gaps.
* For **security issues**, please email \[[security@openstatestack.io](mailto:security@openstatestack.io)] instead of opening a public issue.

### 2. Proposing Features

* Open a [feature request issue](./issues/new) before submitting large changes.
* Feature proposals should align with the **project roadmap** and sovereign infrastructure goals.

### 3. Submitting Code Changes

* Fork the repository and create a feature branch:

  ```bash
  git checkout -b feature/my-change
  ```
* Ensure your changes follow our standards:
  * **Language & Frameworks**: TypeScript, NestJS, Nx monorepo structure
  * **Database Layer**: TypeORM entities aligned with `iam`, `registry`, and `payments` schemas
  * **Tests**: Jest unit + integration tests required for all code
  * **Linting**: Run `pnpm lint` before committing
* Commit messages must follow [Conventional Commits](https://www.conventionalcommits.org).

### 4. Submitting Pull Requests

* Open a PR against the `develop` branch.
* PRs must include:

  * Updated tests
  * Updated documentation (if applicable)
  * Clear explanation of the change and rationale
* The Owner reserves the right to approve, reject, or modify contributions.

## 🛡 Code of Conduct

We expect all contributors to follow our [Code of Conduct](./CODE_OF_CONDUCT.md).

* Be respectful and constructive.
* No harassment or discriminatory behavior.
* Technical disagreements should remain professional.

## 🔐 Licensing of Contributions

* By submitting a contribution, you grant [OpenStateStack Limited](https://openstatestack.io) a **perpetual, worldwide, royalty-free license** to use, modify, and distribute your contribution as part of OpenStateStack.
* You retain copyright over your own code, but contributions **must** be compatible with the [OSRUL License](./LICENSE).

## 📝 Documentation Contributions

* Documentation lives in `docs.openstatestack.io`.
* All new features must include updated developer and API docs.
* Use Markdown with clear, structured sections.

## ✅ Contribution Checklist

Before submitting, please confirm:

* [ ] My code compiles and passes all tests.
* [ ] I ran `pnpm lint` and fixed style issues.
* [ ] I added/updated documentation.
* [ ] I confirm that my contribution complies with the [OSRUL License](./LICENSE).

## 📬 Contact

For questions or special contribution agreements (e.g., government partners, enterprise integrators), please contact: 
📧 [[sp@openstatestack.io](mailto:sp@openstatestack.io)]
