# py.19.11.20
1.
l1=[]
p=['Ronaldo','Virat','Gautam','Federer','Smriti']
l1.append(p)
print(l1)

2.
list1=[1,2,3,4,5,6,7]
n=int(input("enter a no"))
a=list1.count(n)
print(a)

3.
l1=[5,9,2,10,25]
l1.sort()
print(l1)

4.
l1=[1,2,4,6,9]
print(l1.index(4))

6.
list1 = [11, 12, 13, 14, 15]
list2 = [12, 13, 11, 15, 14]
a = set(list1)
b = set(list2)
if a == b:
	print("The list1 and list2 are equal")
else:
	print("The list1 and list2 are not equal")

5.
l1=[1,2,3]
l2=[4,5,6]
l3=[7,8,9]
t1=[]
t1.append(l1)
t1.append(l2)
t1.append(l3)
print(t1)

Questionaries:
1.
When an item (a.k.a element) of beatles is changed, the associated names list is also changed. This is an important property of Python. Mutability is the ability for certain types of data to be changed without entirely recreating it. This is important for Python to run programs both quickly and efficiently.


2.Basically, Python lists are very flexible and can hold completely heterogeneous, arbitrary data, and they can be appended to very efficiently, in amortized constant time. If you need to shrink and grow your array time-efficiently and without hassle, they are the way to go. But they use a lot more space than C arrays.

The array.array type, on the other hand, is just a thin wrapper on C arrays. It can hold only homogeneous data, all of the same type, and so it uses only sizeof(one object) * length bytes of memory.

So a list can be like: [1, 'a', [1, 2], 'string']

But an array can only contain things of the same type: [1, 2, 3, 4]
