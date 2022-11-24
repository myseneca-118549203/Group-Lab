# Group-Lab

Initial Documentation
Group Lead: Karl-Roen Agbayani
Code developer: Karl-Roen Agbayani, Johnnu Joseph
QA tester: Johnnu Joseph, Karl-Roen Agbayani
Documenter: Karl-Roen Agbayani
GitHub Publisher: Johnnu Joseph

To play this python game the user must choose a number between 0 to 2 with 0 being Rock, 1 being Paper and 2 being Scissors. Once the computer also chooses, the game determines who wins based the rule defined in the script. After the game is done, the play can choose to play again with either a “y” (yes) or “n” (no) which can be seen in grouplab1.py. 

Breaking the script down the game_images variable stores the images of Rock, Paper and Scissors which is call on later to show what the user and computer picked. The while True statement is used to loop back to the beginning to the game which will be explained later. User_choice store the value of players input which can be a number between 0-2, likewise computer_choice stores the random value between 0 to 2 with the help of the random module. The replay variable is used to determine if the player wants to play again which is shown with the “y” (yes) or “n” (no) and if the input is “y” the value becomes True and loops back to the beginning of the game.
