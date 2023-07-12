# Non-NegativeProduct
# cook your dish here
for i in range(int(input())):
    n=int(input())
    li=list(map(int,input().split()))
    count=1
    for j in li:
         count=count*j
    if(count==0):
        print(0)
    elif(count<0):
        print(1)
    else:
        print(0)
