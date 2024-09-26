# Homework_2.2

number = int(input("Введите 5-значное число "))
num_1 = (number // 10000)
num_2 = (number // 1000) % 10
num_3 = (number // 100) % 10
num_4 = (number // 10 ) % 10
num_5 = number % 10
reversed_number = num_5 * 10000 + num_4 * 1000 + num_3 * 100 + num_2 * 10 + num_1
print("Число в обратном порядке", reversed_number)
