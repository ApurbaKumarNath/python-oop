**![][image1]**

**Course Title: Programming Language I**  
**Course Code: CSE 110**  
**Assignment no: 3 (Loops)**

**Task 1**

Write the python programs, which prints the following sequences of values in loops:

a) 24, 18, 12, 6, 0, \-6  
b) \-10, \-5, 0, 5, 10, 15, 20  
c) 18, 27, 36, 45, 54, 63  
d) 18, \-27, 36, \-45, 54, \-63      

\===============================================================

**Hint (1):** You may use a while loop for solving these problems.

**Hint (2):** We are already familiar with the print() function. But, when we use it to print any value, it automatically adds an additional newline after each print statement.

For example:  
print(1)  
print(2)

Output:  
1  
2

\===============================================================

To solve this problem, in Python3, we can add an extra argument (end \= " ") in the print function which tells the program to skip printing the additional newline.

For example:  
print(1, end \="")  
print(2)

Output: (prints the next output right to the previous one)  
12

\===============================================================

In Task-1(a), the loop counter may be initialized at 24 and then the loop should terminate when the loop counter reaches \-6. The difference between the first two values is 24 \- 18 \= 6\. So, the loop counter value is getting decremented by 6 in every iteration for the given sequence here.

For your understanding, the code for Task 1(a) is done for you.

|  \# a) 24, 18, 12, 6, 0, -6 \# initializing loop counter counter = 24 \# loop structure while counter \>= \-6:          \#inside loop body     if counter == \-6:         print(counter, end = "")      else:         print(counter, end = ", ")            counter = counter - 6 \#updating loop counter     \#inside loop body      \#outside loop body  |
| :---- |

**Hints for 1(d):**

print(5 \* (-1)) gives output \-5  
print("-" \+ str(5)) gives output \-5

**Task 2**

Write a Python code for the following:

1\) Ask the user to enter the name of his favorite car.  
2\) Ask the user to enter a Number

Display the name of the user’s favorite car, the number of times specified in the second step.

\===============================================================**Example 1:** If the user enters “Toyota” and 2, your program should print the name “Toyota” two times.

**Sample Input 1:**  
Toyota  
2

**Sample Output 1:**  
Toyota  
Toyota

\===============================================================**Example 2:** If the user enters “Veyron” and 5, your program should print the name “Veyron” five times.

**Sample Input 2:**  
Veyron  
5

**Sample Output 2:**  
Veyron  
Veyron  
Veyron  
Veyron  
Veyron

**Task 3**

Write the Python code of a program that adds all numbers that are multiples of **both 7 and 9** up to 600 (including 600\) i.e. 63, 126, 189, 252, ....

**The output of your program should be:** 2835  
since 63 \+ 126 \+ 189 \+ 252 \+ 315 \+ 378 \+ 441 \+ 504 \+ 567 \= 2835

**Task 4**

Write a Python code of a program that adds all numbers that are multiples of **either 7 or 9 but not both**, up to 600 (including 600\) i.e. 7, 9, 14, 18, 21..... and so on but not the numbers 63, 126, 189..... which are multiples of both 7 and 9\.

**The output of your program should be:** 39814

**Task 5**

Write the Python code of a program that displays all the **odd numbers** between 10 and 50 (inclusive).

**Output:** 11 13 15 17 19 21 23 25 27 29 31 33 35 37 39 41 43 45 47 49

**Task 6**

Write a Python code that will calculate the **value of y if the expression** of y is as follows (n is the input):

y=12−22\+32−42\+52.........+n2

\===============================================================

**Sample Input 1:**  
5

**Sample Output 1:**  
15

**Explanation:** y \= 1 \- 4 \+ 9 \- 16 \+ 25 \= 15

\===============================================================**Sample Input 2:**  
10

**Sample Output 2:**  
\-55

**Explanation:** y \= 1 \- 4 \+ 9 \- 16 \+ 25 \- 36 \+ 49 \- 64 \+ 81 \- 100 \= \-55

\===============================================================**Sample Input 3:**  
20

**Sample Output 3:**  
\-210

**Task 7**

Write a Python code of a program that asks the user to enter ten numbers and then display the total and the average of **ONLY** the **odd numbers** among those ten numbers.  
\[Please do not use list for this task\]

\===============================================================**Sample Input 1:**  
1

2

3

4

5

6

7

8

9

10

**Sample Output 1:** The total of the odd numbers is 25 and their average is 5.0

**Explanation:** The total is 1 \+ 3 \+ 5 \+ 7 \+ 9 \= 25 and the average is 25/5 \= 5.0

\===============================================================**Sample Input 2:**  
\-20

13

\-5

40

\-17

10

20

\-8

99

\-200

**Sample Output 2:**

The total of the odd numbers is 90 and their average is 22.5

**Explanation:** The total is 90 \= 13 \+ (-5) \+ (-17) \+ 99\) and their average is 90/4 \= 22.5

**Task 8**

Write a Python code for the following:

* Ask the user to enter a Number, N  
* Display the summation of multiples of 7 up to that number (**from 1 to N inclusive**)

\===============================================================**Sample Input 1:**  
50

**Sample Output 1:**  
196

**Explanation:** The summation of multiples of 7 up to 50 is 7 \+ 14 \+ 21 \+ 28 \+ 35 \+ 42 \+ 49 \= 196

\===============================================================**Sample Input 2:**  
75

**Sample Output 2:**  
385

**Explanation:** The summation of multiples of 7 up to 75 is 7 \+ 14 \+ 21 \+ 28 \+ 35 \+ 42 \+ 49 \+ 56 \+ 63 \+ 70 \= 385

**Task 9**

Write a Python code that will read 5 numbers from the user. Your program should print the first number, the sum of the first 2 numbers, the sum of the first 3 numbers, and so on up to the sum of 5 numbers.

\===============================================================**Sample Input 1:**  
1  
2  
3  
4  
5

**Sample Output 1:**  
1  
3  
6  
10  
15

**Explanation:**  
When the user enters 1 at first, we print 1, then  
The user enters 2, (1 \+ 2\) \= 3, so our output is 3, then  
The user enters 3, (3 \+ 3\) \= 6, hence our output is 6, then  
The user enters 4, and we have (6 \+ 4\) \= 10, we print 10, and finally  
The user enters 5, the final sum is 15 which is printed as the last output.

\===============================================================

**Sample Input 2:**  
11  
\-29  
\-3  
47  
50

**Sample Output 2:**  
11  
\-18  
\-21  
26  
76

**Explanation:**  
When the user enters 11 at first, we print 11, then  
The user enters \-29, (11 \+ (-29)) \= \-18, so our output is \-18, then  
The user enters \-3, (-18 \- 3\) \= \-21, hence our output is \-21, then  
The user enters 4, and we have (-21 \+ 47\) \= 26, we print 26, and finally  
The user enters 50, the final sum is (26 \+ 50\) \= 76 which is printed as the last output.

**Task 10**

Write a Python program which takes a number and prints the digits from the unit place, then the tenth, then hundredth, etc. (Right to Left)

\[Consider the input number to be an INTEGER. You are not allowed to use String indexing for solving this task\]

**Example:** If the user gives 32768, then print 8, 6, 7, 2, 3

\===============================================================

**Hint (1):** The input() function, converts the input data to String data type by default. Therefore, please type cast it to an integer before proceeding further.

**Hint (2):** First to get the digit from the right side, we can take the remainder of the number using modulus (%) operator i.e. mod 10 to get the rightmost digit and print it. For dropping the last digit, we can perform floor division by 10 on the number and then continue the same to print the other digits as shown below.

32768 % 10 \= 8

32768 // 10 \= 3276

Then,

3276 % 10 \= 6

3276 // 10 \= 327

and so on

327 % 10 \= 7

327 // 10 \= 32

32 % 10 \= 2

32 // 10 \= 3

3 % 10 \= 3

3 // 10 \= 0

Done\! When the number becomes 0 you can end your loop.

**Task 11**

Write a Python program that takes a number and prints how many digits are in that number.  
\[Consider the input number to be an INTEGER.\]

\[You are not allowed to use len() function\]

**Example:** If the user gives 9876, your program should print 4\.

**Hint:** We may keep floor dividing by ten and count how many times this can be done until the number becomes 0 as illustrated below.

9876 // 10 \= 987, count \= 1  
then, 987 // 10 \= 98, count \= 2  
98 // 10 \= 9, count \= 3  
9 // 10 \= 0, count \= 4

Done\! When the number becomes 0 your loop can end giving you the count of digits, in this case for our input of 9876, 4 digits.

**Task 12**

Write a Python program that takes a number from the user and prints its digits from left to right.

\[Consider the input number to be an INTEGER. You are not allowed to use String indexing for solving this task\]

**Example:** if the user gives 32768, then print 3, 2, 7, 6, 8

\===============================================================

**Hint(1):** The input() function takes the input data as String data type by default. Please convert it to an integer before starting your code for the task.

**Hint(2):**

Step 1: First, count how many  
Step 2: Then, calculate 10 to the power (number of digits \- 1).

Step 3 with explanation: Say, the input given by the user as in our example, 32768 has 5 digits, so calculating 10 to the power 4 gives us 10000\. Then floor dividing 32768 by 10000, we can get 3\. 

Proceeding further, the remainder of 32768 by 10000 (32768 % 10000\) gives us 2768\. This time to get 2 we need to floor divide 2768 by 1000 which is basically our 10000/10. Again, taking remainder of 2768 by 1000 gives us 768 which we then divide by 100 (i.e. 1000/10) and keep on doing this until there are no more digits left (zero).

**To summarize and clarify:**  
Loop 1: First, we count digits like our Task 12, say 5 in this case for 32768  
Loop 2: Then, we calculate 10 to the power 4 (5-1), that is 10000\.  
Loop 3: Then we keep repeating the three steps of floor dividing, modulus and dividing by 10 as demonstrated below.

32768 // 10000 \= 3  
32768 % 10000 \= 2768  
10000 // 10 \= 1000

2768 // 1000 \= 2  
2768 % 1000 \= 768  
1000 // 10 \= 100

768 // 100 \= 7  
768 % 100 \= 68  
100 // 10 \= 10

68 // 10 \= 6  
68 % 10 \= 8  
10 // 10 \= 1

8 // 1 \= 8  
8 % 1 \= 0  
1 // 10 \= 0

Done. Loop ends as number has become 0\.

**Task 13**

Write a Python program that takes a number as input from the user and prints the divisors of that number as well as how many divisors the number has.

\===============================================================**Sample Input 1:**  
6

**Sample Output 1:**  
1

2

3

6  
Total 4 divisors.

\===============================================================**Sample Input 2:**  
121

**Sample Output 2:**  
1

11

121  
Total 3 divisors.

**Task 14**

Write a Python program that takes a number as input from the user and tells if it is a perfect number or not.

**Perfect Number:** An integer number is said to be a perfect number if its factors, including 1 but not the number itself, sum to the number.

\===============================================================**Sample Input 1:**  
6

**Sample Output 2:**  
6 is a perfect number

**Explanation:**  
6 has 4 divisors: 1, 2, 3, and 6\.  
If we add all factors except 6 itself, 1 \+ 2 \+ 3 \= 6\. The sum of the factors excluding the number itself sum up to the number therefore "6 is a perfect number" is printed.

\===============================================================**Sample Input 2:**  
28

**Sample Output 2:**  
28 is a perfect number

**Explanation:**  
28 has the divisors: 1, 2, 4, 7, 14, and 28\.  
If we add all factors except itself, we get 28, 1 \+ 2 \+ 4 \+ 7 \+ 14 \= 28\.

\===============================================================**Sample Input 3:**  
33

**Sample Output 3:**  
33 is not a perfect number

**Explanation:**  
33 has 4 divisors: 1, 3, 11, and 33\.  
If we add all factors except itself, 15 \= 1 \+ 3 \+ 11\. The sum is not equal to the number, therefore 33 is not a perfect number.

**Task 15**

Write a Python program that asks the user for one number and tells if it is a prime number or not.

**Prime Number:** If a number has only two divisors, (1 and itself), then it is a prime number. If it is divisible by more numbers, then it is not a prime.

**Hint:** You may use the code for counting divisors from Task 14\.

\===============================================================**Sample Input 1:**  
11

**Sample Output 1:**  
11 is a prime number

**Explanation:** 11 has only 2 divisors: 1 and 11\.

\===============================================================**Sample Input 2:**  
6

**Sample Output 2:**  
6 is not a prime number

**Explanation:** 6 has 4 divisors: 1, 2, 3 and 6\.

**Task 16**

Write a Python program that asks the user for a quantity, then takes that many numbers as input and prints the maximum, minimum and average of those numbers.

\[Please note that you CANNOT use max, min built-in functions\]

\[Also, you DO NOT need to use lists for this task\]

\===============================================================**Example:** If the user enters 5 as an input for quantity and the enters the 5 numbers, 10, 4, \-1, \-100, and 1\.  
The output of your program should be: “Maximum 10”, “Minimum \-100”, “Average is \-17.2” as shown below.

**Input:**  
5 

10 

4 

\-1 

\-100 

1

**Output:**  
Maximum 10  
Minimum \-100  
Average is \-17.2

**Explanation:** Average calculation: (10 \+ 4 \+ (-1) \+ (-100) \+ 1)/5 \= \-86/5 \= \-17.2

**Task 17**

Write a python program that prints a square of size N using \+ where N will be given as input as illustrated in the examples below.

**Hint:** You may need to use nested loops to solve this problem.

\===============================================================**Sample Input 1:**

5

**Sample Output 1:**  
\+++++  
\+++++  
\+++++  
\+++++  
\+++++

**Explanation:** Here, we may see it as 5 rows and 5 columns, where in each horizontal row/line, 5 '+' is printed next to each other and we have a total of 5 lines.

\===============================================================

**Sample Input 2:**

3

**Sample Output 2:**  
\+++  
\+++  
\+++

**Explanation:** If the input is 3, then there will be 3 rows and 3 columns, where in each horizontal row/line, '+' is printed 3 times, 1 in each of the 3 columns and we will have a total of 3 lines.

**Task 18**

Write a python program that prints a rectangle of size M (height/line numbers) and N (length/column numbers) using incrementing numbers where M and N will be given as input. Please look at the examples below for clarification.

**Hint:** You may need to use nested loops and print the loop counter variable in one of the loops.

\===============================================================**Sample Input 1:**  
4  
6

**Sample Output 1:**  
123456  
123456  
123456  
123456

**Explanation:** The user has given 4 rows/lines and 6 columns as input. Therefore, we have 4 lines in our output here and in each line, the column number is printed from 1 through to 6 for the 6 columns.

\===============================================================**Sample Input 2:**  
3  
2

**Sample Output 2:**  
12  
12  
12

**Explanation:** Our user input this time is 3 rows/lines and 2 columns. So, our output has 3 lines and, in each line, the column number 1 and 2 are printed next to each other as the user only wants 2 columns here.

**Task 19**

Write a python program that prints a right-angled triangle of height N using incrementing numbers where N will be given as input.

**Hint:** You may need to use nested loops. Try to think up to which point should the inner loop run.

\===============================================================**Sample Input 1:**  
4

**Sample Output 1:**  
1  
12  
123  
1234

**Explanation:** For an input of 4, we have 4 rows/lines where in each line, the respective column number is printed sequentially up to the line/row number. So, in line number 1, we have 1 only. In line 2, 12 is printed. In line 3, we have 123 and so on.

\===============================================================**Sample Input 2:**  
5

**Sample Output 2:**  
1  
12  
123  
1234  
12345

**Explanation:** Numbers are printed sequentially up to the line number for each of the lines.

**Task 20**

| 1 | x \= 0 |
| :---: | :---- |
| **2** | **p \=0** |
| **3** | **sum \= 0** |
| **4** | **p \= 1** |
| **5** | **x \= 2** |
| **6** | **q \= None** |
| **7** | **sum \= 0** |
| **8** | **while p \< 12:** |
| **9** | **    q \= x \+ p \- (sum \+ 7 / 3) / 3.0 % 2** |
| **10** | **    sum \= sum \+ x \+ int(q)** |
| **11** | **    x \+= 1** |
| **12** | **    print(sum)** |
| **13** | **    if x \> 5:** |
| **14** | **        p \+= 4 / 2** |
| **15** | **    else:** |
| **16** | **        p \+= (3 % 1)** |
| **17** | **sum \= int(sum \+ p)** |
| **18** | **print(sum)** |

| Output |
| ----- |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |

**Task 21**

| 1 | x \= 0 |
| :---: | :---- |
| **2** | **p \= 0** |
| **3** | **sum \= 0** |
| **4** | **p \= 1** |
| **5** | **x \= 2** |
| **6** | **q \= 0.0** |
| **7** | **sum \= 0** |
| **8** | **while (p \< 10) :** |
| **9** | **  q \= x \+ p \- (sum \+ int(5 / 3)) / 3.0 % 2** |
| **10** | **  sum \= sum \+ x \+ int(q)** |
| **11** | **  x \+= 1** |
| **12** | **  print(sum)** |
| **13** | **  if (x \> 5) :** |
| **14** | **    p \+= int(4 / 2)** |
| **15** | **  else :** |
| **16** | **    p \+= 3 % 1** |
| **17** | **sum \= sum \+ p** |
| **18** | **print(sum)** |

| Output |
| ----- |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |

**Task 22**

| 1 | x \= y \= 0  |
| :---: | :---- |
| **2** | **sum \= 0** |
| **3** | **while (x \< 10):** |
| **4** | **  y \= x \- 3** |
| **5** | **  while (y \< 3):** |
| **6** | **    sum \= x \- y \* 2 ** |
| **7** | **    print(sum)** |
| **8** | **    y \= y \+ 1** |
| **9** | **  if (x \> 7): ** |
| **10** | **    x \+= 1** |
| **11** | **  else: ** |
| **12** | **    x \+= 3** |
| **13** | **sum \= x \- y \* 2** |
| **14** | **print(sum)** |

| Output |
| ----- |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |

**Task 23**

| 1 | x = 0 |
| :---: | :---- |
| **2** | **y = 0** |
| **3** | **sum = 0** |
| **4** | **p = 0.0** |
| **5** | **while (x \< 10):** |
| **6** | **    y = x // 2** |
| **7** | **    while (y \< x):** |
| **8** | **        p = (x + 10.0) / 2** |
| **9** | **        sum = (sum % 2) + x - y \* 2 + int(p)** |
| **10** | **        print(sum)** |
| **11** | **        y = y + 2** |
| **12** | **    if (x \> 5):** |
| **13** | **        x += 1** |
| **14** | **    else:** |
| **15** | **        x += 2** |

| Output |
| ----- |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |

**Task 24**

| 1 | test \= 1 |
| :---: | :---- |
| **2** | **j \= 0** |
| **3** | **k \= 100** |
| **4** | **while (k \> 0):** |
| **5** | **  while ( j \< k ):** |
| **6** | **    test \= k \+ j \-21** |
| **7** | **    print(str(1 \+ int (test / 2)))** |
| **8** | **    j \+= 10** |
| **9** | **  k \-= 10** |
| **10** | **test \= 1** |
| **11** | **j \= 0** |
| **12** | **k \= 100** |

| Output |
| ----- |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |
|  |

**Optional Tasks (25 \- 29\) \[Ungraded\]**

---

**These tasks are just for practice. No marks will be deducted for not completing them and no extra marks will be given for solving them. Just try and practice these advanced problems.**

---

**Task 25**

Write a python program that prints all the Fibonacci numbers from 0 to N where N will be given as input by the user.

**A Fibonacci number is a number which is the summation of its previous two Fibonacci numbers.**

The first two Fibonacci numbers are 0 and 1\.

So, the 3rd is 0 \+ 1 \= 1,

the 4th is 1 \+ 1 \= 2,

the 5th is 1 \+ 2 \= 3,

the 6th one is 2 \+ 3 \= 5,

and so on.

i.e. 0, 1, 1, 2, 3, 5, 8, 13, 21.......

\===============================================================**Sample Input 1:**  
10

**Sample Output 1:**  
0 1 1 2 3 5 8

**Explanation**: All Fibonacci numbers up to the number 10 is printed separated by spaces.

\===============================================================**Sample Input 2:**  
15

**Sample Output 2:**  
0 1 1 2 3 5 8 13

**Explanation**: All Fibonacci numbers up to the number 15 is printed separated by spaces.

**Task 26**

Write a python program that converts a decimal integer number to a binary number.

***Hint**: A decimal can be converted to a binary number by keeping track of the remainders after each division of that number by 2\.*

\===============================================================**Example 1:**

For example, to convert 11 to a binary number, we can try the following approach.

11 // 2 \= 5 (Remainder 1\)  
5 // 2 \= 2 (Remainder 1\)  
2 // 2 \= 1 (Remainder 0\)  
1 // 2 \= 0 (Remainder 1\)

Now, taking the remainders from bottom to top gives us the binary number which is 1011\. Binary of 11 is 1011\.

**Sample Input 1:**  
11

**Sample Output 1:**  
1011

\===============================================================**Example 2:**

Similarly, to convert 13 to a binary number:

13 // 2 \= 6 (Remainder 1\)  
6 // 2 \= 3 (Remainder 0\)  
3 // 2 \= 1 (Remainder 1\)  
1 // 2 \= 0 (Remainder 1\)

Again, taking the remainders from the bottom to top, which is 1101 gives us the binary number. Binary of 13 is 1101\.

**Sample Input 2:**  
13

**Sample Output 2:**  
1101

**Task 27**

Write a python program that converts a binary number to a decimal integer number after taking the binary number as an input from the user.

**Note: A binary number can be converted to its corresponding decimal number by multiplying each binary digit with a power of 2, where the power denotes the position of the binary digit**

\===============================================================

**Example 1:**

For example, to convert 1010 to decimal, we can do this

23 × 1 \+ 22 × 0 \+ 21 ×1 \+ 20 × 0 \= 10

**Sample Input 1:**  
1010

**Sample Output 1:**  
10

\===============================================================

**Example 2:**

So, to convert 11101, we can do this

24 x 1 \+ 23 x 1 \+ 22 x 1 \+ 21 x 0 \+ 20 x 1 \= 29

**Sample Input 2:**  
11101

**Sample Output 2:**  
29

**Task 28**

Write a Python program that asks the user for a range (a starting number and an ending number) and then **counts** how many numbers are prime numbers and how many numbers are perfect numbers between that range. It also **prints** those numbers in the format shown in the output of the example given below.

\===============================================================

**Hint (1):** We may declare two strings/lists to store the prime and perfect numbers. Inside the loop, we check for prime and perfect numbers and add them to respective string/list besides counting them.

**Hint (2):** We may need to convert numbers in String to integers for checking and calculations. We may again need to convert numbers to Strings for storing and printing as the outputs shown in the example below.

\===============================================================

**Example:** If the user gives us a range of between 2 and 6, there are 3 prime numbers (2, 3, 5\) and 1 perfect number (6) in that range.

**Input:**  
2  
6

**Output:**  
Between 2 and 6,  
Found 3 prime numbers  
Found 1 perfect number  
Prime numbers: 2, 3, 5  
Perfect number: 6

**Task 29**

Write a python program that asks the user for a range, a starting number(inclusive) and an ending number (inclusive). Then, take another input for checking. If the product of all the digits of each number in the range is divisible by the third input, then print the number.

\===============================================================

**Sample Input 1:**  
25  
30  
4

**Sample Output 1:**  
12 16 0

**Explanation:** The product of all the digits of each number from 25 to 30 are 2 × 5, 2 × 6, 2 × 7, 2 × 8, 2 × 9 and 3 × 0\. The final products are 10, 12, 14, 16, 18 and 0 respectively. Out of these numbers only 12, 16 and 0 are divisible by the third input 4 and therefore they are printed.

\===============================================================

**Sample Input 2:**  
351  
356  
9

**Sample Output 2:**  
45 90

**Explanation:** The product of all the digits of each number from 351 to 356 are 3×5×1, 3×5×2, 3×5×3, 3×5×4, 3×5×5 and 3×5×6. The final products are 15, 30, 45, 60, 75 and 90 respectively. Out of these numbers only 45 and 90 are divisible by 9 and therefore they are printed.

[image1]: <data:image/png;base64,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>