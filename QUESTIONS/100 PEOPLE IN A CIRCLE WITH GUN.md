100 people in a circle with gun puzzle
Last Updated : 11 May, 2024
100 people standing in a circle in an order 1 to 100. No. 1 has a sword. He kills the next person (i.e. No. 2) and gives the sword to the next (i.e. No. 3). All people do the same until only 1 survives. Which number survives at the last? 
There are 100 people starting from 1 to 100.  Is there any formula for this

This puzzle is a variant of the **Josephus problem**, which is a well-known theoretical problem in mathematics and computer science.

### Solution Outline

For the Josephus problem:
- If there are \( n \) people standing in a circle and every second person is eliminated until only one person remains, the position of the last surviving person can be determined by a formula:
  
  \[
  J(n) = 2 \times (n - L) + 1
  \]

  where:
  - \( n \) is the total number of people,
  - \( L \) is the largest power of 2 less than or equal to \( n \) (i.e., \( L = 2^{\lfloor \log_2(n) \rfloor} \)).

### Step-by-Step Calculation for 100 People

1. **Identify \( n = 100 \)**.
   
2. **Find the largest power of 2 less than or equal to 100**:
   - \( L = 2^6 = 64 \) (since \( 2^7 = 128 \), which is greater than 100).

3. **Apply the formula**:
   \[
   J(100) = 2 \times (100 - 64) + 1
   \]
   \[
   J(100) = 2 \times 36 + 1 = 72 + 1 = 73
   \]

### Answer
So, the last person standing will be **position 73**.

### Explanation of the Formula
The Josephus problem solution leverages powers of 2 and cyclic elimination patterns. The pattern in which people are eliminated follows a consistent sequence based on powers of 2, making this formula efficient for large numbers.

A **power of 2** is any number that can be expressed as \( 2^n \), where \( n \) is a non-negative integer. In other words, a power of 2 is a number that results from multiplying 2 by itself \( n \) times. The sequence of powers of 2 starts as follows:

- \( 2^0 = 1 \)
- \( 2^1 = 2 \)
- \( 2^2 = 4 \)
- \( 2^3 = 8 \)
- \( 2^4 = 16 \)
- \( 2^5 = 32 \)
- \( 2^6 = 64 \)
- \( 2^7 = 128 \)
- \( 2^8 = 256 \)
- \( 2^9 = 512 \)
- \( 2^{10} = 1024 \)
- And so on...

### Key Points:
- The **binary representation** of a power of 2 always has only one bit set to 1, and all other bits are 0. For example:
  - \( 2^0 = 1 \) (binary: `0001`)
  - \( 2^1 = 2 \) (binary: `0010`)
  - \( 2^2 = 4 \) (binary: `0100`)
  - \( 2^3 = 8 \) (binary: `1000`)
  
- Powers of 2 are widely used in computer science, especially in memory addressing and algorithms (like the Josephus problem) due to their binary nature.
This puzzle is an extended version of the **Josephus problem**, where you have 1000 people in a circle, and every second person is eliminated until only one person remains.

### Formula for the Josephus Problem

For \( n \) people, the position of the last person standing can be found using the following formula:

\[
J(n) = 2 \times (n - L) + 1
\]

Where:
- \( n \) is the total number of people,
- \( L \) is the largest power of 2 less than or equal to \( n \), i.e., \( L = 2^{\lfloor \log_2(n) \rfloor} \).

### Step-by-Step Calculation for 1000 People

1. **Identify \( n = 1000 \)**.

2. **Find the largest power of 2 less than or equal to 1000**:
   - The largest power of 2 less than or equal to 1000 is \( 2^9 = 512 \), because \( 2^{10} = 1024 \), which is greater than 1000.

3. **Apply the formula**:
   \[
   J(1000) = 2 \times (1000 - 512) + 1
   \]
   \[
   J(1000) = 2 \times 488 + 1 = 976 + 1 = 977
   \]

### Answer

The last person standing in a circle of 1000 people, following this elimination pattern, will be **position 977**.

### Explanation

- The Josephus problem involves repeatedly halving the circle by eliminating every second person. The formula leverages powers of 2 because the elimination process follows a pattern similar to binary numbers, where each step is like halving the remaining people in the circle.
- The formula \( 2 \times (n - L) + 1 \) accounts for this halving and ensures that we can directly calculate the position of the last survivor without simulating the entire elimination process.
