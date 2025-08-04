# Prompt user to enter their access code
access_code = input("Please enter your 7-digit access code: ")

# Validation checks
is_valid_length = len(access_code) == 7
starts_with_digit = access_code[0].isdigit() if is_valid_length else False
ends_with_T = access_code[-1] == "T" if is_valid_length else False

# Final validation and output
if is_valid_length and starts_with_digit and ends_with_T:
    print("✅ Valid passcode you may proceed")
else:
    print("❌ Invalid passcode!")
