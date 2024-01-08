# Java-Cources
# Lab 3

print ("Hello,  robot")

a = int(input("Введите A:"))
b = int(input("Введите B:"))
c = int(input("Введите C:"))
s = a + b + c
print(s)

ap = int(input("Введите A:"))
bp = int(input("Введите B:"))
p = ap * bp
print(p)

#Математические функции
import math
x = float(input("Введите X:"))
t = float(input("Введите T:"))
z = (9 * math.pi * t + 10 * math.cos(x)) / (math.sqrt(t) - abs(math.cos(t))) * math.exp(x)
z = round(z, 2)
print(z)

#Условия и логические операторы
a = int(input("Введите A:"))
b = int(input("Введите B:"))
if (a>b):
 print(a)
else:
 print(b)

a = int(input("Введите A:"))
b = int(input("Введите B:"))
c = int(input("Введите C:"))
if (a>b):
 d=a
else:
 d=b
if (c>d):
 print(c)
else:
 print(d)

#Строки и списки
from collections import deque
def rotate_left(triple):
    return triple[1:] + triple[:1]
def rotate_right(triple):
    return triple[-1:] + triple[:-1]

triple = ('A', 'B', 'C')
print("Исходная тройка:", triple)
print("Вращение влево:", rotate_left(triple))
print("Вращение вправо:", rotate_right(triple))

#Расчет разницы углов
import math
def diff():
    alpha = int(input("Введите первый угол: "))
    beta = int(input("Введите второй угол: "))
    diff1 = abs(beta - alpha)
    diff2 = 360 - diff1
    result = min(diff1, diff2)
    print("Наименьшая разница между углами: ", result)
diff()

#Расчет числа Фибоначчи
def fib(n):
    if n <= 1:
        return n
    else:
        return fib(n-1) + fib(n-2)
a = int(input("Введите число: "))
print("Результат: "+ str(fib(a)))
