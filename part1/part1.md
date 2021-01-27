1. At line 11, the final value of `i` will be printed, since the `var` declaration means `i` is function-scoped.
2. At line 12, the final value of `discountedPrice` will be printed, since the `var` declaration means `discountedPrice` is function-scoped.
3. At line 13, the final value of `finalPrice` will be printed, since the `var` declaration means `finalPrice` is function-scoped.
4. The function will return `[10, 100, 150]`. `discounted` is initialized as an empty list, and `finalPrice` is initialized to `0`. The for loop goes through the indices of `prices`, calculating a new `discountedPrice` every time, which is half the value since `discount` is set to `0.5`. This new value is pushed onto `discounted`, which by the end is returned.
5. At line 11, there will be an error, since the `let` declaration means `i` is only in the scope of the for-loop.
6. At line 12, there will be an error, since the `let` declaration means `discountedPrice` is only in the scope of the for-loop.
7. At line 13, the final value of `finalPrice` will be printed, since the `let` declaration means `finalPrice` is function-scoped.
8. The function will return `[10, 100, 150]`, for the same reasons as in question 4.
9. At line 11, there will be an error, since the `let` declaration means `i` is only in the scope of the for-loop.
10. At line 12, there will be an error, since the `const` declaration means `discountedPrice` is only in the scope of the for-loop.
11. At line 13, the initial value of `finalPrice` will be printed, since the `const` declaration means `finalPrice` is function-scoped and keeps its initial value.
12. The function will return `[0, 0, 0]`, since `finalPrice` is a constant, and will never change from its original value of `0`, so only `0` is pushed onto `discounted`, and not any updated `finalPrice` value.
13. Object notation:  
    A. `student.name`  
    B. `student["Grad Year"]`  
    C. `student.greeting()`  
    D. `student["Favorite Teacher"].name`  
    E. `student.courseLoad[0]`
14. Arithmetic  
    A. `'32'`, appending to `'3'` requires a string, so `2` is type converted to `'2'`, which is then appended.  
    B. `1`, subtracting a `2` requires a number, so `'3'` is type converted to `3`, which is then subtracted.  
    C. `3`, adding to `3` requires a number, so `null` is type converted to `0`, which is then added.  
    D. `'3null'`, appending to `'3'` requires a string, so `null` is type converted to `'null'`, which is then appended.  
    E. `4`, adding to `3` requires a number, so `true` is type converted to `1`, which is then added.  
    F. `0`, adding requires numbers, so `false` is type converted to `0`, and `null` is type converted to `0`, which are then added.  
    G. `"3undefined"`, appending to `"3"` requires a string, so `undefined` is type converted to `"undefined"`, which is appended.  
    H. `NaN`, subtracting requires numbers, so `"3"` is type converted to `3`, and `undefined` is type converted to `NaN`, the subtraction of `NaN` from `3` leads to an output of `NaN`  
15. Comparison  
    A. `true`, comparison of different types converts into numbers, so `'2'` is type converted to `2`, which is greater than `1`.  
    B. `false`, comparison of strings uses lexicographical order, so `'2'` is greater than `'12'`.  
    C. `true`, comparison of different types converts into numbers, so `'2'` is type converted to `2`, which is equal to `2`.
    D. `false`, strict equality does not type convert, so `2` is not equal to `'2'`.
    E. `false`, comparison of different types converts into numbers, so `true` is type converted to `1`, which is not equal to `2`.
    F. `true`, `Boolean(2)` evaluates to `true`, which is equal to `true`.
16. The `==` operator converts differently typed operands to numbers, while the `===` operator does not do any type conversion.  
17. `How are you?` will be printed. `2 == true` evaluates to `false`, so `Hello!` will not be printed. The `if` conditional requires a boolean, so `2` is type converted to `true`, which means `How are you?` will be printed.  
19. The result will be `[6, 8, 10]`. The function `modifyArray` creates a new array with values created by running the `callback` input on the values of the old array with another input function which doubles a number. In this case, `callback` is `doSomething`, which runs its own input `callback` on its other input `num` plus two. So, in `modifyArray`, a new array is created with values created by running `doSomething` which itself runs the doubling function on the old array values incremented by two.  
21. 
</ol>