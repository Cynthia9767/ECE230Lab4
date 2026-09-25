# Lab 04 - SOP/POS and KMaps

In this lab, you’ve learned how to apply KMaps, Sum Of Products and Products of
sums to simplify digital logic equations. Then, you’ve proven out that they work
using an implemented design on your Basys3 boards.

## Rubric

| Item | Description | Value |
| ---- | ----------- | ----- |
| Summary Answers | Your writings about what you learned in this lab. | 25% |
| Question 1 | Your answers to the question | 25% |
| Question 2 | Your answers to the question | 25% |
| Question 3 | Your answers to the question | 25% |

## Lab Summary

Summarize your learnings from the lab here.

## Lab Questions

### Why are the groups of 1’s (or 0’s) that we select in the KMap able to go across edges?
They are able to go across edges because only one input value changes across edges.

### Why are the names Sum of Products and Products of Sums?
When you think of the AND operator as multiplication and the OR operator as adding, Sum of
Products translates to adding an amount of products from multiplication and Products of Sums
is multiplying several amounts of sums from adding.

### Open the test.v file – how are we able to check that the signals match using XOR?
XOR determines if they have the same value due to the property of XOR wherein it only
outputs 1 if only one input is 1.
