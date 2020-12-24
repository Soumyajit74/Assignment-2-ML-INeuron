# Assignment-2-ML-INeuron

#Assignment 2
#1.Nested for loop

for i in range(1,6):
    for j in range(1,i+1):
        print('*', end="")
    print('\n')

for i in range(4,0, -1):
    for j in range(i+1,1, -1):
        print('*', end="")
    print('\n')

#2. Inverting words
s= input("Input word: ")
s[::-1]
