# arithmetic-python-operators
#1
x=input("enter first number : ")
y=input("enter second number : ")
i=int(x)
j=int(y)
print("THE SUM :" , i+j)

#2
x=int(input("enter first number"))
y=int(input("enter second number"))
print("THE SUM : ", x+y)

#3
print("THE SUM : ",int(input("enter first number : "))+int(input("enter second number:")))

#4
a="3.5"
b="6.5"
c=float(a)+float(b)
print(c)
print(type(c))

#5
a,b=9,2
print("remaining book :", a%b)
print("book per person :",a//b)

#6
a=3
b=4
print(a-b)
print(a*b)
print(a**b)
a,b=3,4 
print(a**b,"Addition \t",a+b,"\n",a-b,a*b,"\t",a/b)

#7
i=1
final=[]
for i in range(1,11):
    print(i,'x',i+1,'=',1*2)
    final.append(i*2)
    i+=1
print('Sum=',sum(final))

#8
name=input("what is your namr? :")
print('HELLO' + name)

#9
old=int(input("enter your old age? :"))
new=old+2
print(new)

#10
num=18
print(float(num))
print(str(num))
print(bool(num))

#11
first=input("input 1st number :")
second=input("enter second number :")
sum=first+second
print(sum)

#12
print(5/2)
print(5//2)
print(5%2)
print(5**2)

#13
i=5
i=1+5
i+=5
print(i)
i*=2
print(i)
i/=2
print(i)


#14
