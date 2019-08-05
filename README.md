# even-numbers-and-their-sum-with-average
python program to find number of even numbers in a given range and find the sum as well as average for that even numbers 
n=int(input('Enter Range:'))
s=0
c=0
for i in range(n+1):
  if(i%2==0):
    print(i)
    s=s+i
    c=c+1
print('Sum of above numbers is',s)
avg=s/c
print('Average of the above numbers is',int(avg))
