# Phase 3 - Multi-Agent Orchestration

## Goal

Build a coordinator capable of dynamically delegating work to specialized agents.

## Architectures

- Coordinator-worker
- Parallel execution
- Sequential pipeline
- Dynamic delegation

## CCAR-F Concepts

- Agentic loops
- Multiple tool calls
- Parallel subtasks
- Coordinator visibility
- Goal-oriented delegation
- Dynamic task generation
- Agent state

## Human Must Implement

- Coordinator architecture
- Delegation logic
- Agent prompts
- Parallelization decisions
- Dynamic task generation
- Context passed to subagents
- Result aggregation

## AI May Implement

- Supporting code
- Concurrency utilities
- Logging
- Test harnesses

## Exercises

1. Run independent research tasks in parallel.
2. Compare sequential vs parallel execution.
3. Generate a new subtask based on discovered information.
4. Restrict subagent tools.
5. Simulate a failed subagent.
6. Recover without restarting the entire workflow.

## Completion Criteria

The coordinator can dynamically delegate independent work while retaining control and visibility over the workflow.
