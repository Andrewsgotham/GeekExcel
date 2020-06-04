---
ID: 4241
post_title: >
  How to use EOMONTH Function in Microsoft
  Excel 365?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-eomonth-function-in-microsoft-excel-365/
published: true
post_date: 2020-03-03 12:25:49
---
<h2>EOMONTH Function in Excel:</h2>
This article describes the explanation, fundamental syntax, and usage of the <strong>EOMONTH function</strong> in Microsoft Excel 365.
<h2>Jump To:</h2>
<ul>
 	<li><a href="#eomonth-1"><strong>Explanation of EOMONTH Function</strong></a></li>
 	<li><a href="#eomonth-2"><strong>Fundamental Syntax of EOMONTH Function</strong></a></li>
 	<li><a href="#eomonth-3"><strong>EOMONTH Function - Practical Examples</strong></a></li>
 	<li><a href="#eomonth-4"><strong>A Brief Synopsis</strong></a></li>
</ul>
<h2 id="eomonth-1"><strong>Explanation of EOMONTH Function:</strong></h2>
The MS Excel <strong>EOMONTH Function </strong>returns the last day of the month after adding/subtracting a specified number of months to a date. This function is useful while we are calculating due dates, maturity dates and accounts payable/receivable that fall on the last day of the month.
<h2 id="eomonth-2"><strong>Basic Syntax of EOMONTH Function:</strong></h2>
<pre>=EOMONTH(start_date,months)</pre>
<h3><strong>Argument Description:</strong></h3>
<ol>
 	<li><strong>Start_date (Required): </strong>The start date to be used in the calculation.</li>
 	<li><strong>Months (Required):</strong> The number of months before/after start_date.</li>
</ol>
<ul>
 	<li style="text-align: left;">    Positive (+) value - To get a date in the future.</li>
 	<li>    Negative (-) value - To get a date in the past.</li>
</ul>
<h2 id="eomonth-3"><strong>EOMONTH Function - Practical Examples:</strong></h2>
Let's look at some examples of <strong>EO</strong><b>MONTH function</b> and explore how it works in Microsoft Excel.

<strong>Example 1: Returns last day of the month, one month after the given date </strong>
<ul>
 	<li>The input value is entered in the C4 cell.</li>
 	<li>Then, we have entered the below formula in order to display the last day of the month, one month after the date in the C4 cell.</li>
</ul>
<pre>=EOMONTH(C4,1)</pre>
[caption id="attachment_4252" align="aligncenter" width="655"]<img class="size-full wp-image-4252" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_1-3.png" alt="EOMONTH function in Excel" width="655" height="313" /> EOMONTH function in Excel[/caption]
<ul>
 	<li>Now, we have to click enter to show the output in the E4 cell.

[caption id="attachment_4253" align="aligncenter" width="655"]<img class="size-full wp-image-4253" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_2-2.png" alt="Example 1 - Output" width="655" height="314" /> Example 1 - Output[/caption]</li>
</ul>
<strong>Example 2: Returns last day of the month, five months before the given date </strong>
<ul>
 	<li>The input value is entered in the C4 cell.</li>
 	<li>Then, we have entered the below formula in order to display the last day of the month, five months before the date in the C4 cell.</li>
</ul>
<pre>=EOMONTH(C4,-5)</pre>
[caption id="attachment_4254" align="aligncenter" width="653"]<img class="size-full wp-image-4254" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_3-3.png" alt="Example 2" width="653" height="316" /> Example 2[/caption]
<ul>
 	<li>Click Enter to display the output in the E4 cell.

[caption id="attachment_4255" align="aligncenter" width="654"]<img class="size-full wp-image-4255" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_4-2.png" alt="Example 2 - Output" width="654" height="310" /> Example 2 - Output[/caption]</li>
</ul>
<strong>Example 3: </strong>
<ul>
 	<li>Repeat the above steps in order to calculate the last day of the month. You can directly enter the value in months argument or else you can give the months value in a separate column and then select the cell value as like below example.</li>
 	<li>If you give 0 in months argument, it will just display the last day of the given start_date.

[caption id="attachment_4256" align="aligncenter" width="609"]<img class="size-full wp-image-4256" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_5-2.png" alt="Example 3" width="609" height="336" /> Example 3[/caption]</li>
</ul>
<h2 id="eomonth-4"><strong>A Brief Synopsis:</strong></h2>
In the above short article, we have described the explanation, basic syntax, and usage of the <strong>EO</strong><b>MONTH </b>function with a few practical examples. Drop your valuable <strong>queries/feedback</strong> in the below comment section. Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel!!</a></strong> Keep Learning with us!!
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a href="https://geekexcel.com/how-to-use-today-function-in-excel-365/">TODAY Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-asin-function-in-microsoft-excel-365/">ASIN Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-abs-function-in-microsoft-excel-365/">ABS Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-days-function-in-excel-365/">DAYS Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-edate-function-in-excel-365/">EDATE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-networkdays-function-in-ms-excel-365/">NETWORKDAYS Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-year-function-in-excel-365/">YEAR Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-hour-function-in-microsoft-excel-365/">HOUR Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/sum-function/">SUM Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-minute-function-in-excel-365/">MINUTE Function in Excel</a></strong></li>
</ul>