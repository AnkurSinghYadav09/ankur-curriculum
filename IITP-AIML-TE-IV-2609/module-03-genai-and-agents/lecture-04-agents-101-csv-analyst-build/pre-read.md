# Pre-Read: Agents 101: CSV Analyst Build

**Batch:** IITP-AIML-TE-IV-2609
**Module:** 03 — genai-and-agents
**Week:** 14 | **Session:** 14.2
**Taken by:** Industry Mentor

---

## Why this matters
_One or two lines on where this session fits in the batch journey._

## Topics covered
- Builds on 14.1: put validated tool calls inside a loop that decides the next step
- Agents 101 (basics): what makes an agent
- single agent with 1-2 tools in a tool registry, described by JSON schemas
- the ReAct loop
- idempotent tool design so the loop's retries are safe
- short-term memory: the message history the loop carries between steps
- hard stop on iterations
- mini-build: CSV Analyst over the orders data (FAQ Helpdesk as the alternative)

## Learning objectives
By the end of this session, learners can:
- Describe what makes a system an agent rather than a single LLM call
- Build a tool registry exposing several Python functions to an agent
- Implement a ReAct loop that calls a tool and feeds the observation back
- Implement an agent that chains two dependent tool calls to answer one question
- Implement an idempotent tool that returns the same result when an agent repeats a call
- Configure a stopping rule limiting an agent's iterations and total tool calls

## Prerequisites
- _Prior session / concept needed before class._

## Key terms
| Term | Meaning |
|------|---------|
| _term_ | _definition_ |

## Come to class ready to answer
- _Warm-up question 1_
- _Warm-up question 2_

## Optional deeper dives
- _Resource link_
