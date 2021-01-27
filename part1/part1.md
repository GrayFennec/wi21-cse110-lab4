<ol>
<li>At line 11, the final value of `i` will be printed, since the var declaration means `i` is function-scoped.</li>
<li>At line 12, the final value of `discountedPrice` will be printed, since the var declaration means `discountedPrice` is function-scoped.</li>
<li>At line 13, the final value of `finalPrice` will be printed, since the var declaration means `finalPrice` is function-scoped.</li>
<li>The function will return `[10, 100, 150]`. `discounted` is initialized as an empty list, and `finalPrice` is initialized to `0`. The for loop goes through the indices of `prices`, calculating a new `discountedPrice` every time, which is half the value since `discount` is set to 0.5. This new value is pushed onto `discounted`, which by the end is returned.</li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
</ol>