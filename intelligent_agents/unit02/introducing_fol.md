# Introducing First Order Logic
{: .hidden-title }

## Activity

Read chapter 8 of the core book Russell and Norvig (2021) and be prepared to discuss the concepts of first order logic with some worked examples and interactive discussions.

### Worked Example: Representing Family and Activity Information in First-Order Logic

This example demonstrates how to represent a small set of facts about three individuals—Bill, Pete, and Michael using First-Order Logic (FOL). It focuses on relationships (brotherhood), age order, and an individual activity.

Assume we are given the following facts:
- Bill, Pete, and Michael are brothers.
- Bill is the eldest, followed by Pete, then Michael.
- Pete is the only one who does sport.


### Step 1: Define the Constants and Predicates

#### Constants:

```Bill``` – represents Bill

```Pete``` – represents Pete

```Michael``` – represents Michael

#### Predicates:

```Brother(x, y)``` – x is a brother of y

```Elder(x, y)``` – x is older than y

```DoesSport(x)``` – x participates in sport

### Step 2: Encode the Facts in FOL
Brother Relationships: 
```FOL
Brother(Bill, Pete)
Brother(Bill, Michael)
Brother(Pete, Michael)

The Brother relation is symmetric and transitive, so the other pairs are implied.
```

Age Order (Bill > Pete > Michael):
```FOL
Elder(Bill, Pete)
Elder(Bill, Michael)
Elder(Pete, Michael)
```

Sport Activity:
``` FOL
DoesSport(Pete)
¬DoesSport(Bill)
¬DoesSport(Michael)
```
Or more concisely:
```FOL
∀x ((x ≠ Pete) → ¬DoesSport(x))
```

### Reflection

Reading this chapter gave me a clearer picture of how first-order logic builds on propositional logic to represent more complex ideas. I found it interesting how adding objects and relationships makes it possible to describe richer scenarios, like in the Wumpus World example. The idea that different logics have different "commitments" is interesting and makes sense; some systems are just better suited to certain types of problems. 

It’s clear that even powerful tools like first-order logic have their limits, however, especially when it comes to dealing with more subjective or fuzzy concepts. While it’s great for clearly defined facts and relationships, it struggles when the boundaries aren’t well defined, like when we're trying to capture personal opinions, cultural nuances, or vague descriptors such as “tall” or “delicious.” These kinds of "facts" often depend on context or perception, things which first-order logic isn’t equipped to handle. This limitation highlights why other approaches, like probabilistic reasoning or fuzzy logic, are sometimes needed to complement more formal systems.

## References

Russell, S. and Norvig, P. (2021) Artificial Intelligence, Global Edition : A Modern Approach. 4th edn. Harlow, UK: Pearson Education Limited. Available at: https://elibrary.pearson.de/book/99.150005/9781292401171.




[Back to Intelligent Agents](/intelligent_agents)