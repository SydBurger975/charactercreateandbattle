# charactercreateandbattle
#This repel uses 3 subroutines, health, strength, and rollDice. 
#these subroutines are called back into a while True: loop to mimic two characters battling. 
#The code will count the rounds it takes for one of the characters to defeat another. 
#I used a dice function to roll random numbers for the character's health and strength. 
#The damage of each character = (p1's strength - p2's strength + 1).
#A character's strength = ((rollDice(6)*rollDice(12)/2) +12 and the health +((rollDice(6)*rollDice(12)/2) +10. 
#The game will end when a player's health is below zero.
