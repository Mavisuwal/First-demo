# Quiz-game
<h1>This is my first repository</h1>
</br>
print("Welcome to My Computer Quiz!")

playing = input("Do you want to play? ")

if playing.lower() != "yes":
    quit()

print("okay! Let's play :)")
score = 0

answer = input("What does CPU stand for? ")
if answer.lower()== "central processing unit":
    print('Correct! ')
    score += 1

else:
    print("Incorrect")

answer = input("What does GPU stand for? ")
if answer.lower() == "graphic processing unit":
    print('Correct! ')
    score += 1
else:
    print("Incorrect")

answer = input("What does PSU stand for? ")
if answer.lower() == "Power supply":
    print('Correct! ')
    score += 1
else:
    print("Incorrect")

print("You got "+ str(score) + " questions correct! ")
print("You got "+ str((score / 4) * 100) + "%.")


