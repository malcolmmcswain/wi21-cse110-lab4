1. The last value assigned to i will be printed because, since it was declared as a var, it exists inside the function scope

2. The last value assigned to discountedPrice will be printed because it also exists inside the function scope

3. The last value assigned to finalPrice will be printed as it was declared in the function scope

4. The function will return an array containing the price after discount of each price from the parameter array of prices

5. The function would throw an error, since let variables only exist in the scope of the block they're declared in

6. The function would also throw an error as discountedPrice was also declared in the for loop block

7. The last value assigned to finalPrice will be printed since it was declared in the function scope

8. The function will return the same array from question 4 since let declarations are mutable

9. The function would throw an error, since let variables only exist in the scope of the block they're declared in

10. The first value assigned to discountedPrice would be printed since it can't be changed after its declaration

11. 0 would be printed because it is also a const

12. The function would return an empty array because the local variable used as the return value was also declared as a const

13A. student.name

13B. student['Grad Year']

13C. student.greeting()

13D. student['Favorite Teacher'].name

13E. student.courseLoad[1]

14A. '32' because the + is interpreted as concatenation following a string

14B. 1 because the - is a mathematical operation, so '3' is automatically converted to 3

14C. 3 because the null is interpreted as a 0 in the + mathematical operation

14D. '3null' because null is interpreted as the string 'null' since + is now interpreted as concatenation

14E. 4 because true is interpreted as 1 in a mathematical expression

14F. 0 because false and null will both be interpreted as 0

14G. '3undefined' because undefined is interpreted as the string 'undefined' since we are concatenating

14H. NaN because this is not a valid expression

15A. true because the '2' was interpreted as a 2 in this context

15B. false because the value '2' is greater than the value '1'

15C. true because the '2' is interpreted as a 2 in this context

15D. false because === considers type as part of the comparison

15E. false because this expression is interpreted as 1 == 2

15F. true because Boolean(2) will return the value true since 2 is non-zero

16. == is a looser equality comparator as it only considers value and will attempt to resolve different datatypes, where === enforces that both variables are of the same type

17. 'How are you?' will be printed since the first condition will fail as true has the value 1, but the second condition will pass as 2 is non-zero and will be interpreted as true

18. See part1-question18.js

19. The function will return [6,8,10] since modifyArray will call the outer callback (doSomething), which adds 2 to the original number, then passes an inner callback (doSomething's callback) that multiplies that number by 2. Going item by item in the array we get: (1+2)\*2=6, (2+2)\*2=8, (3+2)\*2=10.

20. See part1-question20.js

21. The function will immediately print 1 and 4, then 3 after a 0ms delay, then 2 after a 1000ms delay
