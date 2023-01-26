# Day-10
a=int(input())
b=1
c=2
if a==1:
    print(b)
elif a==2:
    print(c)
else:
    for i in range(2,a):
        d=b+c
        b=c
        c=d
    print(d)
