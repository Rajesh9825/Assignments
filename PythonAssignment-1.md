## Assignment Part-1
Q1. Why do we call Python as a general purpose and high-level programming language?
Ans: Python is an object-oriented, high-level programming language. Object-oriented means this language is based around objects (such as data) rather than functions, and high-level means it's easy for humans to understand.

Q2. Why is Python called a dynamically typed language?
Ans: Python is both a strongly typed and a dynamically typed language. Strong typing means that variables do have a type and that the type matters when performing operations on a variable. Dynamic typing means that the type of the variable is determined only during runtime.

Q3. List some pros and cons of Python programming language?
Ans: Pros ->
	Python is easy to learn and read
	Python enhances productivity
	Python has a vast collection of libraries
	Python is free, open-source, and has a vibrant community
	Python is a portable programming language
	Python is an interpreted language
     Cons ->
	Python has speed limitations
	Python is not so strong with mobile computing
	Python can have runtime errors
	Python consumes a lot of memory space
	Python is not easy to test	

Q4. In what all domains can we use Python?
Ans: 	Data Science
        Automation
        Application Development 
        AI & Machine Learning 
        Audio/Video Applications

Q5. What are variable and how can we declare them?
Ans: A variable declaration always contains two components: the type of the variable and its name. Also, the location of the variable declaration, that is, where the declaration appears in relation to other code elements, determines the scope of the variable.

Q6. How can we take an input from the user in Python?
Ans: by using input() function. Ex: Name= input() or Name:input(enter your name:) 

Q7. What is the default datatype of the value that has been taken as an input using input() function?
Ans: String Datatype

Q8. What is type casting?
Ans: Type Casting, Converting one datatype into another is known as type casting
     int(), float(), str(), bool() this are the function we use for type casting.

Q9. Can we take more than one input from the user using single input() function? If yes, how? If no, why?
Ans: Yes,
	x, y = input("Enter First Name: "), input("Enter Last Name: ") 
	print("First Name is: ", x) 
	print("Second Name is: ", y)

Q10. What are keywords?
Ans: False, elif, if, and,  or, else, not, return, True, False, break
	
	
Q11. Can we use keywords as a variable? Support your answer with reason.
Ans: We cannot use a keyword as a variable name, function name, or any other identifier. They are used to define the syntax and structure of the Python language.

Q12. What is indentation? What's the use of indentaion in Python?
ANs: Indentation refers to the spaces at the beginning of a code line. Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important. Python uses indentation to indicate a block of code.

Q13. How can we throw some output in Python?
Ans: By using Print() function.

Q14. What are operators in Python?
Ans: 	+ for addition
        - for substractions
        * for multiplication
        / for float division
        // for integer division
        ** for power calculation
        % for Modulus

Q15. What is difference between / and // operators?
Ans: 	/ for float division -> after division its output will be in decimal points.
	    // for integer division

Q16. Write a code that gives following as an output.
```
iNeuroniNeuroniNeuroniNeuron
```
Ans: 	name= "iNeuron"
	    print(name*4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans: 	num= int(input("Enter Number:"))
        if (num % 2) == 0:
                print("Number is Even")
        else:
                print("Number is Odd")


Q18. What are boolean operator?
Ans: Boolean operators are also called as logical operator.
	 and, or, not This are the boolean operator.

Q19. What will the output of the following?
Ans: 
    1 or 0 -> True

    0 and 0 -> False

    True and False and True -> False

    1 or 0 or 0 -> True


Q20. What are conditional statements in Python?
Ans:  	== , Equals to condition 
        != , Not Equals to condition 
        > , Greater than condition 
        < , Less than condition 
        >= , Greater than and Equals to condition 
        <= , Less than and Equals to condition 

Q21. What is use of 'if', 'elif' and 'else' keywords?
Ans: if, elif, else this keywords we use in nested if-else condition.
	

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
Ans: 	age=int(input("Enter age of person:"))
        if age >= 18:
                print("I can Vote")
        else:
                print("I can't Vote")

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans: 	numbers = [12, 75, 150, 180, 145, 525, 50]
        Result=0
        for i in numbers:
                if (i % 2) == 0 :
                Result += i

        print(Result)
        
        



Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans: 	num1=int(input("Enter num1:"))
        num2=int(input("Enter num2:"))
        num3=int(input("Enter num3:"))

        if (num1 >= num2) and (num1 >= num3):
            Largest_number= num1
        elif (num2 >= num3) and (num2 >= num1):
            Largest_number= num2
        else: 
            Largest_number= num3

        print("Largest Number is: ",Largest_number)
    

Q25. Write a program to display only those numbers from a list that satisfy the following conditions

- The number must be divisible by five

- If the number is greater than 150, then skip it and move to the next number

- If the number is greater than 500, then stop the loop
```
numbers = [12, 75, 150, 180, 145, 525, 50]

Ans: 	numbers = [12, 75, 150, 180, 145, 525, 50]
        Result = []

        for i in numbers:
                if i > 150:
                    if i > 500:
                        break
                    continue
                if i % 5 == 0:
                Result.append(i)
            
        print(Result)


```