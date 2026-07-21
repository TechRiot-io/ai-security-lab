# Session 001: Task-scoped authorization for AI agents

**Date:** TBD  
**Speaker:** Security Engineer, Snap  
**Format:** Live technical demonstration  
**Recording:** To be added

## Summary

This session demonstrates how an AI coding agent can be placed on a least-privilege leash by granting access only for the task it is currently performing.

The walkthrough focuses on a live Claude Code workflow using open-source tooling and task-scoped authorization.

## What will be demonstrated

- defining the task an agent is authorised to perform
- granting narrowly scoped access for that task
- preventing broader access outside the task boundary
- observing and validating agent actions
- revoking or expiring access when the task ends

## Security problem

AI agents often operate with credentials and permissions that are broader or longer-lived than the task requires. This increases the impact of prompt injection, tool misuse, compromised dependencies, and unintended agent behaviour.

Task-scoped authorization aims to reduce that blast radius.

## Questions the session should answer

- What is the authorization boundary?
- Who or what defines the task?
- How is policy enforced across tools?
- How are permissions issued and revoked?
- What happens when the agent changes its plan?
- What evidence is captured for audit and incident response?
- Which failure modes remain?

## Demo material

Add reproducible material under `demo/` after speaker review.

## Architecture

Add sanitised diagrams under `diagrams/`.

## Resources

See [resources.md](resources.md).

## Disclaimer

This session record is educational and may not represent the speaker's employer. Validate the approach in your own environment before production use.
