# Genesis Law

## Definition

Genesis defines a universal law of system evolution under constraints:

S_{t+1} = argmax_{S'} U(S')  subject to  Cost(S → S') ≤ B

Where:
- S — current system state
- S' — candidate next state
- U(S') — utility (fitness, performance, value)
- Cost(S → S') — transition cost
- B — available budget (compute, money, time, energy)

---

## Interpretation

Any system evolves by selecting the highest-utility reachable state within its constraints.

Genesis is not a model.  
It is an operator over state transitions.

---

## Core Invariants

### 1. Budget Constraint
No transition occurs if:
Cost(S → S') > B

---

### 2. Monotonic Selection
For any two valid states S1, S2:

If U(S1) > U(S2) and both satisfy budget,
then S1 dominates S2.

---

### 3. Pareto Dominance
A state S1 dominates S2 if:
- U(S1) ≥ U(S2)
- Cost(S → S1) ≤ Cost(S → S2)
- At least one strict inequality

Dominated states are eliminated from evolution.

---

### 4. Reachability
Only reachable states are considered:

Reachable(S') ⇔ Cost(S → S') is finite and computable

---

## Implications

- Evolution is constrained optimization
- Architectures emerge as optimal states
- Inefficient systems are unstable and replaced
- Innovation = discovery of higher U / lower Cost states

---

## Specialization (LLMs)

- S = model architecture + weights
- U = validation accuracy / loss
- Cost = parameters, FLOPs, latency
- B = memory / compute budget

---

## Statement

Genesis replaces static classification with dynamic selection.

It describes not what systems are,  
but how they inevitably change.