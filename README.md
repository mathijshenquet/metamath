# Metamath (working title)
Meta math aims to be a mathematical manipulation environment like Mathematica.

## Design goals

* Closely mimicking to mathematical notation and thought process.

  We want to be able to supply axiomatic rules and then immediately use them for mathematical manipulation. For example supplying the rules for a group should immediatly allow you to express and check proofs about groups. You should be able to visualize these mathematical structures then by predefined code which is kind of duck typed to these axioms.

* Clear separation between logic and display code

  The presentation code should be orthogonal to the logic of what you try to express. For example the size of a diagram/plot should be living in a different conceptual plane (math) then the function/object being shown (presentation).

* Easy modularization, metamath should encourage writing modules.

  Mathematica is horrible in this.


## Design

### Fronted

* React

* MathBox / ThreeJS

### Backend

* BabelJS / Flow

* TypeScript

* Some language that can compile to JS