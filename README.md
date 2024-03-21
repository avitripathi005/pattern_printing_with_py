# pattern_printing_with_py
This is my first Git Repository. <br>
#pattern 1 <br>
Output:- <br>
#1 <br>
#2 2 <br>
#3 3 3 <br>
#4 4 4 4 <br>
#5 5 5 5 5 <br>
n=int(input("Enter a number : "))
for i in range(1,n+1):#i for no. of rows starts from 1 ends with n+1
    for j in range(1,i+1):#j for no. of columns starts from 1 ends with i+1
        print(i,end=" ")#end to print in a single line
    print("")#to print in next line
input("Enter any key to exit : ")#helps to see output window
    
