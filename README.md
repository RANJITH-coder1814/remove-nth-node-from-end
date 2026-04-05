# remove-nth-node-from-end
🔗 Remove Nth Node From End of List (LeetCode 19)
📌 Problem Statement

Given the head of a linked list, remove the nth node from the end of the list and return its head.
💡 Approach: Two Pointer (Optimal)

We use two pointers:

Fast Pointer → moves n+1 steps ahead
Slow Pointer → follows behind
🔄 Steps:
Create a dummy node pointing to head
Move fast pointer n+1 steps ahead
Move both pointers until fast reaches NULL
Remove the target node using slow
