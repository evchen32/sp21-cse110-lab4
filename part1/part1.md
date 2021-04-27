# Part 1a
1. Prints the sum of num1 and num2.
2. Nothing, due to the return statement in line 11.
3. Returns error, because result is defined in the if block by let keyword but, result is also used outside the if block.
4. Nothing, due to the return statement in line 11.
5.  Returns error, because result is declared as a const in line 5 but, is defined again in line 7.
6.  Nothing, due to the return statement in line 11.

# Part 1b
1. Prints 3, because the for loop stops when i reaches the length of the prices array.
2. Prints 150, because the for loop cycles through the prices array and the last value of the prices array (300) is the last to redefine discountedPrice before the for loop is exited.
3. Prints 150, because the for loop cycles through the prices array and the last value of the prices array (300) is the last to redefine discountedPrice which also redefines finalPrice before the for loop is exited.
4. Returns an array containing 50, 100, 150. This is due to the for loop going through the prices array and calculating the discounted price for each based on the discount given and then pushing each discounted price (after rounding it) into the array "discounted" which will be returned.
5. Returns error, because i is defined in the for loop with let and line 12 is trying to use i outside its block.
6. Returns error, because discountedPrice is defined in the for loop with let and line 13 is trying to use discountedPrice outside its block.
7. Prints 150, because the for loop cycles through the prices array and the last value of the prices array (300) is the last to redefine discountedPrice which also redefines finalPrice before the for loop is exited.
8. Returns an array containing 50, 100, 150. This is due to the for loop going through the prices array and calculating the discounted price for each based on the discount given and then pushing each discounted price (after rounding it) into the array "discounted" which will be returned.
9. Returns an error, because i is defined with let in the for loop and line 11 is trying to access i outside of its block.
10. Prints 3, because length is defined by the length of the prices array.
11. Returns an array containing 50, 100, 150. This is due to the for loop going through the prices array and calculating the discounted price for each based on the discount given and then pushing each discounted price into the array "discounted" which will be returned.

12. Notations:
- A. student.name
- B. student['Grad Year']
- C. student.greeting()
- D. student['Favorite Teacher'].name
- E. student.courseLoad[0]

13. Arithmetic
- A. '32', since the '3' is a string then the plus operator concatenates the 2 as a string to '3'.
- B. 1, since the '3' maps to 3 and subtracts 2.
- C. 3, since null maps to 0.
- D. '3null', since null maps to 'null' in string conversion and the plus operator concatenates it to the '3' string.
- E. 4, since true maps to 1.
- F. 0, since false maps to 0 and null maps to 0.
- G. '3undefined', since undefined maps to 'undefined' in string conversion and the plus operator concatenates it to the '3' string.
- H. NaN, since '3' is converted to a number due to the minus operator while undefined is converted to its numeric value of NaN.

14. Comparison
- A. True, since we are comparing two different types, '2' is converted to a number. Javascript converts the values to numbers when comparing values of different types.
- B. False, since we are comparing strings, Javascript will look at the first character of both strings and '2' is higher than '1' in '12'.
- C. True, since we are comparing two different types, '2' is converted to a number. Javascript converts the values to numbers when comparing different types.
- D. False, because === checks the equality without type conversion which means an immediate return of false if types don't match. In this case, we are comparing a number to a string so, different types.
- E. False since, true converts to 1 in this case.
- F. True, because Boolean(2) maps to true.

15. == is a regular equality check that converts operands to numbers when they are different types. ===, on the other hand, is a strict equality operator that checks the equality without type conversion which means an immediate return of false if types don't match.
    
17\. modifyArray will return an array that contains 2,4,6. modifyArray is called with an array of [1,2,3] and the doSomething function as parameters. Inside modifyArray, a for loop takes each value of the array given through the parameters and calls the doSomething function on each which multiplies each value by 2. These new values are then stored in a new array that is returned.

18. 1  
    4  
    3  
    2
