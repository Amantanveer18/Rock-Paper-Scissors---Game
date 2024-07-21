# Rock-Paper-Scissors---Game
Player_1 = str(input("Player 1 >>"))
Player_2 = str(input("Player 2 >>"))

def Game(Player_1 , Player_2):
    if Player_1 == "rock" and Player_2 == "paper":
        print("Player 2 won")
    elif Player_1 == "paper" and Player_2 == "scissors":
        print("Player 2 won")
    elif Player_1 == "scissors" and Player_2 == "rock":
        print("Player 2 won")    
    elif Player_2 == "rock" and Player_1 == "paper":
        print("Player 1 won")
    elif Player_2 == "paper" and Player_1 == "scissors":
        print("Player 1 won")
    elif Player_2 == "scissors" and Player_1 == "rock":
        print("Player 1 won")  
    elif Player_2 == "paper" and Player_1 == "paper":
        print("Tie")
    elif Player_2 == "scissors" and Player_1 == "scissors":
        print("Tie")  
    elif Player_2 == "rock" and Player_1 == "rock":
        print("Tie")                
    else:
        print("Invalid option") 
    

Game(Player_1 , Player_2)
