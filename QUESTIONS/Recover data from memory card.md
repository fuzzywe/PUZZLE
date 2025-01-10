Suppose you have three memory cards, M1, M2, and M3, each with a 1GB capacity. You also have 3GB of data. You have to divide these data into M1, M2, and M3 such that if any one of the memory cards among M1, M2, M3 got crashed, you should be able to recover all the data from the remaining two memory cards.

For example, if M1 crashes, you should recover 3GB of data from M2 and M3.

This problem is about **fault-tolerant data storage** using redundancy across three memory cards. Let's break down a solution using a technique called **parity-based redundancy**. Here's how to divide and store data to achieve the goal:

---

### Step 1: Data Division
You have **3GB of data**, denoted as:
- ( D1 ), ( D2 ), and ( D3 ) — where each part is 1GB.

We need to split and store them across **M1**, **M2**, and **M3** in a way that ensures:
1. If **any one card fails**, we can recover all the data from the other two.

![Screenshot 2025-01-10 101540](https://github.com/user-attachments/assets/f5fd76b4-d251-4ea9-8158-d1792032142c)

---

### Step 2: Storage Strategy
We use **parity (XOR-based)** redundancy to distribute the data.

#### Storage configuration:



---
![Screenshot 2025-01-10 101423](https://github.com/user-attachments/assets/ea81fb3f-aadd-4ce4-93c7-2cc7f312e594)

### Step 3: Recovery Process
If one memory card fails, we can reconstruct the data:



### Step 4: If Another Card Fails (Examples)
- If **M2** fails, use data from **M1** and **M3**.
- If **M3** fails, use data from **M1** and **M2**.

---

### Conclusion
This method uses **XOR-based redundancy** to store data such that any one memory card failure allows recovery of the entire dataset. This is similar to how RAID-5 systems handle fault tolerance.
