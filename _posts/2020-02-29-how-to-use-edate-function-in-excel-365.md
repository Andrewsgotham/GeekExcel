---
ID: 4170
post_title: How to use EDATE Function in Excel 365?
author: Merin
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-edate-function-in-excel-365/
published: true
post_date: 2020-02-29 14:00:35
---
<strong>EDATE Function in Excel:</strong> It is a <strong>Built-in Function</strong> in Excel. The<strong> EDATE Function</strong> adds or subtracts the specified number of months with the given date and returns the serial number that represents the result date in Excel.
<h2>Jump To:</h2>
<ul>
 	<li><a href="#edate-1"><strong>EDATE Function Syntax</strong></a></li>
 	<li><a href="#edate-2"><strong>EDATE Function with Practical Examples</strong></a></li>
 	<li><a href="#edate-3"><strong>A Quick Synopsis</strong></a></li>
</ul>
<h2 id="edate-1">EDATE Function Syntax:</h2>
<pre>=EDATE(start_date,month) 
</pre>
<strong>EDATE</strong> Function adds the specified month to the given start-date and returns the result date's serial number.

<strong>DATE Format: </strong>the Default Date Format in Excel is "<strong>MM/DD/YY</strong>".
<h2 id="edate-2">EDATE Function with Practical Examples:</h2>
Look at the below examples.
<h3>Example 1:</h3>
[caption id="attachment_4183" align="aligncenter" width="771"]<img class="size-full wp-image-4183" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_2-15.png" alt="EDATE Function Example 1" width="771" height="251" /> EDATE Function Example 1[/caption]

Let us assume a date 1 Jan 2019 and if you need to find the<strong> EDATE</strong> after 5 months and then you have to use the formula<strong> =EDATE("1/1/19",5) or EDATE(C6,5).</strong> It will print the serial number of the result date <strong>6/1/19.</strong>

To find the date of the output serial number and then use the formula <strong>=TEXT(cell, format)</strong>

For Example, <strong>=TEXT(E6,"m/d/y")</strong> It will display the date format of the serial number.

[caption id="attachment_4187" align="aligncenter" width="704"]<img class="size-full wp-image-4187" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_1-15.png" alt="EDATE Function Example 2" width="704" height="258" /> TEXT Function Example[/caption]
<h2>Example 2:</h2>
[caption id="attachment_4188" align="aligncenter" width="769"]<img class="size-full wp-image-4188" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_3-14.png" alt="EDATE Function Example 2" width="769" height="238" /> EDATE Function Example 2[/caption]

Here is the example to find the <strong>EDATE Function</strong> before<strong> 7 months</strong> from the given date<strong> 4 July 2019</strong> and then the EDATE function returns the serial number of the result date.
<h2 id="edate-3">A Quick Synopsis:</h2>
In this article, we have discussed the <strong>EDATE Function</strong> syntax, definition, and usage in Excel 365 with practical examples. Please leave your comments in case of any <strong>queries</strong> and share your <strong>suggestions</strong> in the comment box. Thank you for visiting our website <strong><a href="https://geekexcel.com/">GeekExcel</a></strong>.
<h2>Related articles:</h2>
<ul>
 	<li><strong><a href="https://geekexcel.com/how-to-use-datevalue-function-in-excel-365/">DATEVALUE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-day-function-in-excel-365/">DAY Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-date-function-in-microsoft-excel-365/">DATE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-hour-function-in-microsoft-excel-365/">HOUR Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/sum-function/">Sum Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-month-function-in-microsoft-excel-365/">Month Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-abs-function-in-microsoft-excel-365/">ABS Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-create-custom-add-function-in-excel-365/">Custom ADD Function</a></strong></li>
</ul>