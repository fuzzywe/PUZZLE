Puzzle 18 | (Torch and Bridge)
Last Updated : 19 Aug, 2024
Puzzle: There are 4 persons (A, B, C and D) who want to cross a bridge at night.

A takes 1 minute to cross the bridge.
B takes 2 minutes to cross the bridge.
C takes 5 minutes to cross the bridge.
D takes 8 minutes to cross the bridge.
There is only one torch with them and the bridge cannot be crossed without the torch. There cannot be more than two persons on the bridge at any time, and when two people cross the bridge together, they must move at the slower person’s pace.Can they all cross the bridge in 15 minutes?         Solution: They must cross the bridge in the following way:

Step 1: A and B cross the bridge. A comes back. Time taken 3 minutes. Now B is on the other side.
Step 2: C and D cross the bridge. B comes back. Time taken 8 + 2 = 10 minutes. Now C and D are on the other side.
Step 3: A and B cross the bridge. Time taken is 2 minutes. All are on the other side.
Total time spent: 3 + 10 + 2 = 15 minutes.

To minimize the time:

The trick here is the persons with the fastest speeds only should come back (and that too only if there is a need to come back, as here we need to bring back the torch). A comes back in step-1 and B comes back in step-2. And, finally reduce the number of traveling back, like C, D does not come back.

This is a classic problem that combines logic with time optimization. Here’s a step-by-step breakdown of how the four people can cross the bridge in exactly 15 minutes, along with an explanation of the strategy used.

### Key Constraints and Conditions
1. Only one torch, which must be with anyone crossing the bridge.
2. No more than two people can cross at once.
3. When two people cross, they go at the pace of the slower person.

### Steps to Solve the Puzzle

The idea is to minimize the time by:
- Having the fastest people (A and B) come back with the torch.
- Avoiding unnecessary trips back for the slower people (C and D).

### Step-by-Step Solution

1. **Step 1**: **A and B cross the bridge together.**
   - **Time taken**: 2 minutes (since B is slower).
   - **Bridge status**: A and B are on the other side; C and D are on the starting side.
   - **Total elapsed time**: 2 minutes.

2. **Step 2**: **A returns with the torch.**
   - **Time taken**: 1 minute (since A is the fastest).
   - **Bridge status**: A, C, and D are on the starting side; B is on the other side.
   - **Total elapsed time**: 3 minutes.

3. **Step 3**: **C and D cross the bridge together.**
   - **Time taken**: 8 minutes (since D is the slowest).
   - **Bridge status**: B, C, and D are on the other side; A is on the starting side.
   - **Total elapsed time**: 3 + 8 = 11 minutes.

4. **Step 4**: **B returns with the torch.**
   - **Time taken**: 2 minutes.
   - **Bridge status**: A and B are on the starting side; C and D are on the other side.
   - **Total elapsed time**: 11 + 2 = 13 minutes.

5. **Step 5**: **A and B cross the bridge together again.**
   - **Time taken**: 2 minutes.
   - **Bridge status**: All are now on the other side of the bridge.
   - **Total elapsed time**: 13 + 2 = 15 minutes.

### Final Time Calculation
The total time spent is:
- Step 1: 2 minutes
- Step 2: 1 minute
- Step 3: 8 minutes
- Step 4: 2 minutes
- Step 5: 2 minutes  
**Total time** = 15 minutes

### Explanation of the Strategy
- The fastest person (A) returns the torch initially, allowing the slowest people (C and D) to cross without delay.
- By having B (the second fastest) return the torch for the final trip, we minimize the total time.
