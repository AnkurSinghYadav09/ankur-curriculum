# Lecture Script: Agents 101: CSV Analyst Build

**Batch:** IITP-AIML-TE-IV-2609
**Module:** 03 — genai-and-agents
**Week:** 14 | **Session:** 14.2
**Taken by:** Industry Mentor

---

## Learning outcomes
By the end of this lecture, learners can:
- Describe what makes a system an agent rather than a single LLM call
- Build a tool registry exposing several Python functions to an agent
- Implement a ReAct loop that calls a tool and feeds the observation back
- Implement an agent that chains two dependent tool calls to answer one question
- Implement an idempotent tool that returns the same result when an agent repeats a call
- Configure a stopping rule limiting an agent's iterations and total tool calls

## Topics to cover
- Builds on 14.1: put validated tool calls inside a loop that decides the next step
- Agents 101 (basics): what makes an agent
- single agent with 1-2 tools in a tool registry, described by JSON schemas
- the ReAct loop
- idempotent tool design so the loop's retries are safe
- short-term memory: the message history the loop carries between steps
- hard stop on iterations
- mini-build: CSV Analyst over the orders data (FAQ Helpdesk as the alternative)

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
