## 1a. 
1. 20
2. 20
3. 20
4. This code returns an error because let does not have function scope like var does, so result cannot be accessed outside of the if block.
5. This code returns an error because const cannot be assigned to, which result = num1 + num2 tries to do. 
6. This code returns an error because const cannot be assigned to, which result = num1 + num2 tries to do. 

## 1b. 
1. The console will log the length of the prices array, which is 3. 
2. The console will log the last discounted price in the array. In this case, it is 300 * (1 - 0.5), which is 150. 
3. The code rounds the discounted price to the nearest hundredths by multiplying the discounted price by 100 and rounding it, and then dividing by 100 to get it back to its decimal form. In this case, the code is (150 * 100) / 100, which is 150. 
4. The function will return [50, 100, 150], The code iterates through the prices array, stores the discounted price and rounds the price to the nearest hundredth. It then adds it into a discounted array, which is returned by the program after discounting [100, 200, 300] by half. 
5. It will cause an error because i is declared with let, so it can only be used in the for block. console.log(i) is outside of the for block.
6. It will cause an error because discountedPrice is declared with let, so it can only be used in the for block. console.log(discountedPrice) is outside of the for block.
7. It will return 150 because final price is declared in the same block scope as console.log(finalPrice). It will print out the last final price from the prices array. 
8. The function will return [50, 100, 150], with the same logical reasoning as question 4. Changing the vars to lets only affected the variable scopes, but it did not affect the actual execution of the program.
9. Error because i is declared with let, so it can only be accessed within the for block. 
10. It will print 3, because length is assigned to the length of the prices array. It will also not cause an error, because the const variable is only set once. 
11. It will return [50, 100, 150], and the change to const did not affect the program execution. This is because every single const variable was only declared once at the start and was never re-assigned. 

12.
    a. student.name
    b. student["Grad Year"]
    c. student.greeting()
    d. student["Favorite Teacher"].name
    e. student.courseLoad[0]
    
13.
    a. '32' because the 2 is automatically converted to a string to concatenate. 
    b. 1, because you cannot subtract a string so it converts the '3' into numerical value.
    c. 3, because null is automatically converted to a zero. 
    d. '3null' because null is converted to a string when '3' is a string. 
    e. 4, because true is converted to numerical 1. 
    f. 0, because false and null both convert into numerical zero. 
    g. 3undefined, because '3' is already a string so it concatenates the 3 and undefined.
    h. NaN, because undefined converts into NaN when doing a numerical conversion. 

14.
    a. True, because 2 becomes the number 2.
    b. False, because when strings are compared they are compared lexicographically, and 1 is less than 2.
    c. True, because '2' is converted into the numerical 2.
    d. False, because === compared types and 2 is not the same type as the string '2'. 
    e. False, because true is converted into 1, and 1 is not equal to 2. 
    f. True, because Boolean(2) converts to true, and true is the same type as true (both booleans). 
    
15. == just compared the values of the data type, while === compares the data types too. 

17.

19.


