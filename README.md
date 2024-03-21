# pattern_printing_with_py
This is my first Git Repository.
#pattern 1 
Output:-
#1
#2 2
#3 3 3
#4 4 4 4
#5 5 5 5 5
n=int(input("Enter a number : "))
for i in range(1,n+1):#i for no. of rows starts from 1 ends with n+1
    for j in range(1,i+1):#j for no. of columns starts from 1 ends with i+1
        print(i,end=" ")#end to print in a single line
    print("")#to print in next line
input("Enter any key to exit : ")#helps to see output window
    
