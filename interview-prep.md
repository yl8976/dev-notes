# Interview Prep

## Algorithms

### Randomized Algorithms

- Las Vegas Algorithm
  - Correct but only probably fast
- Monte Carlo Algorithm
  - Fast but only probably correct
- Atlantic City Algorithm
  - Bounded probabilistic polytime that are probably correct and probably fast
  - Correct at least 75% of the time (or in some versions 50%)

## Theory

- [MapReduce](https://en.wikipedia.org/wiki/MapReduce)

  - The canonical MapReduce example counts the appearance of each word in a set of documents:

    ```javascript
    function map(String name, String document):
      // name: document name
      // document: document contents
      for each word w in document:
        emit (w, 1)
    
    function reduce(String word, Iterator partialCounts):
      // word: a word
      // partialCounts: a list of aggregated partial counts
      sum = 0
      for each pc in partialCounts:
        sum += pc
      emit (word, sum)
    ```

- [Higher-order Functions](https://en.wikipedia.org/wiki/Higher-order_function)

  - Function that takes functions as input(s) or outputs a function(s)
  - [Lambda expression](https://en.wikipedia.org/wiki/Anonymous_function)

- Functional Programming

  - [Monads](https://en.wikipedia.org/wiki/Monad_(functional_programming))

