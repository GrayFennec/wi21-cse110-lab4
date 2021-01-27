1. At line 11, the final value of `i` will be printed, since the `var` declaration means `i` is function-scoped.
2. At line 12, the final value of `discountedPrice` will be printed, since the `var` declaration means `discountedPrice` is function-scoped.
3. At line 13, the final value of `finalPrice` will be printed, since the `var` declaration means `finalPrice` is function-scoped.
4. The function will return `[10, 100, 150]`. `discounted` is initialized as an empty list, and `finalPrice` is initialized to `0`. The for loop goes through the indices of `prices`, calculating a new `discountedPrice` every time, which is half the value since `discount` is set to `0.5`. This new value is pushed onto `discounted`, which by the end is returned.
5. At line 11, there will be an error, since the `let` declaration means `i` is only in the scope of the for-loop.
6. At line 12, there will be an error, since the `let` declaration means `discountedPrice` is only in the scope of the for-loop.
7. At line 13, the final value of `finalPrice` will be printed, since the `let` declaration means `finalPrice` is function-scoped.
8. The function will not return because of the errors in variable scope described above.
9. At line 11, there will be an error, since the `let` declaration means `i` is only in the scope of the for-loop.
10. At line 12, there will be an error, since the `const` declaration means `discountedPrice` is only in the scope of the for-loop.
11. At line 13, the initial value of `finalPrice` will be printed, since the <const>const` declaration means `finalPrice` is function-scoped and keeps its initial value.
12. The function will not return because of the errors in variable scope described above.
13. 
    A. student.name
    B. student["Grad Year"]
</ol>