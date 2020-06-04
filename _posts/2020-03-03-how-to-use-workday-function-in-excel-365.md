---
ID: 4258
post_title: >
  How to use WORKDAY Function in Excel
  365?
author: Merin
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-workday-function-in-excel-365/
published: true
post_date: 2020-03-03 15:52:44
---
<strong>WORKDAY Function:</strong> It is a Built-in Function in Excel used to calculate the <strong>proximate working day</strong> based on the value we provide and returns a number that represents the date. This Function mostly useful to calculate the delivery dates, shipping dates, event completion date, etc.
<h2>Jump To:</h2>
<ul>
 	<li><a href="#work-1"><strong>WORKDAY Function Syntax</strong></a></li>
 	<li><a href="#work-2"><strong>WORKDAY Function with Examples</strong></a></li>
 	<li><a href="#work-3"><strong>A Quick Synopsis</strong></a></li>
</ul>
<h2 id="work-1">WORKDAY Function Syntax:</h2>
<pre> =WORKDAY(Start_date,days,[holiday])</pre>
<strong>Start_Date: </strong>The starting date.

<strong>Days: </strong>Number of <strong>non-weekend</strong> and <strong>non-working</strong> days before or after the start date.

<strong>Holiday: </strong>Number of Holidays in date format. It is an <strong>optional argument.</strong>

The <strong>WORKDAY Function</strong> considers the <strong>Saturday</strong> and <strong>Sunday</strong> as <strong>non-working days. </strong>The WORKDAY Function <strong>excludes</strong> the <strong>holidays</strong> and <strong>non-working days</strong> and calculates the proximate working day.
<h2 id="work-2">WORKDAY Function with Examples:</h2>
Let's evaluate the <strong>WORKDAY</strong> Function with the following examples
<h3>Example 1:</h3>
Let us assume that, we are ordering a product online. Now, we can calculate the estimated arrival date of the product.

[caption id="attachment_4279" align="aligncenter" width="874"]<img class="size-full wp-image-4279" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_1-7.png" alt="WORKDAY Function Example 1" width="874" height="326" /> WORKDAY Function Example 1[/caption]

In the above example, the order date is<strong> 25th Mar 2020</strong> and the product will arrive within <strong>7 working days </strong>from the start date, and we have specified the holidays for the <strong>March</strong> month. <strong>=WORKDAY(C4,D4,C9:C11)</strong> Function <strong>excludes</strong> the <strong>non-working</strong> days, <strong>holidays</strong> and returns the arrival date after <strong>7</strong> working days as <strong>6</strong><strong>th Apr 2020.</strong>
<h3>Example 2:</h3>
[caption id="attachment_4280" align="aligncenter" width="873"]<img class="size-full wp-image-4280" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_2-3.png" alt="WORKDAY Function Example 2" width="873" height="335" /> WORKDAY Function Example 2[/caption]

In this example, the order date is<strong> 7th Mar 2020</strong> and the arrival days is <strong>20</strong> working days from the start date. Now, <strong>=WORKDAY(C5,D5,C9:C11) Function </strong>returns the estimated arrival date after 7 days as <strong>7</strong><strong>th Apr 2020.</strong>
<h3>Example 3:</h3>
[caption id="attachment_4268" align="alignnone" width="937"]<img class="wp-image-4268 size-full" style="font-size: 19px; font-weight: 600;" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_4-3.png" alt="WORKDAY Function Example 3" width="937" height="338" /> WORKDAY Function Example 3[/caption]

The <strong>WORKDAY</strong> Function can calculate the previous working day from the given start date. For example, the start date is <strong>31st Mar 2020</strong> and the number of working days is<strong>-10 (before the start date). </strong>The <strong>WORKDAY</strong> function will calculate the working day before 10 days from the starting date.

<strong>=WORKDAYS(C7,D7,C9:C11) </strong>prints the workday as<strong> 16th Mar 2020.</strong>
<h2 id="work-3">A Quick Synopsis:</h2>
We hope this article gives you the complete tutorial about <strong>WORKDAY</strong> Function syntax, definition, and usage in Excel 365.  We have explained the <strong>WORKDAY</strong> Function with related examples. Please comment your <strong>queries</strong> and share your <strong>suggestions</strong> in the comment section. Stay connected to get instant updates. Thank you for visiting our website <strong><a href="https://geekexcel.com/">GeekExcel</a></strong>
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a href="https://geekexcel.com/how-to-create-custom-add-function-in-excel-365/">Custom ADD Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-today-function-in-excel-365/">TODAY Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-networkdays-function-in-ms-excel-365/">NETWORKDAYS Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-date-function-in-microsoft-excel-365/">DATE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-eomonth-function-in-microsoft-excel-365/">EOMONTH Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-datevalue-function-in-excel-365/">DATEVALUE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-second-function-in-microsoft-excel-365/">SECOND Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-hour-function-in-microsoft-excel-365/">HOUR Function in Excel</a></strong></li>
</ul>