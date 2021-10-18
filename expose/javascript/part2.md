1. It will print '3'. This is because 'i' gets incremented to '3' when it exits the loop.
2. It will print '150'. This is the discounted price of the final item in the prices list.
3. Final price will also print '150'. It is the price of the last item in the list and it is already a rounded, whole number.
4. Discounted will return a list of length equal to the original prices list. The elements will be the newly discounted prices. Since it is a return, nothing will be printed.
5. It will error. This is because 'i' is declared outside the scope and can only be accessed in the loop block.
6. It will error. Similar to the above, 'discountedPrice' is declared in the loop block and cannot be accessed outside of it.
7. It will print out '150'. This is because finalPrice is not declared with 'let' or 'const', so it should be accessible outside the for loop.
8. It will return a list of the discounted prices. This works because it is called in the same scope as the it was created. It is in the same scope as 'let discounted = []'.
9. The code will error. This is because 'i' can only be accessed in the scope of the loop since it is declared using 'let'.
10. It will print '3'. Length is defined as '3' in the top of the function, and it is in the same scope as when the console.log is called.
11. It will return a list of length 3 with the discounted prices. This is because we are not changing the const variable, it is still an array/list. We are only updating and adding to the list with out discounted prices. It still remains as the same structure as it is defined.
12. 
    A. student.name
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0]
13. 
    A. '32'  It is concatenating '3' with '2'
    B. 1     It is taking 3 as an integer and subtracting 2 from it
    C. 3     Null is treated as a integer 0
    D. 3null Null is treated as a string input 'null' and concatenated to '3'
    E. 4     True is equivalent to the integer 1 and added to integer 3
    F. 0     False and null are both equivalent to integer 0, adding 0+0=0
    G. '3undefined'  Undefined is treated as a string input and concatenated to the string '3'
    H. NaN   It is trying to do arithmetic, but you cannot subtract an undefined value. Thus, it is Not A Number.
14. 
    A. True  '2' is casted as an integer and 2 > 1 is True
    B. False '12' is lower in the ASCII value table than '2' since '1' is before '2' and it compares first index first
    C. True   '2' is casted as an integer and the expression 2==2 is true
    D. False  There is no type conversion and an integer is not equal to a string
    E. False  True can be converted to a integer 1, but 1 != 2, so it will return False
    F. True   Boolean(2) is the same as true, so the two are equivalent
15. The == operator checks whther its two operands are equal and returns a Boolean result. It will attempts to convert and compare operands that are different types. However, the === operator will not try to convert and compare operands, it only checks whether the two sides are equal as inputed. Thus, is always considers operands of different types to not be equal.
17. In this example, we are passing in a function as a parameter. Starting from the first index in the [1,2,3] array, we are passing each value (arr[i]) into the doSomething function and essentially doubling that value. We then push the new value onto the newArr and return newArr once we are done with all the elements in the original array. Essentially newArr goes from [] > [2] > [2,4] > [2,4,6] and finally returns [2,4,6]. The return value is the original array with each index multiplied by 2 due to the doSomething function.
19. The output of the code should be 1 4 3 2. The code is read top to bottom, so the console will print out 1 before 4. 2 and 3 are set as a Timeout so both of them will execute after 1 and 4. 3 is set as a Timeout of 0 so it will print out right after 4. 2 has a timeout of 1000 which is equivalent to 1 second, so it will print 1 second after it is called. Thus, the order is 1 4 3 2.
    