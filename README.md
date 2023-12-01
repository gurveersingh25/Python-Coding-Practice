print("hello world") x=5
 y=5
 print(x+y)
 x=3
 c=6
 z=x*c
 print(z)
# elif z=="//":
#     print(x//y)
# else:
#     print("enter valid")

# count_odd=0
# count_even=0
for i in range(0,10):
  if(i%2==0):
     print(i,"is even")
     count_even+=1
 else:
     print(i,"is odd")
#     count_odd+=1
# print("count_odd")
# print("count_odd")
# i=0
# for i in range(0,10):
#     if(i==6):
#         break
#         print(i)
#         i+=1
#         print("thank you")
# i=0
# while i in range(0,10):
#      if i==4 or i==5 or i==8:
#          i=i+1
#          continue
#      else:
#          print(i)
#          i=i+1
# i=0
# for i in reversed(range(10,21)):
#     if i==4 or i==5 or i==8:
#         i=i+1
#         continue
#     else:
#         print(i)
#         i=i+1
# list = ["apple", "banana", "cherry", "banan", "pickle", "mango"]


# print(type(list))
# print(len(list))
# print(list[-1:-4:-1])
# if "apple" in list:
#     print("yes","apple is in the list")
# else:
#     print("no" "apple is not in list")
# list[1:2]=["blackcurrant","watermelon"]
# print(list)
# print(len(list))
# print(list[-1::-1])
# list=["apple","banana","cherry","orange","kiwi","mango"]
# list[1:3]=["blankcurrant","watermelon"]
# print(list)
# list=["apple","banana","cherry"]
# list[1:3]=["watermelon"]
# print()
# letters="harsh"
# string_letters=str(letters)
# list_letters=list(letters)
# tuples_letters=tuple(letters)
# sets_letters=set(letters)
# print("string",string_letters)
# print("lists",list_letters)
# print("tuples",tuples_letters)
# print("sets:",sets_letters)#sets are not odered
# list.append("harsh")
# print(list)
# list.clear()
# print(list)
# def reverse(string):
#     string = string[::-1]
#     return string
#
#
# s = "popoy"
#
# print("The original string is : ", end="")
# print(s)
#
# print("The reversed string is : ", end="")
# print(reverse(s))
# x=39
# y=(x-32)*5/9
# print(y)
# number=int(input("enter a number"))
# num=number
# sum=0
# if number<=0:
#     print("enter a positive number")
# else:
#     while num>0:
#         sum=sum+num
#         num=num-1;
# print("sum of first",number,"natural number is:",sum)
# list=[12,13,13]
# list.clear()
# print(list)
# list.append(10)
# print(list)
# list.append(50)
# print(list)
# x=list.copy()
# print(x)
# x.append(5)
# print(x)
# print(list)
# y=list.count(10)
# print(y)
# list=[13,13,14]
# # list.extend((12,14))
# # print(list)
# list.extend(['a','b','c'])
# print(list)
# list.extend([2,3,4])
# print(list)
# x=list.index(4)
# print(x)
list=[1,2,3,4,5,6]
# list.insert(6,"hello")
# print(list)
# list.pop(2)
# print(list)
# list.remove(1)
# print(list)
# list.reverse()
# print(list)
# list.sort()
# print(list)
# list.sort(reverse=True)
# print(list)
# fruits=["apple","banana","cherry","kiwi","mango"]
# newlist=[]
# for x in fruits:
#     if "a" in x:
#         newlist.append(x)
# print(newlist)
# newlist=[x for x in range(10)]
#
# print(newlist)
# nlist=[x for x in range(10) if x<5]
# print(nlist)
# square = list(map(lambda x: x**2, range(10)))
# print(square)
#sq=[x**2for x in range(10)]
#print(sq)
# newlist=[(x,y) for x in [1,2,3] for y in [3,1,4] if x!=y]
# print(newlist)
# hr=newlist[0]
# print(hr)
# print(type(hr))
# matrix=[[1,2,3,4],[5,6,7,8],[9,10,11,12],]
# print([[row[i]for row in matrix] for i in range(4)])
# print(type(matrix))
# print(len(matrix))
# tuple1=("apple","banana","cherry")
# print(tuple1)
# tpl=("apple")
# print(type(tpl))
# tp1=("apple",)
# print(type(tp1))
#x=("apple","banana","cherry")
# x[1]=("kiwi")
#p=list(x)
# tup=(3,5,2,4,7)
# y=('a','b','c')
# x=tup+y
# print(x)
# a,b,c,d,e=tup
# #print(a,b,c,d,e)
# a,b, *c=tup
# print(a,b,c)
# a, *b,c=tup
# print(a,b,c)
# def factorial(n):
#    if n==1:
#        return n
#    else:
#        return n*factorial(n-1)
# print(factorial(7))
# print("hello world")
# x=5
# y=5
# for i in range(1,x+1,1):
#     for j in range (i,y+1,-1):
#         print(j,end=" ")
#     print(" ")
# size = 7
# m = (2 * size) - 2
# for i in range(0, size):
#     for j in range(0, m,):
#         print(end=" ")
#     # decrementing m after each loop
#     m = m - 1
#     for j in range(0, i + 1):
#         print("* ", end=' ')
#     print(" ")
# rows = 5
# i = 1
# while i <= rows:
#     j = rows
#     while j > i:
#         # display space
#         print(' ', end=' ')
#         j -= 1
#     print('*', end=' ')
#     k = 1
#     while k < 2 * (i - 1):
#         print(' ', end=' ')
#         k += 1
#     if i == 1:
#         print()
#     else:
#         print('*')
#     i += 1
def add(x,y):
    return x+y
    print(x+y)
add(3,4)
