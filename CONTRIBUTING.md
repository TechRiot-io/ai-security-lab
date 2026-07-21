# Contributing to AI Security Lab

Thank you for helping make production AI security work more visible and reusable.

## Ways to contribute

You can:

- propose a live session
- improve an existing session summary
- add implementation notes or diagrams
- contribute a safe, reproducible demo
- correct technical errors
- add relevant open-source resources

## Session selection criteria

A session is a strong fit when it:

- demonstrates a real implementation
- addresses a concrete AI security problem
- includes meaningful technical depth
- explains design choices and trade-offs
- avoids becoming a product pitch
- can be shared without exposing confidential information

Practitioners are prioritised. Submissions from security vendors are considered when the speaker is presenting substantive implementation work rather than a commercial overview.

## Adding a session

1. Open a Session Proposal issue.
2. Agree the scope with the maintainers.
3. Copy `templates/session-readme.md` into a numbered folder under `sessions/`.
4. Add demo material, diagrams, and resources where appropriate.
5. Open a pull request.

Use this naming pattern:

```text
sessions/NNN-short-descriptive-title/
```

## Safety and confidentiality

Before contributing, remove:

- API keys and tokens
- private hostnames and IP addresses
- customer or employee data
- internal repository names
- production secrets
- proprietary source code
- exploit details that create unnecessary risk

Use synthetic data and local test environments wherever possible.

## Pull requests

A useful pull request should explain:

- what changed
- why it changed
- how the change was validated
- any security or licensing considerations

By contributing, you confirm that you have the right to publish the submitted material.
