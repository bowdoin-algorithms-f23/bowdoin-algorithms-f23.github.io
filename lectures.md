---
layout: default 
title: Detailed schedule
nav_order: 6
---


### Detailed schedule (Fall 2023)

### Week 1: Warmup (bubble sort, insertion sort, selection sort) and analysis.

_August 30-September 1_

__Objectives:__ 
  * Understand searching (linear search, binary search) and simple sorting (bubble sort, selection sort, insertion sort) and be able to analyze  and apply  them to various inputs
  * Understand the basics of algorithm analysis, big-Oh notation,  best-case and worst-case analysis

__Resources:__     
  * __Notes:__ [LN-warmup.pdf](../docs/LN-warmup.pdf)     
  *  __Lab:__   [Lab 1](../docs/lab1.pdf), [python-warmup.ipynb](../docs/python-warmup.ipynb), [python-insertionSort.ipynb](../docs/python-insertionSort.ipynb)
  
 ***
 
 
 
### Week 2: Asymptotic Notation and Summations

_September 4-8_

__Objectives:__ 
* Understand the relevance of analysis in practice, as well as its assumptions and limitations
* Understand the definitions of O(), Ω(), Θ()
* Understand the rate of growth of common functions
* Find the rate of growth of a function
* Compare the order of growth of two arbitrary functions f(n), g(n)
* Analyze basic algorithm running times using O(), Ω(), Θ() 
* Understand arithmetic and geometric summations and their Θ() bound 
* Recognize arithmetic and geometric summations in different forms and give Θ() bounds


__Resources:__    
  * __Notes:__ [LN-asymptoticNotation.pdf](../docs/LN-asymptoticNotation.pdf),  [LN-summations.pdf](../docs/LN-summations.pdf), [quiz2-practice.pdf](../docs/quiz2-practice.pdf)
  * __Lab:__   [Lab2](../docs/lab2.pdf) 
  
***
      
   
### Week 3: Mergesort and Recurrences
_September 11-15_

__Objectives:__ 
* Understand Mergesort: how it works, why it works, and its running time analysis
* Understand how to express the running time of recursive algorithms using recurrences
* Solve recurrences by repeated iteration
* Recognize broadly classes of recurrences ( logarithmic, linear, Θ(n lg n), exponential)

__Resources:__    
  * __Notes:__ [LN-recurrences.pdf](../docs/LN-recurrences.pdf), [quiz3-practice.pdf](../docs/quiz3-practice.pdf)
   * __Lab:__   [Lab3](../docs/lab3.pdf) 
   
 ***



### Week 4: Quicksort and Heapsort 
_September 18-22_

__Objectives:__ 
* Understand Lomuto partition, Quicksort, Randomized-Quicksort and analysis
* Understand  how the binary heap is defined and the operations supported  (deleteMin, insert, heapify, buildheap) along with  analysis 
* Understand how Heapsort works in place 
* Be able to use the heap as a tool to solve new problems 



__Resources:__     
* __Notes:__ [LN-heapsort.pdf](../docs/LN-heapsort.pdf), [LN-quicksort.pdf](../docs/LN-quicksort.pdf),  [slides-heaps.pdf](../docs/slides-heaps.pdf) ; [slides-quicksort.pdf](../docs/slides-quicksort.pdf)
* __Lab:__   [Lab4](../docs/lab4.pdf)   

 ***
  
  
  
### Week 5: Sorting lower bound. Sorting without comparisons. 
_September 25-29_

__Objectives:__ 
* Can a sorting algorithm do better than Θ(n lg n) in the worst-case? Understand the comparison-based sorting lower bound, when it applies and what assumptions it makes
* Non-comparison sorting: Understand BucketSort and CountingSort,  their analysis and assumptions

__Resources:__     
  * __Notes:__ [LN-linsort.pdf](../docs/LN-linsort.pdf)
 * __Lab:__  [Lab5](../docs/lab5.pdf),  [python-mergeSort.ipynb](../docs/python-mergesort.ipynb), [python-quickSort.ipynb](../docs/python-quicksort.ipynb)
          
 ***




### Week 6: Exam 1 review and exam 1. Selection. 
_October 2-6_

__Objectives:__ 
* The selection problem
* Quick-Select
* An elegant and ingenious algorithm for selection that runs in O(n) worst-case.

__Resources:__
  * __Notes:__  [LN-selection.pdf](../docs/LN-selection.pdf) 
  * __Lab:__   [Lab6](../docs/lab6.pdf) 
  *   Exam1 in class
  
 ***

What do you do when you want to solve a problem and you don't know where to start? Although there are no recipes, there are some techniques that come up frequently.  

### Week 7: Divide-and-conquer
_October 11-13 (half week)_

__Objectives:__ 
* Understand how  D&C works in general 
* Understand the D&C algorithms for integer multiplication and matrix multiplication (Karatsuba and Strassen) 
* Apply D&C to new problems

__Resources:__
  * __Notes:__ [LN-divideAndConquer.pdf](../docs/LN-divideAndConquer.pdf)
   * __Lab:__   [Lab7](../docs/lab7.pdf)
          
***
 

### Week 8, 9: Dynamic Programming 
_October 16-27_

__Objectives:__ 
* Understand  how  dynamic programming  works
* Understand the  examples discussed in  class (Fibonacci, board game, rod cutting and knapsack) (including justification of correctness and analysis) 
* Apply DP to new problems 

__Resources:__
* __Lecture notes:__ [LN-dynprog.pdf](../docs/LN-dynprog.pdf), [LN-rod.pdf](../docs/LN-rod.pdf), [rod-summary.pdf](../docs/summary-rod.pdf), [LN-knapsack.pdf](../docs/LN-knapsack.pdf), [knapsack-summary.pdf](../docs/summary-knapsack.pdf)
 * __Lab:__   [Lab8](../docs/lab8.pdf) , [Fibonacci.ipynb](../docs/python-Fibonacci.ipynb),   [Lab9](../docs/lab9.pdf), [rodcutting.ipynb](../docs/python-RodCutting.ipynb)
  
 ***
 
 
 
### Week 10: More DP examples and the Greedy technique. Exam2 review.  
_October 30-November 3_

__Objectives:__ 
* The greedy technique vs. DP
* Activity selection, including the correctness justification
* Apply the greedy technique to new problems
  
__Resources:__
* __Lecture notes:__ [LN-greedy.pdf](../docs/LN-greedy.pdf),  [LN-lcs.pdf](../docs/LN-lcs.pdf) ; [LN-review.pdf](../docs/LN-review.pdf) ; [lcs.ipynb](../docs/python-LCS.ipynb) ; [summary-lcs.pdf](../docs/summary-lcs.pdf)
* __Lab:__   [Lab10](../docs/lab10.pdf) 
* Exam 2 in class

***



### Week 11, 12: Graphs: Basics, BFS and DFS and their applications.  Topological order.
_November 6-17_

__Objectives:__ 
* Compare and contrast the adjacency list and adjacency matrix representation of a graph 
* Compare and contrast different types of graph: sparse, complete, dense, trees
* Understand basic graph problems:  path, connectivity, connected components, reachability
* Understand breadth-first and depth-first traversals, their complexity,  and their properties 
* Understand  the concept of topological order and the two algorithms for computing a topological order 

__Resources:__
*  __Lecture notes:__ [LN-graphBasics.pdf](../docs/LN-basics.pdf), [LN-bfsdfs.pdf](../docs/LN-bfsdfs.pdf), [LN-topsort.pdf](../docs/LN-topsort.pdf)
*  __Lab:__   [Lab11](../docs/lab11.pdf) 

***
 
 
 
### Week 12, 13, 14:    Shortest paths on DAGs,  Dijkstra and  Bellman-Ford. 
_November 13-30_

We discuss shortest paths on graphs and see some of the nicest
algorithms in computer science: Dijkstra's and Bellman-Ford's
algorithms. While describing them we try to understand some common
principles that guided their design. We'll see that Bellman-Ford's
algorithm uses dynamic programming and Dijkstra's is a greedy
algorithm, making these nice applications of the techniques we studied
earlier in the semester.


__Objectives:__

* Understand the algorithms for computing shortest paths explained in
the notes: how they work, why they work, and their analysis

__Resources:__
*  __Lecture notes__:  [LN-shpaths.pdf](../docs/LN-shpaths.pdf), [LN-mst.pdf](../docs/LN-mst.pdf), [LN-mst-summary.pdf](../docs/LN-mst-summary.pdf), 
*  __Lab:__   [Lab12](../docs/lab12.pdf)  , [Lab13](../docs/lab13.pdf)
  
 ***
 


 
### Week 14, 15: The Minimum Spanning Tree (MST) 
_November 27-December 8_

Another fundamental problem on graphs is computing a MST. We discuss
some properties of MSTs which will get us intuition for how to
compute an MST efficiently. We'll glance at two well-known algorithms,
Prim's and Kruskal's, which are both greedy algorithms much in the
spirit of Dijkstra.  Their correctness follows from a neat result
called The Cut Theorem.



__Objectives:__ 
* Understand the concept of MST (minimum spaninng tree) in a graph, and be able to answer basic questions about it sproperties
* Know the general idea of Kruskal's and Prim's algorithms, and the Cut Theorem which captures their correctness

__Resources:__
*  __Lecture notes__:  [LN-shpaths.pdf](../docs/LN-shpaths.pdf), [LN-mst.pdf](../docs/LN-mst.pdf), [LN-mst-summary.pdf](../docs/LN-mst-summary.pdf), 
*  __Lab:__    [Lab14](../docs/lab14.pdf) 
  
 ***
 
 
### Last lecture
_December 8_

A quick review and some extra fun problems!
__Resources:__
* __Notes:__  [LN-review.pdf](../docs/LN-review.pdf)
                    
***

### Exam 3: [final exam slot will be posted in Polaris]


