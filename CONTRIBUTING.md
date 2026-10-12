# Contributing to Plurano

Describe the problem and the expected behavior in an issue before changing a
public interface. Use a feature branch from the default branch and a pull
request with a Conventional Commit title. Explain what changed, why, which
checks ran and any remaining limitation.

Sign every commit and add a `Signed-off-by` line with the identity you commit
under. Follow each repository's own `CONTRIBUTING.md` and local checks where it
has them; they take precedence over this file.

Never bypass a check or weaken a failing gate. Workflows use the built-in
repository token with read-only defaults and write permissions scoped to the job
that needs them. Pin third-party actions and tools to an exact commit or digest.

Each repository includes the complete EUPL-1.2 text. Contributions must be yours
to license; keep third-party notices and their licences with the code they
cover.

Security reports do not belong in issues or pull requests: follow
[SECURITY.md](SECURITY.md).
