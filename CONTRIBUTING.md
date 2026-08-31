# Contributing

Thanks for taking an interest in one of our projects. These guidelines apply across all public repositories in the [Nirmitee-tech](https://github.com/Nirmitee-tech) organization; individual repos may add their own `CONTRIBUTING.md` with project-specific setup.

## Before you start

- **Open an issue first** for anything larger than a bug fix or a docs correction. It saves you from building something we are already changing.
- **Check the repository's README** for how to run the project and its tests locally.

## Pull requests

1. Fork the repository and create a branch off `main`.
2. Keep the change focused — one concern per pull request.
3. Add or update tests for behaviour you change.
4. Make sure the existing test suite and linters pass.
5. Write a clear description: what changed, why, and how you verified it.

We review pull requests on a best-effort basis and aim to give you a first response within a week.

## Never commit

- Real patient data, PHI or PII — use synthetic data in tests and examples
- Credentials, API keys, tokens or certificates
- Client names or deployment details

If you spot any of these in a repository, email **security@nirmitee.io** rather than opening an issue.

## Healthcare data in examples

Several of these projects carry HL7 v2 messages, FHIR resources or X12 EDI files as fixtures. All of it must be synthetic. When adding a fixture, use obviously fake names, dates and identifiers, and do not derive it from a real message by find-and-replace — residual identifiers survive that far more often than people expect.

## Licensing

By contributing, you agree that your contribution is licensed under the same license as the repository you are contributing to.

## Questions

Open a discussion or issue on the repository, or reach us at [nirmitee.io/contact](https://nirmitee.io/contact).
