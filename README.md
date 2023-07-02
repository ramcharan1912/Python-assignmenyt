# Python-assignment
def determine_age_category(age):
    if age < 18:
        return "You are a minor"
    elif age < 65:
        return "You are an adult"
    else:
        return "You are a senior"

age = int(input("Enter your age: "))
age_category = determine_age_category(age)
print(age_category)
