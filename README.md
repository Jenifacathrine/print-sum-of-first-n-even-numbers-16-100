# print-sum-of-first-n-even-numbers-16-100
n = int(input("Enter a number: "))
sum_of_even_numbers = 0
for i in range(2, 2*n+1, 2):
    sum_of_even_numbers += i
print("The sum of first", n, "even numbers is:", sum_of_even_numbers)


