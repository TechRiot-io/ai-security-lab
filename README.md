# AI Security Lab

**Live demos. Open source. No slideware.**

AI Security Lab is a practitioner-led community by [TechRiot.io](https://techriot.io) for people building and securing AI systems in production.

Each session focuses on a real implementation, shown live by the person who built it. The goal is to make practical AI security knowledge easier to inspect, reproduce, and improve.

## Join upcoming sessions

AI Security Lab hosts live practitioner sessions every two weeks.

[View and register for upcoming sessions on Luma](https://luma.com/ai-security-lab)

## What belongs here

This repository is the public record for AI Security Lab sessions. It can contain:

- session summaries
- architecture diagrams
- demo code and configuration
- threat models
- implementation notes
- links to recordings
- downloadable transcripts and chat logs
- lessons learned
- follow-up resources

The repository is not intended to be a collection of vendor pitches, generic frameworks, or slide-only talks.

## Principles

1. **Show the implementation.** Working systems are more useful than abstract claims.
2. **Explain the trade-offs.** What failed, what changed, and what remains unresolved matter.
3. **Make it reproducible.** Share enough context for another practitioner to understand or test the approach.
4. **Protect sensitive information.** Do not publish credentials, customer data, internal identifiers, or proprietary code.
5. **Prioritise practitioners.** Security and engineering practitioners come first. Vendor participation is welcome when the session is implementation-led and technically substantive.

## Sessions

| Session | Topic | Speaker | Status |
|---|---|---|---|
| [001](./sessions/001-task-scoped-authorization-for-ai-agents/) | Task-scoped authorization for AI agents | Niki Aimable, Security Engineer at Snap | Published |

## Browse by security pattern

| Pattern | Sessions |
|---|---|
| Least privilege | [001](./sessions/001-task-scoped-authorization-for-ai-agents/) |
| Task-scoped authorization | [001](./sessions/001-task-scoped-authorization-for-ai-agents/) |
| Default deny | [001](./sessions/001-task-scoped-authorization-for-ai-agents/) |
| Argument-level controls | [001](./sessions/001-task-scoped-authorization-for-ai-agents/) |
| Human approval | [001](./sessions/001-task-scoped-authorization-for-ai-agents/) |
| Audit trail | [001](./sessions/001-task-scoped-authorization-for-ai-agents/) |
| Sandboxed execution | [001](./sessions/001-task-scoped-authorization-for-ai-agents/) |

This index will grow as new practitioner sessions are published.

## Repository structure

```text
.
├── sessions/
│   └── <number>-<session-title>/
│       ├── README.md
│       ├── transcript.vtt
│       ├── chat.txt
│       ├── demo/
│       ├── diagrams/
│       └── resources.md
├── templates/
│   ├── session-proposal.md
│   └── session-readme.md
├── CONTRIBUTING.md
├── CODE_OF_CONDUCT.md
└── SECURITY.md
```

Not every session will include every optional file or directory. Each session should include a concise `README.md`; transcripts, chat logs, demo code, diagrams, and additional resources are added when available and authorised for publication.

## Propose a session

Open a Session Proposal issue using the repository issue template.

Strong proposals usually include:

- a real system or control already implemented
- a clear AI security problem
- a live technical walkthrough
- reusable code, patterns, or lessons
- honest discussion of limitations

## Contributing

You can help by:

- sharing an implementation you have built
- suggesting a future speaker or topic
- improving session notes
- adding useful references
- opening an issue or pull request

See [CONTRIBUTING.md](./CONTRIBUTING.md) for details.

## Support AI Security Lab

If this repository is useful:

- star the repository
- share it with your team or community
- recommend a practitioner who should present a future session
- join an upcoming session on [Luma](https://lu.ma/aisecuritylab)

> **Make production AI security knowledge accessible to every security engineer.**

## Reuse and licensing

Unless a session folder states otherwise:

- original written content and diagrams are intended for release under CC BY 4.0
- original code is intended for release under Apache License 2.0

Speakers must only contribute material they are authorised to publish. Third-party projects retain their original licences.

## Maintained by

AI Security Lab is a practitioner community initiative by [TechRiot.io](https://techriot.io).
