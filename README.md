# AI-HW1
This is homework no. 1 of the "Artificial Intelligence" course in the spring semester of 2021 at Shiraz University.

## Question 1
Write a PEAS description of the task environment and environment features (discrete or continuous, fully or partially observable, etc.) for the following:
1. Tennis against the wall agent.
2. Digikala site

## Question 2
From the five types of agents (simple reflex agent, model-based reflex agent, goal-based agent, utility-based agent, learning agent), which of the following agents fit in? Justify your answer.
1. Playing soccer agent.
2. Exploring the subsurface ocean of titan agent.
3. Bidding on an item at an auction agent.

## Question 3
You are trying to recover a password to an encrypted file, by using search methods. 
You know that the password is up to 10 letters long and contains only the letters *'A'*, *'B'*, *'C'*.
You formulate a search problem as following:
- The initial state is the empty string.
- The successor function is to append one letter (A, B, or C) to the string.
- The goal test is to verify a candidate’s password using the decryption software. There are 6 correct passwords: *AAACCC*, *ABBCC*, *BABAB*, *BCABACB*, *CBAC*, and *CBACB*.
- Assume that all ties are broken alphabetically. For example, if there is a tie between states *'A'*, *'B'*, and *'C'*, expand *'A'* first, then *'B'*, then *'C'*.

1. Will breadth-first search return the correct password? Justify your answer.
2. Will depth-first search return the correct password? Justify your answer.
3. You suspect that some letters are more likely to occur in the password than others. You model this by setting *cost(A) = 1*, *cost(B) = 2*, *cost(C) = 3*. Will uniform cost search return the correct password? Justify your answer.

## Question 4
For each of the following graph search strategies, work out the order in which states are expanded, as well as the path returned by graph search.

In all cases, assume ties resolve in such a way that states with earlier alphabetical order are expanded first. The start and goal state are S and G, respectively.

Remember that in graph search, a state is expanded only once.

<p align="center">
  <img src="https://s6.uupload.ir/files/graph_mmqo.png" alt="Graph."/>
</p>
