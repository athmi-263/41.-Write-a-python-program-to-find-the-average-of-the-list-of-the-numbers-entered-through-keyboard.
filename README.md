# 41.-Write-a-python-program-to-find-the-average-of-the-list-of-the-numbers-entered-through-keyboard.
n=int(input("enter the limit "))
s=0
for i in range(1,n+1):
    print("enter ",i,end='')
    a=int(input("th number : "))
    s=s+a
avg=s/n
print("the sum of entered numbers : ",s)
print("the average of entered numbers : ",avg)

OUTPUT
enter the limit 3
enter  1th number : 26
enter  2th number : 24
enter  3th number : 25
the sum of entered numbers :  75
the average of entered numbers :  25.0

