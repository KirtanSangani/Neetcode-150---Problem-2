# Problem 1929: Concatenation of Array

7/09/2025

## Thought Process
I knew this would be another for loop problem. The idea is to just traverse through the nums list and appending the values to another list. My initial thought, to save space, was to just use one list; however, a syntax error would happen as a result, so I stuck with using two Lists. 

##  Solution
I created my ans list, and traversed through the num list. I put all the num variables into their respective spots and then added     (len(nums)) to the i index to be able to reach the further indexes. After the for loop ran, I returned the ans list. 

Initial solution - 0 ms

Complexity - O(n)

## Takeaways
I learned more about traversing through a list and being able to concatenate arrays with different sizes.
