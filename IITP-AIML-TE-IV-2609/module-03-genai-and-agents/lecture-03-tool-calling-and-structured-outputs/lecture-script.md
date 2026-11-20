# Lecture Script: Tool Calling & Structured Outputs

**Batch:** IITP-AIML-TE-IV-2609
**Module:** 03 — genai-and-agents
**Week:** 14 | **Session:** 14.1
**Taken by:** Industry Mentor

---

## Learning outcomes
By the end of this lecture, learners can:
- Construct a tool-calling schema describing one external function and its parameters
- Trace a single tool-calling round trip from model request to returned result
- Construct a JSON schema describing the fields a model response must return
- Configure an API call to return output conforming to a supplied schema
- Implement a validation and repair loop for malformed structured outputs
- Implement retry with exponential backoff and jitter for a request rejected by a rate limit

## Topics to cover
- Builds on 13.2: good text isn't enough, the model must call our code (e.g. look up an order) and return data we can trust
- function/tool calling round trip
- tool schemas
- structured outputs (JSON/validation) with Pydantic
- validate-and-repair for bad JSON
- retries/backoff on rate-limited LLM calls

## Agenda
| Time | Segment |
|------|---------|
| 0–5 min | Hook / recap of pre-read |
| 5–25 min | Core concept block 1 |
| 25–45 min | Core concept block 2 |
| 45–55 min | Live demo / walkthrough |
| 55–60 min | Q&A + wrap + next-session preview |

---

## 1. Hook / recap (0–5 min)
_Opening question or real-world framing._

## 2. Concept block 1 (5–25 min)
**Talking points**
- _point_

**Check for understanding**
- _question to ask the room_

## 3. Concept block 2 (25–45 min)
**Talking points**
- _point_

## 4. Live demo / walkthrough (45–55 min)
- _code / dataset / steps_

## 5. Wrap + Q&A (55–60 min)
- Three things they must remember
- Preview of next session
- Assignment / practice

---

## Instructor notes
- Common misconceptions: _..._
- Likely questions: _..._
