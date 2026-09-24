# Security policy

Rekey reads the keyboard system-wide: it runs a global keyboard event tap and uses the
Accessibility API to rewrite text in other apps. A flaw in software with that reach matters, so
security reports are read first and taken seriously.

## Reporting a vulnerability

Please **do not open a public issue.** Report it privately instead:

**[Report a vulnerability](https://github.com/x51xxx/Rekey/security/advisories/new)**

Include the Rekey version (menu bar ▸ About), your macOS version, and the steps to reproduce.
Private reports are answered before any public issue.

## In scope

- Anything that lets typed text leave the Mac, or be read by another process through Rekey
- Rekey acting on input it should ignore — password fields, Secure Input, the lock screen
- Tampering with updates: the update feed, the download, or its signature check
- The data Rekey does send (see the [privacy policy](https://trishchuk.com/rekey/privacy.html))
  carrying more than the policy says

Wrong corrections, missed words and crashes are ordinary bugs — use the
[Bug report](https://github.com/x51xxx/Rekey/issues/new?template=bug_report.yml) template.

## Supported versions

Only the latest beta receives fixes. Rekey updates itself, so that is the version to test.

There is no bug bounty.
