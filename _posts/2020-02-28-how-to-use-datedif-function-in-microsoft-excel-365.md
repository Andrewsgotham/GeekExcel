---
ID: 4125
post_title: >
  How to use DATEDIF Function in Microsoft
  Excel 365?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-datedif-function-in-microsoft-excel-365/
published: true
post_date: 2020-02-28 17:23:51
---
<h2>DATEDIF Function in Excel:</h2>
In this short tutorial, we will discuss the definition, syntax, and usage of the <strong>DATEDIF function</strong> in Microsoft Excel 365.
<h2>Jump To:</h2>
<ul>
 	<li><a href="#datedif-1"><strong>DATEDIF function - Description</strong></a></li>
 	<li><a href="#datedif-2"><strong>Fundamental Syntax of DATEDIF Function</strong></a></li>
 	<li><a href="#datedif-3"><strong>Realistic Examples of DATEDIF Function</strong></a></li>
 	<li><a href="#datedif-4"><strong>Verdict</strong></a></li>
</ul>
<h2 id="datedif-1"><strong>DATEDIF Function - Description:</strong></h2>
The <strong>DATEDIF function</strong> returns the calculated <strong>difference between the two dates</strong>. If you want to evaluate the <strong>number of days, months or years</strong> between two dates, then this is the function you will be needed in Excel. It returns the output as a numerical value that indicates the number of days/months/years.
<h2 id="datedif-2"><strong>Fundamental Syntax of DATEDIF Function:</strong></h2>
<pre>=DATEDIF(start_date,end_date,unit)</pre>
<h3><strong>Arguments Explanation:</strong></h3>
<ul>
 	<li><strong>Start date: </strong>Initial date of the given period.</li>
 	<li><strong>End date: </strong>End date of the given period.</li>
 	<li><strong>Unit: </strong>The type of value that you want as output. You can mention the unit either in the lower/upper case. It is important that you have to enter the unit within the quotations or else it will display #NAME? error. Refer to the table below to know each unit and its result.</li>
</ul>
[su_table]
<table>
<tbody>
<tr>
<td><strong>Unit</strong></td>
<td><strong>Result</strong></td>
</tr>
<tr>
<td>"Y"</td>
<td>The difference in complete years</td>
</tr>
<tr>
<td>"M"</td>
<td>The difference in complete months</td>
</tr>
<tr>
<td>"D"</td>
<td>Difference in days</td>
</tr>
<tr>
<td>"MD"</td>
<td>Difference between the days, ignoring months &amp; years</td>
</tr>
<tr>
<td>"YM"</td>
<td>Difference between the months, ignoring days &amp; years</td>
</tr>
<tr>
<td>"YD"</td>
<td>Difference between the days, ignoring years</td>
</tr>
</tbody>
</table>
[/su_table]
<h3>Note:</h3>
<ul>
 	<li><strong>#NUM! Error:</strong>  If start_date is greater than end_date, then you will be displayed with this error.</li>
</ul>
<h2 id="datedif-3"><strong>Realistic Examples of DATEDIF Function:</strong></h2>
Let's look at some examples of <b>DATEDIF function</b> and explore how to use it in Microsoft Excel.

<strong>Example 1: Number of years between two dates</strong>
<ul>
 	<li>Input values of start_date &amp; end_date are entered in C5 and E5 cells.</li>
 	<li>Then, you have to enter the below formula to display the output of difference in years.</li>
</ul>
<pre>=DATEDIF(C5,E5,"Y")</pre>
[caption id="attachment_4133" align="aligncenter" width="754"]<img class="size-full wp-image-4133" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_4-11.png" alt="DATEDIF function in Excel" width="754" height="310" /> DATEDIF Function in Excel[/caption]
<ul>
 	<li>Click Enter to display the output in the G5 cell.

[caption id="attachment_4134" align="aligncenter" width="754"]<img class="size-full wp-image-4134" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_1-13.png" alt="Example 1 - Output" width="754" height="314" /> Example 1 - Output[/caption]</li>
</ul>
<strong>Example 2: Number of days between two dates</strong>
<ul>
 	<li>Input values of start_date &amp; end_date are entered in C5 and E5 cells.</li>
 	<li>Then, you have to enter the below formula to display the output of the difference in days (Note: Unit can be mentioned either in the lower/upper case).</li>
</ul>
<pre>=DATEDIF(C5,E5,"d")</pre>
[caption id="attachment_4136" align="aligncenter" width="753"]<img class="size-full wp-image-4136" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_2-14.png" alt="Example 2" width="753" height="311" /> Example 2[/caption]
<ul>
 	<li>Click Enter to display the output in the G5 cell.

[caption id="attachment_4137" align="aligncenter" width="753"]<img class="size-full wp-image-4137" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_3-12.png" alt="Example 2 - Output" width="753" height="312" /> Example 2 - Output[/caption]</li>
</ul>
<strong>Example 3: Difference between the months by ignoring days &amp; years.  </strong>
<ul>
 	<li>Repeat the above steps in order to calculate the difference between the months by ignoring days and years.

[caption id="attachment_4142" align="aligncenter" width="754"]<img class="size-full wp-image-4142" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_5-6.png" alt="Example 3" width="754" height="311" /> Example 3[/caption]

[caption id="attachment_4143" align="aligncenter" width="754"]<img class="size-full wp-image-4143" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_6-9.png" alt="Example 3 - Output" width="754" height="313" /> Example 3 - Output[/caption]</li>
</ul>
<h2 id="datedif-4"><strong>Verdict:</strong></h2>
In the above short article, we have illustrated the definition, basic syntax, and usage of the <b>DATEDIF </b>function with a few practical examples. If you have any <strong>queries/suggestions</strong>, kindly share it in the below comment box.
<h2>Related Articles:</h2>
<ul>
 	<li><a href="https://geekexcel.com/how-to-use-now-function-in-microsoft-excel-365/">NOW Function in Excel</a></li>
</ul>