# python11
star operations
n=int(input())
for i in range(n):
    for j in range(n):
        if j==0 or j=n-1 i==j or i+j=n-1:
          print("*",end=" ")
        else:
            print(" ",end=" ")
    print()

#python11(b)
n=int(input())
for i in range(n):
    for j in range(n):
        if j==i:
          print("*",end=" ")
        else:
            print(" ",end=" ")
    print()



#model ques
n=int(input())
for i in range(n):
    for j in range(n):
        if i==n//2 or j==n//2:
          print("*",end=" ")
        else:
            print(" ",end=" ")
    print()
 


#star printing 
n=int(input())
for i in range(n):
    for j in range(i):
        print("*",end=" ")
    print()

#pyramid
n=int(input())
for i in range(1,n+1):
    for j in range(n-i):
        print(" ",end=" ")
    for k in range(2*i-1):
        print("*",end=" ")
    print()

#reverse pyramid

    n=int(input())
for i in range(n,0,-1):
    for j in range(n-i):
        print(" ",end=" ")
    for k in range(2*i-1):
        print("*",end=" ")
    print()
