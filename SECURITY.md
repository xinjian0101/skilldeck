# Security Policy

## Current status

SkillDeck is in the foundation phase. No published version should be treated as production-ready until a preview release is explicitly announced.

## Reporting a problem

Do not include private files, account information, or detailed reproduction material in a public Issue.

Use GitHub private vulnerability reporting when available. Otherwise open a minimal Issue requesting a private communication channel and include only the affected component and general impact.

A useful report includes the affected commit, operating system, application version, reproduction steps, observed impact, and a sanitized example.

## Sensitive areas

- Reading or changing local configuration files.
- Importing untrusted packages or manifests.
- Replacing files without backup and rollback.
- Displaying private values in logs or screenshots.
- Update behavior that cannot be verified.
- Compatibility adapters that write unexpected output.

## Expected safeguards

The application should preview changes, preserve backups, validate imported data, use least-privilege file access, and provide clear recovery instructions.

## Disclosure

Validated reports will be investigated privately where practical. Public notes should explain affected versions, impact, and remediation without exposing user information.