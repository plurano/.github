# Organisation profile

<!-- praetor:readme-governance:start -->
[![HISS Adopted][praetor-hiss-badge]][praetor-hiss-agents]

Praetor manages this repository's declared governance policy. This managed
block records adoption state; it is not a verification certificate.

**Verification**: `make verify-all` runs the repository's configured
verification cascade.

**HISS Audit**: `praetorctl audit` enforces policy, generated-surface
integrity, and the debt ratchet.

**Context Sync**: `praetorctl compile-context --verify` verifies every
generated agent context against `AGENTS.md`.

**Debt Baseline**: `.standards-baseline.json` anchors the debt ratchet at
0 recorded infractions; audit forbids growth.

[praetor-hiss-badge]: https://img.shields.io/badge/Standards-HISS%20Adopted-blue
[praetor-hiss-agents]: https://github.com/plurano/.github/blob/HEAD/AGENTS.md
<!-- praetor:readme-governance:end -->

The profile page of this organisation and its default community files.
The profile text is in [profile/README.md](profile/README.md).

Default community files for every repository of the organisation that has
no file of its own: [code of conduct](CODE_OF_CONDUCT.md),
[contributing guide](CONTRIBUTING.md), [security policy](SECURITY.md) and the
issue forms under [.github/ISSUE_TEMPLATE](.github/ISSUE_TEMPLATE).
