## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
It can be used to create a variety of different programs and isn't specialized for any specific problems and it is a high-level language which really just means that it's simpler and more intuitive for a human to use

Q2. Why is Python called a dynamically typed language?
	Because the type of the variable is determined only during runtime.

Q3. List some pros and cons of Python programming language?
	Pros:
		Python is a portable programming language
		Python is an interpreted language - No need to compile the program
	Cons:
		Python has speed limitations
		Python consumes a lot of memory space	

Q4. In what all domains can we use Python?
	Data Science 
	Web dev

Q5. What are variable and how can we declare them?
    	Variable is the address of memory location , inside the memory we can store data
Q6. How can we take an input from the user in Python?
    	Using input() function
Q7. What is the default datatype of the value that has been taken as an input using input() function?
		String 
Q8. What is type casting?
		Changing from one data type to another
Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
		Using split() function 
Q10. What are keywords?
	
Q11. Can we use keywords as a variable? Support your answer with reason.
     No , because keyword are predefined in python and compiler will get confuse 
Q12. What is indentation? What's the use of indentaion in Python?
		Indentation refers to the spaces at the beginning of a code line
	 	Python uses indentation to indicate a block of code.
Q13. How can we throw some output in Python?
	 Using print function
Q14. What are operators in Python?
		Operators are special symbols that designate that some sort of computation should be performed.
		
Q15. What is difference between / and // operators?
		/ - is used for float divison
		// - used for integer divison and outputs an integer value 
Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```

print(```
iNeuroniNeuroniNeuroniNeuron
```
)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
	a=int(input())
	if a%2==0:
		print("Even")
	else:
		print("Odd")
Q18. What are boolean operator?
	 	Boolean Operators are those that result in the Boolean values of True and False. These include and, or and not.
Q19. What will the output of the following?
```
1 or 0 :- 1

0 and 0 :- 0

True and False and True :- False

1 or 0 or 0 :- 0
```

Q20. What are conditional statements in Python?
		A conditional statement as the name suggests itself, is used to handle conditions in your program

Q21. What is use of 'if', 'elif' and 'else' keywords?
		if is used for conditional statement
		elif is used after if , when if fails then elif conditional statement will be checked
		else is used after if , when if fails then else will conditional statement will be checked

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
	age = int(input())
	if age>=18:
		print("I can vote")
	else:
		print("I can't vote")
Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
sum=0
for i in numbers:
	sum+=i

print(sum)

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.

a=int(input())
b=int(input())
c=int(input())

if a>b:
	if a>c:
		print(a)
	else 
		print(c)
else 
	if b>c:
		print(b)
	else
		print(c)


Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```

for i in numbers:
	if i>500:
		continue
	elif i>150:
		break 
	else if i%5==0:
		print(i)
	