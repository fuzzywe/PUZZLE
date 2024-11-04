Puzzle – Chameleons go on a date
Last Updated : 01 Oct, 2024
Question: 

13 purple, 15 yellow, and 17 maroon chameleons are found on an island. When two different-coloured chameleons come together, they both turn into the third colour. Do all chameleons eventually have the same hue after a certain number of pairwise meetings?

The "Chameleons on a Date" puzzle is a classic problem involving chameleons of different colors and their transformations. Here’s the typical setup:

Imagine there are three types of chameleons — **red**, **green**, and **blue**. Whenever two chameleons of different colors meet, they both change to the third color. The puzzle usually asks whether it's possible to get all chameleons to be the same color through a series of these transformations, and if so, how.

### Problem Example
Suppose there are:
- 12 red chameleons
- 15 green chameleons
- 18 blue chameleons

The goal is to determine if it’s possible for all the chameleons to end up the same color, and if so, how. If it’s not possible, we want to understand why.

### Solution Approach

1. **Understand the Transformation Rule**:
   - When a red and green chameleon meet, both turn blue.
   - When a red and blue chameleon meet, both turn green.
   - When a green and blue chameleon meet, both turn red.

2. **Key Insight: Conservation of Differences**:
   - Let’s track the difference between the counts of each color.
   - Define:
     - \( R \) = number of red chameleons
     - \( G \) = number of green chameleons
     - \( B \) = number of blue chameleons
   - Notice that each transformation affects two colors and reduces one of the differences while increasing the other, but the **parity** (whether the difference is odd or even) of each difference remains the same.

3. **Check Initial Differences**:
   - Calculate the difference between each pair:
     - \( R - G = 12 - 15 = -3 \) (odd)
     - \( G - B = 15 - 18 = -3 \) (odd)
     - \( B - R = 18 - 12 = 6 \) (even)

4. **Parity Observation**:
   - For it to be possible to make all chameleons the same color, **all differences must be even** (or zero), because each transformation preserves parity.
   - Since we have odd differences between some colors initially, it’s **impossible** to make all chameleons the same color in this scenario.

### Conclusion

With 12 red, 15 green, and 18 blue chameleons, it’s not possible to transform them so that all chameleons are the same color due to the initial odd differences between their counts.


Let's walk through the "Chameleons on a Date" puzzle step-by-step with a concrete example, focusing on why having **odd differences** means we can't make all chameleons the same color.

---

### Puzzle Recap
We have:
- 12 **Red** chameleons
- 15 **Green** chameleons
- 18 **Blue** chameleons

The task is to see if we can get all chameleons to be the same color by transforming them, following the rule:

- When two chameleons of different colors meet, they both change to the **third color**.

Let's try to visualize how these transformations affect the numbers.

---

### Step-by-Step Example with Transformations

#### Initial State
We start with:
- **Red (R) = 12**
- **Green (G) = 15**
- **Blue (B) = 18**

#### Calculating Differences
To get all chameleons to be the same color, we need these groups to **balance out** — ideally, making two colors reach zero, leaving only one color with all the chameleons.

1. **Calculate differences between colors**:
   - \( \text{R - G} = 12 - 15 = -3 \) → This is **odd**.
   - \( \text{G - B} = 15 - 18 = -3 \) → This is **odd**.
   - \( \text{B - R} = 18 - 12 = 6 \) → This is **even**.

2. Notice that two of these differences are **odd**. This is the key to why we can't get all chameleons to be the same color.

---

### Trying Transformations to Understand Parity Preservation

Let's go through a few example transformations and see what happens.

#### Example Transformation 1
Suppose a **Red** and a **Green** chameleon meet:
- Both transform into **Blue**.
- New counts: 
  - Red = 11
  - Green = 14
  - Blue = 19

Now, recalculate the differences:
- \( \text{R - G} = 11 - 14 = -3 \) → **still odd**
- \( \text{G - B} = 14 - 19 = -5 \) → **still odd**
- \( \text{B - R} = 19 - 11 = 8 \) → **still even**

After this transformation, the differences remain **odd** where they started as odd and **even** where they started as even. This pattern holds for every possible transformation: **odd differences remain odd, and even differences remain even**.

---

### Why Odd Differences Mean We Can't Get to All the Same Color
To reach a state where all chameleons are the same color, we’d need to make two groups reach zero. But to get to zero, each of the differences between the groups would need to become zero as well.

Since two of our initial differences are **odd**, we’ll never be able to reduce them to zero by adding or subtracting multiples of 2 (which is what each transformation essentially does). 

---

### Conclusion
In short, because two of the differences (Red-Green and Green-Blue) are odd, we’re **stuck** with these odd values, making it impossible to balance the groups to all the same color.
