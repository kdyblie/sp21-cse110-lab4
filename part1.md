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
    9. undefined, because i is declared using let which has block scope and its scope is contained to the scope of the for loop
    10. 3 is printed to the console, because variable length is declared using const and is logged to the console within the same scope
    11. An array of the discounted prices with values [50, 100, 150], because discounted is declared using const and is returned within the same scope, additionally arrays declared with const can still have elements added, as for discountedPrice changing with each iteration despite the use of const in its declarition is because a new block scope is created with each iteration.
    12. 
        A. student.name
        B. student['Grad Year']
        C. student.greeting()
        D. student['Favorite Teacher'].name
        E. student.courseLoad[0]
    13. 