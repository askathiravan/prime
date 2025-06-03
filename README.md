def prime(a):
    c=0
    for i in range(2,a):
        if a%i==0:
            c=c+1
        return c==0
def sum1(b):
    d=0
    e=str(b)
    for i in e:
        d=d+int(i)
    return d
   
for i in range(100,1000):
    if(prime(i) and prime(sum1(i))):
        print(i)
