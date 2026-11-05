# Security Policy

## Supported Versions

Security updates are provided for the latest maintained release.

| Version | Supported |
|---|---|
| Latest release | :white_check_mark: |
| Previous releases | :x: |
| Development / unreleased builds | :x: |

Only official releases published by the repository maintainers should be considered trusted.

## Reporting a Vulnerability

We take the security of this project and its users seriously.

If you discover a security vulnerability, please report it responsibly.

**Do not publicly disclose security vulnerabilities through GitHub Issues, Discussions, pull requests, or social media.**

Instead, use GitHub's private vulnerability reporting feature:

1. Open this repository on GitHub.
2. Navigate to the **Security** tab.
3. Select **Report a vulnerability**.
4. Provide a detailed description and reproduction steps.

If private vulnerability reporting is unavailable, contact the repository owner through their verified GitHub profile.

### What to Include

Please include:

- A clear description of the vulnerability.
- Steps to reproduce the issue.
- Affected versions or release assets.
- Potential security impact.
- Relevant logs, screenshots, or proof of concept, if safe to provide.
- Suggested remediation, if available.

Do not include real user credentials, private keys, passwords, or sensitive personal information in reports.

### Response Timeline

We aim to:

- Acknowledge reports within 3 business days.
- Perform an initial assessment within 7 business days.
- Provide status updates during investigation.
- Coordinate a fix and responsible disclosure timeline with the reporter.

These are target response times, not guaranteed deadlines.

### Vulnerability Handling

If a report is accepted:

- We investigate and assess its impact.
- We prepare and verify a fix.
- We publish a security update when appropriate.
- We credit the reporter if they agree to be acknowledged.

If a report is declined:

- We explain the reason where possible.
- We may request additional information if the issue is unclear.
- We may close reports that are not security-related, cannot be reproduced, or are outside the project's scope.

Please allow maintainers reasonable time to investigate and address reported vulnerabilities before public disclosure.

---

## Official Sources and Release Integrity

Only trust font files, manifests, and release assets published through the official repository:

**Repository:** https://github.com/quantumhatch/font-packs

**Official Releases:** https://github.com/quantumhatch/font-packs/releases

**Latest Manifest:** https://github.com/quantumhatch/font-packs/releases/latest/download/manifest.json

Security expectations:

- Download font packs only from official, verified release assets.
- Do not trust unofficial mirrors or third-party download links.
- Verify SHA-256 checksums against the official manifest.
- Do not install modified or unverified font files.
- Treat unexpected changes to download URLs, checksums, or release metadata as suspicious.
- Do not trust files merely because their filenames match official assets.

A matching checksum confirms file integrity against the trusted manifest; it does not independently prove that a font file is harmless.

## Protection Against Scams, Impersonation, and Malware

To protect users and contributors:

- Maintainers will not ask users to share passwords, GitHub tokens, private keys, or authentication codes.
- Never execute scripts, installers, or commands from unknown contributors without reviewing their contents.
- Be cautious of accounts impersonating project maintainers.
- Do not download replacement font packs from unsolicited messages.
- Do not trust unofficial websites claiming to distribute modified or premium versions of this project.
- Verify repository ownership and release URLs before downloading files.
- Report suspicious accounts, malicious pull requests, fake releases, and phishing attempts privately.

The project does not authorize unofficial maintainers or third parties to distribute modified releases under its identity.

## Repository and Contribution Security

All contributions and release changes should follow these security practices:

- Review pull requests before merging.
- Do not execute untrusted code from pull requests.
- Review changes to GitHub Actions workflows and build scripts carefully.
- Avoid committing credentials, API keys, access tokens, or private configuration files.
- Use least-privilege permissions for repository access and automation.
- Protect important branches and releases where repository settings permit.
- Review font source, licensing, and provenance before including new files.
- Validate manifest entries, download URLs, file sizes, and checksums.
- Do not accept unexpected changes to release download hosts without verification.

## Font File and Manifest Security

This repository distributes downloadable font files and metadata.

For safety:

- Font files must come from identifiable and appropriately licensed sources.
- Every published font file must have a corresponding SHA-256 checksum.
- Manifest entries must use HTTPS download URLs.
- Download hosts must be explicitly allowlisted by the consuming application.
- Font filenames and metadata must be validated.
- Font downloads should be size-limited.
- Files must be verified before installation.
- Invalid or mismatched files must be rejected.
- Existing installed fonts must not be replaced by incomplete or unverified downloads.

Font files are external binary assets and should always be treated as untrusted input until validated.

## Responsible Disclosure

We appreciate security researchers and contributors who help protect this project.

Please give maintainers a reasonable opportunity to investigate and resolve vulnerabilities before publishing technical details that could expose users to harm.

Thank you for helping keep this project and its users safe.
