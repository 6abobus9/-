a=int(input ("введите значение а: "))
b=int(input ("введите значение б: "))
c=int(input ("введите значение с: "))
d=b**2-4*a*c
if d<0:
     print ("корней нет")
dd=d**0.5
x1=(-b+dd)/(a*2)
x2=(-b-dd)/(a*2)
print (x1)
print (x2)
