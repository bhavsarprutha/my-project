# my-project
def is_even(number):
    if number % 2 == 0:
        return True
    else:
        return False

# Test the function
num = int(input("Enter a number: "))
if is_even(num):
    print(num, "is an even number.")
else:
    print(num, "is not an even number.")
