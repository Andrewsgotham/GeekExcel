---
ID: 3926
post_title: >
  How to find Average using Aggregate
  function?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-find-average-using-aggregate-function/
published: true
post_date: 2020-02-21 14:11:21
---
<h2>Aggregate Function in Excel:</h2>
The <strong>Aggregate function</strong> in Excel performs an aggregate of a database value or list.  We have described the explanation, basic syntax with examples of Aggregate function in MS Excel 365. <span style="font-size: 19px;">With the use of Aggregate function, we can get the output as we want. In general, Excel returns an error if you use the Average function to find the average of values or list with errors. But, it is possible to find the average of a list with errors using the Aggregate function.  In this tutorial, we will discuss the Aggregate syntax and how to calculate the <strong>Average</strong> by using the <strong>Aggregate function</strong> easily. </span>
<h2>Index:</h2>
<ul>
 	<li><a href="#1"><strong>Aggregate Function - Explanation</strong></a></li>
 	<li><a href="#2"><strong>Basic Syntax of Aggregate Function</strong></a></li>
 	<li><a href="#3"><strong>Practical Examples</strong></a></li>
 	<li><a href="#4"><strong>A Short Synopsis</strong></a></li>
</ul>
<h2 id="1">Aggregate Function - Explanation:</h2>
Aggregate Function returns the result of the aggregate in a list or database of values. It comprises multiple math functions<span style="font-size: 19px;"> such as Average, Max, Min, Count, etc., along with the specific options to ignore error values and hidden rows. A total of 19 functions with dissimilar options are available in the Aggregate function. </span>
<h2 id="2">Basic Syntax of Aggregate Function:</h2>
There are two syntaxes for the Aggregate function:

[caption id="attachment_3948" align="aligncenter" width="573"]<img class="size-full wp-image-3948" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_3-3.png" alt="Aggregate Function Syntax" width="573" height="310" /> Aggregate Function Syntax[/caption]
<h3>Array Form:</h3>
<pre>=AGGREGATE(function_num, options, array, [k])</pre>
<h3>Reference Form:</h3>
<pre>=AGGREGATE(function_num, options, ref1, [ref2], …)</pre>
<h3>Arguments Description:</h3>
<ul>
 	<li><strong>Function_num: </strong>It is a number from 1 to 19. It depends on which function you want to use it for the data calculation in the below-mentioned list.</li>
</ul>
[su_table]
<table>
<tbody>
<tr>
<td><strong>S.No</strong></td>
<td><strong>Functions</strong></td>
</tr>
<tr>
<td>1</td>
<td>AVERAGE</td>
</tr>
<tr>
<td>2</td>
<td>COUNT</td>
</tr>
<tr>
<td>3</td>
<td>COUNTA</td>
</tr>
<tr>
<td>4</td>
<td>MAX</td>
</tr>
<tr>
<td>5</td>
<td>MIN</td>
</tr>
<tr>
<td>6</td>
<td>STDEV.S</td>
</tr>
<tr>
<td>7</td>
<td>STDEV.P</td>
</tr>
<tr>
<td>8</td>
<td><a href="https://geekexcel.com/sum-function/">SUM</a></td>
</tr>
<tr>
<td>9</td>
<td>VAR.S</td>
</tr>
<tr>
<td>10</td>
<td>VAR.P</td>
</tr>
<tr>
<td>11</td>
<td>MEDIAN</td>
</tr>
<tr>
<td>12</td>
<td>MODE.SNGL</td>
</tr>
<tr>
<td>13</td>
<td>LARGE</td>
</tr>
<tr>
<td>14</td>
<td>SMALL</td>
</tr>
<tr>
<td>15</td>
<td>PERCENTILE.INC</td>
</tr>
<tr>
<td>16</td>
<td>PRODUCT</td>
</tr>
<tr>
<td>17</td>
<td>QUARTILE.INC</td>
</tr>
<tr>
<td>18</td>
<td>PERCENTILE.EXC</td>
</tr>
<tr>
<td>19</td>
<td>QUARTILE.EXC</td>
</tr>
</tbody>
</table>
[/su_table]
<ul>
 	<li><strong>Options: </strong>It is a number from 0 to 7.  It is a numeric value that identifies which values to ignore in the specific function.</li>
</ul>
[su_table]
<table>
<tbody>
<tr>
<td><strong>Number Code</strong></td>
<td><strong>Functions</strong></td>
</tr>
<tr>
<td>0</td>
<td>Ignore nested SUBTOTAL and AGGREGATE functions</td>
</tr>
<tr>
<td>1</td>
<td>Ignore nested SUBTOTAL, AGGREGATE functions, and hidden rows</td>
</tr>
<tr>
<td>2</td>
<td>Ignore nested SUBTOTAL, AGGREGATE functions, and error values</td>
</tr>
<tr>
<td>3</td>
<td>Ignore nested SUBTOTAL, AGGREGATE functions, hidden rows &amp; error values</td>
</tr>
<tr>
<td>4</td>
<td>Ignore nothing</td>
</tr>
<tr>
<td>5</td>
<td>Ignore hidden rows</td>
</tr>
<tr>
<td>6</td>
<td>Ignore error values</td>
</tr>
<tr>
<td>7</td>
<td><span style="font-size: 19px; background-color: #ffffff;">Ignore hidden rows and error values</span></td>
</tr>
</tbody>
</table>
[/su_table]
<ul>
 	<li><strong>Ref 1:</strong> It is a reference to a cell range for which you want the aggregate value.</li>
 	<li><strong>Ref 2:</strong> It is a second reference argument that is required for the particular functions mentioned below.</li>
</ul>
<ol>
 	<li>LARGE(array,k)</li>
 	<li>SMALL(array,k)</li>
 	<li>PERCENTILE.INC(array,k)</li>
 	<li>QUARTILE.INC(array, quart)</li>
 	<li>PERCENTILE.EXC(array,k)</li>
 	<li>QUARTILE.EXC(array, quart)</li>
</ol>
<h2 id="3">Realistic Examples:</h2>
Let's look at some practical examples of <strong>Average</strong> calculation by using <strong>Aggregate function</strong> and explore how to use it in Microsoft Excel.

<strong>Example 1: Average of two numbers </strong>
<ul>
 	<li>The input values are entered in two data tables.</li>
 	<li>You have to type <strong>=AGGREGATE(</strong> and then you have to choose the Average function which is numbered as <strong>1</strong>.</li>
</ul>
[caption id="attachment_3951" align="aligncenter" width="728"]<img class="size-full wp-image-3951" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_1-4.png" alt="Choose Average" width="728" height="456" /> Choose Average[/caption]
<ul>
 	<li>After that, you have to select the option which you want to perform it in the calculation. Here, we have chosen the option 4 - Ignore nothing.</li>
</ul>
[caption id="" align="aligncenter" width="1033"]<img class="size-full wp-image-3952" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_2-4.png" alt="Select the Option" width="1033" height="432" /> Select the Option[/caption]
<ul>
 	<li><span style="font-size: 19px;">Using the below formula average of two numbers is calculated using the Aggregate function.</span></li>
</ul>
<pre>=AGGREGATE(1,4,B4:C4)</pre>
[caption id="attachment_3953" align="aligncenter" width="649"]<img class="size-full wp-image-3953" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_4-4.png" alt="Aggregate Function - Average" width="649" height="312" /> Aggregate Function - Average[/caption]
<ul>
 	<li>Now, click <strong>Enter</strong> to execute the formula.</li>
</ul>
Finally, the result is returned as output in the E4 cell.

[caption id="attachment_3954" align="aligncenter" width="573"]<img class="size-full wp-image-3954" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_5-2.png" alt="Example 1 - Output" width="573" height="312" /> Example 1 - Output[/caption]

<strong>Example 2: Average of N values </strong>

The above steps need to be repeated for this example so it will display the below output.
<ul>
 	<li><span style="font-size: 19px;">Using the below formula average of 8 values is calculated using the Aggregate function.</span></li>
</ul>
<pre>=AGGREGATE(1,4,B4:C4)</pre>
[caption id="attachment_3955" align="aligncenter" width="660"]<img class="size-full wp-image-3955" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_6-3.png" alt="Aggregate Function - Average" width="660" height="384" /> Aggregate Function - Average[/caption]

[caption id="attachment_3956" align="aligncenter" width="582"]<img class="size-full wp-image-3956" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_7-3.png" alt="Example 2 - Output" width="582" height="385" /> Example 2 - Output[/caption]
<h2 id="4">A Short Synopsis:</h2>
In the above article, we have described the use of <strong>Aggregate function</strong> in Excel for the calculation of <strong>Average</strong> with clear-cut practical examples. Kindly share your valuable comments/feedbacks to keep us motivated.