---
ID: 4433
post_title: >
  How to use YEARFRAC Function in
  Microsoft Excel 365?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-yearfrac-function-in-microsoft-excel-365/
published: true
post_date: 2020-03-06 10:05:43
---
<h2>YEARFRAC Function in Excel:</h2>
Here, we will discuss the description, basic syntax and usage of the <strong>YEARFRAC Function</strong> in MS Excel 365.
<h2>Jump To:</h2>
<ul>
 	<li><strong><a href="#1">YEARFRAC Function - Explanation</a></strong></li>
 	<li><strong><a href="#2">Basic Syntax of YEARFRAC Function</a></strong></li>
 	<li><strong><a href="#3">Examples of YEARFRAC Function</a></strong></li>
 	<li><strong><a href="#4">Verdict</a></strong></li>
</ul>
<h2 id="1"><strong>YEARFRAC function - Explanation:</strong></h2>
The <strong>YEARFRAC Function</strong> returns the fraction of the year by calculating the number of whole days between two dates. You can make use of this function to calculate age, determine the proportion of a whole year's obligations/benefits and more.
<h2 id="2"><strong>Basic Syntax of </strong><strong>YEARFRAC </strong><strong>Function:</strong></h2>
<pre>=YEARFRAC(start_date, end_date, [basis])</pre>
<h3><strong>Parameters Explanation:</strong></h3>
<ul>
 	<li><strong>Start date (Required): </strong>The start date to be used in the calculation.</li>
 	<li><strong>End date (Required): </strong>The end date to be used in the calculation.</li>
 	<li><strong>Basis (Optional): </strong>The kind of day count basis to use.</li>
</ul>
[su_table]
<table>
<tbody>
<tr>
<td><strong>Basis</strong></td>
<td><strong>Day count basis</strong></td>
</tr>
<tr>
<td>0 or omitted</td>
<td>US (NASD) 30/360</td>
</tr>
<tr>
<td>1</td>
<td>Actual/actual</td>
</tr>
<tr>
<td>2</td>
<td>Actual/360</td>
</tr>
<tr>
<td>3</td>
<td>Actual/365</td>
</tr>
<tr>
<td>4</td>
<td>European 30/360</td>
</tr>
</tbody>
</table>
[/su_table]
<h2 id="3"><strong>Examples of </strong><strong>YEARFRAC </strong><strong>Function</strong><strong>:</strong></h2>
Let's look at some examples of the <strong>YEARFRAC</strong><b> function</b> and explore how to use it in Microsoft Excel.

<strong>Example 1: Fraction of the year between two dates, excluding basis argument </strong>
<ul>
 	<li>Input values of start_date &amp; end_date are entered in B5 and D5 cells.</li>
 	<li>Then, you have to enter the below formula to display the output.</li>
</ul>
<pre>=YEARFRAC(B5,D5)</pre>
[caption id="attachment_4444" align="aligncenter" width="632"]<img class="size-full wp-image-4444" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_1-20.png" alt="Example 1" width="632" height="313" /> Example 1[/caption]
<ul>
 	<li>Click Enter to display the output in the F5 cell.</li>
</ul>
[caption id="attachment_4445" align="aligncenter" width="634"]<img class="size-full wp-image-4445" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_2-15.png" alt="Example 1 - Output" width="634" height="311" /> Example 1 - Output[/caption]
<ul>
 	<li>In the above example, two dates are given as input and the YEARFRAC function calculates the fraction by considering the number of whole days between the two dates.</li>
</ul>
<strong>Example 2: Fraction between two dates, using Actual/actual basis   </strong>
<ul>
 	<li>Input values of start_date &amp; end_date are entered in B5 and D5 cells.</li>
 	<li>Then, you have to enter the below formula to display the output.</li>
</ul>
<pre>=YEARFRAC(B5,D5,1)</pre>
[caption id="attachment_4446" align="aligncenter" width="632"]<img class="size-full wp-image-4446" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_3-17.png" alt="Example 2" width="632" height="312" /> Example 2[/caption]
<ul>
 	<li>Here, we have chosen argument 1 that is Actual/actual basis calculation.</li>
 	<li>Click Enter to display the output in the F5 cell.

[caption id="attachment_4447" align="aligncenter" width="634"]<img class="size-full wp-image-4447" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_4-14.png" alt="Example 2 - Output" width="634" height="313" /> Example 2 - Output[/caption]</li>
</ul>
<strong>Example 3: Fraction between two dates, using Actual/365 basis</strong>
<ul>
 	<li>Repeat the same steps as the above example in order to calculate the fraction between two dates.</li>
 	<li>Here, we have chosen the argument 3 that is Actual/365 basis calculation.

[caption id="attachment_4448" align="aligncenter" width="629"]<img class="size-full wp-image-4448" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_5-10.png" alt="Example 3" width="629" height="311" /> Example 3[/caption]</li>
</ul>
<h2 id="4"><strong style="font-size: 30.9985px;">Verdict:</strong></h2>
In the above short article, we have illustrated the definition, basic syntax, and usage of the <strong>YEARFRAC function</strong> with a few practical examples. If you have any <strong>queries/suggestions</strong>, kindly share it in the below comment box. Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel!!</a></strong> Keep Learning!!
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a href="https://geekexcel.com/how-to-use-workday-intl-function-in-excel-365/">WORKDAY.INTL Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-clean-function-in-microsoft-excel-365/">CLEAN Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-upper-function-in-microsoft-excel-365/">UPPER Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-eomonth-function-in-microsoft-excel-365/">EOMONTH Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-workday-function-in-excel-365/">WORKDAY Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-year-function-in-excel-365/">YEAR Function in Excel</a></strong></li>
 	<li><a href="https://geekexcel.com/how-to-use-mid-function-in-microsoft-excel-365/"><strong>MID Function in Excel</strong></a></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-networkdays-intl-function-in-ms-excel-365/">NETWORKDAYS.INTL Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-lower-function-in-microsoft-excel-365/">LOWER Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-now-function-in-microsoft-excel-365/">NOW Function in Excel</a></strong></li>
</ul>