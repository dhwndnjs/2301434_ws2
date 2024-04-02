# 242137_ws
import random

user_action = int(input("선택하시오(가위, 바위, 보 "))
random_number = random.randint(1, 3)

if random_number == 1 :
    computer_action = "가위"
elif random_number == 2 :
    computer_action = "바위"
else :
    computer_action = "보"

print(f"{user_action}, {computer_action}, {random_number}")
