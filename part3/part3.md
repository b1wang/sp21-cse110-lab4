1. The bug is that the js is trying to add the string type values of num1 and num2, so "1" + "2" is "12". 
2. I would fix this by forcing num1 and num2 into numerical types through the Number() function. This calculates to the correct result. 
