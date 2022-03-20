print("Welcome to Python Pizza Deliveries!")
size = input("What size pizza do you want? S, M, or L ")
add_pepperoni = input("Do you want pepperoni? Y or N ")
extra_cheese = input("Do you want extra cheese? Y or N ")
bill = 0
if size == "S":
  bill += 15
  # print("Small Pizza: $15")
  if add_pepperoni == "Y":
    bill +=2
    # print("Pepperoni for Small Pizza: +$2")
elif size == "M":
  bill += 20
  # print("Medium Pizza: $20")
  if add_pepperoni == "Y":
    bill +=3
    # print("Pepperoni for Medium or Large Pizza: +$3")
else:
  bill += 25
  # print("Large Pizza: $25")
  if add_pepperoni == "Y":
    bill +=3
    # print("Pepperoni for Medium or Large Pizza: +$3")

if extra_cheese == "Y":
  bill +=1
print(f"Your final bill is: ${bill}.")
