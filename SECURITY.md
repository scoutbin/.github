# Security Policy

## Supported versions

Only the latest stable release of each tool receives security fixes. Older releases do not, so upgrade to get a fix. Prerelease builds (alpha, beta and rc) are not covered.

If a repository has its own SECURITY.md, that file applies to the repository.

## Reporting a vulnerability

Report security vulnerabilities privately through GitHub private vulnerability reporting. In the affected repository, open the Security tab and select "Report a vulnerability".

Do not report security issues in public issues, discussions or pull requests. Do not post proof-of-concept code or exploit details publicly. There is no email address for security reports.

## What to include

In the commands below, `<tool>` is the name of the CLI tool, for example `pin`. The `version` and `info` commands apply to the CLI tools only.

- The affected version. Paste the output of `<tool> version`, which also shows the operating system and architecture.
- The install channel. Paste the output of `<tool> info`. Replace the executable path if it reveals private information.
- The impact: what an attacker can do and what conditions they need.
- Steps to reproduce, with a proof of concept if you have one.
- Remove secrets, tokens and private data from any logs or files you attach. Log files often contain these, so check them first.

## What happens next

1. We acknowledge your report. We aim to do this promptly.
2. We investigate and confirm whether it is a vulnerability. We may ask for more detail. If it is not, we tell you why.
3. We prepare a fix. Where we can, we agree a disclosure date with you.
4. We release the fix in a new stable release and publish a GitHub security advisory that describes the issue and the fixed version.
5. If you want, we credit you in the advisory and the release notes.

Keep the issue private until a fix is released or we agree on a disclosure date. We aim to keep you informed of progress. Timelines depend on the severity and complexity of the issue, and we cannot guarantee specific response or fix times.

## Scope

In scope:

- The code of the repository the report is filed against.
- Any of the following the repository publishes: release archives, `checksums.txt`, install scripts, the GitHub Action, the Homebrew formula and the npm package.
- Its build and release workflows.

Out of scope:

- Third-party dependencies. Report them to the upstream project.
- Vulnerabilities in GitHub, npm, Homebrew or other platforms. Report them to the platform.
- Problems in another scoutbin repository, such as spine or homebrew-tap. Report them through the Security tab of that repository.

## Pull requests

scoutbin does not accept pull requests, including security fixes. Report the issue as described above, and the maintainers will write the fix.
