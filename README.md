# AI Personal Context Portfolio

This repository contains my Personal Context Portfolio, a portable and agent-agnostic context artifact that I can share with AI agents at the beginning of a collaboration.

## Purpose

- Accelerate alignment with a new AI agent
- Reduce repetitive clarification
- Explain how I prefer to work, communicate, troubleshoot, and make decisions
- Explain how I like code written, including comment style and source attribution
- Capture my standing Azure DevOps defaults for work items and pull requests
- Improve the practical value, safety, governance awareness, and reusability of AI-generated outputs
- Keep durable context curated, versioned, transparent, and under my control

## Files

- `personal-context.md`: Primary context document for AI agents
- `agent-handshake.txt`: Short instruction to send with the portfolio
- `changelog.md`: Version history and notable updates

## Suggested Use

1. Share `agent-handshake.txt` and `personal-context.md` at the beginning of a new AI collaboration.
2. Ask the agent to treat the portfolio as standing guidance for the session.
3. Add project-specific context separately so temporary project details do not become permanent personal context.
4. Review proposed changes before merging them into the portfolio.

## Design Principles

- Agent-agnostic
- Human-readable
- Easy to version in Git
- Focused on durable working preferences
- Explicit about security and governance
- Clear about the difference between stated context and agent inference
