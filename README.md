# House-Expenditure-Project
Python Project - 02


# " Inputs we need from the user "
# " Total Rent "
# " Total food ordered for snacks "
# " Electricity Units Spend "
# " Charge per Unit "
# " Person Living in room/flat " 

## Output
# Total amount you have to pay is


rent = int(input("Enter your hostel/flat rent = "))
food = int(input("Enter the amount of food ordered = "))
electricity_spend = int(input("Enter the amount of electricity spend = "))
charge_per_Unit = int(input("Enter the charge per unit = "))
persons = int(input("Enter the number of persons living in room/flat = "))

total_e_bill = electricity_spend * charge_per_Unit

output = (food + rent + total_e_bill) // persons

print("Each person will pay = " ,  output)
