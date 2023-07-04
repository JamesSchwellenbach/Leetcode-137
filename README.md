# Leetcode 137. Single Number II (Medium)

# Problem

Given an integer array nums where every element appears three times except for one, which appears exactly once. Find the single element and return it.

You must implement a solution with a linear runtime complexity and use only constant extra space.

# Solution

I convert the list to a counter object of the values in the list. Then i check through the counter, removing the key with an occurrences value of 1.
