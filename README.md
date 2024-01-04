# Java-Cources


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
 triple = ('A', 'B', 'C')
 rotate_left(triple)
 ('B', 'C', 'A')
 rotate_right(triple)
 ('C', 'A', 'B')

def rotate_left(triple):
    return triple[1], triple[2], triple[0]

def rotate_right(triple):
    return triple[2], triple[0], triple[1]


#Расчет разницы углов

