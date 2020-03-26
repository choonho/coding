# Problem description
There are n non-negative integers. I am trying to create a target number by adding or subtracting this number appropriately. For example, to make the number 3 with [1, 1, 1, 1, 1], you can use the following five methods.

~~~
-1 + 1 + 1 + 1 + 1 = 3
+ 1-1 + 1 + 1 + 1 = 3
+ 1 + 1-1 + 1 + 1 = 3
+ 1 + 1 + 1-1 + 1 = 3
+ 1 + 1 + 1 + 1-1 = 3
~~~

Write the solution function to return the number of array numbers that can be used, the number of the target number, how to make the target number by adding and subtracting the numbers appropriately when the target is given as a parameter.

# Limitations
* The number given is 2 or more and 20 or less.
* Each number is a natural number between 1 and 50 inclusive.
* The target number is a natural number between 1 and 1000 inclusive.

# I/O example
 numbers | target | return 
----     | ---    | ----
[1,1,1,1,1] | 3   | 5

Input/Output Example Description
Same as the example in the problem.

# Coding

~~~python
def solution(numbers, target):
    answer = 0
    return answer


numbers = [1,1,1,1,1]
target =  3
result = soulution(numbers, target)
print(result)
~~~~
