n=int(input("enter number:"))
for i in range(1,n+1):
    for j in range(1,i+1):
        print(j,end=" ")
    print("\n")
for i in range(1,n+1):
    for j in range(1,n-i+1):
        print(j,end=" ")
    print("\n")
    
    output:
    enter number:3
    1
    1 2
    1 2 3
    1 2 
    1
