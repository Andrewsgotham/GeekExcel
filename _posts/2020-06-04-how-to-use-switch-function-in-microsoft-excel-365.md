---
ID: 7560
post_title: >
  How to use SWITCH Function in Microsoft
  Excel 365?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-switch-function-in-microsoft-excel-365/
published: true
post_date: 2020-06-04 10:18:34
---
<h2>SWITCH Function in Excel:</h2>
This article describes the explanation, basic syntax, and usage of the <strong>SWITCH function</strong> in Microsoft Excel 365.
<h2>Jump To:</h2>
<ul>
 	<li><a href="#1"><strong>Explanation of SWITCH Function</strong></a></li>
 	<li><a href="#2"><strong>SWITCH Function - </strong></a><strong><a href="#month-2">Basic Syntax</a></strong></li>
 	<li><a href="#3"><strong>Practical Examples of </strong></a><strong><a href="#month-3">SWITCH Function</a></strong></li>
 	<li><a href="#4"><strong>A Brief Synopsis</strong></a></li>
</ul>
<h2 id="1"><strong>Explanation of SWITCH Function:</strong></h2>
The <strong>SWITCH function</strong> will <strong>compare one value or expression</strong> against a list of values and returns the output corresponding to the first matching value. This function takes an optional default value when no match is found.
<h2 id="2"><strong>SWITCH Function - </strong><strong>Basic Syntax:</strong></h2>
<pre>=SWITCH(expression, value1, result1, [default_or_value2, result2],…</pre>
<h3><strong>Argument Description:</strong></h3>
<ul>
 	<li><strong>Expression (Required)</strong> - It is the value or expression (number, text, or date) that you want to match against the values.</li>
 	<li><strong>Value1..126 (Required)</strong> - It is a value that will be compared against expression.</li>
 	<li><strong>Result1..126 (Required)</strong> - Result to be displayed when the corresponding value matches the expression.</li>
</ul>
<strong>Note:</strong> You can use up to 126 pairs of arguments (value and result) because the functions are limited to 254 arguments.
<h2 id="3"><strong>Practical Examples of SWITCH Function:</strong></h2>
Let's look at some examples of this function and explore how it works in Microsoft Excel.

<strong>Example 1: </strong>
<ul>
 	<li>The two columns of inputs are entered in the cells from B4 to B7 and C4 to C7.</li>
 	<li>Now, we are going to compare the expression with the values in the column (Pin) to get the result in the column (State).</li>
 	<li>In this example, we have compared the <strong>c4 cell</strong> with the value 23. If it matches, it should show the result as Ohio. You have to give the text values within the double quotation or else it will display the error.</li>
 	<li>We have to enter the below formula in order to acquire the result.</li>
</ul>
<pre>=SWITCH(C4,23,"Ohio")</pre>
[caption id="attachment_7567" align="aligncenter" width="576"]<img class="size-full wp-image-7567" src="https://geekexcel.com/wp-content/uploads/2020/06/sw1.png" alt="Example 1" width="576" height="361" /> Example 1[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to view the result in the <strong>D4 cell</strong>.

[caption id="attachment_7568" align="aligncenter" width="497"]<img class="size-full wp-image-7568" src="https://geekexcel.com/wp-content/uploads/2020/06/sw2.png" alt="Example 1 - Output" width="497" height="314" /> Example 1 - Output[/caption]</li>
</ul>
<strong>Example 2:</strong>
<ul>
 	<li>In this example, we have compared the <strong>c6 cell</strong> with the value 91. If it matches, it should show the result as Utah. If it does not match, it should show the given default value (Unknown).</li>
 	<li>We have to enter the below formula in order to acquire the result.</li>
</ul>
<pre>=SWITCH(C6,91,"Utah","Unknown")</pre>
[caption id="attachment_7570" align="aligncenter" width="574"]<img class="size-full wp-image-7570" src="https://geekexcel.com/wp-content/uploads/2020/06/sw3.png" alt="Example 2" width="574" height="335" /> Example 2[/caption]
<ul>
 	<li>Now, we have to click <strong>Enter</strong> to show the output in the <strong>D6 cell</strong>.

[caption id="attachment_7571" align="aligncenter" width="496"]<img class="size-full wp-image-7571" src="https://geekexcel.com/wp-content/uploads/2020/06/sw4.png" alt="Example 2 - Output" width="496" height="311" /> Example 2 - Output[/caption]</li>
</ul>
<h2 id="4"><strong>Verdict:</strong></h2>
In the above short article, we have described the explanation, basic syntax, and usage of the <strong>SWITCH</strong> <strong>function</strong> with the examples. Drop your valuable <strong>queries/feedback</strong> in the below comment section.

Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel!!</a></strong> Keep Learning with us!!
<h2>Related Articles:</h2>
<ul>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/use-info-function-in-microsoft-excel-365-simple-methods/" target="_blank" rel="noopener noreferrer">Use INFO Function in Microsoft Excel 365- Simple methods!!</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/how-to-use-iserror-function-in-microsoft-excel-365/" target="_blank" rel="noopener noreferrer">How to use ISERROR Function in Microsoft Excel 365?</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/use-hlookup-function-in-microsoft-excel-365-in-easy-ways/" target="_blank" rel="noopener noreferrer">Use HLOOKUP Function in Microsoft Excel 365 In Easy Ways!!</a></li>
</ul>