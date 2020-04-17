#### Please add your answers to the **_Analysis of Algorithms_** exercises here.

## Exercise I

```python
a)  a = 0 # O(1)
    while (a < n * n * n): # O(n)
      a = a + n * n # O(1)
```

This would have a runtime of O(n) --> linear time

```python
b)  sum = 0 # O(1)
    for i in range(n): # O(n)
      j = 1 # O(1 * n)
      while j < n: # O(n * logn) -> O(nlogn)
        j *= 2 # O(1)
        sum += 1 # O(1)
```

This would have a runtime of O(nlogn)

```python
c)  def bunnyEars(bunnies):
      if bunnies == 0:
        return 0 # O(1)
      return 2 + bunnyEars(bunnies-1) # O(n)
```

This would have a runtime of O(n)

## Exercise II

```python

# Binary search would be used to get the value of f


# Store Lowest and Highest floor based on number of stories n
# while Lowest < Highest:
#   Middle = Highest - Lowest // 2
#   if egg breaks at Middle:
#     set Highest to Middle and try again
#   elif egg does not break at Middle:
#     set Lowest to Middle and try again
#   else return Middle as f

# The runtime complexity of this solution is O(logn) since it is a binary search
```
