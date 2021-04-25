Part 1a. A Quick Introduction...

    1. values added: 20
   
    2. final result: 20
   
    3. values added: 20
   
    4. undefined, because let has block scope and its scope is contained to the scope of the if statement
   
    5. code will return error as a const variable cannot be reassigned
   
    6. code will return error as a const variable cannot be reassigned

Part 1b. A Little More of a Challenge...

    1. 3 , i is declared using var and var has no block scope
   
    2. 150 , discountedPrice is declared using var and var has no block scope
   
    3. 150 , finalPrice is declared using var and var has no block scope

    4. An array of the discounted prices with values [50, 100, 150], as at the end of each iteration of the for loop the finalPrice after discounted is pushed to the discounted array.

    5. undefined, because i is declared using let which has block scope and its scope is contained to the scope of the for loop

    6. undefined, because discountedPrice is declared using let which has block scope and its scope is contained to the scope of the for loop

    7. 150 , because finalPrice is declared using let and is logged to the console within the same scope

    8. An array of the discounted prices with values [50, 100, 150], because discounted is delcare using let and is returned within the same scope of its declaration

    9.  undefined, because i is declared using let which has block scope and its scope is contained to the scope of the for loop

    10. 3 is printed to the console, because variable length is declared using const and is logged to the console within the same scope

    11. An array of the discounted prices with values [50, 100, 150], because discounted is declared using const and is returned within the same scope, additionally arrays declared with const can still have elements added, as for discountedPrice changing with each iteration despite the use of const in its declarition is because a new block scope is created with each iteration.

    12.
        
        A. student.name

        B. student['Grad Year']

        C. student.greeting()

        D. student['Favorite Teacher'].name

        E. student.courseLoad[0]

    13.

        A. '32' , since integers map to their exact string representation.

        B. 1 , since in subtraction '3' is mapped to is numeric version thus 3 - 2 = 1, .

        C. 3 , since null is converted to 0 by numeric conversion rules.

        D. '3null' , since null maps to its exact string representation

        E. 4 , since true is converted to 1 by numeric conversion rules.

        F. 0 , since false and null is each converted to 0 by numeric conversion rules.

        G. '3undefined' , since undefined maps to its exact string representation.

        H. NaN , since undefined is converted to NaN by numeric conversion rules and '3' - NaN = NaN. subtracting undefined thing.

    14.

        A. true , since string '2' becomes a number 2.

        B. false , since both '2' and '12' are strings and the first character of '2' is greater than the first character of '12'.

        C. true , string '2' becomes a number 2.

        D. false , since === checks the equality without type conversion thus 2 != '2'.

        E. false , since true becomes a number 1 and 1 != 2.

        F. true , since by Boolean conversion rules Boolean(2) is intuitively "non-empty" thus becomes true. The === checks equality without type conversion and Boolean(2) is of type Boolean and so it true.

    15. The == operator is an equality test with type conversion and the operator === is a strict equality operator that checks the equality without type conversion.

    16. In JS file part1b-question16.js

    17. The reuslt will be the return of newArr = [2,4,6] , in each iteration of the for loop the function doSomething is called since it is passed in as the callback arguement. Thus each value at at index in the inserted array is ran through the doSomething function and the doubled value is pushed on the new array. Essentially the function doSomething is repeatedly invoked, once in each iteration of the forloop.

    18. In JS file part1b-question18.js

    19.
        1
        4
        3
        2