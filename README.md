# Treasure_island-
#my first ever python project.
print(r'''
*******************************************************************************
          |                   |                  |                     |
 _________|________________.=""_;=.______________|_____________________|_______
|                   |  ,-"_,=""     `"=.|                  |
|___________________|__"=._o`"-._        `"=.______________|___________________
          |                `"=._o`"=._      _`"=._                     |
 _________|_____________________:=._o "=._."_.-="'"=.__________________|_______
|                   |    __.--" , ; `"=._o." ,-"""-._ ".   |
|___________________|_._"  ,. .` ` `` ,  `"-._"-._   ". '__|___________________
          |           |o`"=._` , "` `; .". ,  "-._"-._; ;              |
 _________|___________| ;`-.o`"=._; ." ` '`."\ ` . "-._ /_______________|_______
|                   | |o ;    `"-.o`"=._``  '` " ,__.--o;   |
|___________________|_| ;     (#) `-.o `"=.`_.--"_o.-; ;___|___________________
____/______/______/___|o;._    "      `".o|o_.--"    ;o;____/______/______/____
/______/______/______/_"=._o--._        ; | ;        ; ;/______/______/______/_
____/______/______/______/__"=._o--._   ;o|o;     _._;o;____/______/______/____
/______/______/______/______/____"=._o._; | ;_.--"o.--"_/______/______/______/_
____/______/______/______/______/_____"=.o|o_.--""___/______/______/______/____
/______/______/______/______/______/______/______/______/______/______/_____ /
*******************************************************************************
''') 
print("Welcome to Treasure Island.")
print("Your mission is to find the treasure.")
choice_1=input("You are at the cross road. where do you want to go?\n"
               "type 'left' or 'right'\n"). lower()
if choice_1=="left":
    choice_2=input("you have came to the seashore.\n"
                   "there is an island in the middle of the sea.\n"
                   "type 'wait' to wait for a boat or type 'swim' to to swim across\n"). lower()
    if choice_2=="wait":
        choice_3=input("you arrived at the island unharmed.\n"
                       "here is a house of three doors of three different colours.\n"
                       "one is red, one is yellow and one is blue. which colour do u choose.\n"). lower()
        if choice_3=="yellow":
            print("congrats,you found the treasure!")
        elif choice_3=="red":
            print("you burnt by the fire!!game over.")
        elif choice_3=="blue":
            print("the devil killed you!!game over.")
        else :
            print("this colour of door does not exist.game over.")

    else:
        print("you drowned into the sea.game over")

else:
    print("you fell into the hole.game over.")
