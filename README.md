# max-min-of-list-without-library-functions
l=[]
n=int(input('Enter how many numbers you want:'))
l=list(map(int,input('Enter any number:').split()))
max=l[0]
min=l[0]
for i in range(0,n):
    if max<l[i]:
        max=l[i]
    if min>l[i]:
        min=l[i]
print(min)
print(max)
