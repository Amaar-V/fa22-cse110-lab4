### Answers:
1. `3` because `var i` is in **function-scope** so when we print at line 12 then we print `i` final value which runs till price.length which has a value of 3 so `i==3`
2. `150` because at the final iteration of the for loop, `discountedPrice` is set to the value of `price[i] * (1-discount)` where `i=3` and `discount=0.5` thus `discountedPrice=150` which is what is printed at line 13
3. `150` because at the final iteration of the for loop, `finalPrice` is set to the value of `Math.round(discountedPrice * 100) /100` where `discountedPrice=150` so `finalPrice=150` which is what is printed at line 14
4. It returns a list that equals `[50,100,150]` which is the discounted price of each of the values in prices. Since we pass the discount value at `50%` then each final value is at half of what we passed in. After adding the changed values in the list, we return the list at line 16
5. It gives a reference error because `i` is not refined in the scope of line 12. Since we used `let` to declare `i`, it is only defined in the scope of the for loop so referencing `i` outside of that scope gives an error.
6. It gives a reference error because `discountedPrice` is not refined in the scope of line 13. Since we used `let` to declare `discountedPrice`, it is only defined in the scope of the for loop so referencing `discountedPrice` outside of that scope gives an error.
7. `150` because `finalPrice` is defined in the scope of the function so line 14 can reference it. `finalPrice` gets set the value of `150` in the final itereation of the for loop since the for loop is inside the function so it has the scope to reference function scope variables.
8. `discounted` is defined in the fucntions scope so it is able to return at line 16. It returns a list that equals `[50,100,150]` which is the discounted price of each of the values in prices. Since we pass the discount value at `50%` then each final value is at half of what we passed in. After adding the changed values in the list, we return the list at line 16
9. It gives a reference error because `i` is not refined in the scope of line 12. Since we used `let` to declare `i`, it is only defined in the scope of the for loop so referencing `i` outside of that scope gives an error
10. `3` which is the value of `length` which is set to the length of `prices` which is `3` at the end of for loop
11. `discounted` is defined in the fucntions scope so it is able to return at line 16 but even though it is a constant we use the list's functions to add value to it without reassigning it so it can remain `const`. It returns a list that equals `[50,100,150]` which is the discounted price of each of the values in prices. Since we pass the discount value at `50%` then each final value is at half of what we passed in. After adding the changed values in the list, we return the list at line 16
12. 
    a. `student.name`
    b. `student['Grad Year']`
    c. `student.greeting()`
    d. `student['Favorite Teacher'].name`
    e. `student.courseLoad[0]`
13. 
    a. `'32'`, the addition operator `'3'` concatonated with the `2` to give the string.
    b. `1`, the subtraction operator transformed the `'3'` into an integer to then subtract `2` from it.
    c. `3`, `null` maps to 0 so `null+3=3`
    d. `'3null'`, the addition operator `'3'` concatonated with the `null` to give the string.
    e. `4`, `true` maps to 0 so `true+3=4`
    f. `0`, both `false` and `null` map to the value of 0 so their addition is `0`
    g. `'3undefined'`, the addition operator `'3'` concatonated with the `undefined` to give the string.
    h. `NaN` since we are subtracting a string `3` with an undefined type, we get `NaN` which means not a number.
14. 
    a. `true`, string `'2'` becomes a number `2`
    b. `false`, the strings are compared letter by letter so `'1'>'2'` is false
    c. `true`, string `'2'` becomes a number `2`
    d. `false`, the `===` checks without type conversion so a string does not equal a number
    e. `false`, `true` is mapped to `1` but `1 != 2`
    f.  `true`, the `Boolean` function will turn numbers that are not `0` into `true` so `Boolean(2)=true`
15. The `==` operator checks equality with type conversion while `===` checks equality without type conversion.
16. check js file
17. `[2,4,6]`, we start by first calling the `modifyArray` function and pass a list `array=[1,2,3]` and function `callback=doSomething`. In `modifyArray`, we create a new array and loop over `array` and send each element to the function `callback` which returns the element times 2 and we push that returned value to the new array we made. After filling the array with the new values, we return the new array.
18. check js file
19. Output:
```
     1

     4

     3

     2
``` 