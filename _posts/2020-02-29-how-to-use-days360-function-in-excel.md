---
ID: 4157
post_title: How to use DAYS360 Function in Excel?
author: Merin
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-days360-function-in-excel/
published: true
post_date: 2020-02-29 14:00:29
---
<strong>DAYS360 Function:</strong> It is an <strong>Excel Built-in Function. </strong>Used to find the number of days between the two dates but based on the<strong> 360 days calculation </strong>and returns the number of days between the two dates. This means the<strong> DAYS360 Function</strong> consider as <strong>360 days per year and every month have only 30 days.</strong>
<h2>Jump To:</h2>
<ul>
 	<li><a href="#days-1"><strong>DAYS360 Function Syntax</strong></a></li>
 	<li><a href="#days-2"><strong>DAYS360 Function with Practical Examples</strong></a></li>
 	<li><a href="#days-3"><strong>A Quick Synopsis</strong></a></li>
</ul>
<h2 id="days-1">DAYS360 Function Syntax:</h2>
<pre>=DAYS360(start-date, end-date, method[optional]) 
</pre>
The first argument is the start date and the second argument is the end date the <strong>method</strong> argument is optional a <strong>logical value</strong> for calculations.

The DAYS360 Function's third argument is the method argument it is an optional argument and consists of boolean value TRUE or FALSE. Used to define the type of day.

&nbsp;

<strong>FALSE</strong> - (<strong>default method in DAYS360 Function</strong>) - US method. If the start date is the last day of the month, the FALSE method will set to the 30th day of the same month. If the end date is the last day of the month, then it will check whether the start date &lt; 30 or not if the start date is &lt;30 then the end date is set to the 1st of the next month, otherwise, the end date is set to the 30th of the same month.

<strong>TRUE</strong> - European method. In this method, the last day of the Start date and end date are set to the 30th of the same month
<h2 id="days-2">DAYS360 with Practical Examples:</h2>
Let us evaluate the DAYS360 with the following Examples
<h2>Example 1:</h2>
[caption id="attachment_4158" align="aligncenter" width="687"]<img class="size-full wp-image-4158" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_5-7.png" alt="DAYS360 Example 1" width="687" height="257" /> DAYS360 Example 1[/caption]

In the above example, the DAYS360 function returns the number of days <strong>1923 </strong> for the dates between 19 Oct 2014 to 29 Feb 2020 as per the <strong>360 days calculations. </strong>
<h2>Example 2:</h2>
[caption id="attachment_4180" align="aligncenter" width="730"]<img class="size-full wp-image-4180" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_5-8.png" alt="DAYS360 Example 2" width="730" height="250" /> DAYS360 Example 2[/caption]

Take a glance at the above example the DAYS360 function calculates the number of days between 1 Oct 2014 and 1 Dec 2014 and prints <strong>60</strong>.
<h2 id="days-3">A Quick Synopsis:</h2>
We hope this article gives you the complete tutorial on the DAYS360 Function in Excel. Leave your Queries/Suggestions in the comment section. Stay connected to get instant updates. Thank you for visiting our website <strong><a href="https://geekexcel.com/">GeekExcel</a></strong>.
<h2>Related Articles :</h2>
<ol>
 	<li><a href="https://geekexcel.com/how-to-use-datevalue-function-in-excel-365/"><strong>DATEVALUE Function in Excel</strong></a></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-hour-function-in-microsoft-excel-365/">HOUR Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-second-function-in-microsoft-excel-365/">SECOND Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-minute-function-in-excel-365/">MINUTE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-day-function-in-excel-365/">DAY Function in Excel</a></strong></li>
 	<li><a href="https://geekexcel.com/how-to-find-average-using-aggregate-function/"><strong>Average Function in Excel</strong></a></li>
 	<li><a href="https://geekexcel.com/how-to-use-abs-function-in-microsoft-excel-365/"><strong>ABS Function in Excel</strong></a></li>
 	<li><a href="https://geekexcel.com/how-to-use-date-function-in-microsoft-excel-365/"><strong>DATE Function in Excel</strong></a></li>
 	<li><a href="https://geekexcel.com/how-to-use-today-function-in-excel-365/"><strong>TODAY Function in Excel</strong></a></li>
</ol>