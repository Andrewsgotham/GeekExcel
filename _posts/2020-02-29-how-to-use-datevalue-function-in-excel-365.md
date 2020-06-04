---
ID: 4122
post_title: >
  How to use DATEVALUE Function in Excel
  365?
author: Merin
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-datevalue-function-in-excel-365/
published: true
post_date: 2020-02-29 09:57:35
---
<strong>DATEVALUE Function:</strong> It is used to transform the Date represented in a string into the formal Excel Date and returns the serial number of the Date in Excel.
<h2>Jump To:</h2>
<ol>
 	<li><a href="#date-1"><strong>DATEVALUE Function Syntax</strong></a></li>
 	<li><a href="#date-2"><strong>DATEVALUE Function Practical Examples</strong></a></li>
 	<li><strong><a href="#date-3"> #VALUE Error in Excel</a></strong></li>
 	<li><a href="#date-4"><strong>A Quick Synopsis</strong></a></li>
</ol>
<h2 id="date-1">DATEVALUE Function Syntax:</h2>
<pre>=DATEVALUE("date-string")</pre>
The <strong>DATEVALUE</strong> function accepts the dates only in the <strong>string format </strong>and the date should be in the correct format as per the <strong>Excel rules.</strong> Otherwise, it shows you the <strong>#value error.  </strong>For example, <strong>=DATEVALUE("month/date/year")</strong> is an accepted date format in excel.

<strong>Date Format</strong>: The default system date format is <strong>MM/DD/YY. </strong>
<h2 id="date-2">DATEVALUE Function with Practical Examples:</h2>
Let's Evaluate the DATEVALUE Function with the following examples
<h3>Example 1:</h3>
Let's assume the date 19 Oct 2014.<strong> =DATEVALUE("10/19/2014")</strong> the DATEVALUE function accepts both the date formats.

[caption id="attachment_4128" align="aligncenter" width="702"]<img class="size-full wp-image-4128" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_4-10.png" alt="DATEVALUE Example 1" width="702" height="311" /> DATEVALUE Example 1[/caption]

The DATEVALUE function converts the string value and prints the serial number of the Date in Excel.
<h3>Example 2:</h3>
Let's assume the Date 16th October. <strong>=DATEVALUE("16 oct")</strong> otherwise <strong>=DATEVALUE("oct 16"). </strong>Both formats are correct.

[caption id="attachment_4129" align="aligncenter" width="722"]<img class="size-full wp-image-4129" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_1-12.png" alt="DATEVALUE Function Example 2" width="722" height="309" /> DATEVALUE Function Example 2[/caption]

It accepted the value and printed the serial number of the date.
<h2 id="date-3">#VALUE Error in Excel:</h2>
[caption id="attachment_4135" align="aligncenter" width="747"]<img class="size-full wp-image-4135" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_2-13.png" alt="#VALUE ERROR EXAMPLE 1" width="747" height="287" /> #VALUE ERROR EXAMPLE 1[/caption]

When you enter the Date format incorrectly in the DATEVALUE function it will return <strong>#VALUE error.</strong> You need to change the date into the correct format.

In the above example, <strong>30/03/1993</strong> is not the correct date format in Excel.<strong> 03/30/1993</strong> is the correct format of the date in Excel.

[caption id="attachment_4141" align="aligncenter" width="750"]<img class="size-full wp-image-4141" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_3-13.png" alt="#VALUE ERROR EXCEL 2" width="750" height="249" /> #VALUE ERROR EXCEL 2[/caption]

Here, Mar 30 1993 is not an accepted date format in Excel. 30 Mar 1993 is the correct format of the date in Excel.
<h2 id="date-4">A Quick Synopsis:</h2>
We hope this article gives you the complete tutorial on DATEVALUE Function syntax and usage on Excel 365. Stay Connected to get instant updates. Please leave a comment in case of any <strong>queries</strong> and leave your valuable <strong>suggestion</strong> in the comment section so that we can improve our services.
<h2>Related Articles:</h2>
<strong><a href="https://geekexcel.com/how-to-use-day-function-in-excel-365/">DAY Function in Excel</a></strong>

<strong><a href="https://geekexcel.com/how-to-use-date-function-in-microsoft-excel-365/">DATE Function in Excel</a></strong>

<strong><a href="https://geekexcel.com/how-to-use-today-function-in-excel-365/">TODAY Function in Excel</a></strong>