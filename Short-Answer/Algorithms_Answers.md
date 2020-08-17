#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

a) The while loop is O(n^3) complexity, but the inside is O(n^2). Since the inside controls how much each loop iterates through, we have to divide the complexities. So our TOTAL complexity is O(n^3/n^2) = O(n).

b) O(n^2) complexity. The while loop is O(n/2) complexity, but is nested inside a for loop that has O(n) complexity. Therefore it's O(n^2) \*We ignore the denominator in n/2.

c) O(n) complexity. Every recursion loop the value of the input (aka bunnies) is decreasing by 1. So no matter how many inputs there are, the recursion loop will grow by n.

## Exercise II

Start at floor 1 and drop an egg.
If the egg DOES NOT break, go up a floor.
Continue until the dropped egg breaks.
Return current floor number as "f".
Complexity: O(n). If "f" is low then we'd find it quickly, but if "f" was high then it would take awhile. Benefit is we only break 1 egg on the first floor that the egg breaks.
