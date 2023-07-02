# 100-test-code

# -*- coding: utf-8 -*-
"""코드업 기초100제

Automatically generated by Colaboratory.

Original file is located at
    https://colab.research.google.com/drive/1eZptbo84leefqHu-7o1d-ze8SxOgtZ_A
"""

#1001
print("Hello")

#1002
print("Hello World")

#1003
print("Hello")
print("World")

#1004
print("\'Hello\'")

#1005
print("\"Hello World\"")

#1006
print("\"!@#$%^&*()\"")

#1007
print("\"C:\Download\hello.cpp\"")

#1008
print("\u250c\u252c\u2510")
print("\u251c\u253c\u2524")
print("\u2514\u2534\u2518")

#1010
n = input()
print(n)

#1011
n = input()
print(n)

#1012
n = float(input())
print("%f"%n)

#1013
a,b = input().split()
print("{} {}".format(a,b))

#1014
a,b = input().split()
print("{} {}".format(b,a))

#1015
n = float(input())
print("%.2f"%n)

#1017
a = input()
print("{} {} {}".format(a,a,a))

#1018
a = input()
h = a.split(':')[0]
m = a.split(':')[1]

print("{}:{}".format(h,m))

#1019
a = input()
y = int(a.split('.')[0])
m = int(a.split('.')[1])
d = int(a.split('.')[2])

print("%04d.%02d.%02d"%(y,m,d))

#1020
a = input()
print("{}{}".format(a.split('-')[0],a.split('-')[1]))

#1021
a = input()
print(a)

#1022
a = input()
print(a)

#1023
f = input()
a = f.split('.')[0]
b = f.split('.')[1]
print(a)
print(b)

#1024
n = input()
m = list(n)
for i in range(len(m)):
  print("\'{}\'".format(m[i]))

#1025
n = input()
m = list(n)
for i in range(len(m)):
  print("[{}]".format(int(m[i])*(10**(4-i))))

#1026
n = input()
m = n.split(':')[1]
print(int(m))

#1027
n = input()
m = n.split(".")
print("%02d-%02d-%04d"%(int(m[2]),int(m[1]),int(m[0])))

#1028
n = input()
print(n)

#1029
n = float(input())
print("%.11lf"%n)

#1030
n = input()
print(n)

#1031
n = int(input())
print("%o"%n)

#1032
n = int(input())
print("%x"%n)

#1033
n = int(input())
print("%X"%n)

#1034
n = input()
m = '0o' + n
m = int(m,8)
print(m)

#1035
n = input()
m = '0x' + n
m = int(m,16)
l = oct(m)
l = str(l)
l=l.replace("0o","")
print(l)

#1036
n = input()
print(ord(n))

#1037
n = input()
print(chr(int(n)))

#1038
a,b = input().split()
c = int(a)+int(b)
print(c)

#1039
a,b = input().split()
c = int(a)+int(b)
print(c)

#1040
n = int(input())
print(-n)

#1041
n = input()
m = ord(n)
m = m+1
print(chr(m))

#1042
a,b = input().split()
print(int(int(a)/int(b)))

#1043
a,b = input().split()
c = int(a)%int(b)
print(c)

#1044
n = int(input())
print(n+1)

#1045
a,b = input().split()
a = int(a)
b = int(b)
c = a+b
print(c)
c = a-b
print(c)
c = a*b
print(c)
c = a//b
print(c)
c = a%b
print(c)
c = a/b
print("%.02f"%c)

#1046
a,b,c = input().split()
a = int(a)
b = int(b)
c = int(c)

total = a+b+c
avg = total/3

print(total)
print("%.1f"%avg)

#1047
a = int(input())
a = a<<1
print(a)

#1048
a,b = input().split()
a = int(a)
b = int(b)

c = a<<b
print(c)

#1049
a,b = input().split()
a = int(a)
b = int(b)
if a>b:
  print(1)
else :
  print(0)

#1050
a,b = input().split()
a = int(a)
b = int(b)

if a == b : 
  print(1)
else : 
  print(0)

#1051
a,b = input().split()
a = int(a)
b = int(b)

if b >= a :
  print(1)
else :
  print(0)

#1052
a,b = input().split()
a = int(a)
b = int(b)

if a!=b :
  print(1)
else : 
  print(0)

#1053
a = int(input())

if a == 0 :
  print(1)
else : 
  print(0)

#1054
a,b = input().split()
a = bool(int(a))
b = bool(int(b))

if a and b :
  print(1)
else :
  print(0)

#1055
a,b = input().split()
a = bool(int(a))
b = bool(int(b))

if a or b :
  print(1)
else :
  print(0)

#1056
a,b = input().split()
a = bool(int(a))
b = bool(int(b))

if a ^ b :
  print(1)
else :
  print(0)

#1057
a,b = input().split()
a = bool(int(a))
b = bool(int(b))

if not(a ^ b) :
  print(1)
else :
  print(0)

#1058
a,b = input().split()
a = bool(int(a))
b = bool(int(b))

if not(a or b) :
  print(1)
else :
  print(0)

#1059
a = int(input())
b = ~a
print(b)

#1060
a,b = input().split()
a = int(a)
b = int(b)

c = a&b
print(c)

#1061
a,b = input().split()
a = int(a)
b = int(b)

c = a|b
print(c)

#1062
a,b = input().split()
a = int(a)
b = int(b)

c = a^b
print(c)

#1063 
a,b = input().split()
a = int(a)
b = int(b)

c = a if a>b else b
print(c)
#파이썬에서 3항 연산자

#1064
a,b,c = input().split()
a = int(a)
b = int(b)
c = int(c)

d = (a if a<b else b) if (a if a<b else b)<c else c
print(d)

#1065
a,b,c = input().split()
a = int(a)
b = int(b)
c = int(c)

if not(bool(a%2)) :
  print(a)
if not(bool(b%2)) :
  print(b)
if not(bool(c%2)) :
  print(c)

#1066
a,b,c = input().split()
a = int(a)
b = int(b)
c = int(c)

if not(bool(a%2)) :
  print("even")
else :
  print("odd")
if not(bool(b%2)) :
  print("even")
else :
  print("odd")
if not(bool(c%2)) :
  print("even")
else :
  print("odd")

#1067
a = int(input())

if a > 0 : 
  if a%2 == 0 : 
   print("plus")
   print("even")
  else : 
    print("plus")
    print("odd")
else :
  if a%2 == 0 :
    print("minus")
    print("even")
  else : 
    print("minus")
    print("odd")

#1068
a = int(input())

if a >= 90 : 
  print("A")
elif a >= 70 :
  print("B")
elif a >= 40 :
  print("C")
elif a >= 0 :
  print("D")

#1069
a = input()

if a == "A" : 
  print("best!!!")
elif a == "B" :
  print("good!!")
elif a == "C" :
  print("run!")
elif a == "D" :
  print("slowly~")
else : 
  print("what?")

#1070
a = int(input())

if a==12 or a==1 or a==2 :
  print("winter")
elif a==3 or a==4 or a==5 :
  print("spring")
elif a==6 or a==7 or a==8 :
  print("summer")
elif a==9 or a==10 or a==11 :
  print("fall")

#1071
n = list(input().split())
for i in range(len(n)) :
  if int(n[i]) == 0 : break;
  else : print(n[i])

#1072
a = input()
n = list(map(int,input().split()))
for i in range(len(n)) : print(n[i])

#1073
n = list(input().split())
for i in range(len(n)) :
  if int(n[i]) == 0 : break;
  else : print(n[i])

#1074
n = int(input())
while n != 0 :
  print(n)
  n -=1

#1075
n = int(input())
while n != 0 :
  n -=1
  print(n)

#1076
n = input()
a = 'a'
while a <= n : 
  print(a)
  a = chr(ord(a)+1)

#1077
n = int(input())
for i in range(n+1) : 
  print(i)

#1078
n = int(input())
total = 0
for i in range(1,n+1) :
  if i % 2 == 0 : 
    total += i

print(total)

#1079
n = list(input().split())
for i in range(len(n)) :
   if n[i] == 'q' :
    print(n[i]) 
    break
   else : print(n[i])

#1080
max = int(input())
total = 0
n = 1
while True :
  total += n
  if total >= max : break;
  n += 1
print(n)

#1081
n,m = input().split()
n = int(n)
m = int(m)

for i in range(1,n+1) : 
  for j in range(1,m+1) :
    print("{} {}".format(i,j))

#1082
n = input()
m = '0x' + n
m = int(m,16)

for i in range(1,16) : 
  print("%X*%X=%X"%(m,i,m*i))

#1083
n = int(input())

for i in range(1,n+1):
  if i%3 == 0 : print("X",end = " ")
  else : print(i,end = ' ')

#1084
r,g,b = input().split()
r = int(r)
g = int(g)
b = int(b)
count = 0

for i in range(r) : 
  for j in range(g) :
    for k in range(b) :
      print("{} {} {}".format(i,j,k))
      count += 1

print(count)

#1085
h,b,c,s = input().split()
h = int(h)/1024
b = int(b)
c = int(c)
s = int(s)

store = h*b*c*s/(8*1024)

print("%.1f MB"%store)

#1086
r,g,b = input().split()
r = int(r)
g = int(g)
b = int(b)

print("%.2f MB"%(r*g*b/8/1024/1024))

#1087
n = int(input())
m = 1
sum = 0
while sum < n : 
  sum += m
  m +=1

print(sum)

#1088
n = int(input())

for i in range(1,n+1) : 
  if i%3==0 : continue
  else : print(i,end=' ')

#1089
a,d,n = input().split()

a = int(a)
d = int(d)
n = int(n)

r = a+d*(n-1)
print(r)

#1090
a,r,n = input().split()

a = int(a)
r = int(r)
n = int(n)

r = a*r**(n-1)
print(r)

#1091
a,m,d,n = input().split()

a = int(a)
m = int(m)
d = int(d)
n = int(n)

r = a
for i in range(n-1) : 
  r = r*m+d

print(r)

#1092
a,b,c, = input().split()
a = int(a)
b = int(b)
c = int(c)

n=1
while True :
  if n%a==0 and n%b==0 and n%c==0 : break
  n += 1
print(n)

#1093
num = [0 for i in range(23)]

n = int(input())
random = list(map(int,input().split()))

for i in random : 
  num[i-1] += 1

for i in range(23) : 
  print(num[i], end = ' ')

#1094
n = int(input())
random = list(map(int,input().split()))

for i in range(n) : 
  print(random[n-i-1], end = ' ')

#1095
n = int(input())
random = list(map(int,input().split()))

min = random[0]

for i in range(n) : 
  if min > random[i] : 
    min = random[i]

print(min)

#1096
array = [[0 for col in range(19)] for row in range(19)]

n = int(input())
for i in range(n) : 
  x,y = input().split()
  x = int(x)
  y = int(y)
  array[x-1][y-1] = 1

for i in range(19) : 
  for j in range(19) : 
    print(array[i][j],end=' ')
  print()

#1097
array = [[0 for col in range(19)] for row in range(19)]
for i in range(19) : 
  array[i] = list(map(int, input().split()))

n = int(input())
for i in range(n) : 
  x,y = input().split()
  x = int(x)
  y = int(y)
  for j in range(19) : 
    if array[x-1][j] == 0 : array[x-1][j] = 1
    else : array[x-1][j] = 0
  for j in range(19) : 
    if array[j][y-1] == 0 : array[j][y-1] = 1
    else : array[j][y-1] = 0

for i in range(19) : 
  for j in range(19) : 
    print(array[i][j],end=' ')
  print()

#1098
h,w = input().split()
h = int(h)
w = int(w)
array = [[0 for col in range(w)] for row in range(h)]

n = int(input())
for i in range(n) :
  l,d,x,y = input().split()
  l = int(l)
  d = int(d)
  x = int(x)-1
  y = int(y)-1
  if d == 0 :
    for j in range(l) : 
      array[x][y+j] = 1
  else :
    for j in range(l) : 
      array[x+j][y] = 1

for i in range(h) : 
  for j in range(w) : 
    print(array[i][j],end=' ')
  print()

#1099
array = [[0 for col in range(10)] for row in range(10)]
for i in range(10) : 
  array[i] = list(map(int, input().split()))

x = 1
y = 1

while True :
  if array[x][y] == 2 : 
    array[x][y] = 9
    break
  if x == 8 and y == 8 : 
    array[8][8] = 9
    break
  if array[x + 1][y] == 1 and  array[x][y + 1] == 1 : break

  if array[x][y+1] == 0 or array[x][y+1] == 2 :
    array[x][y] = 9
    y += 1 
  elif array[x + 1][y] == 0 or array[x + 1][y] == 2 : 
    array[x][y] = 9
    x += 1
    
for i in range(10) : 
  for j in range(10) : 
    print(array[i][j],end=' ')
  print()
