# Sum Two Lists

This function takes two lists of equal length and returns a new list where each element  
is the sum of the corresponding elements from the two input lists.

## How to use

1. Copy the function code into your Python file.

```python
def sum_two_lists(list1, list2):
    result_list = []
    for i in range(len(list1)):
        result_list.append(list1[i] + list2[i])
    return result_list
```
2. Call the function with two lists of the same length.

```python
print(sum_two_lists([1, 2, 3], [4, 5, 6]))
# Output: [5, 7, 9]
```
Example
list1 = [10, 20, 30]
list2 = [1, 2, 3]
result = sum_two_lists(list1, list2)
print(result)  # Output: [11, 22, 33]

Contact
Email: filippovychh@gmail.com
