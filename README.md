# pat2-subtask1
# Name: [REFENTSE CAROLINE]
# Surname: [MOTUPA]
# Register Number: [0212270042089]

print("=== TVET College Mobile Clinic System ===")

# Prompt user for number of visitors
num_males = int(input("Enter number of male students (18–25): "))
num_females = int(input("Enter number of female students (18–25): "))
num_elderly_males = int(input("Enter number of elderly males (60–70): "))
num_elderly_females = int(input("Enter number of elderly females (60–70): "))

# Calculate individual totals
total_males = num_males * 25.00
total_females = num_females * 23.00
total_elderly_males = num_elderly_males * 18.00
total_elderly_females = num_elderly_females * 16.00

# Calculate overall total
total_fee = total_males + total_females + total_elderly_males + total_elderly_females

# Output all totals formatted to 2 decimal places
print("\n--- Daily Fee Summary ---")
print(f"Male students total: R{total_males:.2f}")
print(f"Female students total: R{total_females:.2f}")
print(f"Elderly males total: R{total_elderly_males:.2f}")
print(f"Elderly females total: R{total_elderly_females:.2f}")
print(f"\nTotal clinic fee collected: R{total_fee:.2f}")
