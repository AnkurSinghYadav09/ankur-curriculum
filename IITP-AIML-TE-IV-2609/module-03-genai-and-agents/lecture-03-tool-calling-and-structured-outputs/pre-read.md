# Pre-Read: Tool Calling & Structured Outputs

**Batch:** IITP-AIML-TE-IV-2609
**Module:** 03 — genai-and-agents
**Week:** 14 | **Session:** 14.1
**Taken by:** Industry Mentor

---

## Why this matters
_One or two lines on where this session fits in the batch journey._

## Topics covered
- Builds on 13.2: good text isn't enough, the model must call our code (e.g. look up an order) and return data we can trust
- function/tool calling round trip
- tool schemas
- structured outputs (JSON/validation) with Pydantic
- validate-and-repair for bad JSON
- retries/backoff on rate-limited LLM calls

## Learning objectives
By the end of this session, learners can:
- Construct a tool-calling schema describing one external function and its parameters
- Trace a single tool-calling round trip from model request to returned result
- Construct a JSON schema describing the fields a model response must return
- Configure an API call to return output conforming to a supplied schema
- Implement a validation and repair loop for malformed structured outputs
- Implement retry with exponential backoff and jitter for a request rejected by a rate limit

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
