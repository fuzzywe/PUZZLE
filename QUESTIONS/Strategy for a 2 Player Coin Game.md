Puzzle 14 | (Strategy for a 2 Player Coin Game)

Puzzle: Consider a two-player coin game where each Player A and Player B gets the turn one by one. There is a row of even number of coins, and a player on his/her turn can pick a coin from any of the two corners of the row.  The player that collects coins with more value wins the game. Develop a strategy for the player making the first turn i.e, Player A, such that he/she never loses the game. Note that the strategy to pick a maximum of two corners may not work. In the following example, the first player, Player A loses the game when he/she uses a strategy to pick a maximum of two corners. 

![image](https://github.com/user-attachments/assets/fb27a48d-8806-4110-b18b-59e0711d4b13)


 Example:

 Initial row:  18 20 15 30 10 14
Player A picks 18, now row of coins is: 20,15,30,10,14

After first pick:  20 15 30 10 14
Player B picks 20, now row of coins is: 15,30,10,14

After second pick:  15 30 10 14
Player A picks 15, now row of coins is

After third pick:  30 10 14
Player B picks 30, now row of coins is

After 4th pick:  10 14
Player A picks 14, now row of coins is

Last pick:  10 
Player B picks 10, game over.

The total value collected by Player B is more (20 + 
30 + 10) compared to first player (18 + 15 + 14).
So the second picker, Player B wins. 

https://www.youtube.com/watch?v=i5mIJoiRX6A&ab_channel=SimplyLogical
