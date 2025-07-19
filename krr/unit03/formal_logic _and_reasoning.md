# Formal Logic and Reasoning in Artificial Intelligence
{: .hidden-title }

## Activity 1: Formal Logic Puzzles

This activity explored two classical logic problems using **First-Order Logic (FOL)** to demonstrate how reasoning and formalization can uncover contradictions, resolve ambiguity, and support decision-making under uncertainty.



### 1. The Barber’s Paradox

**Problem**  
In a town, the following rules define the work of the barber:

- Anyone who does not shave himself **must be shaved** by the barber.  
- Anyone who **is shaved by the barber** must not shave himself.

The task is to show, using FOL, that no such barber can logically exist.

**Formalization**

Let:
```
shaves(x, y)` mean “x shaves y”
b represent the barber
```
We formalize the two regulations as:

```
1. ∀x (¬shaves(x, x) → shaves(b, x))
2. ∀x (shaves(b, x) → ¬shaves(x, x))
```

Now consider the case where `x = b`. Substituting into the above gives:

- From (1):  
```¬shaves(b, b) → shaves(b, b)```

This can only be true if `shaves(b, b)` is true.

- From (2):  
```shaves(b, b) → ¬shaves(b, b)```

Which leads to a contradiction.

**Conclusion**  
Since assuming both rules are true leads to a logical contradiction, the scenario is unsatisfiable. This paradox—originally posed by Bertrand Russell—illustrates the limitations of naive set membership and self-reference in logic systems.



### 2. The Canadian Puzzle (Truth-Teller and Liar)

**Problem**  
A traveler in Quebec needs to choose the correct path to Chicoutimi. He sees two locals—Henri and Pierre. One always tells the truth, the other always lies, but the traveler doesn't know who is who.

He must ask **Henri a single question** to determine the correct direction.

**FOL Vocabulary and Predicates**
- Constants: `henri`, `pierre`
- Question: `gauche` (Is left the correct way?)

Predicates:
- `TruthTeller(x)`
- `Answer-yes(x, q)`
- `True(q)`
- `Go-left`

Functions:
- `dit-oui(x, q)` → "Would x say yes to q?"
- `dit-non(x, q)` → "Would x say no to q?"

**Knowledge Base (KB)**

1. One inhabitant is a truth-teller, the other is not:  
`(TruthTeller(henri) ∧ ¬TruthTeller(pierre)) ∨ (¬TruthTeller(henri) ∧ TruthTeller(pierre))`


2. How people answer:
`∀x, q: Answer-yes(x, q) ↔ [(TruthTeller(x) ∧ True(q)) ∨ (¬TruthTeller(x) ∧ ¬True(q))]`


3. Truth of `gauche`:
`True(gauche) ↔ Go-left`


4. Meaning of `dit-oui`:
`True(dit-oui(x, q)) ↔ Answer-yes(x, q)`


5. Meaning of `dit-non`:
`True(dit-non(x, q)) ↔ ¬Answer-yes(x, q)`


**Solution Strategy**

To determine the correct direction using one question, the traveler can ask Henri:

> “Would you say no if I asked Pierre whether I should go left?”

In FOL:
```t := dit-non(henri, dit-oui(pierre, gauche))```

We can show:
```Answer-yes(henri, t) ↔ Go-left```

**Conclusion**

This cleverly constructed question guarantees a truthful answer about the direction—regardless of whether Henri is the liar or truth-teller. The logic structure uses nested reference and truth conditions to overcome incomplete information.

**Note on Entailment**

The KB alone does not entail whether `Go-left` is true or false. Two consistent models exist:
- One where `Go-left` is true
- One where `Go-left` is false

Only asking question `t` resolves the ambiguity.



## Activity 2: Formalizing a Crossing Problem in FOL

This task involved analyzing a “crossing problem” from the **Palomino et al. (2005)** paper (as discussed in Lecturecast), and expressing each state using **First-Order Logic**.


### Problem Overview

The setup involves four entities needing to cross a river:

- **F** = Farmer  
- **W** = Wolf  
- **G** = Goat  
- **C** = Cabbage  

Constraints:
- The farmer can only take one item with him.
- The goat cannot be left alone with the wolf or the cabbage.


### FOL Representation

We define two unary predicates:
- `Left(x)` — x is on the left bank
- `Right(x)` — x is on the right bank

Each **state** of the crossing is represented as a conjunction of these predicates.

#### Example Representation of States

**State S0:** (Start)
Left(F) ∧ Left(W) ∧ Left(G) ∧ Left(C)


**State S1:** Farmer crosses alone
Right(F) ∧ Left(W) ∧ Left(G) ∧ Left(C)


**State S2:** Farmer returns with goat
Left(F) ∧ Left(W) ∧ Left(C) ∧ Right(G)


**State S3:** Farmer crosses again with cabbage
Right(F) ∧ Left(W) ∧ Right(C) ∧ Right(G)

### References

Palomino, M., Martí-Oliet, N. and Verdejo, A. (2005) ‘Playing with Maude’, Electronic Notes in Theoretical Computer Science, 124(1), pp. 3–23. Available at: https://doi.org/10.1016/j.entcs.2004.07.012.


### Reflections

This activity demonstrated how logical representation can clarify dynamic problem-solving tasks. By expressing each state formally, it becomes possible to systematically verify constraints, avoid unsafe states, and model transitions logically. These representations also illustrate the power of logic-based AI in planning and reasoning under rules.

Through these activities, I strengthened my ability to translate natural-language problems into formal logic. Each puzzle showcased different aspects of reasoning—from uncovering contradictions to designing truth-preserving questions and modeling complex state transitions.

These foundational skills are directly applicable to areas such as knowledge representation, planning, and automated reasoning—core areas of artificial intelligence.