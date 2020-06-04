---
ID: 4422
post_title: >
  How to use ISOWEEKNUM Function in
  Microsoft Excel 365?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-isoweeknum-function-in-microsoft-excel-365/
published: true
post_date: 2020-03-05 16:47:54
---
<h2>ISOWEEKNUM Function in Excel:</h2>
This article explains the definition of <strong>ISOWEEKNUM Function</strong> in <strong>MS Excel 365</strong>. Further, we have described the usage of this function with practical examples. This function will work well in Windows 8, 8.1 and 10. We assure that you will be well-versed about the <strong>ISOWEEKNUM Function</strong> at the end of this tutorial.
<h2>Table of Contents:</h2>
<ul>
 	<li><a href="#1"><strong>ISOWEEKNUM Function - Description</strong></a></li>
 	<li><a href="#2"><strong>Fundamental Syntax of ISOWEEKNUM Function</strong></a></li>
 	<li><a href="#3"><strong>Realistic Examples</strong></a></li>
 	<li><a href="#4"><strong>Summary</strong></a></li>
</ul>
<h2 id="1"><strong>ISOWEEKNUM Function</strong> - Description:</h2>
The <strong>ISOWEEKNUM Function</strong> in Excel is used to find out the <strong>ISO week number of the year</strong> from the given date. This Excel function will return a number between 1 to 52, specifying in which week the given date falls.
<h2 id="2">Fundamental Syntax of <strong>ISOWEEKNUM Function</strong>:</h2>
The fundamental syntax of Excel <strong>ISOWEEKNUM Function</strong> is,
<pre>=ISOWEEKNUM(date)</pre>
<h3>Argument Explanation:</h3>
<ul>
 	<li><strong>Date: </strong>The date from which you want to get the ISO week number.</li>
</ul>
<strong>Note:</strong>

1) MS Excel stores the dates as sequential numbers and so it can be utilized in calculations. By default,
<ul>
 	<li style="text-align: left;">January 1, 1900 - serial number 1</li>
 	<li style="text-align: left;">January 1, 2008 - serial number 39448 (because it is 39,448 days after Jan 1, 1900)</li>
</ul>
2) #NUM! error - if the date argument is not a valid number, then the function returns this error.

3) #VALUE! error - if the date argument is not a valid date type, then the function returns this error.
<h2 id="3">Realistic Examples:</h2>
Let's look at some practical examples of <strong>ISOWEEKNUM Function</strong> and explore how to use it in Microsoft Excel.

<strong>Example 1: </strong>
<ul>
 	<li>The input value is entered into the B5 cell.</li>
 	<li>Using the below formula ISOWEEKNUM value is calculated.</li>
</ul>
<pre>=ISOWEEKNUM(B5)</pre>
[caption id="attachment_4434" align="aligncenter" width="495"]<img class="size-full wp-image-4434" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_1-19.png" alt="Example 1" width="495" height="289" /> Example 1[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to execute the formula.</li>
 	<li>Now, the result is returned as output in the D5 cell.

[caption id="attachment_4435" align="aligncenter" width="494"]<img class="size-full wp-image-4435" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_2-14.png" alt="Example 1 - Output" width="494" height="286" /> Example 1 - Output[/caption]</li>
 	<li>By default, this function will take Monday as the start of the week. It will give values from 1 to 53 for the weeks present in a year.</li>
 	<li>30/12/2019 (Monday) to 05/01/2020 (Sunday) - Serial Number 1. So, after that week starts from Monday, this function starts to give serial number 2. Therefore, in this example, 03/05/2020 returns the result as 10.</li>
</ul>
<strong>Example 2: </strong>

The above steps need to be repeated for this example so it will display the below output.

[caption id="attachment_4436" align="aligncenter" width="513"]<img class="size-full wp-image-4436" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_3-16.png" alt="Example 2 " width="513" height="311" /> Example 2[/caption]
<h2 id="4">Summary:</h2>
We hope that this tutorial explained to you clearly about the use of <strong>ISOWEEKNUM Function</strong> in Excel with detailed practical examples. If you have any <strong>queries/doubts</strong>, kindly share it in the below comment section. Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel!!</a></strong> Keep Learning!!
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a href="https://geekexcel.com/how-to-use-concatenate-function-in-microsoft-excel-365/">CONCATENATE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-clean-function-in-microsoft-excel-365/">CLEAN Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-left-function-in-microsoft-excel-365/">LEFT Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-workday-intl-function-in-excel-365/">WORKDAY.INTL Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-edate-function-in-excel-365/">EDATE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-upper-function-in-microsoft-excel-365/">UPPER Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-days360-function-in-excel/">DAYS 360 Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-time-function-in-excel-365/">TIME Function in Excel</a></strong></li>
</ul>