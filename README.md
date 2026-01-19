# SAP Cloud Application Programming Model setup action for Cloud Foundry

[![REUSE status](https://api.reuse.software/badge/github.com/cap-js/cf-setup)](https://api.reuse.software/info/github.com/cap-js/cf-setup)

## About this project

A reusable GitHub action to set up Cloud Foundry and Multi-Target Application (MTA) tooling to deploy SAP Cloud Application Programming Model (CAP) applications.

## Requirements and Setup

We recommend installing via the [GitHub marketplace](https://github.com/marketplace).

### Usage

```yaml
- uses: cap-js/cf-setup@v2
  with:
    api: ${{ vars.CF_API }}
    org: ${{ vars.CF_ORG }}
    space: ${{ vars.CF_SPACE }}
    username: ${{ vars.CF_USERNAME }}
    password: ${{ secrets.CF_PASSWORD }}
    origin: ${{ vars.CF_ORIGIN }}
```

## Support, Feedback, Contributing

This project is open to feature requests/suggestions, bug reports etc. via [GitHub issues](https://github.com/cap-js/cf-setup/issues). Contribution and feedback are encouraged and always welcome. For more information about how to contribute, the project structure, as well as additional contribution information, see our [Contribution Guidelines](CONTRIBUTING.md).

## Security / Disclosure

If you find any bug that may be a security problem, please follow our instructions at [in our security policy](https://github.com/cap-js/cf-setup/security/policy) on how to report it. Please do not create GitHub issues for security-related doubts or problems.

## Code of Conduct

We as members, contributors, and leaders pledge to make participation in our community a harassment-free experience for everyone. By participating in this project, you agree to abide by its [Code of Conduct](https://github.com/cap-js/.github/blob/main/CODE_OF_CONDUCT.md) at all times.

## Licensing

Copyright (2025-)2025 SAP SE or an SAP affiliate company and CAP contributors. Please see our [LICENSE](LICENSE) for copyright and license information. Detailed information including third-party components and their licensing/copyright information is available [via the REUSE tool](https://api.reuse.software/info/github.com/cap-js/cf-setup).
