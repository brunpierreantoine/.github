# Security Policy

## Reporting

Do not open a public issue for a suspected vulnerability. Use GitHub private
vulnerability reporting when enabled. Otherwise contact the repository owner
privately through the contact method shown on the owner's GitHub profile.

Include affected repository and version, reproduction steps, impact, and any known
workaround. Do not include real secrets or personal data.

## Supported versions

Personal projects normally support only the currently deployed version. Security
fixes are applied to active `main` and synchronized back to `dev`.

## Baseline

- No secrets or production data in source control.
- Least-privilege workflow permissions and deployment credentials.
- Frozen dependency installs and reviewed lockfile changes.
- Input validation, parameterized SQL, safe errors, and protected authentication.
- Dependabot and Socket findings treated as review signals.
