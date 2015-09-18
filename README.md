# WSQ07
sum = 0
while True:
    try:
        n = int(input ("please, give the lower number of the range "))
        break
    except ValueError:
        print("invalid value! please write another number")
while True:
    try:
        m = int(input ("please, give me a higher number for the range "))
    except ValueError:
        print("invalid value! please write another number")
    if (n>m):
        print ("the lower number is not lower, please write another number")
        n = int(input ("please, give the lower number of the range "))
    else:
        break
for i in range (n,m+1):
    sum = sum + i
print (sum)
