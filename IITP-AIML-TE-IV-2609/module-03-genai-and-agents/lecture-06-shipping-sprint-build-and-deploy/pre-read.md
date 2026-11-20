# Pre-Read: Shipping Sprint: Build & Deploy

**Batch:** IITP-AIML-TE-IV-2609
**Module:** 03 — genai-and-agents
**Week:** 15 | **Session:** 15.1
**Taken by:** Industry Mentor

---

## Why this matters
_One or two lines on where this session fits in the batch journey._

## Topics covered
- Builds on 14.2: the CSV Analyst agent runs in a notebook, which nobody else can use, so wrap it as a service and put it somewhere real
- a chat endpoint that takes a validated request and returns the agent's reply
- a request schema that rejects a malformed call before it reaches the agent
- provider keys as environment secrets rather than code
- deploying to a hosting platform and serving over HTTP
- the classic works-on-my-machine failure, and reading a deployment log to name the cause, usually a missing environment variable or a version mismatch
- then a fixed prompt set run against the live URL to record how the deployed service actually behaves

## Learning objectives
By the end of this session, learners can:
- Build a FastAPI chat endpoint that passes a validated request to an agent and returns its reply
- Construct a Pydantic request schema that rejects a malformed prediction request
- Configure provider credentials as environment secrets in a deployed service
- Deploy an LLM-backed endpoint that serves requests over HTTP
- Diagnose a service that runs locally but fails in the hosted environment
- Test a deployed endpoint against a fixed prompt set and record its pass rate

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
