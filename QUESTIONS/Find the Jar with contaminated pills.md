https://www.geeksforgeeks.org/puzzle-7-find-the-jar-with-contaminated-pills/

Puzzle 8 | (Find the Jar with contaminated pills)
Last Updated : 19 Jan, 2023
Puzzle: You have 5 jars of pills. Each pill weighs 10 grams, except for contaminated pills contained in one jar, where each pill weighs 9 grams. Given a scale, how could you tell which jar had the contaminated pills in just one measurement?


![image](https://github.com/user-attachments/assets/764749b5-8435-49b3-b70d-33a1a7dcde21)


https://www.youtube.com/watch?v=I5BitmxJqJw&ab_channel=GeeksforGeeksSchool

To find the contaminated Jar, follow this step-wise approach.

Step 1: Take out 1 pill from jar 1, 2 pills from jar 2, 3 pills from jar 3, 4 pills from jar 4 and 5 pills from jar 5.
Step 2: Put all these 15 pills on the scale. The correct weight is 150 (15*10). But one of the jars has contaminated pills. So the weight will definitely be less than 150.
Step 3: If the weight is 149 then jar 1 has contaminated pills because there is only one contaminated pill. If the weight is 148 then jar 2, if the weight is 147 then jar 3, if 146 then jar 4, if 145 then jar 5.


![image](https://github.com/user-attachments/assets/8aaec48e-64fb-42e4-81f7-2e9c136a19e2)
