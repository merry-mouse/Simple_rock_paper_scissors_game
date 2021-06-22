import random
def rps():
    human_hand = input("Please print 'rock', 'paper' or 'scissors':  ").split()
    list_of_hands = ["rock", "paper", "scissors"]
    computer_hand = list(random.choice(list_of_hands).split())
    for i in human_hand:
        if i == "rock" and computer_hand[0] == "paper":
            print("Computer chose {}".format(computer_hand[0]))
            print("Paper beats rock, computer won!")
            again = input("Wanna try again? (yes/no)  ")
            if again == "yes":
                return rps()
            else:
                break
        if i == "paper" and computer_hand[0] == "scissors":
            print("Computer chose {}".format(computer_hand[0]))
            print("Scissors beats paper, computer won! ")
            again = input("Wanna try again? (yes/no)  ")
            if again == "yes":
                return rps()
            else:
                break
        if i == "scissors" and computer_hand[0] == "rock":
            print("Rock beats scissors, computer won! ")
            print("Computer chose {}".format(computer_hand[0]))
            again = input("Wanna try again? (yes/no)  ")
            if again == "yes":
                return rps()
            else:
                break
        if i == "paper" and computer_hand[0] == "rock":
            print("Computer chose {}".format(computer_hand[0]))
            print("Paper beats rock, hooman won!")
            again = input("Wanna try again? (yes/no)  ")
            if again == "yes":
                return rps()
            else:
                break
        if i == "scissors" and computer_hand[0] == "paper":
            print("Computer chose {}".format(computer_hand[0]))
            print("Scissors beats paper, hooman won! ")
            again = input("Wanna try again? (yes/no)  ")
            if again == "yes":
                return rps()
            else:
                break
        if i == "rock" and computer_hand[0] == "scissors":
            print("Computer chose {}".format(computer_hand[0]))
            print("Rock beats scissors, hooman won! ")
            again = input("Wanna try again? (yes/no)  ")
            if again == "yes":
                return rps()
            else:
                break
        else:
            print("Computer chose {}, game continues... ".format(computer_hand[0]))
            return rps()

rps()
