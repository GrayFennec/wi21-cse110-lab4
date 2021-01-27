<ol>
<li>At line 11, the final value of <code>i</code> will be printed, since the var declaration means <code>i</code> is function-scoped.</li>
<li>At line 12, the final value of <code>discountedPrice</code> will be printed, since the var declaration means <code>discountedPrice</code> is function-scoped.</li>
<li>At line 13, the final value of <code>finalPrice</code> will be printed, since the var declaration means <code>finalPrice</code> is function-scoped.</li>
<li>The function will return <code>[10, 100, 150]</code>. <code>discounted</code> is initialized as an empty list, and <code>finalPrice</code> is initialized to <code>0</code>. The for loop goes through the indices of <code>prices</code>, calculating a new <code>discountedPrice</code> every time, which is half the value since <code>discount</code> is set to 0.5. This new value is pushed onto <code>discounted</code>, which by the end is returned.</li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
<li></li>
</ol>