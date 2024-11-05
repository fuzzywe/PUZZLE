Puzzle 17 | (Ratio of Boys and Girls in a Country where people want only boys)
Last Updated : 19 Jan, 2023
In a country, all families want a boy. They keep having babies till a boy is born. What is the expected ratio of boys and girls in the country?

 
 
 

Solution:
Assumptions: Probability of having a boy or girl is same. Also, the probability of next kid being a boy doesn’t depend on history.

The problem can be solved by counting expected number of girls before a baby boy is born.


Let NG be the expected no. of girls before a boy is born

Let p be the probability that a child is girl and (1-p)
be probability that a child is boy.

NG can be written as sum of following infinite series.

NG = 0*(1-p) + 1*p*(1-p) + 2*p*p*(1-p) + 3*p*p*p*(1-p) + 4*p*p*p*p*(1-p) +.....

Putting p = 1/2 and (1-p) = 1/2 in above formula.

NG    = 0*(1/2) + 1*(1/2)2 + 2*(1/2)3 + 3*(1/2)4  +  4*(1/2)5 + ...
1/2*NG = 0*(1/2)2 + 1*(1/2)3 + 2*(1/2)4 + 3*(1/2)5  +  4*(1/2)6 + ...

NG - NG/2 =  1*(1/2)2 + 1*(1/2)3 + 1*(1/2)4 + 1*(1/2)5  +  1*(1/2)6 + ...

Using sum formula of infinite geometrical progression with
ratio less than 1
NG/2 = (1/4)/(1-1/2) = 1/2

NG = 1
So Expected Number of number of girls = 1

Since the expected number of girls is 1 and there is always a baby boy, the expected ratio of boys and girls is 50:50

This is a classic probability puzzle involving families who prefer to have boys. The scenario goes like this:

In a country, every family continues to have children until they have a boy, and then they stop. If they have a girl, they try again until they finally have a boy. The question is: What will be the ratio of boys to girls in this country over time?

### Solution:
It might seem at first that there would be many more boys than girls, since each family stops as soon as they have a boy. However, the key is to think about the probability and expected outcomes on a large scale.

1. **Assumptions and Setup**:
   - Each child has an equal 50% chance of being a boy or a girl.
   - Every family stops having children once they have a boy.
   - We want to calculate the expected ratio of boys to girls across the entire population.

2. **Expected Number of Boys and Girls**:
   - Each family will, on average, have one boy, since they stop as soon as they have a boy.
   - To understand the expected number of girls, let’s consider the probability of how many children they will have until the first boy is born.

3. **Expected Girls per Family**:
   - When a family has a child, there’s a 50% chance of it being a girl.
   - If the first child is a girl, they’ll have another child with a 50% chance of it being a boy.
   - On average, to get one boy, each family will also have **one girl**. Here’s why:

     - The probability of having a girl as the first child is 50%.
     - If the first child is a girl, there’s a 50% chance the next child will be a boy.
     - This pattern continues, with the probability of each subsequent girl being halved.

     So, on average, for each family:
     - The expected number of boys = 1
     - The expected number of girls = 1

4. **Population Ratio**:
   - Across many families, the total number of boys will equal the total number of girls.
   - Thus, the **ratio of boys to girls** in the country will be **1:1**.

### Intuitive Explanation
While each family stops after having a boy, families who have a girl first add to the number of girls in the population. Over many families, the probability balances out, so that on average, each family has one boy and one girl. This means the **overall ratio of boys to girls will be 1:1**.

### Conclusion
Despite each family aiming to have boys, the large-scale ratio of boys to girls in the population remains **1:1** due to the equal probability of each child being a boy or a girl.
