---
ID: 4926
post_title: >
  How to use TEXT Function in Microsoft
  Excel 365?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-text-function-in-microsoft-excel-365/
published: true
post_date: 2020-03-13 11:07:01
---
<h2>TEXT Function in Excel:</h2>
In this short tutorial, we will discuss the explanation, syntax, and usage of the <strong>TEXT function</strong> in Microsoft Excel 365.
<h2>Jump To:</h2>
<ul>
 	<li><a href="#1"><strong>Explanation of TEXT Function</strong></a></li>
 	<li><a href="#2"><strong>TEXT Function - Basic Syntax</strong></a></li>
 	<li><a href="#3"><strong>Practical Examples of TEXT Function</strong></a></li>
 	<li><a href="#4"><strong>A Brief Summary</strong></a></li>
</ul>
<h2 id="1"><strong>Explanation of TEXT Function</strong>:</h2>
The <strong>TEXT Function</strong> in Excel <strong>converts a number to text in the given format</strong>. If you want to combine numbers with symbols/ text, or you want to display numbers in a more readable format, then this function will be useful in those situations.
<h2 id="2"><strong>TEXT Function - Basic Syntax</strong>:</h2>
The fundamental syntax of <strong>TEXT </strong><strong>Function</strong> is,
<pre>=TEXT(value, format_text)</pre>
<h3>Argument Description:</h3>
<ul>
 	<li><strong>Value: </strong>A number that you want to convert into text.</li>
 	<li><strong>Format_text: </strong>The format that you want to apply to the given value.</li>
</ul>
<h2 id="3">Practical Examples of TEXT Function:</h2>
Let's look at some practical examples of <strong>TEXT Function</strong> and explore how to use it in Microsoft Excel.

<strong>Example 1: </strong>
<ul>
 	<li>In this basic example, we would like to convert the date to "d mmmm, yyyy" format.</li>
 	<li>The input value is entered into the <strong>B5</strong> cell.</li>
 	<li>Refer to the below syntax of the <strong>TEXT function</strong> to return the output in the given format.</li>
</ul>
<pre>=TEXT(B5, "d mmmm, yyyy")</pre>
[caption id="attachment_4934" align="aligncenter" width="629"]<img class="size-full wp-image-4934" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_1-47.png" alt="Example 1" width="629" height="312" /> Example 1[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to execute the formula.</li>
 	<li>Now, the result is returned as output in the <strong>D5</strong> cell.

[caption id="attachment_4935" align="aligncenter" width="630"]<img class="size-full wp-image-4935" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_2-43.png" alt="Example 1 - Output" width="630" height="313" /> Example 1 - Output[/caption]</li>
</ul>
<strong>Example 2:</strong>

We all know that Excel will remove any zeros added before the numbers automatically.  But, if we need to keep those zeros then we have to make use of the TEXT function. Let's see this example 2 to understand it clearly.
<ul>
 	<li>In the input column, we have entered the 10-digit bar code '0000123456' in the <strong>B7</strong> cell, but Excel removed the zeros immediately.</li>
 	<li>We can make use of the TEXT function as shown below in order to convert the bar code into a 10-digit number.

[caption id="attachment_4938" align="aligncenter" width="649"]<img class="size-full wp-image-4938" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_3-42.png" alt="Example 2" width="649" height="386" /> Example 2<span style="font-size: 19px;"> </span>[/caption]</li>
 	<li>Click <strong>Enter</strong> to execute the formula.</li>
 	<li>Now, the result is returned as output in the <strong>D7</strong> cell.

[caption id="attachment_4939" align="aligncenter" width="645"]<img class="size-full wp-image-4939" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_4-34.png" alt="Example 2 - Output" width="645" height="359" /> Example 2 - Output[/caption]</li>
 	<li>We can make use of the TEXT function to change the format of the value. Here, we just explained the two different examples to make you understand the basic usage of the TEXT function.</li>
</ul>
<h2 id="4">A Brief Summary:</h2>
In this short tutorial, we have illustrated how to use <strong>TEXT Function</strong> in Excel with clear-cut practical examples. If you have any <strong>queries/doubts</strong>, kindly share it in the below comment section. Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel!!</a></strong> Keep Learning With Us!!
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a href="https://geekexcel.com/how-to-use-mid-function-in-microsoft-excel-365/">MID Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-isoweeknum-function-in-microsoft-excel-365/">ISOWEEKNUM Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-timevalue-function-in-microsoft-excel-365/">TIMEVALUE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-code-function-in-microsoft-excel-365/">CODE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-right-function-in-microsoft-excel-365/">RIGHT Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-find-function-in-microsoft-excel-365/">FIND Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-time-function-in-excel-365/">TIME Function in Excel</a></strong></li>
</ul>