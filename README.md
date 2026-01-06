n=int(input("enter the limit:"))
s=0
for i in range(1,n+1):
print("enter ",i,end='')
a=int(input("th number:"))
s=s+a
avg=s/n

print("the sum of entered number :",s)
print("the average of entered numbers:",avg)
Output:
enter the limit:3
enter 1th number:9
enter 2th number:5
enter 3th number:8
the sum of entered number : 22
the average of entered numbers: 7.333333333333333
