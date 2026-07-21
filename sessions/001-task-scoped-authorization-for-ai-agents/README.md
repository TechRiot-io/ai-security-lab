# Session 001: Task-scoped authorization for AI agents

**Date:** 21 July 2026  
**Speaker:** Niki Aimable, Security Engineer at Snap  
**Format:** Live technical demonstration

## TL;DR

AI agents should not receive broad, long-lived access to tools, credentials, or environments.

This session demonstrated how an AI coding agent can instead receive narrowly scoped authorization for the task it is currently performing. Authorization is enforced outside the LLM, tool arguments can be restricted, delegated permissions can only become narrower, and agent actions can produce an auditable record.

## Key takeaways

- Give agents **task-scoped permissions**, not permanent access.
- Enforce authorization **outside the LLM** with deterministic policy checks.
- Restrict **tool arguments and actions**, not only which tools an agent may call.
- Use **default deny** for tools and actions that are not explicitly authorized.
- Ensure permissions become narrower when delegated to another agent.
- Add **human approval gates** for sensitive actions.
- Capture authorization decisions and agent actions for audit and investigation.

## Security patterns demonstrated

- Default-deny authorization
- Least privilege
- Task-scoped capabilities
- Argument-level controls
- Restricted delegation
- Human approval
- Auditable authorization decisions
- Sandboxed agent execution

## Open-source projects

- [Tenuo](https://github.com/tenuo-ai/tenuo)
- [Claude Governance](https://github.com/tenuo-ai/claude-governance)

## Questions raised by the community

- Can the same authorization model be applied to cloud agents?
- How should limited permissions be associated with an individual user?
- How should permissions be delegated safely between multiple agents?
- What evidence should be retained for audit and incident response?

## Session files

The summary above intentionally includes only the highest-signal points.

Download the original session files to review the complete discussion, implementation details, audience questions, and form your own interpretation:

- [Full transcript](./transcript.vtt)
- [Session chat](./chat.txt)
- [Additional resources](./resources.md)

## Who should share this?

Share this session with people who are building, deploying, governing, or securing AI agents, including:

- Security engineers
- Application security engineers
- Cloud security engineers
- Platform engineers
- AI and LLM engineers
- Security architects
- Engineering leaders responsible for AI adoption

## Help grow AI Security Lab

AI Security Lab is a practitioner-led collection of real-world AI security implementations.

You can help by:

- Starring this repository
- Sharing this session with your team or community
- Opening an issue when something is unclear
- Suggesting a future topic, demonstration, or speaker
- Contributing useful references or implementation patterns

> **Making production AI security knowledge accessible to every security engineer.**

## Disclaimer

This session record is educational and may not represent the speaker's employer. Validate the approach in your own environment before production use.
