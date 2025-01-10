### Solution: Egg Drop Problem (with 4 eggs and 30 floors)

You want to find the **lowest floor** in a 30-floor building where an egg breaks, using **4 eggs** and applying a **binary search strategy** to minimize the number of drops.

---

### **Explanation of Binary Search Approach**
1. **Divide and conquer**: Start by dividing the floors into halves each time.  
   This minimizes the number of drops needed because it narrows the search range more efficiently than linear approaches.  
   
   **First drop**:  
   - Start from the middle floor of the entire building (floor 15).  
   - If the egg **breaks** at floor 15, it means the critical floor is between 1 and 15.  
   - If it **doesn’t break**, the critical floor is between 16 and 30.

2. **Next step**:  
   If the egg didn’t break at floor 15, the second drop will be from the middle of the range 16 to 30, which is floor 23.  
   - If it **breaks** at floor 23, search between 16 and 23.  
   - If it **doesn’t break**, search between 24 and 30.

3. **Continue dividing**:  
   Repeat this process, reducing the range by half each time, until you find the **lowest floor** where the egg breaks.

---

### **Key Steps**
1. Use one egg at a time, testing the middle of the range each time.
2. When an egg breaks, use a new egg to narrow down the lower half of the range.
3. Stop when the exact floor is identified.

---

### **Number of Drops (Worst Case Scenario)**
Binary search with 30 floors takes approximately:
\[
\log_2(30) \approx 5 \text{ to } 6 \text{ drops}.
\]
With 4 eggs available, you have enough to perform this search strategy efficiently.

### **Summary**
- Use binary search to minimize drops.  
- Maximum drops needed: **5 to 6**.
- Critical floors are determined by halving the search range until the lowest breaking point is found.
