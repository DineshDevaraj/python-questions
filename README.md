# Easy
- Matrix Row Sums: Given a 2D matrix of integers, return an array where each element is the sum of a row. 
```
   Input: matrix (list[list[int]])
   Output: list[int] (row sums)
   Example:
      Input: [[1,2,3],[4,5,6]]
      Output: [6,15]
```

- Given a list of strings, group all anagrams together and return a list of groups. Two strings are anagrams if they contain the same characters in different order. The order of the groups and strings within groups does not matter.
 ```
    Input: ["eat","tea","tan","ate","nat","bat"]
    Output: [["eat","tea","ate"], ["tan","nat"], ["bat"]]
``` 

- You are given a list of words and an integer k. Return the k most frequent words. If multiple words have the same frequency, order them lexicographically (alphabetically). Aim for better than full sorting of all unique words if possible.
```
   Input: (words: list[str], k: int)
   Output: list[str]  # length k
   Example: 
      Input: ["i","love","i","python","love","love"], k=2
      Output: ["love","i"]
```

- You are given two sorted lists of integers a and b (ascending). Merge them into one sorted list without using sort() on the final result. The algorithm should be linear in len(a) + len(b).
```
  Input: (a: list[int]), b: list[int])
  Output: list[int]
  Example: 
    Input: [1,3,7], [2,3,10]
    Output: [1,2,3,3,7,10]
```

- You are given a list of integers. Return the sum of all even numbers in the list. If there are no even numbers, return 0. The solution should run in linear time with respect to the list size.
```
  Input: nums: list[int]
  Output: int  # sum of even values
  Example: 
    Input: [1, 2, 3, 4, 6]
    Output: 12
```

- Generate only even number using range function and without if condition
- Generate odd numbers using range function and without if condition

# Medium
- Moving Average

> Design and implement a MovingAverage class that processes a stream of numbers and computes the simple moving average (SMA) of the last k elements added. Your solution must support:   
> 
> MovingAverage(k): Initialize with window size k.
>
> next(val): Add val to the stream and return the current average of the last k elements 
(or fewer if < k elements exist). Must run in O(1) time on average.


- Rectange Overlap
```
   Input1 - tuple[x: int, y: int, h: int, w: int]
   Input2 - tuple[x: int, y: int, h: int, w: int]
   Output - True if they are overlapping else False
```

- Given k sorted linked lists (or sorted lists of integers), merge all of them into one sorted list and return it. 
```
   Input: list[list[int]]
   Output: list[int]
   Example:
      Input: [[1,4,5],[1,3,4],[2,6]]
      Output: [1, 1, 2, 3, 4, 4, 5, 6]
```

- Write a iterator to generate infinite series of even numbers
- Write a generator to generate infinite series of odd numbers

- What will be the output of the below code, tell me your interpretation of the output?
```
   import types, typing
   print(issubclass(typing.Generator, typing.Iterator))
   print(issubclass(types.GeneratorType, typing.Iterator))
```

- Implement the `countries` function in the below code in such a way that it will print all the countries in Europe
```
    for country in countries("Europe"):
	    print(n)
```

- What are decorators? Explain with an example

# Hard

- Implement B64 Encoding
- Implement Caesar Cipher
- Subset Sum
  1. You have n-number of network devices   
  2. Each device can support c1, c2, ..., Cn connections respectively
  3. You want to support at least m connections
  4. Find the minimum of devices required to support at least m connections 
  5. Return the index of respective devices without changing the order

- Given a string containing only the characters ()[]{}, determine if the brackets are valid. A string is valid if every opening bracket is closed by the same type and in the correct order. Return True or False.
```
   Input: expr (string)
   Output: boolean
   Example-1: 
      Input: "{[()]}"
      Output: True ; 
   Example-2:
      Input: "([)]"
      Output: False
```
