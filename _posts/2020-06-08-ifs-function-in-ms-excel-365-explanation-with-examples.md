---
ID: 7695
post_title: 'IFS Function in MS Excel 365 &#8211; Explanation with Examples!!'
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/ifs-function-in-ms-excel-365-explanation-with-examples/
published: true
post_date: 2020-06-08 11:36:38
---
<h2>IFS Function in Excel:</h2>
This article describes the explanation, basic syntax, and usage of the <strong>IFS function</strong> in Microsoft Excel 365.
<h2>Jump To:</h2>
<ul>
 	<li><a href="#1"><strong>Explanation of IFS Function</strong></a></li>
 	<li><a href="#2"><strong>IFS Function - </strong></a><strong><a href="#month-2">Basic Syntax</a></strong></li>
 	<li><a href="#3"><strong>Practical Examples of </strong></a><strong><a href="#month-3">IFS Function</a></strong></li>
 	<li><a href="#4"><strong>A Brief Synopsis</strong></a></li>
</ul>
<h2 id="1"><strong>Explanation of IFS Function:</strong></h2>
The <strong>IFS Function</strong> in Excel is categorized as a logical function. It <strong>checks multiple conditions and returns a value corresponding to the first TRUE result</strong>. Unlike the <strong><a href="https://geekexcel.com/use-if-function-in-microsoft-excel-365-simple-steps/">IF function</a></strong>, IFS lets you test more than one condition without nesting.
<h2 id="2"><strong>IFS Function - </strong><strong>Basic Syntax:</strong></h2>
<pre>=IFS(logical_test1, value_if_true1, ...)</pre>
<h3><strong>Argument Description:</strong></h3>
<ul>
 	<li><strong>logical_test1 (Required) - </strong>First logical result that evaluates to TRUE or FALSE.</li>
 	<li><strong>value_if_true1 (Required) - </strong>The result to be displayed if logical_test1 is true. If required, it can be empty.</li>
 	<li><strong>logical_test2...127 (Optional) - </strong>Condition that evaluates to TRUE or FALSE.</li>
 	<li><strong>value_if_true1..127 (Optional) - </strong>The result to be displayed if logical_testN is true. If required, it can be empty.</li>
</ul>
<strong>Note: </strong>This function allows the user to use 126 pairs of arguments (logical_test and value_if_true) because the functions are limited to 256 arguments.
<h2 id="3"><strong>Practical Examples of IFS Function:</strong></h2>
Let's look at some examples of this function and explore how it works in Microsoft Excel.

<strong>Example 1: Single Condition</strong>
<ul>
 	<li>In this example, we have entered the list of products from B4 to B7.</li>
 	<li>Here, we are going to check a single condition, if the cell B4 is equal to "Acer", it has to display the result as "Laptop".</li>
 	<li>We have to enter the below formula in order to acquire the result.</li>
</ul>
<pre>=IFS(B4="Acer", "Laptop")</pre>
[caption id="attachment_7709" align="aligncenter" width="573"]<img class="size-full wp-image-7709" src="https://geekexcel.com/wp-content/uploads/2020/06/ifs1.png" alt="Example 1" width="573" height="311" /> Example 1[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to view the result in the <strong>D4 cell</strong>.</li>
</ul>
<strong>Example 2: Multiple Conditions</strong>
<ul>
 	<li>In this example, we are going to check multiple conditions, if the cell B5 is equal to "iPhone", it has to display the result as "Mobile".</li>
 	<li>To check the cell with multiple conditions, we have to enter the below formula.</li>
</ul>
<pre>=IFS(B5="Dell", "Laptop", B5="Acer", "Laptop", B5="iPhone", "Mobile")</pre>
[caption id="attachment_7717" align="aligncenter" width="879"]<img class="size-full wp-image-7717" src="https://geekexcel.com/wp-content/uploads/2020/06/ifs3.png" alt="Example 2" width="879" height="385" /> Example 2[/caption]
<ul>
 	<li>Now, we have to click <strong>Enter</strong> to show the output in the <strong>D5 cell</strong>.</li>
</ul>
[caption id="attachment_7718" align="aligncenter" width="496"]<img class="size-full wp-image-7718" src="https://geekexcel.com/wp-content/uploads/2020/06/ifs4.png" alt="Example 2 - Output" width="496" height="312" /> Example 2 - Output[/caption]

<strong>Example 3: Adding an ELSE condition</strong>
<ul>
 	<li>In the previous example, we learned that we can use multiple conditions in the IFS function. When the given condition is TRUE, it will display the corresponding result.</li>
 	<li>But, if none of the conditions are TRUE, it will return #N/A error as you can see below.</li>
</ul>
<pre>=IFS(B7="Acer", "Laptop", B7="iPhone", "Mobile")</pre>
[caption id="attachment_7724" align="aligncenter" width="725"]<img class="size-full wp-image-7724" src="https://geekexcel.com/wp-content/uploads/2020/06/ifs5.png" alt="Example 3" width="725" height="336" /> Example 3[/caption]
<ul>
 	<li>Now, we have to click <strong>Enter</strong> to show the output in the <strong>D7 cell</strong>.

[caption id="attachment_7725" align="aligncenter" width="494"]<img class="size-full wp-image-7725" src="https://geekexcel.com/wp-content/uploads/2020/06/ifs6.png" alt="Example 3 - Output" width="494" height="311" /> Example 3 - Output[/caption]</li>
 	<li>To get rid of #N/A error, we have to add one more condition at the end of the formula as below.</li>
</ul>
<pre>=IFS(B7="Acer", "Laptop", B7="iPhone", "Mobile", TRUE, "Not Categorized")</pre>
[caption id="attachment_7729" align="aligncenter" width="851"]<img class="size-full wp-image-7729" src="https://geekexcel.com/wp-content/uploads/2020/06/ifs7.png" alt="Example 3 - Else Condition" width="851" height="360" /> Example 3 - Else Condition[/caption]
<ul>
 	<li>We have added [TRUE, "Not Categorized"] so if none of the given conditions are TRUE, it will return the value as "Not Categorized".

[caption id="attachment_7730" align="aligncenter" width="545"]<img class="size-full wp-image-7730" src="https://geekexcel.com/wp-content/uploads/2020/06/ifs8.png" alt="Example 3 - Output" width="545" height="312" /> Example 3 - Output[/caption]</li>
</ul>
<h2 id="4"><strong>A Brief Synopsis:</strong></h2>
In the above short article, we have described the explanation, basic syntax, and usage of the <strong>IFS</strong> <strong>function</strong> with the examples. Drop your valuable <strong>queries/feedback</strong> in the below comment section. Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel</a></strong> Keep Learning with us!!
<h2>Related Articles:</h2>
<ul>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/how-to-use-find-function-in-microsoft-excel-365/" target="_blank" rel="noopener noreferrer">How to use FIND Function in Microsoft Excel 365?</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/how-to-use-iserror-function-in-microsoft-excel-365/" target="_blank" rel="noopener noreferrer">How to use ISERROR Function in Microsoft Excel 365?</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/how-to-use-isnumber-function-in-microsoft-excel-365/" target="_blank" rel="noopener noreferrer">How to Use ISNUMBER Function in Microsoft Excel 365?</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/use-true-function-in-microsoft-excel-365-simple-methods/" target="_blank" rel="noopener noreferrer">Use TRUE Function in Microsoft Excel 365 -Simple methods!!</a></li>
</ul>