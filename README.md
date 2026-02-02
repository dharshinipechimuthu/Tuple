# Tuple
tpl=eval(input("Enter Tuple : "))
length=len(tpl)
mean=sum=0
for i in range(0, length) :
    sum+=tpl[i]
mean=sum/length
print("Given tuple is : ", tpl)
print("The Mean of given tuple is : ", mean)

OUTPUT:

Enter Tuple : (1,2,3,4,5)
Given tuple is :  (1, 2, 3, 4, 5)
The Mean of given tuple is :  3.0

