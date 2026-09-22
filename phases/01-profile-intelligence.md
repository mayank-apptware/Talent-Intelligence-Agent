# Phase 1 - Profile Intelligence

## Goal

Build an agent that converts employee documents into a reliable, structured employee profile.

## Flow

Employee Documents
→ Profile Agent
→ Structured Employee Profile
→ Validation

## CCAR-F Concepts

- Structured outputs
- JSON schemas
- Optional and nullable fields
- Enums
- Tool use
- `tool_choice`
- Extraction accuracy
- Few-shot examples
- Source metadata
- Uncertainty handling
- Targeted file reading

## Human Must Implement

- Employee profile schema
- Extraction prompt
- Tool schema
- `tool_choice`
- Evidence representation
- Uncertainty representation
- Validation strategy

## AI May Implement

- Project scaffolding
- File loading
- Document parsing
- Configuration
- Logging
- Basic test infrastructure
- Boilerplate

## Exercises

1. Extract a simple employee profile.
2. Add missing and ambiguous fields.
3. Handle conflicting information.
4. Add source metadata.
5. Test malformed/partial documents.
6. Compare prompt-based formatting with structured tool output.

## Failure Scenarios

- Missing fields
- Invalid enum values
- Fabricated information
- Truncated output
- Incorrect source attribution
- Ambiguous experience

## Completion Criteria

The agent produces a validated profile without inventing missing information and preserves uncertainty and source evidence.
