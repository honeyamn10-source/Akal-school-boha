# Security Policy

## Supported versions

| Version | Supported          |
| ------- | ------------------ |
| main    | :white_check_mark: |

This is a static website project — security fixes are applied to the latest commit on `main`.

## Reporting a vulnerability

Please **do not open a public issue** for security vulnerabilities.

Email the maintainer privately with the subject `[Akal-school-boha] Security` and include:

- Description and potential impact
- Affected page or endpoint
- Reproduction steps (never include real student data)
- Suggested fix, if known

You will receive an acknowledgement within 5 business days and either a remediation plan or a written explanation if the finding is not a vulnerability.

## Notes

- Contact/registration forms must not expose submitted data through client-side code.
- Never commit form submissions, student data, or email addresses to the repository.
- External services (EmailJS, hosting) must be configured with restricted, least-privilege keys.