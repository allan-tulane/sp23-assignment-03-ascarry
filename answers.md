# CMPS 2200 Assignment 3
## Answers

**Name:**____Abby Scarry_____________


Place all written answers from `assignment-03.md` here for easier grading.






- **b.**
What are the recurrences for the Work and Span of this solution? What are their Big Oh solutions?

The recurrence of the work is W(n) = W(n-1)+1 which is O(n)
The recurrence for the span is S(n) = S(n-1)+1 which is also O(N)

- **d.**
Assume that any `map`s are done in parallel, and that we use the efficient implementation of `scan` from class. What are the recurrences for the Work and Span of this solution?

The recurrence for work of scan is W(n) = W(n/2) + n which is O(n)
The recurrence for span of scan is S(n) = S(n/2) + 1 which is O(logn)
The recurrence for work of reduce is W(n) = 2W(n/2) + 1 which is O(n)
The recurrence for span of scan is S(n) = S(n/2) + 1 which is O(logn)

- **f.**
Assuming any recursive calls are done in parallel, what are the recurrences for the Work and Span of this solution? What are their Big Oh solutions?
The recurrence for the work is W(n) = 2W(n/2) + 1 which is O(n)
The reccurrence for the span of the function is S(n) = S(n/2) + 1 which is O(logn)
