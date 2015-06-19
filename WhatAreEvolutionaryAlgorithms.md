## Introduction ##
Evolutionary computation is a subfield of artificial intelligence that involves combinatorial optimization problems. It uses iterative progress, such as growth or development in a population. This population is then selected in a guided random search using parallel processing to achieve the desired end. Such processes are often inspired by biological mechanisms of evolution.

An evolutionary algorithm is a subset of evolutionary computation. They are stochastic search methods that mimic the metaphor of natural biological evolution. Evolutionary algorithms operate on a population of potential solutions applying the principle of survival of the fittest to produce better and better approximations to a solution. At each generation, a new set of approximations is created by the process of selecting individuals according to their level of fitness in the problem domain an d breeding them together using operators borrowed from natural genetics. This process leads to the evolution of populations of individuals that are better suited to their environment than the individuals that they were created from, just as in natural adaptation.

Evolutionary algorithms model natural processes, such as selection, recombination, mutation, migration, locality and neighborhood.


## Implementation of biological processes ##
Usually, an initial population of randomly generated candidate solutions comprise the first generation. The fitness function is applied to the candidate solutions and any subsequent offspring.  In selection, parents for the next generation are chosen with a bias towards higher fitness. The parents reproduce by copying with recombination and/or mutation. Recombination acts on the two selected parents (candidates) and results in one or two children (new candidates). Mutation acts on one candidate and results in a new candidate. These operators create the offspring (a set of new candidates). These new candidates compete with old candidates for their place in the next generation. This process can be repeated until a candidate with sufficient quality (a solution) is found or a previously determined computational limit is reached.

## Evolutionary algorithm techniques ##
Similar techniques differ in the implementation details and the nature of the particular applied problem.

  * **Genetic algorithm** - One seeks the solution of a problem in the form of strings of numbers virtually always applying recombination operators in addition to selection and mutation.
  * **Genetic programming** - Here the solutions are in the form of computer programs, and their fitness is determined by their ability to solve a computational problem.
  * **Evolutionary programming** - Like genetic programming, only the structure of the program is fixed and its numerical parameters are allowed to evolve.
  * **Evolution strategy** - Works with vectors of real numbers as representations of solutions, and typically uses self-adaptive mutation rates.

## References ##
  * http://en.wikipedia.org/wiki/Evolutionary_computation
  * http://en.wikipedia.org/wiki/Evolutionary_algorithm
  * http://www.geatbx.com/docu/algindex-01.html