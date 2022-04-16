<h1 align=center>
  Genetic-Algorithm
</h1>

**Genetic Algorithm made in python.**

I recommend you mess around with the code and understand how it works

<h2 align=center>
  Content
</h2>

The codebase is structured into three modules: `algorithms`, `problems`, and `utils`.

Inside of algorithms you find the implementation of the brute-force approach and the non-problem-specific parts of the implementation of the genetic algorithm.

`problems` contains all problem-specific parts related to the Knapsack problems, like the definition of `Things` and the problem specific fitness function for the genetic algorithm.

`utils` simply contains a utility function which i stole from stack overflow 😉

`genetic_algo.py` uses the brute-force approach to find the best solution for a given Knapsack problem and tries to find the same solution using the genetic algorithm and compares the performance.

`bruteforce_time.py` and `genetic_time.py` compare the needed time a brute-force or genetic algorithm needs for a given number of items. **Be careful the brute-force approach gets slow very fast.**

# Hope this helped you
