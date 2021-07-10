import random

random_number = random.randint(1, 3)
instruction = "Enter R for 'ROCK', P for 'PAPER', S for 'scissors' "
print(instruction)


def gamewin(computer_turn, user_turn):
    if computer_turn == user_turn:
        return None

    elif computer_turn == 'r':
        if user_turn == 'p':
            return True
        elif user_turn == "s":
            return False

    if computer_turn == 'p':
        if user_turn == 's':
            return True
        elif user_turn == 'r':
            return False

    if computer_turn == 's':
		
		
		
		
        if user_turn == 'r':
            return True
        elif user_turn == 'p':
            return False

print("Com has chosen.")
you = (input("Now it's your turn\n>>")).lower()

if random_number == 1:
    com_turn = 'r'

elif random_number == 2:
    com_turn = "p"

elif random_number == 3:
    com_turn = 's'


status = gamewin(com_turn, you)


if status == None:
    print("It's a tie! Try again.")

elif status:
    print('Congrats! You win.')

elif status == False:
    print("Sorry! you lost.")

print(f"com had chosen {com_turn}")
print(f"You had chosen {you}")
