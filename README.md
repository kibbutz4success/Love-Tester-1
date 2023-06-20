# Love-Tester-1
#program that tests the compatibility between two people

print("Welcome to the Love Calculator!")
name1 = input("What is your name? \n")
name2 = input("What is their name? \n")
count_1 = 0
count_2 = 0
name1 = name1.upper()
name2 = name2.upper()

for i in name1:
    if i == "T":
        count_1 +=1
    if i == "R":
        count_1 +=1
    if i == "U":
        count_1 +=1
    if i == "E":
        count_1 +=1

for i in name2:
    if i == "T":
        count_1 +=1
    if i == "R":
        count_1 +=1
    if i == "U":
        count_1 +=1
    if i == "E":
        count_1 +=1

#print(count_1)

for i in name1:
    if i == "L":
        count_2 +=1
    if i == "O":
        count_2 +=1
    if i == "V":
        count_2 +=1
    if i == "E":
        count_2 +=1

for i in name2:
    if i == "L":
        count_2 +=1
    if i == "O":
        count_2 +=1
    if i == "V":
        count_2 +=1
    if i == "E":
        count_2 +=1

#print(count_2)

char_1 = str(count_1)
char_2 = str(count_2)
score_char =char_1 + char_2
score = int(score_char)
if score < 10:
    print(f"Your score is {score}, you go together like coke and mentos.")
elif score > 90:
    print(f"Your score is {score}, you go together like coke and mentos.")
elif score in range(40,50):
    print(f"Your score is {score}, you are alright together.")
else:
    print(f"Your score is {score}.")

    
