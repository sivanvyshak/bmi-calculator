# bmi-calculator
bmi calculator using python

# how to calculate BMI 
def bodymassindex(height weight):
    bmi = (weight)/(height) **2 5
    return bmi
    
# Taking inputs from user
weight=float(input("Enter your weight in kilograms: )) 

height=float(input("Enter_your height in meters: "));

# calling the BMI function
bmi = bodymassindex(height, weight)
print("The Body masss index is ", bmi)

# Conditions to find out BMI category if (bmi < 18.5):
print(" You are underweight")

elif ( bmi >= 18.5 and bmi < 24.9):

print("Awsome your Healthy")

elif ( bmi >= 24.9 and bmi < 30):

print("Oop's you are overweight")

elif ( bmi >=30):

print("Suffering from Obesity You need to find a trainer ")
