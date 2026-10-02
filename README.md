
def calculate_gcd(a, b):
    while b:
        a, b = b, a % b

    return abs(a)


if __name__ == "__main__":
    first = 84
    second = 30

    print("First number:", first)
    print("Second number:", second)
    print("GCD:", calculate_gcd(first, second))
