---
ID: 4759
post_title: >
  How to use DOLLAR Function in Microsoft
  Excel 365?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-dollar-function-in-microsoft-excel-365/
published: true
post_date: 2020-03-10 16:33:25
---
<h2>DOLLAR Function in Excel:</h2>
Here, we will analyze the fundamental syntax and usage of the <strong>DOLLAR function</strong> in Microsoft Excel 365 with some examples.
<h2>Index:</h2>
<ul>
 	<li><a href="#1"><strong>Description of the DOLLAR Function</strong></a></li>
 	<li><a href="#2"><strong>Fundamental Syntax of DOLLAR Function</strong></a></li>
 	<li><a href="#3"><strong>Realistic Examples of DOLLAR Function</strong></a></li>
 	<li><a href="#4"><strong>Verdict</strong></a></li>
</ul>
<h2 id="1"><strong>Description of the DOLLAR Function:</strong></h2>
In Excel, <strong>DOLLAR Function</strong> is used to <strong>change a number into text</strong> with the use of currency number format. The DOLLAR Function utilizes the number format $#,##0.00_);($#,##0.00) and rounds the number to a specified number of decimal places.
<h2 id="2"><strong>Fundamental Syntax of DOLLAR Function:</strong></h2>
<pre>=DOLLAR(number, [decimals])</pre>
<h3>Argument Explanation:</h3>
<ul>
 	<li><strong>Number (Required): </strong>A number that you want to be converted to text.</li>
 	<li><strong>Decimals (Optional):</strong> It is the number of digits to the right of the decimal point. If you omit this argument, it takes 2 by default. If this argument is negative, the given number is rounded to the left of the decimal point.</li>
</ul>
<h2 id="3"><strong>Realistic Examples of DOLLAR Function:</strong></h2>
Let's focus on some examples of the <b>DOLLAR function</b> and explore how to use it in Microsoft Excel.

<strong>Example 1: To display in currency format, excluding decimal argument</strong>
<ul>
 	<li>The input value is entered into the <strong>B5</strong> cell.</li>
 	<li>Refer to the below syntax of the <strong>DOLLAR function</strong> to return the number in text format.</li>
</ul>
<pre>=DOLLAR(B5)</pre>
[caption id="attachment_4761" align="aligncenter" width="514"]<img class="size-full wp-image-4761" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_1-38.png" alt="Example 1" width="514" height="311" /> Example 1[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to execute the formula.</li>
 	<li>Now, the result is returned as output in the <strong>D5</strong> cell.

[caption id="attachment_4762" align="aligncenter" width="514"]<img class="size-full wp-image-4762" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_2-34.png" alt="Example 1 - Output" width="514" height="313" /> Example 1 - Output[/caption]</li>
 	<li>Here, in this example 1, we did not mention the decimals' argument so Excel takes 2 decimal places by default.</li>
</ul>
<strong>Example 2: To display in currency format, given decimal argument</strong>
<ul>
 	<li>The input value is entered into the <strong>B5</strong> cell.</li>
 	<li>Refer to the below syntax of the <strong>DOLLAR function</strong> to return the number in text format.</li>
</ul>
<pre>=DOLLAR(B5, 3)</pre>
[caption id="attachment_4763" align="aligncenter" width="512"]<img class="size-full wp-image-4763" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_3-32.png" alt="Example 2" width="512" height="311" /> Example 2[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to execute the formula.</li>
 	<li>Now, the result is returned as output in the <strong>D5</strong> cell.

[caption id="attachment_4764" align="aligncenter" width="530"]<img class="size-full wp-image-4764" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_4-29.png" alt="Example 2 - Output" width="530" height="311" /> Example 2 - Output[/caption]</li>
</ul>
<ul>
 	<li>In this example 2, we have given the decimals' argument value as 3 so it displays 3 values right to the decimal point of the given input.</li>
</ul>
<strong>Example 3: </strong>

Repeat the above steps in order to make use of the DOLLAR Function.

[caption id="attachment_4765" align="aligncenter" width="589"]<img class="size-full wp-image-4765" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_5-21.png" alt="Example 3" width="589" height="310" /> Example 3[/caption]

[caption id="attachment_4766" align="aligncenter" width="591"]<img class="size-full wp-image-4766" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_6-15.png" alt="Example 3" width="591" height="312" /> Example 3[/caption]

[caption id="attachment_4767" align="aligncenter" width="588"]<img class="size-full wp-image-4767" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_7-9.png" alt="Example 3" width="588" height="312" /> Example 3[/caption]
<h2 id="4"><strong>Verdic</strong><strong>t:</strong></h2>
We expect that this short tutorial helped you to make use of the <strong>DOLLAR Function</strong> in <strong>MS Excel 365</strong> efficiently. In addition, the practical examples let you understand the usage of the DOLLAR function even simpler. Keep us motivated by sharing your <strong>valuable feedback</strong> in the below comment section. Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel!!</a></strong> Keep learning with us!!
<h2>Related Articles:</h2>
<ul>
 	<li><a href="https://geekexcel.com/how-to-use-date-function-in-microsoft-excel-365/"><strong>DATE Function</strong></a></li>
 	<li><a href="https://geekexcel.com/how-to-use-days-function-in-excel-365/"><strong>DAYS Function</strong></a></li>
 	<li><a href="https://geekexcel.com/how-to-use-minute-function-in-excel-365/"><strong>MINUTE Function</strong></a></li>
</ul>