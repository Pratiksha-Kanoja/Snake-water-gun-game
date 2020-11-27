"""
snake,water,gun
snake drink water
gun drop in water
gun shoot snake

used ramdom function(using module)
used while loop
"""
import random
n=1
scorei=0
scorej=0
while(n<=5):
    n=n+1
    print("s=snake,w=water,g=gun")

    print("Enter the name")
    i = input()

    list = ["s", "w", "g"]
    j = random.choice(list)
    print("computer=",j)

    if i == 's' and j == 'w':
        print("snake drink water\n")
        scorei=scorei+1
        continue
    elif i == 'w' and j == 's':
        print("snake drink water\n")
        scorej = scorej + 1
        continue
    elif i == 'w' and j == 'g':
        print("water drop in water\n")
        scorei = scorei + 1
        continue
    elif i == 'g' and j == 'w':
        print("water drop in water\n")
        scorej = scorej + 1
        continue
    elif i == 'g' and j == 's':
        print("gun shoot snake\n")
        scorei = scorei + 1
        continue
    elif i == 's' and j == 'g':
        print("gun shoot snake\n")
        scorej = scorej + 1
        continue
    else:
        print("game withdraw\n")
        continue

if(scorei<scorej):
    print("j is win")
elif(scorei>scorej):
    print("i is win")
else:
    print("game tie")

print("score of i=",scorei)
print("score of j=",scorej)
