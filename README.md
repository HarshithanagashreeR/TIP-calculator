# TIP-calculator
print("welcome to the tip caclculator")
total=int(input("what is your total bill ?"))
tip=int(input("what is the tip you would like to give 10,15,20 ?"))
split=int(input("how many people to split the bill ?"))
total_bill=total+tip/split
print("the total bill is ",total_bill)
