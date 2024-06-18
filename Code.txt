print("--------------Thank you for choosing Python Pizza Deliveries!--------------")
size = input(("Pizza size :")) 
add_pepperoni = input(("add_pepperoni :")) 
extra_cheese = input(("extra_cheese :")) 
bill = 0 
if size == "S" : 
  bill += 15
elif size == "M" : 
  bill += 20
else :
  size == "L"
bill += 25
if add_pepperoni == "Y" :
  size == "S"
  bill += 2 
elif add_pepperoni == "Y" :
  size == "M" and "L"
  bill += 3 
if extra_cheese == "Y":
  bill += 1
print("Thank you for choosing Python Pizza Deliveries!")
print(f"Your final bill is : ${bill}")
