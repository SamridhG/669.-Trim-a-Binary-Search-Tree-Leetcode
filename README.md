# 669.-Trim-a-Binary-Search-Tree-Leetcode
https://leetcode.com/problems/trim-a-binary-search-tree/


Given the root of a binary search tree and the lowest and highest boundaries as low and high, trim the tree so that all its elements lies in [low, high]. Trimming the tree should not change the relative structure of the elements that will remain in the tree (i.e., any node's descendant should remain a descendant). It can be proven that there is a unique answer.

Return the root of the trimmed binary search tree. Note that the root may change depending on the given bounds.

 

Example 1:

![image](https://user-images.githubusercontent.com/63790684/125782167-826b8947-d667-46b2-bb4f-7cbd1face30f.png)

Input: root = [1,0,2], low = 1, high = 2


Output: [1,null,2]


Example 2:


![image](https://user-images.githubusercontent.com/63790684/125782185-cf82c688-2e93-40be-bda8-5075bd158f02.png)


Input: root = [3,0,4,null,2,null,null,1], low = 1, high = 3


Output: [3,2,null,1]


Example 3:



Input: root = [1], low = 1, high = 2


Output: [1]


Example 4:


Input: root = [1,null,2], low = 1, high = 3


Output: [1,null,2]


Example 5:


Input: root = [1,null,2], low = 2, high = 4


Output: [2]
 

Constraints:


The number of nodes in the tree in the range [1, 104].


0 <= Node.val <= 104


The value of each node in the tree is unique.


root is guaranteed to be a valid binary search tree.


0 <= low <= high <= 104
