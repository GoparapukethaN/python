# python
basic python projects


treaure hunt:

print("Welcome to Treasure Island. Your mission is to find the treasure.")

stage1 = input("Left or right? ").lower()
if stage1 == "left":
    print("Moved to the second round.")
    
    stage2 = input("Wait or swim? ").lower()
    if stage2 == "wait":
        print("Moved to the third door.")
        
        stage3 = input("Which door: red, blue, yellow? ").lower()
        if stage3 == "red":
            print("Game over.")
        elif stage3 == "blue":
            print("Game over.")
        elif stage3 == "yellow":
            print("You win!")
        else:
            print("Invalid door choice. Game over.")
    else:
        print("Game over.")
else:
    print("Game over.")
