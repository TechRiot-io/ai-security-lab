# AI Security Lab

**Live demos. Open source. No slideware.**

AI Security Lab is a practitioner-led community by [TechRiot.io](https://techriot.io) for people building and securing AI systems in production.

Each session focuses on a real implementation, shown live by the person who built it. The goal is to make practical AI security knowledge easier to inspect, reproduce, and improve.

## What belongs here

This repository is the public record for AI Security Lab sessions. It can contain:

- session summaries
- architecture diagrams
- demo code and configuration
- threat models
- implementation notes
- links to recordings
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
| [001](sessions/001-task-scoped-authorization-for-ai-agents/) | Task-scoped authorization for AI agents | Security Engineer, Snap | Scheduled |

## Repository structure

```text
.
├── sessions/
│   └── 001-task-scoped-authorization-for-ai-agents/
│       ├── README.md
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

## Propose a session

Open a **Session Proposal** issue using the repository issue template.

Strong proposals usually include:

- a real system or control already implemented
- a clear AI security problem
- a live technical walkthrough
- reusable code, patterns, or lessons
- honest discussion of limitations

## Reuse and licensing

Unless a session folder states otherwise:

- original written content and diagrams are intended for release under **CC BY 4.0**
- original code is intended for release under **Apache License 2.0**

Speakers must only contribute material they are authorised to publish. Third-party projects retain their original licences.

## Maintained by

AI Security Lab is a practitioner community initiative by [TechRiot.io](https://techriot.io).
