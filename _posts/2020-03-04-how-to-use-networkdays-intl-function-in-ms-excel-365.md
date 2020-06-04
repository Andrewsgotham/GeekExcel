---
ID: 4300
post_title: >
  How to use NETWORKDAYS.INTL Function in
  MS Excel 365?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-networkdays-intl-function-in-ms-excel-365/
published: true
post_date: 2020-03-04 16:14:18
---
<h2>NETWORKDAYS.INTL Function in Excel:</h2>
In this short tutorial, we will show how to use <strong>NETWORKDAYS.INTL Function</strong> in MS Excel 365 with few practical examples to make you understand clearly.
<h2>Jump To:</h2>
<ul>
 	<li><strong><a href="#netintl-1">NETWORKDAYS.INTL Function - Explanation</a></strong></li>
 	<li><strong><a href="#netintl-2">Know the syntax of NETWORKDAYS.INTL Function</a></strong></li>
 	<li><strong><a href="#netintl-3">Examples of NETWORKDAYS.INTL Function</a></strong></li>
 	<li><strong><a href="#netintl-4">A Short Synopsis</a></strong></li>
</ul>
<h2 id="netintl-1"><strong>NETWORKDAYS.INTL function - Explanation:</strong></h2>
The Excel <strong>NETWORKDAYS.INTL</strong> <strong>Function</strong> evaluates the <strong>number of working between two dates, excluding weekends and holidays</strong>. It gives a way to define which days of week need to be considered as weekends. This function will automatically exclude Saturdays and Sundays while calculating the number of working days if we omit the weekend parameter. Furthermore, you can also specify the dates of holidays so that it will be treated as non-working days and it will not be included in the result.
<h2 id="netintl-2"><strong>Know the syntax of NETWORKDAYS.INTL </strong><strong>Function:</strong></h2>
<pre>=NETWORKDAYS.INTL(start_date, end_date, [weekend], [holidays])</pre>
<h3><strong>Arguments Description:</strong></h3>
<ul>
 	<li><strong>Start date (Required): </strong>The start date to be used in the calculation.</li>
 	<li><strong>End date (Required): </strong>The end date to be used in the calculation.</li>
 	<li><strong>Weekend (Optional): </strong>This weekend argument can be in the format of numeric or string values. It is the days of the week to consider as weekend days so that it will exclude it in the calculation. If we omit this parameter, it will assume that weekends include Saturdays &amp; Sundays.</li>
</ul>
[su_table]
<table>
<tbody>
<tr>
<td><strong>Weekend number</strong></td>
<td><strong>Weekend days</strong></td>
</tr>
<tr>
<td>1 or omitted</td>
<td>Saturday, Sunday</td>
</tr>
<tr>
<td>2</td>
<td>Sunday and Monday</td>
</tr>
<tr>
<td>3</td>
<td>Monday and Tuesday</td>
</tr>
<tr>
<td>4</td>
<td>Tuesday and Wednesday</td>
</tr>
<tr>
<td>5</td>
<td>Wednesday and Thursday</td>
</tr>
<tr>
<td>6</td>
<td>Thursday and Friday</td>
</tr>
<tr>
<td>7</td>
<td>Friday and Saturday</td>
</tr>
<tr>
<td>11</td>
<td>Sunday</td>
</tr>
<tr>
<td>12</td>
<td>Monday</td>
</tr>
<tr>
<td>13</td>
<td>Tuesday</td>
</tr>
<tr>
<td>14</td>
<td>Wednesday</td>
</tr>
<tr>
<td>15</td>
<td>Thursday</td>
</tr>
<tr>
<td>16</td>
<td>Friday</td>
</tr>
<tr>
<td>17</td>
<td>Saturday</td>
</tr>
</tbody>
</table>
[/su_table]

The string values of the weekend are seven characters long which must be either 0 or 1. Each character in the string points out a day of the week, beginning with Monday.
<ul>
 	<li>1 represents a non-workday (weekend).</li>
 	<li>0 represents a workday.</li>
 	<li>1111111 - returns 0.</li>
</ul>
For example, 0100010 denotes the weekend that is Tuesday &amp; Saturday.
<ul>
 	<li><strong>Holidays (Optional): </strong>It is the list of holidays to exclude from calculation.</li>
</ul>
<h2 id="netintl-3"><strong>Examples of NETWORKDAYS.INTL </strong><strong>Function:</strong></h2>
Let's look at some practical examples of <strong>NETWORKDAYS.INTL </strong><b>function</b> and explore how to use it in Microsoft Excel.

<strong>Example 1: Number of working days calculation by giving start_date and end_date</strong>
<ul>
 	<li>Input values of start_date &amp; end_date are entered in B5 and D5 cells.</li>
 	<li>Then, you have to enter the below formula to display the output of the number of working days.</li>
</ul>
<pre>=NETWORKDAYS.INTL(B5,D5)</pre>
[caption id="attachment_4323" align="aligncenter" width="704"]<img class="size-full wp-image-4323" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_1-11.png" alt="NETWORKDAYS.INTL Function Excel" width="704" height="313" /> NETWORKDAYS.INTL Function Excel[/caption]
<ul>
 	<li>Click Enter to display the output in the F5 cell.

[caption id="attachment_4324" align="aligncenter" width="627"]<img class="size-full wp-image-4324" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_2-7.png" alt="Example 1 - Output" width="627" height="313" /> Example 1 - Output[/caption]</li>
 	<li>In total, February comprised of 29 days. Excel omitted Saturdays &amp; Sundays of February that is 9 days from 20 days and returned the output as 20 number of working days.</li>
 	<li>In this example, we did not mention the weekends &amp; holidays argument. Therefore, Excel by default considered the Saturdays &amp; Sundays as weekends and it is omitted in the calculation.</li>
</ul>
<strong>Example 2: Number of working days calculation excluding weekends. </strong>
<ul>
 	<li>Input values of start_date, end_date &amp; weekends are entered in B5, D5, and F5 cells.</li>
 	<li>Then, you have to enter the below formula to display the number of working days by excluding weekends.</li>
</ul>
<pre>=NETWORKDAYS(B5,D5,F5)</pre>
[caption id="attachment_4327" align="aligncenter" width="828"]<img class="size-full wp-image-4327" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_3-8.png" alt="Example 2" width="828" height="335" /> Example 2[/caption]
<ul>
 	<li>Click Enter to display the output in the H5 cell.</li>
</ul>
[caption id="attachment_4328" align="aligncenter" width="751"]<img class="size-full wp-image-4328" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_4-8.png" alt="Example 2 - Output" width="751" height="336" /> Example 2 - Output[/caption]
<ul>
 	<li>In this example, we have mentioned the weekend number as 6 that denotes Thursday &amp; Friday weekend days so it will be excluded in the calculation. In February, there are 8 days that are 4 Thursdays &amp; 4 Fridays so that it is not included in workdays.</li>
</ul>
<strong>Example 3: Weekend as a string value</strong>
<ul>
 	<li>Repeat the above steps in order to calculate the number of working days by excluding weekends. In this example, we are giving the weekend as a string value so that you can also understand this way clearly.</li>
 	<li>The weekend string value is given as 1010100 so Monday, Wednesday, Friday will be excluded in the calculation.

[caption id="attachment_4337" align="aligncenter" width="754"]<img class="size-full wp-image-4337" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_5-7.png" alt="Example 3" width="754" height="312" /> Example 3[/caption]

[caption id="attachment_4338" align="aligncenter" width="647"]<img class="size-full wp-image-4338" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_6-2.png" alt="Example 3 - Output" width="647" height="310" /> Example 3 - Output[/caption]</li>
</ul>
<p id="netintl-4"><strong>Example 4: Working days calculation by excluding weekends &amp; holidays</strong></p>
You have to follow the steps as same as the previous examples so it will produce the output.

[caption id="attachment_4339" align="aligncenter" width="1024"]<img class="size-full wp-image-4339" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_7-2.png" alt="Example 4" width="1024" height="335" /> Example 4[/caption]

[caption id="attachment_4340" align="aligncenter" width="950"]<img class="size-full wp-image-4340" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_8-1.png" alt="Example 4 - Output" width="950" height="318" /> Example 4 - Output[/caption]
<h2><strong>A Short Synopsis:</strong></h2>
In the above short article, we have described the explanation, syntax, and usage of the <strong>NETWORKDAYS.INTL</strong> <strong>function</strong> with a few real examples. If you have any <strong>queries/suggestions</strong>, kindly share it in the below comment box. Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel!!</a></strong> Keep Learning!!
<h2>Related Articles:</h2>
<ul>
 	<li><a href="https://geekexcel.com/how-to-use-month-function-in-microsoft-excel-365/"><strong>MONTH Function in Excel</strong></a></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-second-function-in-microsoft-excel-365/">SECOND Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-year-function-in-excel-365/">YEAR Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-abs-function-in-microsoft-excel-365/">ABS Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-hour-function-in-microsoft-excel-365/">HOUR Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-datedif-function-in-microsoft-excel-365/">DATEDIF Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-datevalue-function-in-excel-365/">DATEVALUE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-code-function-in-microsoft-excel-365/">CODE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-now-function-in-microsoft-excel-365/">NOW Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-workday-function-in-excel-365/">WORKDAY Function in Excel</a></strong></li>
</ul>