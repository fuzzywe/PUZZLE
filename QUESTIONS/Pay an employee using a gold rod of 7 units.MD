Puzzle 4 | (Pay an employee using a gold rod of 7 units ?)
Last Updated : 19 Jan, 2023
An employee works for an employer for 7 days. The employer has a gold rod of 7 units. How does the employer pay to the employee, so that the number of employee’s rod units increases by one at the end of each day? The employer can make at most 2 cuts in the rod. 

(Hint- after the end of the day employee’s can’t spend any part of rod)

To solve this puzzle, the goal is to pay the employee one unit of gold each day using a 7-unit gold rod with only **2 cuts**.

### Solution:
To achieve this, we can divide the 7-unit rod into segments of 1, 2, and 4 units by making two cuts. Here's how:

1. **Make the first cut** to create a 1-unit piece.
2. **Make the second cut** to create a 2-unit piece. Now we have three pieces of gold: 1-unit, 2-units, and 4-units.

These pieces allow the employer to pay the employee each day with an increment of 1 unit, by combining the pieces as follows:

- **Day 1:** Give the 1-unit piece to the employee.
- **Day 2:** Take back the 1-unit piece and give the 2-unit piece instead. Now the employee has 2 units.
- **Day 3:** Give the 1-unit piece back to the employee. Now the employee has 3 units (2 + 1).
- **Day 4:** Take back both the 1-unit and 2-unit pieces, and give the 4-unit piece. Now the employee has 4 units.
- **Day 5:** Give the 1-unit piece back to the employee. Now the employee has 5 units (4 + 1).
- **Day 6:** Take back the 1-unit piece and give the 2-unit piece instead. Now the employee has 6 units (4 + 2).
- **Day 7:** Give the 1-unit piece back to the employee. Now the employee has 7 units (4 + 2 + 1).

By making only 2 cuts, the employer can pay the employee incrementally each day until the 7 days are completed.
