name = input("Введіть своє ім'я: ")
age = int(input("Введіть свій вік: "))
print(f"Привіт {name}, тобі {age}!")

age = int(input("Введіть свій вік: "))
if age >= 18:
    print("Вхід дозволено!")
else:
    print("Вхід заборонено!")

import random
secret = random.randint(1, 10)
attempts = 3
while attempts > 0:
    guess = int(input("Вгадайте число від 1 до 10: "))
    if guess == secret:
        print("Вітаю! Ви вгадали!")
        break
    elif guess > secret:
        print("Менше")
    else:
        print("Більше")
    attempts -= 1
if attempts == 0:
    print(f"Ви програли! Загадане число було {secret}")

a = int(input("Введіть перше число: "))
b = int(input("Введіть друге число: "))
for i in range(a, b + 1):
    print(i, end=" ")
print()

n = int(input("Введіть число n: "))
for i in range(n, 0, -1):
    if i % 2 == 0:
        print(i, end=" ")
print()

n = int(input("Введіть число для обчислення факторіалу: "))
fact = 1
for i in range(1, n + 1):
    fact *= i
print(f"Факторіал {n} = {fact}")

score = int(input("Введіть кількість балів: "))
if 0 <= score <= 49:
    print("Незадовільно")
elif 50 <= score <= 69:
    print("Задовільно")
elif 70 <= score <= 89:
    print("Добре")
elif 90 <= score <= 100:
    print("Відмінно")
else:
    print("Неправильне значення балів")
