# Define a function to reverse a string
def string_reverse(input_string):
    return input_string[::-1]

# Define a function to convert an integer to reverse binary


def int_to_reverse_binary(integer_value):
    if integer_value <= 0:
        return "0"  # Special case for 0

    binary_str = ''
    while integer_value > 0:
        remainder = integer_value % 2  # Get the remainder when dividing by 2
        binary_str += str(remainder)   # Add the remainder to the binary string
        integer_value //= 2            # Integer division by 2 to get the next bit

    return binary_str


# Input a positive integer from the user
num = int(input("enter integer: "))

# Convert the integer to its reverse binary representation
reverse_binary = int_to_reverse_binary(num)

# Reverse the binary representation string
reverse_binary = string_reverse(reverse_binary)

# Print the reverse binary representation
print(f"{reverse_binary}")
