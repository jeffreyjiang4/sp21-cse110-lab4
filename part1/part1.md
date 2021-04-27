### 1a
1. 20
2. 20
3. 20
4. Undefined error, the variable was declared using let, limiting it to the if block scope.
5. error; tried to reassign a const variable
6. error; result could not be reassigned in line 7 as it was a const
   
### 1b
1. 3 will be printed; it is the value i is at the end of the forloop. will get printed because i was declared with 'var'
2. 150 will be printed as the final value of discountedPrice was 150. discountedPirce was also declared with 'var', so it extends beyond the forloop.
3. 150 will be printed as the final value of finalPrice was 150. finalPrice was declared in the scope as where console.log(finalPrice) is in.
4. This function will return the discounted prices of the original array of prices.
5. error; the scope of i does not extend beyond the forloop as it was declared using 'let'.
6. error; the scope of discounted price does not extend beyond the forloop as it was declared using 'let' in the forloop.
7. print 150; the variable discounted was declared in the same scope it is being returned in.
8. function will return discounted prices of original array of prices. discounted being returned in same scope it was declared.
9. error; the scope of i does not extend beyond the forloop as it was declared using 'let'.
10. 3 will be printed as the variable length was never reassigned and was declared in the same scope as being returned.
11. will return array of discounted prices. able to return as the actual object was not changed whilst being declared as a const.
12. 
    A. student.name
    B. student["Grad Year"]
    C. student.greeting()
    D. student['Favorite Teacher'].name
    E. student.courseLoad[0];
13. 
    A. 32; integers map to exact string representation
    B. 1; '3' is converted to a number
    C. 3; null maps to 0
    D. 3null; null is mapped to exact string representation
    E. 4; true is mapped to 1
    F. 0; both map to 0
    G. 3undefined; undefined mapped to exact string representation
    H. NaN; undefined mapped to NaN
14. 
    A. true; string 2 becomes a number 2
    B. false; lexicographical comparison
    C. true; string 2 becomes a number 2
    D. false; types are different (strict equality)
    E. false; true is converted to 1
    F. true; they are both of boolean type
15. == operator ingnores datatype
    === operator checks datatype and compares
16. part1b-question16.js
17. [2,4,6]; for every index of the array, the doSomething function is being called to double the element of that index.
18. part1b-question18.js
19. 1
    4
    3
    2