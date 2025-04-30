1. It will print 3, as since the loop counter is var, its value will be accessible throughout the function. When the loop ends, we have i = prices.length = 3.
2. Since discountedPrice is var, it is again accessible by the entire function. Since it is set to 150 in the last iteration of the loop, Line 13 prints 150.
3. Similarly to discountedPrice, finalPrice is accessible by the entire function. Since it is set to 150 in the final loop iteration, Line 14 prints 150.
4. The function will return [50, 100, 150], as each element in the list is multiplied by 0.5 and pushed to the result array.
5. The code causes an error, as i is only defined in the scope of the for loop, meaning it is undefined in Line 12, causing an error.
6. The code causes an error, as discountedPrice is only defined in the scope of the for loop, meaning it is undefined in Line 13, causing an error.
7. The code prints 150, as finalPrice is defined in the entire function scope. In the last loop iteration, it becomes 150, meaning Line 14 will print 150.
8. The function will return [50, 100, 150], as each element in the list is multiplied by 0.5 and pushed to the result array.
9. The code causes an error, as i is only defined in the scope of the for loop, meaning it is undefined in Line 11, causing an error.
10. The code prints 3, as length is defined with in the main function body, meaning it is accessible from line 12. Since prices.length is 3, it is permanently set to 3. Thus, Line 12 will print 3.
11. The function will return [50, 100, 150], as each element in the list is multiplied by 0.5 and pushed to the result array. The elements of the discounted array can be modified even though discounted is const.
12. 
    A. student['name']
    B. student['Grad Year']
    C. student.greeting()
    D. student['Favorite Teacher']['name']
    E. student['courseLoad'][0]
13. Arithmetic
    A. '3' + 2 -> '32', since + with a string forces string concatenation
    B. '3' - 2 -> 1, since - forces both to be numbers.
    C. 3 + null -> 3, since null becomes 0 numerically
    D. '3' + null -> '3null', since + with a string forces string concatenation.
    E. true + 3 -> 4, since true becomes 1 numerically
    F. false + null -> 0, since false and null both become 0 numerically.
    G. '3' + undefined -> '3undefined', since + with a string forces string concatenation
    H. '3' - undefined -> NaN, since - tries to make '3' and undefined into numbers, but undefined can't be made into a number so we get NaN
14. Comparison
    A. '2' > 1 -> true, since when JS compares a string and a number they are both considered numbers, giving us 2 > 1, which is true.
    B. '2' < '12' -> false, since when JS compares two strings they are compared using lexicographical order, giving us '2' < '12', which is false.
    C. 2 == '2' -> true, since when JS compares a string and a number they are both considered numbers, giving us 2 == 2, which is true.
    D. 2 === '2' -> false, as === checks that the operands are both the same type, which is not the case here, giving us false.
    E. true == 2 -> false, as the true becomes a 1 numerically, giving us 1 == 2, which is false.
    F. true === Boolean(2) -> true, as since 2 is "truthy", Boolean(2) is true. We then have true === true, which is true.
15. == will perform type conversion when comparing two things, while === will not convert types, simply returning false if the types differ.
16. Code in part2-question16.js
17. The result is [2, 4, 6], as for each element in the array, we apply doSomething to it and add the result to the new array. Since doSomething doubles the number, the resulting array's elements are double those of the original array's. Thus, the result will be [2, 4, 6].
18. Code in part2-question18.js
19. The output is 1 4 3 2.