#WAP Write a Python program to calculate the gross salary of an employee when the basic salary is given. Assume that the House Rent Allowance (HRA) is 20% of the basic salary and the Dearness Allowance (DA) is 10% of the basic salary.
Basic_salary = int(input("Enter the number"))
HRA = 0.20*Basic_salary
DA = 0.10*Basic_salary
Gross_salary = Basic_salary+HRA+DA
print(Gross_salary)



#WAP Write a Python program to calculate the net salary of an employee. The basic salary is given. Assume that HRA is 15%, DA is 10%, and Provident Fund (PF) is 8% of the basic salary.
Basic_salary = int(input("Enter the net salary"))
Hra = 0.15*Basic_salary
Da = 0.10*Basic_salary
Pf = 0.08*Basic_salary
Net_salary = (Basic_salary + Hra + Da) - Pf
print(Net_salary)




 #Write a Python program to calculate the speed of an object when the distance traveled and time taken are given.\
 #X = Distance and t = time
 X = int(input("Enter the Distance = "))
 t = int(input("Enter the Time = "))
 V = X/t     #V is speed
 print(V)




#Write a Python program to calculate the selling price of an item when the marked price and discount percentage are given.
MRP = int(input("Enter the MRP = "))
Discount = float(input("Enter the Discount = "))
Discounts = Discount/100
Discount_amount = MRP * Discounts
Selling_price = MRP - Discount_amount
print(Selling_price)







#Write a Python program to calculate the total marks and percentage obtained by a student when the marks in three subjects are given. Assume the maximum marks for each subject is 100.
Python = int(input("Enter the python = "))
Java = int(input("Enter the Java = "))
C = int(input("Enter the C = "))
Each_Exam_total_Marks = 100
Total_Marks = Python + Java + C
print(Total_Marks)
Percentage = (Total_Marks/300)*Each_Exam_total_Marks
print(Percentage)
