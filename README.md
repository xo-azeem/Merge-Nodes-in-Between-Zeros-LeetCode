# Merge Nodes in Between Zeros

LeetCode Q # 2181.

You are given the head of a linked list, which contains a series of integers separated by 0's. The beginning and end of the linked list will have Node.val == 0.

For every two consecutive 0's, merge all the nodes lying in between them into a single node whose value is the sum of all the merged nodes. The modified list should not contain any 0's.

Return the head of the modified linked list.

Example 1:

<div align = "center">

  ![image](https://github.com/xo-azeem/Merge-Nodes-in-Between-Zeros-LeetCode/assets/171427226/485a11b7-d8e1-47a8-9690-7c10af2ce126)

</div>

> Input: head = [0,3,1,0,4,5,2,0]</br>
> Output: [4,11]</br>
> Explanation: </br>
> The above figure represents the given linked list. The modified list contains</br>
> - The sum of the nodes marked in green: 3 + 1 = 4.</br>
> - The sum of the nodes marked in red: 4 + 5 + 2 = 11.
  
Example 2:

<div align = "center">

  ![image](https://github.com/xo-azeem/Merge-Nodes-in-Between-Zeros-LeetCode/assets/171427226/7b7c3c7a-5b0f-4c88-a059-311529c35972)

</div>

> Input: head = [0,1,0,3,0,2,2,0]</br>
> Output: [1,3,4]</br>
> Explanation: </br>
> The above figure represents the given linked list. The modified list contains</br>
> - The sum of the nodes marked in green: 1 = 1.</br>
> - The sum of the nodes marked in red: 3 = 3.</br>
> - The sum of the nodes marked in yellow: 2 + 2 = 4.</br>

My Solution Analysis:

<div align = "center">

  ![image](https://github.com/xo-azeem/Merge-Nodes-in-Between-Zeros-LeetCode/assets/171427226/d44499a3-c694-4a0a-8659-4935d4dae4f7)

  Time complexity: O(n).</br>Space complexity: O(1).
</div>
