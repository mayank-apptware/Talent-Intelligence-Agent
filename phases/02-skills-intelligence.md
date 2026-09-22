# Phase 2 - Skills Intelligence

## Goal

Transform the employee profile into an evidence-backed skills assessment.

## Flow

Employee Profile
→ Skills Analysis
→ Technical Skills
→ Domain Skills
→ Evidence
→ Skill Gaps

## CCAR-F Concepts

- Subagents
- AgentDefinition
- Subagent prompts
- Tool restrictions
- Context scoping
- Coordinator-to-subagent wiring
- Goal-oriented delegation
- Parallel execution

## Human Must Implement

- Agent boundaries
- Agent responsibilities
- Delegation strategy
- Subagent prompts
- Tool permissions
- Context passed to each agent
- Output schemas
- Parallel/sequential decisions

## AI May Implement

- Supporting utilities
- Type definitions
- Test fixtures
- Boilerplate
- Logging
- Basic test framework

## Exercises

1. Create a single skills agent.
2. Split it into specialized agents.
3. Run independent agents in parallel.
4. Restrict each agent's tools.
5. Introduce an incorrectly configured agent.
6. Diagnose missing permissions and wiring.

## Completion Criteria

Each agent has a clear responsibility, receives only necessary context/tools, and produces structured evidence that can be synthesized later.
