import random
num = random.randint(1,100)
guesses = [0]
while True:
    guess = int(input('What number do you think? '))
    guesses.append(guess)
    if guess > 100 or guess < 1:
        print("Enter a number between 1 and 100.")
        continue
    elif guess == num:
        print("woah you guessed correct!!")
        print(f'You guessed in {len(guesses)-1} guesses!!')
        break
    elif guesses[-2]:  
        if abs(num-guess) < abs(num-guesses[-2]):
            print('WARMER!')
        else:
            print('COLDER!')
    else:
        if abs(num-guess) <= 10:
            print('WARM!')
        else:
            print('COLD!')
