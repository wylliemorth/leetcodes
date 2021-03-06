# [Two Sum](https://leetcode.com/problems/two-sum/)

**_Difficulty:_** easy

Given an array of integers `nums` and an integer `target`, return _indices of the two numbers such that they add up to `target`_.

You may assume that each input would have **\*exactly\* one solution**, and you may not use the _same_ element twice.

You can return the answer in any order.

**Example 1:**

```
Input: nums = [2,7,11,15], target = 9
Output: [0,1]
Output: Because nums[0] + nums[1] == 9, we return [0, 1].
```

**Example 2:**

```
Input: nums = [3,2,4], target = 6
Output: [1,2]
```

**Example 3:**

```
Input: nums = [3,3], target = 6
Output: [0,1]
```

_Even though it isn't shown in the examples, numbers don't have to be sequential._

**Constraints:**

-   `2 <= nums.length <= 10^4`
-   `-10^9 <= nums[i] <= 10^9`
-   `-10^9 <= target <= 10^9`
-   **Only one valid answer exists.**

**Follow-up:** Can you come up with an algorithm that is less than `O(n^2) `time complexity?

## Solutions

-   Solution O(n^2):
    ![image-20210823142342720](python/basic.png)

-   Solution O(n):
    ![](python/on.png)
