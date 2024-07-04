
from art import logo
print(logo)
import random
print("Welcome to the Number Guessing Game!")
print("I'm thinking of a number between 1 and 100.")

def numbergen():
  number = random.randint(1,100)
  return number

def difficulty():
  difficulty = input("Choose a difficulty. Type 'easy' or 'hard': ")
  if difficulty == "easy":
    return 10
  elif difficulty == "hard":
    return 5

def check(guess, number):
  if guess == number:
    print(f"You got it! The answer was {number}.")
    return True
  elif guess > number:
    print("Too high.")
    return False
  elif guess < number:
    print("Too low.")
    return False

def game():
  number = numbergen()
  lives = difficulty()
  while lives > 0:
    print(f"You have {lives} attempts remaining to guess the number.")
    guess = int(input("Make a guess: "))
    if check(guess, number) == True:
      return
    else:
      lives -= 1
  print("You've run out of guesses, you lose.")
game()
