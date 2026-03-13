# DSA.REPO
Time complexiy: time taken to run a code with respect to input size

Big O Notation tells that how fast or slow algorithm grow when input becomes larger
 1 always calculate time complexity in terms of worst case
 2 avoid the constant value 
 3 avoid lower value
 for i in range(1,6):  #here 3 opertion performing (compare i>=6, print,increment i++)
    print("hello")

 op: hello
     hello
     hello   X multiplied by 3 operation 5X3=15 total 15 operation performed
     hello
     hello
3N N=input here 3 operation and N=5 3X5=15

1) always calculate time complexity in terms of worst case
   ex: age=int(input("enter age: "))
if age>=80:
    print(" super senior")
elif age<80 and age>=60:
    print("senior")
elif age<60 and age>=24:
    print(" Working professionals")
elif age<24 and age>=10:
    print(" student")
else:
    print("children")
   here we need calculate worst case and that is age=>10 , the worst case you calculate the more operion will be done,but it does not change time complexity
      
2) avoid time coplexity/3) avoid lower values

TC=5N+20 
here 5 is constant multiplier 
     20 is constant value 

we should ignore both 5 and 20 in this case 

big O --> worst case (upper bound)
theta-->avarage case
omega--> best case (lower bound)

ex: 
for i in range(1,n+1): # run for n time 
    for j in range(1,n+1): # run for n time 
    here TC(time complexity)= nxn=n^2
    0=n^2
        
space complexity
Space Complexity is the amount of memory (RAM) an algorithm uses while running.
1)auxillary space-->the extra space used to solve problems 
2) input space --> the space used to store input


