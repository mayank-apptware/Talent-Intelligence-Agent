# Talent Intelligence Agent

A hands-on agentic AI project built to practice and master the concepts covered in the **Anthropic Claude Certified Architect – Foundations (CCAR-F)** exam.

## Project Flow

Employee Profile → Skills Intelligence → Opportunities → Recommendation → Human Review

The system analyzes employee profiles, identifies skills and gaps, discovers relevant opportunities, and generates evidence-backed recommendations with confidence and uncertainty information.

## Project Phases

- [01 - Profile Intelligence](phases/01-profile-intelligence.md)
- [02 - Skills Intelligence](phases/02-skills-intelligence.md)
- [03 - Multi-Agent Orchestration](phases/03-multi-agent-orchestration.md)
- [04 - Opportunity Discovery](phases/04-opportunity-discovery.md)
- [05 - Recommendation and Synthesis](phases/05-recommendation-and-synthesis.md)
- [06 - Context and State Management](phases/06-context-and-state-management.md)
- [07 - MCP Integration](phases/07-mcp-integration.md)
- [08 - Claude Code Workflows](phases/08-claude-code-workflows.md)
- [09 - CI/CD and Production](phases/09-ci-cd-and-production.md)

## Learning Objective

This project is intentionally designed as a **CCAR-F hands-on laboratory**, not just an application.

The project will progressively cover:

- Agentic loops and parallel tool calls
- Coordinator-worker and multi-agent architectures
- Subagent delegation and tool restrictions
- Structured outputs and JSON schemas
- `tool_choice`
- Context management and optimization
- Session resumption and state persistence
- MCP tools and resources
- Claude Code configuration
- Skills, rules, hooks, and permissions
- Human-in-the-loop review
- Synthesis and uncertainty handling
- Automated testing and CI/CD

## Development Philosophy

The core rule is:

> **Human designs and learns the agentic architecture. AI implements repetitive application code.**

Claude Code may handle boilerplate, infrastructure, UI, utilities, tests, and repetitive implementation.

The learner must personally design and implement important CCAR-F concepts such as:

- Agent architecture
- Agent boundaries
- Delegation strategy
- Agent prompts
- Tool schemas
- Tool permissions
- `tool_choice`
- MCP architecture
- Context strategy
- State persistence and resumption
- Output schemas
- Synthesis logic
- Confidence and uncertainty handling
- Human-review routing

## Project Approach

The project will be built incrementally.

Each phase should introduce:

1. A new capability
2. A CCAR-F concept
3. A hands-on implementation
4. Deliberate failure scenarios
5. Testing and debugging
6. An exam-style architecture challenge

The goal is to understand **why** an architecture or configuration is appropriate, not merely memorize exam answers.
