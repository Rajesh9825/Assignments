## Assignment Part-2
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
Ans: Indentation refers to the spaces at the beginning of a code line. Where in other programming languages the indentation in code is for readability only, the indentation in Python is very important. Python uses indentation to indicate a block of code.

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

	name= "iNeuron"
	print(name*4)

Q17. Write a code to take a number as an input from the user and check if the number is odd or even.
Ans: 	        num= int(input("Enter Number:"))
        if (num % 2) == 0:
                print("Number is Even")
        else:
                print("Number is Odd")


Q18. What are boolean operator?
Ans: Boolean operators are also called as logical operator.
	 and, or, not This are the boolean operator.

Q19. What will the output of the following?
 
    1 or 0 -> True

    0 and 0 -> False

    True and False and True -> False

    1 or 0 or 0 -> True

Q20. What are conditional statements in Python?
 
	== , Equals to condition 
	!= , Not Equals to condition 
	> , Greater than condition 
	< , Less than condition 
	>= , Greater than and Equals to condition 
	<= , Less than and Equals to condition 

Q21. What is use of 'if', 'elif' and 'else' keywords?
	
	if, elif, else this keywords we use in nested if-else condition.
	

Q22. Write a code to take the age of person as an input and if age >= 18 display "I can vote". If age is < 18 display "I can't vote".
	
	age=int(input("Enter age of person:"))
	if age >= 18:
		print("I can Vote")
	else:
		print("I can't Vote")		

Q23. Write a code that displays the sum of all the even numbers from the given list.
```
numbers = [12, 75, 150, 180, 145, 525, 50]
```
Ans: 	
	
	numbers = [12, 75, 150, 180, 145, 525, 50]
        Result=0
        for i in numbers:
                if (i % 2) == 0 :
                Result += i

        print(Result)
        

Q24. Write a code to take 3 numbers as an input from the user and display the greatest no as output.
Ans:

	num1=int(input("Enter num1:"))
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

Q26. What is a string? How can we declare string in Python?

	strings in Python are arrays of bytes representing unicode characters.
      	However, Python does not have a character data type, a single character is simply a string with a length of 1.
      	A = “Hello World!”
      	Print(A)


Q27. How can we access the string using its index?
	
	A = “Hello World!”
      	Print(A[1])

Q28. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "iNeuron"
Ans: 

	string = "Big Data iNeuron"
	print(string[-7:])
	
Q29. Write a code to get the desired output of the following

string = "Big Data iNeuron"
desired_output = "norueNi"
Ans:

	string = "Big Data iNeuron"
	print(string[-1:-8:-1])

Q30. Resverse the string given in the above question.
Ans;

	string = "Big Data iNeuron"
	print(string[-1: : -1])

Q31. How can you delete entire string at once?
Ans:  

	del string
	print(string) 


Q32. What is escape sequence?
Ans:

	Character combinations consisting of a backslash (\) followed by a letter or by a combination of digits are called "escape sequences." To represent a newline character, single quotation mark, or certain other characters in a character constant, you must use escape sequences. An escape sequence is regarded as a single character and is therefore valid as a character constant.
	Escape sequences are typically used to specify actions such as carriage returns and tab movements on terminals and printers. They are also used to provide literal representations of nonprinting characters and characters that usually have special meanings, such as the double quotation mark ("). The following table lists the ANSI escape sequences and what they represent.

Q33. How can you print the below string?
'iNeuron's Big Data Course'
Ans:

	print("'iNeuron's Big Data Course'")
	
Q34. What is a list in Python?
Ans: 

	Lists are used to store multiple items in a single variable.
	Lists are one of 4 built-in data types in Python used to store collections of data, the other 3 are Tuple, Set, and Dictionary, all with different qualities and usage.

Q35. How can you create a list in Python?
Ans:

	list1 = ["hello","hi","Bye","nice"]
	print(list1)

Q36. How can we access the elements in a list?
Ans:

	list1 = ["hello","hi","Bye","nice"]
	print(list1[1])

Q37. Write a code to access the word "iNeuron" from the given list.

lst = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]

Ans:

	list1 = [1,2,3,"Hi",[45,54, "iNeuron"], "Big Data"]
	print(list1[4][2])


Q38. Take a list as an input from the user and find the length of the list.
Ans: 

	list1=[]
	n = int(input("enter number of element"))
	for i in range(0,n):
	    list1.append(int(input()))

	print(list1)
	print(len(list1))
	

Q39. Add the word "Big" in the 3rd index of the given list.

lst = ["Welcome", "to", "Data", "course"]

Ans: 

	list1 = ["Welcome", "to", "Data", "course"]
	list1[3] = "Big"
	print(list1)


Q40. What is a tuple? How is it different from list?
Ans:
	

Q41. How can you create a tuple in Python?
Ans: 
	
	tup = () or tup = (hi, hello, bye, nice) or tuo = (1, 2, 3, 4)
	

Q42. Create a tuple and try to add your name in the tuple. Are you able to do it? Support your answer with reason.

Q43. Can two tuple be appended. If yes, write a code for it. If not, why?

Q44. Take a tuple as an input and print the count of elements in it.

Q45. What are sets in Python?

Q46. How can you create a set?

Q47. Create a set and add "iNeuron" in your set.

Q48. Try to add multiple values using add() function.

Q49. How is update() different from add()?

Q50. What is clear() in sets?

Q51. What is frozen set?

Q52. How is frozen set different from set?

Q53. What is union() in sets? Explain via code.

Q54. What is intersection() in sets? Explain via code.

Q55. What is dictionary ibn Python?

Q56. How is dictionary different from all other data structures.

Q57. How can we delare a dictionary in Python?

Q58. What will the output of the following?

var = {}
print(type(var))
Q59. How can we add an element in a dictionary?

Q60. Create a dictionary and access all the values in that dictionary.

Q61. Create a nested dictionary and access all the element in the inner dictionary.

Q62. What is the use of get() function?

Q63. What is the use of items() function?

Q64. What is the use of pop() function?

Q65. What is the use of popitems() function?

Q66. What is the use of keys() function?

Q67. What is the use of values() function?

Q68. What are loops in Python?

Q69. How many type of loop are there in Python?

Q70. What is the difference between for and while loops?

Q71. What is the use of continue statement?

Q72. What is the use of break statement?

Q73. What is the use of pass statement?

Q74. What is the use of range() function?

Q75. How can you loop over a dictionary?

Coding problems
Q76. Write a Python program to find the factorial of a given number.

Q77. Write a Python program to calculate the simple interest. Formula to calculate simple interest is SI = (PRT)/100

Q78. Write a Python program to calculate the compound interest. Formula of compound interest is A = P(1+ R/100)^t.

Q79. Write a Python program to check if a number is prime or not.

Q80. Write a Python program to check Armstrong Number.

Q81. Write a Python program to find the n-th Fibonacci Number.

Q82. Write a Python program to interchange the first and last element in a list.

Q83. Write a Python program to swap two elements in a list.

Q84. Write a Python program to find N largest element from a list.

Q85. Write a Python program to find cumulative sum of a list.

Q86. Write a Python program to check if a string is palindrome or not.

Q87. Write a Python program to remove i'th element from a string.

Q88. Write a Python program to check if a substring is present in a given string.

Q89. Write a Python program to find words which are greater than given length k.

Q90. Write a Python program to extract unquire dictionary values.

Q91. Write a Python program to merge two dictionary.

Q92. Write a Python program to convert a list of tuples into dictionary.

Input : [('Sachin', 10), ('MSD', 7), ('Kohli', 18), ('Rohit', 45)]
Output : {'Sachin': 10, 'MSD': 7, 'Kohli': 18, 'Rohit': 45}
Q93. Write a Python program to create a list of tuples from given list having number and its cube in each tuple.

Input: list = [9, 5, 6]
Output: [(9, 729), (5, 125), (6, 216)]

Ans:

	list1 = [9, 5, 6]
	res = [(val, pow(val, 3)) for val in list1]
	print(res)
Q94. Write a Python program to get all combinations of 2 tuples.

Input : test_tuple1 = (7, 2), test_tuple2 = (7, 8)
Output : [(7, 7), (7, 8), (2, 7), (2, 8), (7, 7), (7, 2), (8, 7), (8, 2)]
Q95. Write a Python program to sort a list of tuples by second item.

Input : [('for', 24), ('Geeks', 8), ('Geeks', 30)] 
Output : [('Geeks', 8), ('for', 24), ('Geeks', 30)]
Q96. Write a python program to print below pattern.

* 
* * 
* * * 
* * * * 
* * * * * 
Q97. Write a python program to print below pattern.

    *
   **
  ***
 ****
*****
Q98. Write a python program to print below pattern.

    * 
   * * 
  * * * 
 * * * * 
* * * * * 
Q99. Write a python program to print below pattern.

1 
1 2 
1 2 3 
1 2 3 4 
1 2 3 4 5
Q100. Write a python program to print below pattern.

A 
B B 
C C C 
D D D D 
E E E E E 
