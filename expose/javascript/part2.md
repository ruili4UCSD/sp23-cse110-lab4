1. Line 12 will print 3, because i is defined by var, which means it can be access by console.log(i). Since i is increase three times by the for loop start from 0, it would be 3.
2. It would print 150. Because discountedPrice is defined by var, which means it can be access in the function, it store the price that been discounted, in for loop, discountedPrice would iterated to get the last discounted price, which is 300*(1-0.5)=150.
3. It would print 150. Because final Price is defined by var, which means it can be access by console.log(finalPrice);. Since finalPrice=discountedPrice\*100/100 and the last value of discountedPrice is 150, finalPrice = 150\*100/100=150 too.
4. This function will return an array that contains all the discounted prince in order, in this case, it is [50, 100, 150]. Because discounted is an array defined in main body of function discountPrices, so it can be accessed by line 16. In the function we accept an array contains original prices and a discount, and we use a for loop to count the new prince and store them in discounted, which is an array, and we finally return the array.
5. It would give an undifined error because i is defined in for loop with let, which means its block scope is for loop so it cannot be accessed by line 12.
6. It would give an undifined error because discountedPrice is defined in for loop with let, which means its block scope is for loop so it cannot be accessed by line 13.
7. It would print 150. Because finalPrice is defined in function discountPrices so it can be accessed by line 14.
8. [50, 100, 150]. Because discounted is an array defined in main body of function discountPrices, so it can be accessed by line 16. In the function we accept an array contains original prices and a discount, and we use a for loop to count the new prince and store them in discounted, which is an array, and we finally return the array.
9. It would give an undifined error because i is defined in for loop with let, which means its block scope is for loop so it cannot be accessed by line 11.
10. It would print 3. Because length is defined by const in the main body of the function discountPrices, so it can be accessed by line 12. Since the length of the array [100, 200, 300] is 3, length would be 3.
11. [50, 100, 150]. Because although discounted is defined as const to indicate that the array it points to cannot be reassigned, but the elements inside the array can be changed. Therefore, we can add the discounted price into discounted in turn, and finally return it.
12. a. student.name
    
    b. student['Grad Year']

    c. student.greeting()

    d. student['Favorite Teacher'].name

    e. student.courseLoad[0]

13. a. '32' because '3' is a string and we use + operator, js transfer 2 from number to string, and by +, '3'+'2' became 32. 
    
    b. 1. Because we use - operator, js transfer '3' from string to number, 3-2=1

    c. 3. Because js transfer null to number, which is 0, 3+0=3.
    
    d. 3null. Because '3' is a string and we use + operator, js transfer null to string which is 'null', then add it to the end of '3'.
    
    e. 4. js transfer true from bool to number, which is 1, 1+3=4.
    
    f. 0. Because js transfer both false and null to number, which both became 0, 0+0=0
    
    g. 3undifined. Because '3' is a string and we use + operator, js transfer undifined to string which is 'undifined', then add it to the end of '3'.
    
    h. NaN. Because we use - operator, js transfer '3' to number 3, and transfer undefined to NaN, then since NaN is in calculation, it returns NaN.

14. a. true. Because js converts string '2' to number 2, 2>1 is true.
    
    b. false. js compare the first character in both string first, which is '2' and '1', since '2'>'1' in lexi order, false.
    
    c. true. by == operator, js converted '2' to 2, then 2 == 2, true.
    
    d. false. by === operator, 2 and '2' are different type, false.
    
    e. false. by == operator, js convert true to number 1, 1 not equal to 2, false.
    
    f. true. Boolean(2) transfer 2 to bool true, true === true, true.

15. == means loose equality, it allows different types converts to number and compare each other, if equal then return true. === means strict equality, it does not converts type of variables, so if type of variables are different, it return false. 
16. See part2-question16.js
17. The result would be an array: [2, 4, 6]. First in execute line 13, it pass an array [1, 2, 3] and an function doSomething to funtion modifyArray. Function modifyArray takes parameters and build a new empty array newrr, then by an for loop iterate each number in [1, 2, 3] and call function doSomething on it. Function doSomething takes the number num and return 2*num, then modifyArray push the result to the newArr. Therefore, when for loop end, newArr=[2, 4, 6], then we returned newArr in line6, therefore [2, 4, 6] is the result.
18. See file part2-question18.js
19. 1
    
    4
    
    3
    
    2