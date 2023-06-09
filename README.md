# Repository Template

[![Conventional Commits](https://img.shields.io/badge/Conventional%20Commits-1.0.0-%23FE5196?logo=conventionalcommits&logoColor=white)](https://conventionalcommits.org)
[![SemVer Badge](https://img.shields.io/badge/SemVer-3F4551?logo=semver&logoColor=white)](https://semver.org/spec/v2.0.0.html)
[![OpenSSF
Scorecard](https://api.securityscorecards.dev/projects/github.com/molier-net/template/badge)](https://api.securityscorecards.dev/projects/github.com/molier-net/template)

This repository provides a base template for git repositories with features like:

- Trunk Check based linters, formatters, static code analysis tools and spell/grammar checkers.
- GitHub actions based enforcement of the conventional commit convention through commitlint and automated semantic versioning through Google's release-please.

## Table of Contents

1. [Getting Started](#getting-started)
2. [Contribution Guidelines](#contribution-guidelines)
3. [Semantic Versioning](#semantic-versioning)
4. [Testing](#testing)
5. [Deployment](#deployment)
6. [Built With](#built-with)
7. [Versioning](#versioning)
8. [Authors](#authors)
9. [License](#license)
10. [Acknowledgments](#acknowledgments)

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes.

### Prerequisites

What things you need to install and how to install them.

### Installing

A step by step series of examples that tell you how to get a development env running.

## Contribution Guidelines

We enforce a strict standard for our commits. This project uses the Conventional Commits standard, which provides an easy set of rules for creating an explicit commit history.

For example:
´´´bash

- `git commit -m "feat: add new feature"` for new feature
- `git commit -m "fix: fix a bug"` for a bug fix
- `git commit -m "docs: update readme"` for documentation changes
  ´´´

Please see the [CONTRIBUTING.md](./CONTRIBUTING.md) for detailed information.

## Semantic Versioning

We use Semantic Versioning for this project. Every release number is in the form of MAJOR.MINOR.PATCH.

- MAJOR version increments when there are incompatible API changes.
- MINOR version increments when functionality is added in a backwards-compatible manner.
- PATCH version increments when backwards-compatible bug fixes are introduced.

For more details, see [Semver](https://semver.org).

## Testing

Explain how to run the automated tests for this system.

## Deployment

Add additional notes about how to deploy this on a live system.

## Built With

- [Trunk Check](https://trunk.io/products/check) - For enforcing code quality
- [Commitlint](https://github.com/conventional-changelog/commitlint) - For enforcing the conventional commit convention
- [ReleasePlease](https://github.com/googleapis/release-please) - For supporting the semantic versioning
- [OpenSSF Scorecard](https://github.com/ossf/scorecard) - For helping to improve the security aspects of this repository

## Versioning

We use [SemVer](http://semver.org/) for versioning. For the versions available, see the [tags on this repository](https://github.com/molier-net/template/tags).

## Authors

- **Remko Molier** - _Initial work_ - [RemkoMolier](https://github.com/YourUsername)

See also the list of [contributors](./CONTRIBUTORS.md) who participated in this project.

## License

This project is licensed under the [GNU GPL v3](LICENSE).

## Acknowledgments

- Acknowledge the people/projects that helped your project.
