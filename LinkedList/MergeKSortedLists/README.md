# Merge k Sorted Lists（合并 k 个排序链表）

**LeetCode 23**

- [英文版](https://leetcode.com/problems/merge-k-sorted-lists/)

- [中文版](https://leetcode-cn.com/problems/merge-k-sorted-lists/)

## 题目
合并 k 个排序链表，返回合并后的排序链表。请分析和描述算法的复杂度。

示例:
```
输入:
[
  1->4->5,
  1->3->4,
  2->6
]
输出: 1->1->2->3->4->4->5->6
```
## 思路
<details>
<summary>点击展开</summary>

思路一：纯递归实现，每次从`lists`中找出`val`最小的节点，将其指针前进一步；

思路二：分治思想，将问题划分为更小规模的子问题（[合并2个有序链表](../04.MergeSortedLists)）。

</details>

## 代码实现
| C | C++ | Java | Objective-C | Swift | Python | JavaScript | Go | PHP |
| :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: | :--: |
| 🤔 | [😀](./MergeKSortedLists.cpp) | [😀](./MergeKSortedLists.java) | 🤔 | 🤔 | 🤔 | 🤔 | 🤔 | 🤔 |

