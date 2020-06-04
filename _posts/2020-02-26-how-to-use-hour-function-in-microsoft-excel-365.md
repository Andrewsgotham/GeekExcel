---
ID: 4068
post_title: >
  How to use HOUR Function in Microsoft
  Excel 365?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-hour-function-in-microsoft-excel-365/
published: true
post_date: 2020-02-26 17:30:32
---
<h2>HOUR Function in Excel:</h2>
In this short tutorial, we will discuss the syntax and usage of the HOUR Function in Microsoft Excel 365.
<h2>Table of Contents:</h2>
<ul>
 	<li><a href="#hour-1"><strong>HOUR Function - Description</strong></a></li>
 	<li><a href="#hour-2"><strong>Basic Syntax of HOUR Function</strong></a></li>
 	<li><a href="#hour-3"><strong>Realistic Examples of HOUR Function</strong></a></li>
 	<li><a href="#hour-4"><strong>A Short Synopsis</strong></a></li>
</ul>
<h2 id="hour-1">HOUR Function - Description:</h2>
The <strong>HOUR function</strong> returns the <strong>hour of time value </strong>as a number between <strong>0 (12.00 AM) to 23 (11.00 PM)</strong>. Using this HOUR function, you can extract the hour value to feed or insert it into any cell/formula.
<h2 id="hour-2">Basic Syntax of HOUR Function:</h2>
<pre>=HOUR(serial_number)</pre>
<h3>Argument Explanation:</h3>
Serial Number: The value that comprises the hour that you need as output. The values may be as decimal numbers, strings within quotation marks or as results of other functions/formula.
<h2 id="hour-3">Realistic Examples of HOUR Function:</h2>
Let's look at some examples of <b>HOUR function</b> and explore how to use it in Microsoft Excel.

<strong>Example 1: Returns hour value from the current date and time. </strong>
<ul>
 	<li>The input value is entered into the C6 cell.</li>
 	<li>Refer the below syntax of HOUR function for returning the hour value as output.</li>
</ul>
<pre>=HOUR(C6)</pre>
[caption id="attachment_4074" align="aligncenter" width="628"]<img class="size-full wp-image-4074" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_1-9.png" alt="HOUR Function in MS Excel" width="628" height="311" /> HOUR Function in MS Excel[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to execute the formula.</li>
 	<li>Now, the result is returned as output in the E6 cell.

[caption id="attachment_4075" align="alignnone" width="628"]<img class="size-full wp-image-4075" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_2-10.png" alt="Example 1 - Output" width="628" height="312" /> Example 1 - Output[/caption]</li>
</ul>
<strong>Example 2: Returns hour value from a decimal number</strong>

You have to repeat the above steps in order to make use of the HOUR function in Excel.
<ul>
 	<li>In this example, we illustrated how the HOUR function will display the output for the decimal number input.</li>
 	<li>The input value is entered as 0.25 in the C6 cell. Now, the Excel will calculate 25% of 24 hours and return the hour component as output in the E6 cell.</li>
</ul>
[caption id="attachment_4084" align="alignnone" width="589"]<img class="size-full wp-image-4084" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_3-9.png" alt="Example 2 - Output" width="589" height="312" /> Example 2 - Output[/caption]

<strong>Example 3:</strong>
<ul>
 	<li>The Excel will return the output as 0 for the input 12:00 AM and the current date without time.

[caption id="attachment_4085" align="aligncenter" width="592"]<img class="size-full wp-image-4085" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_4-8.png" alt="Example 3 - Output" width="592" height="360" /> Example 3 - Output[/caption]</li>
</ul>
<h2>A Short Synopsis:</h2>
We hope that this short tutorial assisted you to make use of <strong>HOUR Function</strong> in MS Excel effectively. Furthermore, the examples let you understand the usage of the HOUR function clearly. If you find this article helpful, kindly share your valuable <strong>comments/queries</strong> in the below comment box.