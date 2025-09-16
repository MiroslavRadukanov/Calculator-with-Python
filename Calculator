import random
import math
print("Калкулатор с AI функции!")

while True:
  fun = input("Въведи 1 за 'класически', 2 за 'случайна задача', 3 за 'статистика', 4 за 'факториел' или 5 за 'изход' : ")
  
  if fun == "5":
    print("Довиждане!")
    break
  
  elif fun == "1":
    a = float(input("Първо число: "))
    b = float(input("Второ число: "))
    op = input("Избери операция (+, -, *, /, ^, sqrt, %): ")
    if op == "+": print(a + b)
    elif op == "-": print(a - b)
    elif op == "*": print(a * b)
    elif op == "/": 
      if b != 0: print(a / b)
      else: print("Не може да делиш на 0!")
    elif op == "^": print(a ** b)
    elif op == "sqrt": print(a ** 0.5)
    elif op == "%": 
      if b != 0: print(int(a//b), f"(ост. {a%b})")
      else: print("Не се дели на 0!")
      
  elif fun == "2":
    mode = random.choice(["+", "-", "*"])
    x = random.randint(1, 10)
    y = random.randint(1, 10)
    if mode == "+":
        correct = x + y
    elif mode == "-":
        correct = x - y
    else:
        correct = x * y
    answer = int(input(f"{x} {mode} {y} = "))
    if answer == correct:
        print("Браво, позна!")
    else:
        print(f"Не позна, правилният отговор беше {correct}.")
        
  elif fun == "3":
    nums = input("Въведи числа: ")
    parts = nums.split(" ")
    nums = []
    for n in parts:
      num = float(n)
      nums.append(num)
    print("Средно аритметично:", sum(nums) / len(nums))
    print("Максимум:", max(nums))
    print("Минимум:", min(nums))
    print("Брой числа:", len(nums))
    print("Сума:", sum(nums))
  
  elif fun == "4":
  	fact = int(input("Въведи число за факториел: "))
  	multi = 1
  	while fact >= 1:
  		multi = multi * fact
  		fact -= 1
  	print(multi)
  	
  	
  else:
    print("Невалидна опция!")
