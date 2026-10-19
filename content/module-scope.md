
# Module Scope — Algorithms, Data Structures & Connectionist AI

- **Team:** [Smash Bros]
- **Content Lead:** [攀焱霖-Elijah Hopple]
- **Version:** 1.1 · **Updated:** 19 Oct 2026
- **Audience:** a beginner with no prior CS or AI background, learning independently.
- **Theme:** a *fictional* FBI-style investigation. 

## Central Question

How can an analyst organize case information, search it efficiently, and judge a pattern flagged by an AI system, without mistaking a prediction for verified evidence?

## Scope at a Glance

| Area | Must cover (taught, practised, assessed) | Mention only | Out of scope |
|---|---|---|---|
| **Algorithms** | Algorithm vs. program; pseudocode and tracing; linear vs. binary search (sorted data required); intuitive O(1), O(log n), O(n) | Sorting as the way to prepare data for binary search | Formal proofs; algorithm-design theory |
| **Data structures** | Array/matrix, stack, queue, hash table, graph; BFS uses a queue, DFS uses a stack; choosing a structure for a task | Linked lists, priority queues | Trees, heaps, shortest-path algorithms; writing full programs |
| **Connectionist AI** | Neuron (inputs, weights, weighted sum, activation); layers; arrays/matrices holding inputs and weights; training vs. inference; learned patterns vs. fixed rules; errors (false positives and negatives), limited or unrepresentative training data, human verification | Which kinds of task suit neural networks (e.g., images) | Backpropagation calculus; large-scale deep learning and big data (a separate course module); real biometric or identification systems |

**Bridge:** a neural network is itself an algorithm running on arrays of numbers. Lookup and graph search organize the case around it; they do not recognize images.

## History & Key People

Briefly introduce the historical development of algorithms, data structures, and connectionist AI, from Euclid's early algorithm to modern neural networks.

Include one timeline slide and short explanations in the study guide. Historical context will support the main technical material without introducing advanced theory.

**Full timeline:** [History & Key People](history.md)


## Learning Objectives

A beginner can:

1. **Distinguish** an algorithm from a program and **trace** short pseudocode.
2. **Choose** a data structure for a given task and **justify** the choice.
3. **Trace** BFS and DFS on a graph of up to six nodes, give the visit order, and explain the queue/stack difference.
4. **Compare** the steps taken by linear and binary search. State hash-table lookup as *expected* O(1) but O(n) in the worst case (collisions).
5. **Calculate** the output of one artificial neuron by hand from arrays of inputs and weights.
6. **Explain** training vs. inference, and how unrepresentative training examples can cause errors or unfairness. *Data bias is not the neuron's "bias" parameter.*

## Core Activities

Each has a worked example, a learner exercise, an answer key, and a common-mistake check.

- **A. Follow a Lead:** look up a fictional record by exact ID (hash table), then trace a five-node contact graph with BFS (queue) and compare DFS (stack). *Exact-key lookup is not biometric matching.*
- **B. Evaluate an AI Lead:** given a fictional vehicle-image classifier, name its input and output, compute one neuron's output by hand, then judge a false-positive result and explain how thin training data could cause it. *A prediction is a lead, never evidence.*

## One Content, Three Deliverables

One reviewed Markdown source feeds all three; a correction is made there first, then pushed to every deliverable.

- **Study guide:** objectives, explanations, brief historical context, activities, answer keys, references.
- **Slides:** one historical timeline, diagrams of the graph, queue/stack, and neuron, plus worked examples.
- **Videos:** narrated BFS/DFS traces and the neuron calculation.

## Quality Gates

1. Each key concept follows: **correct term → own-words explanation → example → contrast with a related concept → beginner question + answer.**
2. Every objective has an explanation, an example, and an exercise with an answer key.
3. Activities are tested with a beginner outside the team; fix the Markdown first.
4. Every fact is checked against a source; every member can explain what they submit; AI drafts are human-verified.
5. Changes are committed to GitHub; the fictional disclaimer stays on every deliverable.

## Sources (checked 17 Oct 2026)

- **Russell & Norvig, *Artificial Intelligence: A Modern Approach*, 4th ed.**: Ch. 3 *Solving Problems by Searching* (BFS/DFS), Ch. 19 *Learning from Examples*, Ch. 21 *Deep Learning*. Chapters confirmed on the book's official site. Advanced; use it to verify, not to teach.
- **Brookshear & Brylow, *Computer Science: An Overview*, 13th ed.**: chapters *Algorithms*, *Data Abstractions*, *Artificial Intelligence*. Confirm the edition before adding page numbers.