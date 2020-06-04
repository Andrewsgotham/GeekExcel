---
ID: 4503
post_title: >
  How to use TIMEVALUE Function in
  Microsoft Excel 365?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-timevalue-function-in-microsoft-excel-365/
published: true
post_date: 2020-03-06 17:30:23
---
<h2>TIMEVALUE Function in Excel:</h2>
In this short tutorial, we will describe the definition, syntax, and usage of the <strong>TIMEVALUE function in Microsoft Excel 365</strong>.
<h2>Index:</h2>
<ul>
 	<li><a href="#1"><strong>TIMEVALUE function - Definition</strong></a></li>
 	<li><a href="#2"><strong>Fundamental Syntax of TIMEVALUE Function</strong></a></li>
 	<li><a href="#3"><strong>Practical Examples of TIMEVALUE Function</strong></a></li>
 	<li><a href="#4"><strong>A Short Summary</strong></a></li>
</ul>
<h2 id="1">TIMEVALUE function - Definition:</h2>
The <strong>TIMEVALUE Function</strong> in Excel is used to get the <strong>decimal fraction of time</strong>. It converts the given time into an actual Excel time. You can obtain the output as a numerical representation of the given time text. Numeric time values are more useful as they can be directly utilized with formulas.
<h2 id="2">Fundamental Syntax of TIMEVALUE Function:</h2>
The fundamental syntax of the TIMEVALUE function is,
<pre>=TIMEVALUE(time_text)</pre>
<h3>Argument Explanation:</h3>
<ul>
 	<li><strong>Time_text (Required): </strong>A text string denotes time in any Excel format.  It should be mentioned in quotation marks. For example, "1:00 PM" or "13:00".</li>
</ul>
Note:
<ul>
 	<li>If you give the text string as a date &amp; time combination, the date will be ignored.</li>
 	<li>Time values are a part of a date value and it is denoted by a decimal number (12:00 PM is denoted as 0.5 as it is half of a day).</li>
 	<li>#VALUE! error – It occurs, if you enter the value which is not a valid Excel time.</li>
</ul>
<h2 id="3">Practical Examples of TIMEVALUE Function:</h2>
Let's look at some examples of <b>TIMEVALUE function</b> and explore how to use it in Microsoft Excel.

<strong>Example 1: Returns the decimal part of a day, time only given</strong>
<ul>
 	<li>In the B5 cell, the following formula is entered to calculate the TIMEVALUE function.</li>
</ul>
<pre>=TIMEVALUE("1:00 PM")</pre>
[caption id="attachment_4506" align="aligncenter" width="580"]<img class="size-full wp-image-4506" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_1-23.png" alt="Example 1" width="580" height="314" /> Example 1[/caption]
<ul>
 	<li>Click Enter to display the output in the B5 cell.

[caption id="attachment_4507" align="aligncenter" width="581"]<img class="size-full wp-image-4507" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_2-20.png" alt="Example 1 - Output" width="581" height="308" /> Example 1 - Output[/caption]</li>
</ul>
<strong>Example 2: Returns the decimal part of a day, time and date given</strong>
<ul>
 	<li>In the B5 cell, the following formula is entered to calculate the TIMEVALUE function.</li>
</ul>
<pre>=TIMEVALUE("06-Mar-2020 4:00 AM")</pre>
[caption id="attachment_4508" align="aligncenter" width="580"]<img class="size-full wp-image-4508" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_3-20.png" alt="Example 2" width="580" height="314" /> Example 2[/caption]
<ul>
 	<li id="4">Click Enter to display the output in the B5 cell.

[caption id="attachment_4509" align="aligncenter" width="584"]<img class="size-full wp-image-4509" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_4-17.png" alt="Example 2 - Output" width="584" height="311" /> Example 2 - Output[/caption]</li>
 	<li>In this Example 2, as by default, the given date is ignored while calculating the TIMEVALUE Function.</li>
</ul>
<h2><strong>A Short Summary:</strong></h2>
In the above short article, we have described the usage of the <strong>TIMEVALUE function in Excel</strong> with relevant practical examples. Kindly share your valuable <strong>comments</strong> to keep us motivated all the time.

Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel!!</a></strong> Keep Learning!!
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a href="https://geekexcel.com/how-to-use-concatenate-function-in-microsoft-excel-365/">CONCATENATE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-year-function-in-excel-365/">YEAR Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-isoweeknum-function-in-microsoft-excel-365/">ISOWEEKNUM Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-workday-intl-function-in-excel-365/">WORKDAY.INTL Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-mid-function-in-microsoft-excel-365/">MID Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-days-function-in-excel-365/">DAYS Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-datedif-function-in-microsoft-excel-365/">DATEDIF Function in Excel</a></strong></li>
</ul>