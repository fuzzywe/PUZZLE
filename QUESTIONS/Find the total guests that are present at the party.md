Find the total guests that are present at the party
Last Updated : 13 Mar, 2023
A person hosts a party and invites N guests to it. However, each guest has a condition, that each guest ‘Gi’ only stays at the party if there are at least ‘Pi’ people already at the party, otherwise leaves. The total number of guests N and the number of people each guest needs ‘Pi’ are given as input for each guest. The task is to find the total guests that are present at the party. It is also given that the guests arrive at the party in the order given in the array ‘Pi’
Examples: 
 

Input: N = 5, Pi = {1, 0, 2, 1, 3}
Output: 2
Explanation: 
Since 5 guests are invited to the party.
Total guest present initially = 0

For Guest number 1:
The 1st guest needs at least 1 person, 
since he is the first to arrive, 
and there is no one else, so he leaves.
Therefore, Total guest so far = 0

For Guest number 2:
The 2nd guest needs 0 people, so he stays. 
Therefore, Total guest so far = 0 + 1 = 1

For Guest number 3:
The 3rd guest needs at least 2 people,
And there are still only 1 guest present,
so he leaves.
Therefore, Total guest so far = 1 + 0 = 1

For Guest number 4:
The 4th guest needs at least 1 people,
And there is 1 guest present, so he stays. 
Therefore, Total guest so far = 1 + 1 = 2

For Guest number 5:
The 5th guest needs at least 3 people,
And there is only 2 guest present, so he leaves. 
Therefore, Total guest so far = 2 + 0 = 2

Total guests that are present at the party = 2.

Input: N = 3, Pi = {0, 2, 1}
Output: 2
Explanation: 
Since 3 guests are invited to the party.
Total guest present initially = 0

For Guest number 1:
The 1st guest needs 0 people, so he stays.
Therefore, Total guest so far = 1

For Guest number 2:
The 2nd guest needs at least 2 people,
And there are still only 1 guest present,
so he leaves.
Therefore, Total guest so far = 1 + 0 = 1

For Guest number 3:
The 3rd guest needs at least 1 people,
And there is 1 guest present, so he stays. 
Therefore, Total guest so far = 1 + 1 = 2

Total guests that are present at the party = 2.
 

Approach: 
 

Get the number of guests invited in N and the requirement of each guest in array guest[].
Initialize totalGuests to 0, as the total number of guests present.
Iterate in the array guest[] from 0 to N-1.
If the requirement of the guest is less than or equal to totalGuests, Increment totalGuests by 1
When complete array guest[] has been traversed, print the total number of guests ‘totalGuests’
Implementation: 
 




// C++ program to get the 
// total number of guests at the party 
```cpp
#include <bits/stdc++.h> 
using namespace std; 
  
// Function to find the totalGuests 
int findGuest(int array[], int N) 
{ 
    // Total guest before the party are 0 
    int count = 0; 
  
    // Checking requirements for each guest 
    for (int i = 0; i < N; i++) { 
  
        // If requirements are met 
        if (array[i] <= count) { 
  
            // The Gi guest decides to stay 
            // So increment total guest by 1 
            count++; 
        } 
    } 
  
    // Return the totalnumber of guest 
    return count; 
} 
  
// Driver code 
int main() 
{ 
  
    // Get the number of guests invited 
    int N = 5; 
  
    // Guests array stores 
    // the requirement by each guest 
    int guests[] = { 1, 0, 2, 1, 3 }; 
  
    // Get the total number of guests present 
    int totalGuests = findGuest(guests, N); 
  
    cout << totalGuests << endl; 
  
    return 0; 
} 

```
Output: 
2
 

Time complexity: O(N) where N is size of given input array

Auxiliary Space: O(1)
