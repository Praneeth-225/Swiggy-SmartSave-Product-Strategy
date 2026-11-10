# Swiggy SmartSave

**Reducing food delivery cancellations through predictive insights and intelligent order management**

> A Product Management case study focused on preventing order cancellations rather than just processing refunds.

**Independent portfolio project — not affiliated with Swiggy.**  
All figures, targets, and impact scenarios in this case study are illustrative hypotheses unless otherwise stated.

---

## Overview

Most cancellation work in food delivery starts **after** the customer taps “Cancel”. SmartSave starts earlier.

It predicts which orders are drifting toward failure, tells the customer the truth while there is still time to act, and only then offers choices.

**Core idea:**  
Prevent the cancellation, not just the refund.

### The Problem
A cancelled order creates cost for four parties at once:

| Stakeholder       | Cost of Cancellation                          |
|-------------------|-----------------------------------------------|
| Customer          | Time wasted, uncertainty, loss of trust       |
| Restaurant        | Lost revenue + food wastage                   |
| Delivery Partner  | Wasted trip + lost earnings                   |
| Platform (Swiggy) | Lost GMV, support load, weaker retention      |

Cancellations happen at different stages (preparation delay, late partner assignment, ETA drift, etc.). Research suggests that **ETA accuracy and delays before pickup** are major drivers of customer-initiated cancellations.

---

## Solution

**SmartSave** is an intelligent order-management layer built on top of the existing tracking experience.

### Recommended MVP (Phase 1)
**Smart ETA Prediction + Proactive Delay Alerts**

- Predict more realistic delivery times using restaurant prep history, kitchen load, partner availability, traffic, and order complexity
- Notify the customer early when a meaningful delay is predicted
- Show the **updated ETA + reason**
- Primary action: **Keep my order**
- Cancel remains fully available and transparent

### Future Phases
| Phase | Focus                              | Goal                              |
|-------|------------------------------------|-----------------------------------|
| 1     | Predictive ETA + Delay Alerts      | Reduce uncertainty & cancellations|
| 2     | Smart Alternative Recommendations  | Recover at-risk orders            |
| 3     | Restaurant–Partner Coordination    | Fix operational root causes       |

---

## Key Highlights

- **Target (pilot hypothesis):** ~20% reduction in order cancellation rate  
- **Illustrative impact:** ~1,600 orders potentially saved per month in a 100,000-order pilot  
- **Prioritisation:** 3 candidate solutions scored with **RICE** → Smart ETA selected as MVP  
- Research-grounded hypotheses from academic papers on on-demand delivery platforms  
- Clear goals, non-goals, success metrics, and guardrails  
- Full product design: user journey, wireframes, alert logic, and acceptance criteria  
- Proper experiment design (A/B test, sample size, primary/secondary/guardrail metrics)

---

## Approach & Frameworks Used

- Problem framing & stakeholder analysis  
- Research grounding (academic literature)  
- User personas (Customer + Restaurant partner)  
- Solution ideation + trade-off analysis  
- **RICE prioritisation**  
- Product design (journey mapping + wireframes)  
- Metrics & North Star definition  
- Risk assessment + A/B experiment design  
- Business impact modelling  

---

## Success Metrics (Proposed)

**North Star:** Completed orders per 100 orders placed, within the promised ETA window

| Metric                          | Proposed Target     | Type      |
|---------------------------------|---------------------|-----------|
| Order cancellation rate         | –20%                | Primary   |
| Customer-initiated cancellations| –25%                | Primary   |
| Late deliveries                 | –15%                | Secondary |
| Order-tracking engagement       | +20%                | Secondary |
| Cancellation-related support    | –20%                | Secondary |

---

## Project Structure
