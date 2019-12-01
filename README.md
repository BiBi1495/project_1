# project_1
find the prime number
# for loop with range - prime numble

for num in range(2,15,1):

 for i in range(2,num,1):
 
   if num % i == 0:
	k = int(num/i)
	print(num,' = ', i, ' * ', k)
	break
 else: # this else is a part of second for. it work when the second for loop is finished
   print(num, ' is a prime numble')
