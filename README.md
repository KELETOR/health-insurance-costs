# health-insurance-costs
# create the initial variables below
age = 28
sex = 0
bmi = 26.2
num_of_children = 3
smoker = 0

# Add insurance estimate formula below
insurance_cost = (250 *age) - (128 * sex) + (370 *bmi) + (425 * num_of_children) + (24000 * smoker) - 12500
print(f"This Persons insurance cost is {insurance_cost} dolars\n")

# Age Factor
age += 4

new_insurance_cost = (250 *age) - (128 * sex) + (370 *bmi) + (425 * num_of_children) + (24000 * smoker) - 12500

print(f"This Persons insurance cost is {new_insurance_cost} dolars")

change_in_insurance_cost = new_insurance_cost - insurance_cost

print (f"The change in cost of insurance after increasing the age by 4 years is {change_in_insurance_cost} dollars\n")


# BMI Factor
age = 28
bmi += 3.1

new_insurance_cost = (250 *age) - (128 * sex) + (370 *bmi) + (425 * num_of_children) + (24000 * smoker) - 12500

print(f"This Persons insurance cost is {new_insurance_cost} dolars")

change_in_insurance_cost = new_insurance_cost - insurance_cost

print (f"The change in cost of insurance after increasing the BMI by 3.1 is {change_in_insurance_cost} dollars\n")

# Male vs. Female Factor
bmi = 26.2
sex = 1

new_insurance_cost = (250 *age) - (128 * sex) + (370 *bmi) + (425 * num_of_children) + (24000 * smoker) - 12500

print(f"This Persons insurance cost is {new_insurance_cost} dolars")

change_in_insurance_cost = new_insurance_cost - insurance_cost

print (f"The change in cost of insurance after changing sex to male is {change_in_insurance_cost} dollars\n")

# Extra Practice
sex = 0
smoker = 1

new_insurance_cost = (250 *age) - (128 * sex) + (370 *bmi) + (425 * num_of_children) + (24000 * smoker) - 12500

print(f"This Persons insurance cost is {new_insurance_cost} dolars")

change_in_insurance_cost = new_insurance_cost - insurance_cost

print (f"The change in cost of insurance after to a smoker is {change_in_insurance_cost} dollars\n")
