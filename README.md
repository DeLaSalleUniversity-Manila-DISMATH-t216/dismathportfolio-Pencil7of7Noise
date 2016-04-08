# My DISMATH Portfolio
dismathportfolio-Pencil7of7Noise created by Classroom for GitHub
- Keith Ivan B. Maderazo
- EL


# WEEK 1
- Discrete Mathematics is the study of distinct and countable objects.
- Mathematical proof of a proposition is a chain of logical deductions leading to the preposition from a base set of axioms.
- Prepositions are declarative statements that can either only be true or false.
- Logical Deduction is a process of reasoning from one or more premises to reach a logically certain conclusion.
- Axioms are prepositions that are established, accepted, or self-evidently true.
- Logical Connectives
  1. Negation Operator
  2. Conjunction Operator
  3. Disjunction Operator
  4. Exclusive or Operator
  5. Conditional Operator
  6. Biconditional Operator
- Propositional variables are variables expressing or representing proposition/s.
- Truth Table lists all possible combinations of the input with their corresponding output.
- Bitwise operation uses logical operators one by one.
- Logical expressions are composed of propositional variables with logical connectives.
- I can't believe I still can't remember my favorite quote.

# WEEK 2

- Logical Equivalences
  1. Identity Laws
  2. Domination Laws
  3. Negation Laws
  4. Double Negation Laws
  5. Idempotent Laws
  6. Commutative Laws
  7. Associative Laws
  8. De Morgan's Laws
  9. Absorption Laws
- Conversion of a statement reverses the role of the antecedent with the consequent.
- Inverse of a statement negates the original statement.
- Contraposition of a statement is the combination of conversion and inversion, and it is equivalent to the original statment.
- Predicate Logic is when the internal structures of the propositions: subjenct and predicate; are concerned and not the statement as a whole.
- Quantifiers indicate the generality of the open sentences in which a variable occurs.
  1. Universal Quantifiers (for all)
  2. Existential Quantifiers (there exists)
- Counterexamples disprove a universal claim.
- Substitution can't prove a universal claim.
- Rules of Inference
  1. Modus Ponens
  2. Modus Tollens
  3. Hypothetical Syllogism
  4. Disjunctive Syllogism
  5. Addition
  6. Simplification
  7. Conjunction
  8. Resolution
- Argument-sequence of statements that end with a conclusion.
- Valid-the conclusion must follow from the truth of the preceding statements of the argument; may either be true or false.
- Fallacy-common form of incorrect reasoning which leads to invalid arguments.
- Tautology-statement that is always true.
- Superman isn't real.

# WEEK 3

- Proof
  - Methods of Proof
    1. Direct Proof
    2. Proof by Contraposition (indirect)
    3. Vacuous & Trivial Proof
    4. Proof by Contradiction (indirect)
- Closure property states that theresult would be part of the same set as its conditions.

# WEEK 4
- Proof
  - Methods of Proof
    -e. Mathematical Induction (=! Recursion)
- Recursion
  - Steps
    1. Basis Step
    2. Recursive Step
  - Recursive Algorithm-solves a problem by reducing it to an instance of the same problem.

# WEEK 5
- Program Correctness
   - Program Verification
    - 2 Steps
      1. Partial Correctness
        - Hoare Triple, p{S}q 
      2. Show program termination
    - Rules of Inferences
      - Composition Rule
      - Conditional Statement
- Power Series
  - Zeno's Paradox
   - Geometric Progression
 - f(x) defined inside a convergence (finite sum).
- Set Theory
  - Set
    - Empty Set
    - Membership
    - Set Builder Notation
    - Venn Diagram
      - Set Identities
        1. Commutative Laws
        2. Associative Laws
        3. Distributive Laws
        4. Identity Laws
        5. Complementation Laws
        6. Complement Laws
        7. Idempotent Laws
        8. Universal Bound Laws
        9. De Morgan’s Laws
        10. Absorption Laws
    - Subset
      - Power Set
        - set of all subsets
    - Cardinality
      - no. of elements a set contains
- Operator Precedence
  1. Parenthesis
  2. Negation
  3. Conjunction
  4. Disjunction
  5. Conditional
  6. Biconditional

# WEEK 6
- Functions
  - Co-domain
    - whole of y-values
    - assigns to final result
    - Range
      - subset of co-domain
  - Types
    - One-to-One
    - Onto Function
    - Bijection

# WEEK 7
- Algorithm
  - finite set of precise instructions for performing a computationn or for solving a problem
  - to instruct machines
    - Precondition-initial assertion; describes valid input
    - Postcondition-final assertion; should satisfy input
    - Iteration Table
      - used to help in understanding algorithms
  - Pseudocode
    - high-level description of algorithm that uses the structural conventions of a programming language
    - Properties
      - Input
      - Output
      - Definiteness
      - Correctness
      - Finiteness
      - Generality
  - Searching Algorithm
    1. Linear Serch-recommended for a small number of elements; sequential
    2. Binary Search-recommended for a large number of elements; dividing

# WEEK 8
- Algorithm
  - Sorting Algorithm
    1. Bubble Sort-right to left
    2. Insertion Sort-left to right
- swap operator
- Loop
    - for loop-start & end are known
    - while loop-uncertain end
    - no loop if incrementing
  - Greedy Algorithm
    - to know the best steo

# WEEK 9
- Growth of Functions
  - Big-O Notation (upper-bound)
  - Big-Ω Notation (lower-bound)
  - Big-ϴ Notation (both)

# WEEK 10
- Algorithm Time Complexity
  - ϴ(1)-constant complexity
  - ϴ(log n)-lograrithmic complexity
  - ϴ(n)-linear complexity
  - ϴ(n log n)-n log n complexity
  - ϴ(n^b), where b>1-polynomial complexity
  - ϴ(b^n), where b>1-exponential complexity
  - ϴ(n!)-factorial complexity
- log has a base of 2.

#WEEK 11
- Graph Theory
  - Graph
    - discrete structure containing vertices and edges
      - Vertex (Node)
        - Pendant Node
          - has one degree
          - 1 pendant-no circuit
          - 3 pendants-no path and circuit
        - Isolated Node-
      - Edge-has either one or twoe vertices associated with it called endpoints
    - Degree [of a Vertex]-no. of connection it makes
    - Handshaking Theorem
      - 2e = ∑deg(v); e=no. of edge/s; deg=degree; v=no. of vertex/ices
    - Subgraph
      -subset of an existing graph
    - Path (Route)
      -sequence of edges that begins at a vertex of a graph and travels form vertex to vertex along the edges of the graph
    - Circuit (Network)
      - path that returns to its initial position
    - Euler Circuits and Paths
      - contains every edge
      - (circuit) has even degree for each vertex
      - (path) has 2 vertices with odd degrees
        - Euler's Formula
          - r = e-v+2; r=no. of regions
    - Hamilton Circuits and Paths
      - passes through every vertex exactly once
    - Walk
      - open walk (path)
      - closed walk (circuit)
    - Matwices of Graphs
      - Adjacency Matrix
        - n by n zero-one matrix w/ 1 as (i,j)th entry when the nodes are adjacent, and 0 as ots (i,j)th entry when they are not                connected
    - Isomorphism of Graphs
      - equivalent graphs with different shapes
      - connections are preserved
    - Planar Graphs
      - graphs that can be drawn in the plane without edges having to cross
      - applies to somorphic graphs
    - Homeomorphic Graphs
      - supergraph
    - Kuratowski's Theorem
      - Elementary Subdivision-way to know if the graph is planar or not, and if it is homeomorphic or not

# WEEK 12 
- Graph Theory
  - Graph Coloring
    - minimal no. nodes such that no adjacent colors are the same
    - represent islands as nodes
    - Chromatic no. of Graphs
      - least no. of colors
        - planar-4
          - 4 Color Theorem
            - chromatic no. of a planar graph is no greater than 4
        - cycle
          - odd-3
          - even-2
        - K-sub-n-n
        - wheel
          - star-2
  - Tree
    - connected indirected graph woth no simple circuits
    - Parts
      - Root-head
      - Parent-on top of a node/s
      - Sibling-beside each other
      - Child-below a arent
      - Leaf-last part; no children
    - Forest-graph with at least 2 trees
    - Rooted Tree
      - designated root and every edges goes awau from it
      - Ordered Rooted Tree
        - children of each internal vertex are ordered
    - Internal Vertices
      - nodes w/ children
    - Subtree
      - cut at a certain point 
    - m-ary Tree
      - uniform no. of children
      - Binary Tree
        - m=2
    - Tree Traversal
      - form of graph traversal and refers to the process of visiting--checking and/or updating--each node in a tree data structure,          exactly once
    - Spanning Trees
      - subset of a graph, which has all the vertices covered with minimum possible number of edges
- Modeling Computation
  - task turns into 2 questions
    - Can it be done?
    - How?
  - Structures
    - Language and Grammars
      - Grammar
        - generate words in a language to determine whether a word is in a language
        - important in the construction and theory of compilers
      - Formal Language
        - provide models for both natural languages and programming languages
        - syntax>semantics
        - specified by a well-defined set of rules of syntax
      - Compiler
        - a program that reads a program written in a source language
      - Strings
        - common way to represent alphabets
        - Alphabet
          - defines strings
          - finite set of symbols
    - Finite-State Machines
      - Automata Theory
        - studies the laws of computation
        - Finite Automation
          - simplest model of a computing device
        - Lexical Analysis
          - stream of characters read from left-to-right and grouped into tokens
          - Tokens
            - sequence of characters w/ a collective meaning
      - M = (states, S; input, I; finite output, O; transitional function, f; output function, g; initial state, s-sub-0)
- Relations
  - A binary relation R from set to set is a subset of Cartesian product.
  - Properties
    - A relation on set A is a subset of AxA.
    - Relations over Integers
    - Functions as Relations
      - Relation over integers Z
      - Function from Z to Z
      - Function from A to B assigns exactly one element from B to each input from A
        - i.e., a functions is a restricted type of relation where every a in A is in exactly one ordered pair (a,b).
    - Reflexive Relation
    - Symmetric Relation
    - Antisymmetric Relation
    - Transitive Relation
    - Combining Relations
      - Composite Relation
        - Power of Relation
  - n-ary Relations
    - An n-ary relation involves n sets and can be described by a set of n-tuples.
  - Representing Relations
    - Matrix
    - Digraph
  - Closures of Relations
    - The closure of a relation R with respect to property P is the relation obtained by adding the minimum number of ordered pairs to       R to obtain property P. In terms of the digraph representation of R.
    - to find the reflexive closure, add loops
  - Equivalence Relations
    - is a binary relation that is at the same time a reflexive relation, a symmetric relation and a transitive relation
    - provides a partition of a set into equivalence classes
  - Partial Ordering
    - Partial Order
      - relations that are reflexive, antisymmetric, and transitive
