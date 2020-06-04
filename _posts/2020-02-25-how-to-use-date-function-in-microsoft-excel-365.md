---
ID: 4053
post_title: >
  How to use DATE Function in Microsoft
  Excel 365?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-date-function-in-microsoft-excel-365/
published: true
post_date: 2020-02-25 13:42:09
---
<h2>DATE Function in Excel:</h2>
In this article, we will discuss the definition, syntax, and usage of the DATE function in Microsoft Excel 365.
<h2>Index:</h2>
<ul>
 	<li><a href="#date-1"><strong>DATE function - Explanation</strong></a></li>
 	<li><a href="#date-2"><strong>Basic Syntax of DATE Function</strong></a></li>
 	<li><a href="#date-3"><strong>Example of DATE Function</strong></a></li>
 	<li><a href="#date-4"><strong>Verdict</strong></a></li>
</ul>
<h2 id="date-1"><strong>DATE function - Explanation:</strong></h2>
The <strong>DATE</strong> function in Excel combines three different values and returns it as a date. If you enter individual year, month and date in separate cells, it will merge it to produce a date as an output.
<h2 id="date-2"><strong>Basic Syntax of DATE Function:</strong></h2>
<pre>=DATE(year,month,day)</pre>
<h3><strong>Arguments Explanation:</strong></h3>
<ul>
 	<li><strong>Year: </strong>The <strong>year</strong> value needs to be in four digits to prevent unwanted outputs (for example, if you enter 02, it could mean "1902", "2002").</li>
 	<li><strong>Month: </strong>The <strong>month</strong> of the year can be a positive or negative integer from 1 to 12 (January to December).</li>
 	<li><strong>Day: </strong>The day of the month can be a positive or negative integer from 1 to 31.</li>
</ul>
<h2 id="date-3"><strong>Example of DATE Function:</strong></h2>
Let's look at some examples of <b>DATE function</b> and explore how to use it in Microsoft Excel.

<strong>Example: Combining three values to display in date format </strong>
<ul>
 	<li>Input values are entered in C5, D5, and E5 cells for the year, month and date columns.</li>
 	<li>Next, you have to enter the below formula for displaying the output in the date format. You can type the cell value one by one directly in the formula or else you can click the input cell so that it will display the cell value in the formula.</li>
</ul>
<pre>=DATE(C5,D5,E5)</pre>
[caption id="attachment_4055" align="aligncenter" width="761"]<img class="size-full wp-image-4055" src="https://geekexcel.com/wp-content/uploads/2020/02/date-formula.png" alt="DATE function in Excel" width="761" height="355" /> DATE function in Excel[/caption]
<ul>
 	<li>Click Enter to display the output in the G5 cell.

[caption id="attachment_4056" align="aligncenter" width="759"]<img class="wp-image-4056 size-full" src="https://geekexcel.com/wp-content/uploads/2020/02/date-output.png" alt="Example - Output" width="759" height="360" /> Example - Output[/caption]</li>
</ul>
<h2 id="date-4"><strong>Verdict:</strong></h2>
In the above article, we have illustrated the definition, basic syntax, and usage of the <b>DATE </b>function with an example. If you have any <strong>queries/suggestions</strong>, kindly share it in the below comment section.