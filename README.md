# PythonCoding_Problem_Solving4_Life_in_weeks
Your Life in Weeks and realised just how little time we actually have.  https://waitbutwhy.com/2014/05/life-weeks.html  Create a program using maths and f-Strings that tells us how many days, weeks, months we have left if we live until 90 years old. f-Strings coding example: name = 'Tushar' ; age = 23 ;
print(f"Hello, My name is {name} and I'm {age} years old.")

age = input("What is your current age?")
# 🚨 Don't change the code above 👆

# Write your code below this line 👇
# 1 yr is 365 days; 1 yr is 52 weeks; 1 yr is 12 months

year_to_days = (90-int(age))  * 365

year_to_weeks = (90 - int(age)) * 52

year_to_months = (90 - int(age)) * 12

print(f"You have {year_to_days} days, {year_to_weeks} weeks, {year_to_months} months left")
