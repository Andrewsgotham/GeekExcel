---
ID: 4642
post_title: >
  How to use WEEKNUM Function in Microsoft
  Excel 365?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-weeknum-function-in-microsoft-excel-365/
published: true
post_date: 2020-03-09 17:21:31
---
<h2>WEEKNUM Function in Excel:</h2>
In this short tutorial, we will discuss the explanation, syntax, and usage of the <strong>WEEKNUM function</strong> in Microsoft Excel 365.
<h2>Jump To:</h2>
<ul>
 	<li><a href="#1"><strong>Explanation of WEEKNUM Function</strong></a></li>
 	<li><a href="#2"><strong>WEEKNUM Function - Basic Syntax</strong></a></li>
 	<li><a href="#3"><strong>Practical Examples of WEEKNUM Function</strong></a></li>
 	<li><a href="#4"><strong>A Brief Summary</strong></a></li>
</ul>
<h2 id="1"><strong>Explanation of WEEKNUM Function</strong>:</h2>
The <strong>WEEKNUM Function</strong> in Excel takes the date as an input and <strong>returns the week number (1 to 54)</strong>. This function will start to count the week from January 1. Make use of this function to calculate how many weeks we have been crossed since from January 1 to the present date.
<h2 id="2"><strong>WEEKNUM Function - Basic Syntax</strong>:</h2>
The fundamental syntax of <strong>WEEKNUM Function</strong> is,
<pre>=WEEKNUM(serial_number, [return_type])</pre>
<h3>Argument Description:</h3>
<ul>
 	<li><strong>Serial_number (Required):</strong> The date for which you need to get the week number.</li>
 	<li><strong>Return_type (Optional): </strong>A number that identifies the return value type.</li>
</ul>
[su_table]
<table>
<tbody>
<tr>
<td><strong>Return_type</strong></td>
<td><strong>Week Starts on</strong></td>
<td><strong>System</strong></td>
</tr>
<tr>
<td>1 or omitted</td>
<td>Sunday</td>
<td>1</td>
</tr>
<tr>
<td>2</td>
<td>Monday</td>
<td>1</td>
</tr>
<tr>
<td>11</td>
<td>Monday</td>
<td>1</td>
</tr>
<tr>
<td>12</td>
<td>Tuesday</td>
<td>1</td>
</tr>
<tr>
<td>13</td>
<td>Wednesday</td>
<td>1</td>
</tr>
<tr>
<td>14</td>
<td>Thursday</td>
<td>1</td>
</tr>
<tr>
<td>15</td>
<td>Friday</td>
<td>1</td>
</tr>
<tr>
<td>16</td>
<td>Saturday</td>
<td>1</td>
</tr>
<tr>
<td>17</td>
<td>Sunday</td>
<td>1</td>
</tr>
<tr>
<td>21</td>
<td>Monday</td>
<td>2</td>
</tr>
</tbody>
</table>
[/su_table]
<ul>
 	<li><strong>System 1: </strong>The first week of the year is considered from January 1 and it is numbered as week 1.</li>
 	<li><strong>System 2: </strong>The first week of the year is considered from the first Thursday of the year and it is numbered as week 1. This kind of system is mentioned in ISO 8601 and also referred to as the European week numbering system.</li>
</ul>
<strong>Note:</strong>

1) MS Excel stores the dates as sequential numbers and so it can be utilized in calculations. By default,
<ul>
 	<li style="text-align: left;">January 1, 1900 - serial number 1</li>
 	<li style="text-align: left;">January 1, 2008 - serial number 39448 (because it is 39,448 days after Jan 1, 1900)</li>
</ul>
2) #NUM! error - if the serial_number or return_type is out of range, then the function returns this error.
<h2 id="3">Practical Examples of WEEKNUM Function:</h2>
Let's look at some practical examples of <strong>WEEKNUM Function</strong> and explore how to use it in Microsoft Excel.

<strong>Example 1: </strong>
<ul>
 	<li>The input value is entered into the B5 cell.</li>
 	<li>Using the below formula WEEKNUM value is calculated.</li>
</ul>
<pre>=WEEKNUM(B5)</pre>
[caption id="attachment_4651" align="aligncenter" width="514"]<img class="size-full wp-image-4651" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_1-34.png" alt="Example 1" width="514" height="313" /> Example 1[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to execute the formula.</li>
 	<li>Now, the result is returned as output in the D5 cell.

[caption id="attachment_4652" align="aligncenter" width="516"]<img class="size-full wp-image-4652" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_2-30.png" alt="Example 1 - Output" width="516" height="313" /> Example 1 - Output[/caption]</li>
 	<li>In this example 1, we did not mention the return_type so the function takes the default value 1.</li>
 	<li>As per the System 1, January 1 is considered to be the first week of the year. So, 09/03/2020(Monday - March 9th) is the 11th week starting from the first week on January 1.</li>
</ul>
<strong>Example 2: </strong>

The above steps need to be repeated for this example so it will display the below output.
<ul>
 	<li>In this example 2, we have chosen the return_type as 13, but it comes under system 1 so the output will not differ because of the change in return_type.

[caption id="attachment_4653" align="aligncenter" width="516"]<img class="size-full wp-image-4653" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_3-27.png" alt="Example 2" width="516" height="312" /> Example 2[/caption]</li>
</ul>
<h2 id="4">A Brief Summary:</h2>
In this short tutorial, we have illustrated how to use <strong>WEEKNUM Function</strong> in Excel with detailed practical examples. If you have any <strong>queries/doubts</strong>, kindly share it in the below comment section. Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel!!</a></strong> Keep Learning With Us!!
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a href="https://geekexcel.com/how-to-use-clean-function-in-microsoft-excel-365/">CLEAN Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-left-function-in-microsoft-excel-365/">LEFT Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-edate-function-in-excel-365/">EDATE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-upper-function-in-microsoft-excel-365/">UPPER Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-days360-function-in-excel/">DAYS 360 Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-time-function-in-excel-365/">TIME Function in Excel</a></strong></li>
</ul>