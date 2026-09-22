# Talent Intelligence Agent - Claude Code Instructions

## Project Purpose

This is a hands-on learning project for mastering Anthropic CCAR-F concepts through a Talent Intelligence Agent.

Project flow:

Employee Profile → Skills → Opportunities → Recommendation → Human Review

## Core Rule

**Human designs and learns the agentic architecture. AI implements supporting code.**

Do not optimize for completing the project as quickly as possible.

Optimize for preserving learning opportunities.

## DO NOT Make These Architectural Decisions

Do not independently design, replace, or substantially modify:

- Agent architecture
- Agent boundaries
- Coordinator-worker relationships
- Subagent delegation strategy
- Goal-oriented vs procedural delegation
- Agent prompts
- AgentDefinition configuration
- Tool restrictions
- Tool schemas
- `tool_choice`
- MCP resource vs tool decisions
- MCP server architecture
- Context-management strategy
- State persistence strategy
- Session-resumption strategy
- Output schemas for agentic workflows
- Synthesis strategy
- Confidence/uncertainty semantics
- Human-review routing
- Claude Code configuration strategy
- Skills, rules, hooks, or permission architecture

If one of these decisions is required and no explicit specification exists, **stop and ask the learner rather than deciding autonomously**.

## What You MAY Implement

You may implement:

- Project scaffolding
- Boilerplate
- UI components
- Basic API endpoints
- Database plumbing
- File handling
- Document parsing
- Logging
- Error-handling infrastructure
- Configuration loaders
- API clients
- Serialization utilities
- Test infrastructure
- Fixtures and mock data
- Linting and formatting
- Docker/CI boilerplate
- Repetitive refactoring
- Documentation
- Basic unit tests

## Implementation Rule

When the learner provides an architecture or technical specification:

1. Implement it faithfully.
2. Do not redesign it.
3. Do not silently add agentic behavior.
4. Do not introduce additional agents or tools without approval.
5. Preserve explicit tool boundaries.
6. Preserve explicit schemas.
7. If requirements conflict or are ambiguous, ask before proceeding.

## Learning Mode

When implementing CCAR-F concepts, prefer this workflow:

Human designs → Human implements → AI reviews

For supporting application code:

Human specifies → AI implements → Human reviews

## Do Not Hide Complexity

Do not create abstractions that hide important agentic concepts from the learner.

For example, do not hide:

- Agent spawning
- Tool invocation
- Parallel execution
- Context passing
- State persistence
- MCP configuration
- Structured output
- Retry logic

behind a large opaque framework unless explicitly requested.

The learner should be able to inspect and understand the relevant implementation.

## Testing

Tests should include both:

- Normal successful cases
- Deliberately broken/misconfigured cases

When reviewing code, identify:

- Incorrect tool permissions
- Incorrect agent configuration
- Missing coordinator-to-subagent wiring
- Context leakage
- Incorrect structured output
- Missing evidence
- Unsupported assumptions
- Incorrect MCP configuration
- Unnecessary tool calls
- Poor error handling

Do not automatically fix these learning issues without first explaining them when they concern a CCAR-F concept.

## Exam Alignment

When a change directly relates to a CCAR-F objective, briefly identify the relevant concept in the response.

Do not provide memorized exam answers unless explicitly requested.

Prefer explaining:

- Why the architecture works
- What alternative architectures exist
- When each alternative should be used
- What failure mode the design prevents
