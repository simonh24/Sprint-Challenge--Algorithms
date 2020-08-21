#### Please add your answers to the ***Analysis of  Algorithms*** exercises here.

## Exercise I

a) The while loop is ran n * n * n times, so O(n^3)


b) The for loop is ran n times and the while loop inside is ran n/2 times. O(n^2/2) which about equals O(n^2)


c) Recursion runs at O(n)

## Exercise II
Suppose that you have an n-story building and plenty of eggs. Suppose also that an egg gets broken if it is thrown off floor f or higher, and doesn't get broken if dropped off a floor less than floor f. Devise a strategy to determine the value of f such that the number of dropped + broken eggs is minimized.

Write out your proposed algorithm in plain English or pseudocode AND give the runtime complexity of your solution.

for f in n:
    if egg.broken == true:
        return f

This will loop through until floor f is found from 0, so the runtime complexity will be O(n).