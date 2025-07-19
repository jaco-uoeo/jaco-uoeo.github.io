# Sets, Set Theory, Truth Tables and Logic
{: .hidden-title }

### Seminar Activity Summary

In this seminar, the focus was on constructing truth tables for various logical statements to determine when these statements are false. This practical exercise builds understanding of basic propositional logic, which is foundational in knowledge representation and reasoning.

The exercises are based on the definitions and concepts introduced in Sharma et al. (2022) on truth tables.

---

### Truth Tables and When Statements are False

Below are truth tables created for each logical clause (a) to (f), alongside an explanation of when each statement evaluates as false.

| Clause | Logical Statement | When is it False?                          |
|--------|-------------------|-------------------------------------------|
| a      | ¬P                | False when P is true.                      |
| b      | P ∧ Q             | False when either P or Q (or both) are false. |
| c      | P ∨ Q             | False only when both P and Q are false.   |
| d      | P → Q             | False only when P is true and Q is false. |
| e      | P ↔ Q             | False when P and Q have different truth values. |
| f      | P → ¬Q            | False when P is true and Q is true.       |

---

### Detailed Example: (∼Q) → (∼P) vs P → Q

**1. When is (∼Q) → (∼P) false?**  
It is false when the antecedent (∼Q) is true, and the consequent (∼P) is false. That is:  
- Q is false  
- P is true  

**2. When is P → Q false?**  
It is false when P is true and Q is false.

---

**3. Do (∼Q) → (∼P) and P → Q mean the same thing?**  
They do. These two statements are **contrapositives** of each other, which means they are logically equivalent. This can be verified by constructing their truth tables:

| P | Q | ¬Q | ¬P | (¬Q) → (¬P) | P → Q |
|---|---|----|----|-------------|-------|
| T | T | F  | F  | T           | T     |
| T | F | T  | F  | F           | F     |
| F | T | F  | T  | T           | T     |
| F | F | T  | T  | T           | T     |

Both columns for (¬Q) → (¬P) and P → Q match exactly.

---

### Constructing Truth Table for P XOR Q

| P | Q | P XOR Q |
|---|---|---------|
| T | T | F       |
| T | F | T       |
| F | T | T       |
| F | F | F       |

XOR (exclusive or) is true only when exactly one of P or Q is true.

---

### Truth Tables for Additional Statements

**1. ¬(P ∧ Q)**

| P | Q | P ∧ Q | ¬(P ∧ Q) |
|---|---|-------|----------|
| T | T | T     | F        |
| T | F | F     | T        |
| F | T | F     | T        |
| F | F | F     | T        |

**2. P ∨ (Q ∧ R)**

| P | Q | R | Q ∧ R | P ∨ (Q ∧ R) |
|---|---|---|-------|-------------|
| T | T | T | T     | T           |
| T | T | F | F     | T           |
| T | F | T | F     | T           |
| T | F | F | F     | T           |
| F | T | T | T     | T           |
| F | T | F | F     | F           |
| F | F | T | F     | F           |
| F | F | F | F     | F           |

**3. P ∨ (Q ∨ R)** and **(P ∨ Q) ∨ R**

These two are logically equivalent because OR is associative.

| P | Q | R | Q ∨ R | P ∨ (Q ∨ R) | P ∨ Q | (P ∨ Q) ∨ R |
|---|---|---|-------|-------------|-------|-------------|
| T | T | T | T     | T           | T     | T           |
| T | T | F | T     | T           | T     | T           |
| T | F | T | T     | T           | T     | T           |
| T | F | F | F     | T           | T     | T           |
| F | T | T | T     | T           | T     | T           |
| F | T | F | T     | T           | T     | T           |
| F | F | T | T     | T           | F     | T           |
| F | F | F | F     | F           | F     | F           |

**4. **

This is the logical equivalence (biconditional) P ↔ Q.

| P | Q | P → Q | Q → P | (P → Q) ∧ (Q → P) |
|---|---|-------|-------|-------------------|
| T | T | T     | T     | T                 |
| T | F | F     | T     | F                 |
| F | T | T     | F     | F                 |
| F | F | T     | T     | T                 |

---

### Reflection

Constructing these truth tables helps in visualising how different logical operators behave and when compound statements are true or false. It is especially useful for understanding logical equivalences, like the contrapositive relation between P → Q and (¬Q) → (¬P). This foundational knowledge supports more complex reasoning tasks and is directly applicable in knowledge representation, automated reasoning, and artificial intelligence.


### References
Sharma, G., Lo, N. and Pilling, G. (no date) Truth Tables. Available at: https://brilliant.org/wiki/truth-tables/ (Accessed: 6 May 2025).