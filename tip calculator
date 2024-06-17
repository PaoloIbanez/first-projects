print("Welcome to the tip calculator. For your intelligent group of friends, who prefer to use a program to calculate your bill.")
bill = input("What was the total bill? $")
tip = input("What percentage tip would you like to give? 10, 12, 15, or 20? ")
people = input("How many people to split the bill? ")
bill_float = float(bill)
tip_float = float(tip)
people_int = int(people)
tip_percent = tip_float / 100
tip_amount = bill_float * tip_percent
total_bill = bill_float + tip_amount
bill_per_person = total_bill / people_int
final_amount = round(bill_per_person, 2)
#next line is to format and make it show 2 decimal places even if the last digit is 0
final_amount = "{:.2f}".format(bill_per_person)
print(f"Each person should pay: ${final_amount}")
