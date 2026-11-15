# Contributing

scoutbin does not accept pull requests.

All code in these projects is written by the maintainers. This is a supply-chain integrity decision: it keeps the origin of every line we ship known. Unsolicited pull requests are closed without review, regardless of size or quality. Code sent through any other channel will not be merged either.

Do not spend time on a fix as a pull request. Describe the problem in an issue instead.

You can still help through GitHub Issues:

- Report bugs.
- Request features.
- Give feedback on behavior, output or documentation.

Open the issue on the repository for the tool you are using. Search existing issues before opening a new one. If a matching issue exists, add your details there, such as confirming the problem on another OS or version. Keep each issue to one problem or one feature.

## Reporting a bug

In the commands below, `<tool>` is the name of the CLI tool, for example `pin`. The `version` and `info` commands apply to the CLI tools only.

A bug report we can act on includes:

- **Version and environment.** The output of `<tool> version` and `<tool> info`. Replace the executable path if it reveals private information, such as a user name or internal directory. If you built from source, include the commit SHA.
- **Steps to reproduce.** The smallest set of commands, configuration and input that triggers the problem.
- **Expected and actual behavior.** State both. "It fails" does not say what you expected.
- **Logs or output.** The full error output and the input lines involved.

Remove secrets, tokens, credentials and personal data before you paste anything. Logs often contain them. Redact them, do not just trim them. Replace private names and URLs with placeholders.

We may ask for more detail. Reports without steps to reproduce may be closed until they include them.

## Requesting a feature

Describe the problem before the solution. A useful feature request covers:

- The task you are trying to do and how you do it today.
- The alternatives you tried and why they did not work.
- The behavior you want.
- An example of input and the output you would expect, if it applies.

Maintainers review feature requests, but accepting one does not guarantee it will be built.

## See also

- [SECURITY.md](https://github.com/scoutbin/.github/blob/main/SECURITY.md) for vulnerabilities. Do not report them in public issues.
- [SUPPORT.md](https://github.com/scoutbin/.github/blob/main/SUPPORT.md) for questions.
- [GOVERNANCE.md](https://github.com/scoutbin/.github/blob/main/GOVERNANCE.md) for how decisions are made.
