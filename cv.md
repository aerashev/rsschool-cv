# Erashev Aleksandr 
## Contacts

**Phone:** +7 (985) 979-86-98

**Telegram:** @aerashev

**E-mail:** [erashevaleksandr@yandex.ru](mailto:erashevaleksandr@yandex.ru)



## Info
My career started 6 years ago as an analyst. Over the years, I've learned a lot about information systems, from business requirements and metrics to integration interactions.
Having gained experience in the role of a systems analyst, I realized that I needed tangibility in my work, so I chose web development

## Skills
- Git
- .NET
- Python
- SQL
- Figma

## Code example
[Two Sum from leetcode.com](https://leetcode.com/problems/two-sum/)

**Description**:
>Given an array of integers nums and an integer target, return indices of the two numbers such that they add up to target.
You may assume that each input would have exactly one solution, and you may not use the same element twice.
You can return the answer in any order.

```java
class Solution {
    public int[] twoSum(int[] nums, int target) {
        for (int i = 0; i < nums.length; i++) {
            for (int j = i + 1; j < nums.length; j++) {
                if (nums[j] + nums[i] == target) {
                    return new int[] { i, j };
                }
            }
        }
        return null;
    }
}
```
