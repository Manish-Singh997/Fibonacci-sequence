# Fibonacci-sequence
#Python code snippet that calculates the Fibonacci sequence and displays the first 10 numbers

def fibonacci(n):
    fib_sequence = [0, 1]
    for i in range(2, n):
        fib_sequence.append(fib_sequence[i - 1] + fib_sequence[i - 2])
    return fib_sequence

def main():
    n = 10  # Change this value to generate a different number of Fibonacci numbers
    fib_numbers = fibonacci(n)
    print(f"First {n} Fibonacci numbers:", fib_numbers)

if __name__ == "__main__":
    main()
