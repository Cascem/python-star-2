# python-star-2
print star pattern python(2)
import sys
n = int(sys.stdin.readline())
for i in range(n):
    for j in range(n-(i+1)):
        print(" ",end="")
    for j in range(i+1):
        print("*",end="")
    print("")
