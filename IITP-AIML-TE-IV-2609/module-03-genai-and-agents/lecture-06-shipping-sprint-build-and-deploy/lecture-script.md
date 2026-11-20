# Lecture Script: Shipping Sprint: Build & Deploy

**Batch:** IITP-AIML-TE-IV-2609
**Module:** 03 — genai-and-agents
**Week:** 15 | **Session:** 15.1
**Taken by:** Industry Mentor

---

## Learning outcomes
By the end of this lecture, learners can:
- Build a FastAPI chat endpoint that passes a validated request to an agent and returns its reply
- Construct a Pydantic request schema that rejects a malformed prediction request
- Configure provider credentials as environment secrets in a deployed service
- Deploy an LLM-backed endpoint that serves requests over HTTP
- Diagnose a service that runs locally but fails in the hosted environment
- Test a deployed endpoint against a fixed prompt set and record its pass rate

## Topics to cover
- Builds on 14.2: the CSV Analyst agent runs in a notebook, which nobody else can use, so wrap it as a service and put it somewhere real
- a chat endpoint that takes a validated request and returns the agent's reply
- a request schema that rejects a malformed call before it reaches the agent
- provider keys as environment secrets rather than code
- deploying to a hosting platform and serving over HTTP
- the classic works-on-my-machine failure, and reading a deployment log to name the cause, usually a missing environment variable or a version mismatch
- then a fixed prompt set run against the live URL to record how the deployed service actually behaves

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
