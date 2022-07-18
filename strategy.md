---
layout: post
title: "My Strategy"
---

### My Strategy for OI Contests

#### General

* Focus at one problem at a time.
* Make sure to leave at least 1 hour for each problem.
* Spend at least 20 mins on each problem coding brute force.

#### Thinking
* Write down thoughts.
* If stuck over 10 mins, reread statements.
  * Weird conditions? Properties?
* Guess time complexity.
* Brainstorm known algorithms.
  * *String*: Suffix Array? KMP? Trie? DP?
  * *Tree*: Centroid / D&C? HLD? Tree Traversals?
  * *Graph*: DSU? Dijkstra? BCC? SCC? 2-SAT? Flows?
  * *Data-structure*: Segtree? Treap? Small to Large?
  * *Math*: DP? Pattern Finding?
* Others:
  * Greedy?
  * Sqrt?
  * Random?
  * Hashing?
  * Backwards?
  * Pattern Finding?
* Make sure to spend at least 10 mins thinking about each type of algorithm.
* Try to combine algorithms.
* Check your algorithm with samples.

#### Implementation
* Leavy heavy implementation for later.
* If estimated implementation time > 30 mins, think for an extra 10 mins.
* Unless it is something coded before many times, think carefully on paper before implementing.
* Stay organized.

#### Pre-submit
* Corner cases: $N=0$? $N=1$?
* Array bounds?
* Integer overflow?
* Solution fits in TL?
* Solution fits in ML?

#### Debugging
* Print statements
* Assertions

#### WA
* Reread statement?
* 100% algorithm works?
* Stress test?
* Array bounds? Mod? INF?
* Corner cases: $N=0$, $N=1$?
* Outputting correct format?
* Clearing DS between test cases?
* Unitialized variables?
* Undefined behavior? Array out of bounds?
* Integer overflow?
* `return` vs `continue` vs `break`?
* `std::` functions work as you think?
* Make test cases?
* Go through this list again?
* Make sense of every line?
* Small walk?
* Rewrite solution?

#### RTE
* Tested corner cases locally?
* Unitialized variables?
* Assertions might fail?
* Reading or writing out of range of arrays?
* Division by $0$?
* Infinite recursion?
* Invalidated pointeres/iterators?
* Too much memory?
* Use resubmits + assertions?

#### TLE
* Infinite loops?
* Time complexity too large?
* Use references instead of copying data?
* Avoid `std::vector`/`std::map`, use `std::array`/`std::unordered_map`.
* Pragmas?
* `std::multiset.count()` is $\mathcal O(K)$.

#### MLE
* Maximum amount of memory needed?
* Clearing data structures between test cases?
* If using pointers, use bump allocator.
