# LeetCode 92 – Reverse Linked List II

Given the head of a singly linked list and two integers `left` and `right`, reverse the nodes from position `left` to position `right`.

The remaining part of the linked list should stay unchanged.

## Example

### Input

```text
head = [1,2,3,4,5]
left = 2
right = 4
```

### Output

```text
[1,4,3,2,5]
```

## Approach

I use a **Dummy Node** and reverse the required portion of the linked list in-place.

First, I move to the node just before the `left` position.

Then I repeatedly move the next node to the front of the section being reversed.

This reverses the selected portion without creating another linked list.

## Complexity

* **Time Complexity:** `O(N)`
* **Space Complexity:** `O(1)`

## Language

**Python**

## LeetCode

**Problem:** 92. Reverse Linked List II
**Difficulty:** Medium
**Topic:** Linked List

## Author

T.Nandhini
