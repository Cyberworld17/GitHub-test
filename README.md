# GitHub-test
# Get user input for name and age
name = input("Enter your name: ")
age = int(input("Enter your age: "))

# Calculate the year when the user will turn 100
current_year = 2024  # You can update this to the current year
years_until_100 = 100 - age
century_year = current_year + years_until_100

# Display a personalized greeting
print(f"Hello, {name}! You will turn 100 years old in the year {century_year}.")
