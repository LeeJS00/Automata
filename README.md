# Automata
CSED341: Automata & Formal Languages

## Book

Introduction to Automata Theory, Languages, and Computations
by John E. Hopcroft, Rajeev Motwani, Jeffrey D. Ullman.

---

## 1. Preliminaries

- Formal proof
    - adequate proof
    - Deduction
    - Induction
    - Contradiction
- Automata theory
    - study of abstract computing machines or models
- Alphabets(∑)
    - Finite, non-empty set of symbols
- Strings
    - finite sequence of symbols
    - empty string ε. |ε| = 0
    - Σ^k. length k. Σ^* ⇒ all strings
    - w^0 = ε, εw = wε =w, wv = connect
- Languages
    - A set of strings from Σ^*
- Finite automata
    - computing machines with finite number of states

---

## 2. Finite Automata

- start →, arc, final O*2
- DFA(Deterministic Finite Automata)
    - current state to only state
    - unique computation
    - M = (Q, Σ, δ, q0, F)
    - Q : finite state set
    - δ : transition function
    - q0 : start state
    - F : set of final state
- NFA(non-Deterministic Finite Automata)
    - several state at once
- Transition function δ(q,a)
    - state q, input symbol a
    - accept when end in final state
- Extended transition function \hat{\sigma}
    - 
- Transition diagram
    - state circle
    - transition function arrow
- Transition table
    - arrow → start state
    - * final state

---
