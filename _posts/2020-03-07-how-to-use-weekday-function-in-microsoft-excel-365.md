---
ID: 4530
post_title: >
  How to use WEEKDAY Function in Microsoft
  Excel 365?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-weekday-function-in-microsoft-excel-365/
published: true
post_date: 2020-03-07 14:29:04
---
<h2>WEEKDAY Function in Excel:</h2>
Here, we will analyze the basic syntax and usage of the <strong>WEEKDAY function</strong> in Microsoft Excel 365 with some examples.
<h2>Index:</h2>
<ul>
 	<li><a href="#1"><strong>Explanation of the WEEKDAY Function</strong></a></li>
 	<li><a href="#2"><strong>Fundamental Syntax of WEEKDAY Function</strong></a></li>
 	<li><a href="#3"><strong>Examples of WEEKDAY Function</strong></a></li>
 	<li><a href="#4"><strong>Verdict</strong></a></li>
</ul>
<h2 id="1"><strong>Explanation of the WEEKDAY Function:</strong></h2>
The <strong>WEEKDAY Function</strong> in Excel returns a number (ranging from 1 to 7) that represents the day of the week for a given date. By default, it gives an integer from 1 (Sunday) to 7 (Saturday).
<h2 id="2"><strong>Fundamental Syntax of WEEKDAY Function:</strong></h2>
<pre>=WEEKDAY(serial_number, [return_type])</pre>
<h3>Argument Description:</h3>
<ul>
 	<li><strong>Serial_number (Required):</strong> The date for which you need to obtain the day of the week.</li>
 	<li><strong>Return_type (Optional): </strong>A number that identifies the return value type.</li>
</ul>
[su_table]
<table>
<tbody>
<tr>
<td><strong>Return_type</strong></td>
<td><strong>Number Returned</strong></td>
</tr>
<tr>
<td>1 or omitted</td>
<td>1 to 7 (Sunday - Saturday)</td>
</tr>
<tr>
<td>2</td>
<td>1 to 7 (Monday - Sunday)</td>
</tr>
<tr>
<td>3</td>
<td>0 to 6 (Monday - Sunday)</td>
</tr>
<tr>
<td>11</td>
<td>1 to 7 (Monday - Sunday)</td>
</tr>
<tr>
<td>12</td>
<td>1 to 7 (Tuesday - Monday)</td>
</tr>
<tr>
<td>13</td>
<td>1 to 7 (Wednesday - Tuesday)</td>
</tr>
<tr>
<td>14</td>
<td>1 to 7 (Thursday - Wednesday)</td>
</tr>
<tr>
<td>15</td>
<td>1 to 7 (Friday - Thursday)</td>
</tr>
<tr>
<td>16</td>
<td>1 to 7 (Saturday - Friday)</td>
</tr>
<tr>
<td>17</td>
<td>1 to 7 (Sunday - Saturday)</td>
</tr>
</tbody>
</table>
[/su_table]
<h2 id="3"><strong>Examples of WEEKDAY Function:</strong></h2>
Let's focus on some examples of the <b>WEEKDAY function</b> and explore how to use it in Microsoft Excel.

<strong>Example 1: Day of the week, excluding return_type </strong>
<ul>
 	<li>The input value is entered into the <strong>B5</strong> cell.</li>
 	<li>Here, in this example, we did not mention the return_type so the Excel takes the <strong>default range from 1 (Sunday) to 7 (Saturday)</strong>.</li>
 	<li>Refer the below syntax of the <strong>WEEKDAY function</strong> for returning the day of the week as a numeric value.</li>
</ul>
<pre>=WEEKDAY(B5)</pre>
[caption id="attachment_4564" align="aligncenter" width="514"]<img class="size-full wp-image-4564" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_1-27.png" alt="Example 1" width="514" height="310" /> Example 1[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to execute the formula.</li>
 	<li>Now, the result is returned as output in the <strong>D5</strong> cell.

[caption id="attachment_4565" align="aligncenter" width="514"]<img class="size-full wp-image-4565" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_2-24.png" alt="Example 1 - Output" width="514" height="310" /> Example 1 - Output[/caption]</li>
 	<li>In the above example, we have given the input as 01/01/2020 - Wednesday. As per the default return range, Wednesday will get the 4th numeric value so it returned the output as 4.</li>
</ul>
<strong>Example 2: Day of the week, return_type as 13</strong>
<ul>
 	<li>The input value is entered into the <strong>B5</strong> cell.</li>
 	<li>Here, in this example, we have chosen the return_type as 13 so Excel takes the<strong> range from 1 (Wednesday) to 7 (Tuesday)</strong>.</li>
 	<li>Refer the below syntax of the <strong>WEEKDAY function</strong> for returning the day of the week as a numeric value.</li>
</ul>
<pre>=WEEKDAY(B5, 13)</pre>
[caption id="attachment_4566" align="aligncenter" width="692"]<img class="size-full wp-image-4566" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_3-22.png" alt="Example 2" width="692" height="432" /> Example 2[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to execute the formula.</li>
 	<li>Now, the result is returned as output in the <strong>D5</strong> cell.

[caption id="attachment_4567" align="aligncenter" width="509"]<img class="size-full wp-image-4567" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_4-20.png" alt="Example 2 - Output" width="509" height="312" /> Example 2 - Output[/caption]</li>
</ul>
<ul>
 	<li>We have given the same input as 01/01/2020 - Wednesday. But, we have chosen the range as 13 so Wednesday will get 1st numeric value and so it returned the output as 1.</li>
</ul>
<strong>Example 3: Day of the week, return_type as 13</strong>

Repeat the above steps in order to make use of WEEKDAY Function.
<ul>
 	<li>We have given the same input as 01/01/2020 - Wednesday. Here, we have chosen the range as 3 so Wednesday will get 2nd numeric value and so it returned the output as 2.</li>
</ul>
[caption id="attachment_4568" align="aligncenter" width="515"]<img class="size-full wp-image-4568" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_5-13.png" alt="Example 3" width="515" height="314" /> Example 3[/caption]
<h2 id="4"><strong>Verdic</strong><strong>t:</strong></h2>
We expect that this short tutorial helped you to make use of the <strong>WEEKDAY Function</strong> in <strong>MS Excel 365</strong> efficiently. In addition, the practical examples let you understand the usage of the WEEKDAY function even simpler. Keep us motivated by sharing your <strong>valuable feedback</strong> in the below comment section. Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel!!</a></strong> Keep learning with us!!
<h2>Related Articles:</h2>
<ul>
 	<li><a href="https://geekexcel.com/how-to-use-date-function-in-microsoft-excel-365/"><strong>DATE Function</strong></a></li>
 	<li><a href="https://geekexcel.com/how-to-use-days-function-in-excel-365/"><strong>DAYS Function</strong></a></li>
 	<li><a href="https://geekexcel.com/how-to-use-minute-function-in-excel-365/"><strong>MINUTE Function</strong></a></li>
</ul>