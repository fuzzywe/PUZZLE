Puzzle – Blind Games
Last Updated : 20 Mar, 2024
Given that you are in a dim room where a table is kept. There are 50 coins put on the table, out of which 10 coins show tails and 40 coins show heads. The task is to separate this arrangement of 50 coins into 2 groups (not really a similar size) such that both groups have the same number of coins showing tails, you can perform any number of flips on any coin. 

To solve this puzzle, we need to separate the 50 coins into two groups such that each group has the same number of coins showing tails. Here’s a way to approach it:

### Solution

1. **Divide the Coins**:
   - Take **any 10 coins** from the 50 coins and put them in a separate group (Group A).
   - The remaining **40 coins** form the second group (Group B).

2. **Flip All Coins in Group A**:
   - Now, count the number of tails in Group A. Let’s say there are \( X \) tails among the 10 coins in Group A.
   - Since there are 10 tails in total (between both groups), Group B must then have \( 10 - X \) tails.

3. **Flipping Logic**:
   - Flip all 10 coins in Group A.
   - After flipping, any coin that was initially a tail in Group A will now be a head, and any coin that was a head will now be a tail.
   - So after flipping, Group A will end up with exactly \( X \) tails.

4. **Final Check**:
   - Now, both Group A and Group B have \( X \) tails each.

### Explanation with an Example

Suppose in Group A (the 10 coins you separated), there were initially 3 tails. This means Group B (the remaining 40 coins) has \( 10 - 3 = 7 \) tails.

- After flipping all coins in Group A:
  - The 3 tails in Group A become heads.
  - The 7 heads in Group A become tails.

Thus, Group A now has 7 tails, and Group B has 7 tails, satisfying the requirement.

### Conclusion

This solution guarantees that both groups will have an equal number of tails, regardless of the initial distribution of tails in Group A.
