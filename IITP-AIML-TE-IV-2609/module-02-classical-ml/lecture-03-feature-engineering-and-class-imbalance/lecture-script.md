# Lecture Script: Feature Engineering & Class Imbalance

**Batch:** IITP-AIML-TE-IV-2609
**Module:** 02 — classical-ml
**Week:** 9 | **Session:** 9.2
**Taken by:** Industry Mentor

---

## Learning outcomes
By the end of this lecture, learners can:
- Extract calendar features such as day-of-week and month from a datetime column
- Aggregate transaction rows into per-customer recency, frequency and monetary features
- Construct a ratio or difference feature from two existing columns
- Diagnose a target-leaking engineered feature by tracing how it was constructed
- Apply class weighting or resampling to a training set with a rare positive class
- Encode a high-cardinality categorical column using frequency or target encoding

## Topics to cover
- Builds on 9.1: with clean inputs in place, raw columns still hide patterns, and cancelled orders are rare
- simple feature engineering from dates: day-of-week, month, hour
- count features: recency, order frequency and total spend per customer
- ratio features
- spotting a feature that leaks the target
- count and frequency encoding for many-valued columns
- class imbalance basics: resampling the rare cancelled orders now, and class weights as the model-side option practised in 10.2

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
