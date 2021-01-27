<ol>
<li>At line 11, the final value of <code>i</code> will be printed, since the <code>var</code> declaration means <code>i</code> is function-scoped.</li>
<li>At line 12, the final value of <code>discountedPrice</code> will be printed, since the <code>var</code> declaration means <code>discountedPrice</code> is function-scoped.</li>
<li>At line 13, the final value of <code>finalPrice</code> will be printed, since the <code>var</code> declaration means <code>finalPrice</code> is function-scoped.</li>
<li>The function will return <code>[10, 100, 150]</code>. <code>discounted</code> is initialized as an empty list, and <code>finalPrice</code> is initialized to <code>0</code>. The for loop goes through the indices of <code>prices</code>, calculating a new <code>discountedPrice</code> every time, which is half the value since <code>discount</code> is set to <code>0.5</code>. This new value is pushed onto <code>discounted</code>, which by the end is returned.</li>
<li>At line 11, there will be an error, since the <code>let</code> declaration means <code>i</code> is only in the scope of the for-loop.</li>
<li>At line 12, there will be an error, since the <code>let</code> declaration means <code>discountedPrice</code> is only in the scope of the for-loop.</li>
<li>At line 13, the final value of <code>finalPrice</code> will be printed, since the <code>let</code> declaration means <code>finalPrice</code> is function-scoped.</li>
<li>The function will not return because of the errors in variable scope described above.</li>
<li>At line 11, there will be an error, since the <code>let</code> declaration means <code>i</code> is only in the scope of the for-loop.</li>
<li>At line 12, there will be an error, since the <code>const</code> declaration means <code>discountedPrice</code> is only in the scope of the for-loop.</li>
<li>At line 13, the initial value of <code>finalPrice</code> will be printed, since the <const>const</code> declaration means <code>finalPrice</code> is function-scoped and keeps its initial value.</li>
<li>The function will not return because of the errors in variable scope described above.</li>
<li>
    <li>student.name</li>
    <li>student["Grad Year"]</li>
</ol>