[9/28, 8:23 AM] Ruthika: If I am eating pizza for three days consecutively and on the fourth day I have the option to eat home-cooked food which is not of my liking or pizza (I have both options), which will I choose and why? (This question have no right or wrong answer but only the way you reason out your answer)
[9/28, 8:46 AM] Ruthika: Then he gave me a puzzle. There are 12 balls out of which 11 balls are identical in weight and 1 is different(can be heavy or light). We are given a set of balance scales. We need to find the minimum number of times required to use the balance scale to find the ball which has a different weight
Puzzle
2 Eggs 100 floors

Problem approach
When we drop an egg off a floor, we explore that floor. If the egg breaks, then we’re forced to explore the lower floors with 1 egg and t−1 tries. But if the egg survives, then we can move on to the upper floors with 2 eggs and t−1 tries. So the total distance that we can explore with 2 eggs and t tries is:
d2(t)=1+d1(t−1)+d2(t−1)
For one egg problem : d1(t) = t , t>=0
d2(t)=1+(t−1)+d2(t−1)
d2(t)=t+d2(t−1)
We can expand this recurrence relation:
d2(t)=t+(t−1)+...+1+d2(0)
When we’re out of tries, we can’t explore any further, no matter how many eggs we have left:
dn(0)=0
This gives the closed-form solution:
d2(t)=t+(t−1)+...+1
d2(t)=(t*(t+1))/2 for t≥0
In particular:
d2(13)=91
d2(14)=105
So, given two eggs, we’re guaranteed to find the right floor of a 100-story building within fourteen tries.
A psychometric question, If your colleague who is a very close friend, is not following the code and conduct of the firm. What would you do, Whether you will report to the higher officials or not(Reporting to higher officials would break the friendship bond)?
