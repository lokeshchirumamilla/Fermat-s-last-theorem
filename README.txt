										
Description



A program in python code which solve the formula x^n + y^n = z^n
in that formula x, y, and z is the positive integers, and program code is used for checking the condition
of n values which will lies between 2 to 12 i.e. 2<n<12. x, y, and z may be equal or not, and checking the possible condition according to the given input 
i.e. it is equal 
or not and which condition they make at that time.



This is a python program to find the "near misses" for the equation x^n + y^n = z^n.this python program is
based on the fermat theorem which definethat x^n + y^n = z^n will not be equal to greater the value of n to 2 and x, y, z != 0. The program 
asks the user for n (the power to use in the equation) and k for value from where to they need output,
n. For each possible x,y combination, the program calculates (x^n + y^n), and then looks for whole numbers 
z and z + 1 that "bracket" (x^n + y^n), so that z^n < (x^n + y^n) < (z+1)^n. The program then finds out 
which one (either z^n or (z+1)^n) is closer to (x^n + y^n), and determines the "miss" as the smallest of
these two values: [(x^n + y^n) - z^n] or [(z+1)^n - (x^n + y^n)]. The program then divides that miss by 
(x^n + y^n) to obtain the RELATIVE size of the miss. The program keeps track of the smallest relative miss, 
and prints out the x, y, z, actual miss, and relative miss for each new smallest relative miss. The program 
ends when all possible x, y, z triples have been exhausted,and prints the smallest possible miss as the last 
thing on the screen.