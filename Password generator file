#Password Generator Project
import random

letters = ['a', 'b', 'c', 'd', 'e', 'f', 'g', 'h', 'i', 'j', 'k', 'l', 'm', 'n', 'o', 'p', 'q', 'r', 's', 't', 'u', 'v', 'w', 'x', 'y', 'z', 'A', 'B', 'C', 'D', 'E', 'F', 'G', 'H', 'I', 'J', 'K', 'L', 'M', 'N', 'O', 'P', 'Q', 'R', 'S', 'T', 'U', 'V', 'W', 'X', 'Y', 'Z']
numbers = ['0', '1', '2', '3', '4', '5', '6', '7', '8', '9']
symbols = ['!', '#', '$', '%', '&', '(', ')', '*', '+']

print("Welcome to the PyPassword Generator!")
nr_letters= int(input("How many letters would you like in your password?\n")) 
nr_symbols = int(input("How many symbols would you like?\n"))
nr_numbers = int(input("How many numbers would you like?\n"))

# Order not randomised:


# for letter in range(0, nr_letters):
#   random_letter = random.randint(0, len(letters)-1)
#   print(letters[random_letter], end = "")
# for symbol in range(0, nr_symbols):
#   random_symbol = random.randint(0, len(symbols)-1)
#   print(symbols[random_symbol], end = "")
# for number in range(0, nr_numbers):
#   random_number = random.randint(0, len(numbers)-1)
#   print(numbers[random_number], end = "")


  
# Order of characters randomised:
password = ""


for letter in range(0, nr_letters):
  random_letter = random.randint(0, len(letters)-1)
  password += letters[random_letter]
for symbol in range(0, nr_symbols):
  random_symbol = random.randint(0, len(symbols)-1)
  password += symbols[random_symbol]
for number in range(0, nr_numbers):
  random_number = random.randint(0, len(numbers)-1)
  password += numbers[random_number]






password_list = list(password)  # Convert to list
random.shuffle(password_list)  # Shuffle the list in-place
password = ''.join(password_list)  # Join the list back into a string


print(f"Your password is: {password}")
