# Решение задач 

## LeetCode
1. [x] **Задача**: [Числа Фибоначчи](https://leetcode.com/problems/fibonacci-number/description/). 
      ```python
   # Example 1:
   Input: n = 2
   Output: 1
   
   # Example 2:
   Input: n = 3
   Output: 2
   
   # Example 3:
   Input: n = 4
   Output: 3
   ```
   [Решение](solutions/leetcode/fibonacci_number.md).
2. [x] **Задача**: [Палиндром](https://leetcode.com/problems/valid-palindrome/description/).
      ```python
   # Example 1:
   Input: s = "A man, a plan, a canal: Panama"
   Output: true
   
   # Example 2:
   Input: s = "race a car"
   Output: false
   ```
   [Решение](solutions/leetcode/paliandrom.md).
3. [x] **Задача**: [Flatten Nested List Iterator](https://leetcode.com/problems/flatten-nested-list-iterator/description/)
   ```python
   # Code for Test
   i, v = NestedIterator(nested_list), []
   while i.has_next(): v.append(i.next())
   print(v)
   
   # Example 1:
   Input: nested_list = [[1,1],2,[1,1]]
   Output: [1,1,2,1,1]
   
   # Example 2:
   Input: nested_list = [1,[4,[6]]]
   Output: [1,4,6]
   ```
   [Решение](solutions/leetcode/flatten_nested_list_Iterator.md).
4. [x] **Задача**: [Слияние интервалов](https://leetcode.com/problems/merge-intervals/description/)
   ```python
   # Example 1:
   Input: intervals = [[1,3],[2,6],[8,10],[15,18]]
   Output: [[1,6],[8,10],[15,18]]
   
   # Example 2:
   Input: intervals = [[1,4],[4,5]]
   Output: [[1,5]]
   ```
   [Решение](solutions/leetcode/merge_intervals.md).
5. [x] **Задача**: [Не перекрывающиеся интервалы](https://leetcode.com/problems/non-overlapping-intervals/description/)
   ```python
   # Example 1:
   Input: [[1,2],[2,3],[3,4],[1,3]]
   Output: 1
   
   # Example 2:
   Input: [[1,2],[1,2],[1,2]]
   Output: 2
   
   # Example 3:
   Input: [[1,2],[2,3]]
   Output: 0
   ```
   [Решение](solutions/leetcode/non_overlapping_intervals.md).
6. [x] **Задача**: [Обход бинарного дерева в обратном порядке](https://leetcode.com/problems/binary-tree-inorder-traversal/description/)
   ```python
   # Example 1:
   Input: root = [1,null,2,3]
   Output: [1,3,2]
   
   # Example 2:
   Input: root = [1,2,3,4,5,null,8,null,null,6,7,9]
   Output: [4,2,6,5,7,1,3,9,8]
   
   # Example 3:
   Input: root = []
   Output: []
   
   # Example 4:
   Input: root = [1]
   Output: [1]
   ```
   [Решение](solutions/leetcode/binary_three_inorder.md).
## Задачи с собеседований
1. [x] **Задача**: Написать функцию, которая проверяет правильность строки по скобкам.
    ```python
    # Example 1:
    Input: s = ()
    Output: True
   
    # Example 2:
    Input: s = (()
    Output: False
   
    # Example 3:
    Input: s = )
    Output: False
   
    # Example 4:
    Input: s = ()()((((()))))
    Output: True
    ```
   [Решение](solutions/litecode/сhecking_brackets.md).
2. [x] **Задача**: Вычислить если такие два числа в упорядоченном списке, сумма которых равна числу (number).
    ```python
    # Example 1:
    Input: func([1,2,3,4,5], 6)
    Output: True
   
    # Example 2:
    Input: func([1,2,3,4,5], 10)
    Output: False
    ```
    [Решение](solutions/litecode/search_equal_numbers.md).
3. [x] **Задача**: Написать бесконечный счетчик. Если передается число, то он ограничен. [Решение](solutions/litecode/infinite_counter.md).
4. [x] **Задача**: Написать декоратор, который выводит количество вызовов функции. [Решение](solutions/litecode/count_call_func.md).

## Задачи из прочих источников

1. [x] **Задача**: Реализуйте сортировку массива пузырьком. [Решение](solutions/others/bubble_sort.md).
2. [x] **Задача**: Дан массив nums, в котором содержится n+1 чисел в промежутке [1, n]. 
В массиве nums есть только одно число, которое повторяется несколько раз. Выведите это число. [Решение](solutions/others/find_duplicate.md).
3. 

