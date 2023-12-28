# BMI-CALC
Body Mass Index Calculator

print("Welcome to BMI Calculator")

height= input("What is your height in meters: ")
height_as_int= float(height)

weight= input("Enter your Weight in lbs: ")
weight_as_int= int(weight)

bmi= weight_as_int/(height_as_int * height_as_int)

print(f"Your BMI is {bmi}")
