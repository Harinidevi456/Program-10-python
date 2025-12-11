n=int(input("Enter the Limit less than 99999999999 "))
small=99999999999
for i in range(1,n+1):
    print("Enetr ",i,end='')
    a=int(input("th number : "))
    if a<small:
        small=a
print("smallest no. is : ",small)

Output
Enter the Limit less than 99999999999  10
Enetr  1th number : 2
Enetr  2th number : 1
Enetr  3th number : 4
Enetr  4th number : 5
Enetr  5th number : 2
Enetr  6th number : 6
Enetr  7th number : 4
Enetr  8th number : 7
Enetr  9th number : 8
Enetr  10th number : 3
smallest no. is :  1

