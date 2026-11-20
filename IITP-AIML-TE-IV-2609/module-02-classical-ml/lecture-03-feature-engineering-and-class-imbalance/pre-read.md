# Pre-Read: Feature Engineering & Class Imbalance

**Batch:** IITP-AIML-TE-IV-2609
**Module:** 02 — classical-ml
**Week:** 9 | **Session:** 9.2
**Taken by:** Industry Mentor

---

## Why this matters
_One or two lines on where this session fits in the batch journey._

## Topics covered
- Builds on 9.1: with clean inputs in place, raw columns still hide patterns, and cancelled orders are rare
- simple feature engineering from dates: day-of-week, month, hour
- count features: recency, order frequency and total spend per customer
- ratio features
- spotting a feature that leaks the target
- count and frequency encoding for many-valued columns
- class imbalance basics: resampling the rare cancelled orders now, and class weights as the model-side option practised in 10.2

## Learning objectives
By the end of this session, learners can:
- Extract calendar features such as day-of-week and month from a datetime column
- Aggregate transaction rows into per-customer recency, frequency and monetary features
- Construct a ratio or difference feature from two existing columns
- Diagnose a target-leaking engineered feature by tracing how it was constructed
- Apply class weighting or resampling to a training set with a rare positive class
- Encode a high-cardinality categorical column using frequency or target encoding

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
