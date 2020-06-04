---
ID: 4332
post_title: >
  How to use WORKDAY.INTL Function in
  Excel 365?
author: Merin
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-workday-intl-function-in-excel-365/
published: true
post_date: 2020-03-04 17:17:28
---
<strong>WORKDAY.INTL Function:</strong> It is a Built-in Function in Excel used to calculate the <strong>proximate working day</strong> based on the values we provide and returns a number that represents the date. In WORKDAY.INTL Function allows you to customize the weekends(which can any day of the week). This Function is mostly used to calculate the delivery dates, shipping dates, event completion date, etc.
<h2>Jump To:</h2>
<ul>
 	<li><a href="#work-1"><strong>WORKDAY.INTL Function Syntax</strong></a></li>
 	<li><a href="#work-2"><strong>WORKDAY.INTL Function with Examples</strong></a></li>
 	<li><a href="#work-3"><strong>A Quick Synopsis</strong></a></li>
</ul>
<h2 id="work-1">WORKDAY.INTL Function Syntax:</h2>
<pre> =WORKDAY.INTL(Start_date,days,[Weekend],[holiday])</pre>
<strong>Start_Date: </strong>The starting date.

<strong>Days: </strong>Number of <strong>non-weekend</strong> and <strong>non-working</strong> days before or after the start date.

<strong>Weekend: </strong>Days of the week should be considered as weekends. These are the default values for weekends supported by Excel.
<table id="tblID0EDBDAAA" class="banded flipColors">
<tbody>
<tr>
<td class="">
<p class="">1 or default</p>
</td>
<td class="">
<p class="">Saturday, Sunday</p>
</td>
</tr>
<tr>
<td>2</td>
<td>Sunday, Monday</td>
</tr>
<tr>
<td>3</td>
<td>Monday, Tuesday</td>
</tr>
<tr>
<td>4</td>
<td>Tuesday, Wednesday</td>
</tr>
<tr>
<td>5</td>
<td>Wednesday, Thursday</td>
</tr>
<tr>
<td>6</td>
<td>Thursday, Friday</td>
</tr>
<tr>
<td>7</td>
<td>Friday, Saturday</td>
</tr>
<tr>
<td>11</td>
<td>
<p class="">Sunday only</p>
</td>
</tr>
<tr>
<td>12</td>
<td>Monday only</td>
</tr>
<tr>
<td>13</td>
<td>Tuesday only</td>
</tr>
<tr>
<td>14</td>
<td>Wednesday only</td>
</tr>
<tr>
<td>15</td>
<td>Thursday only</td>
</tr>
<tr>
<td>16</td>
<td>Friday only</td>
</tr>
<tr>
<td>17</td>
<td>Saturday only</td>
</tr>
</tbody>
</table>
&nbsp;

<strong>Holiday: </strong>The number of Holidays should be in date format. It is an <strong>optional argument.</strong>

By default, the <strong>WORKDAY.INTL Function</strong> considers the <strong>Saturday</strong> and <strong>Sunday</strong> as <strong>non-working days. </strong>The <strong>WORKDAY.INTL</strong> Function <strong>excludes</strong> the <strong>holidays</strong> &amp; <strong>non-working days</strong> and calculates the proximate working day.
<h2 id="work-2">WORKDAY.INTL Function with Examples:</h2>
Let's evaluate the <strong>WORKDAY.INTL</strong> Function with the following examples
<h3>Example 1:</h3>
Let us assume that an employee needs to complete the project within a number of working days.

Now, the formula to calculate the estimated completion date of the project is,

[caption id="attachment_4346" align="aligncenter" width="965"]<img class="size-full wp-image-4346" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_1-12.png" alt="WORKDAY.INTL Function Example 1" width="965" height="420" /> WORKDAY.INTL Function Example 1[/caption]
<ul>
 	<li>The employee stated the project on 20th Mar 2020,</li>
 	<li>He needs to complete the project within 20 working days from the starting date.</li>
 	<li>Here, <strong>Saturdays and the Holidays are considered</strong> as non-working days. The WORKDAY.INTL Function <strong>=WORKDAY.INTL(B8,C8,17,B14:B16) </strong>prints the completion date as <strong>15th Apr 2020.</strong></li>
 	<li>The employee will complete the project at the date of <strong>15th Apr 2020.</strong></li>
</ul>
<h3>Example 2:</h3>
Consider a scenario of a professor, he has to complete the lesson in a particular number of working days. Let's calculate the lesson completion date.

[caption id="attachment_4347" align="aligncenter" width="964"]<img class="size-full wp-image-4347" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_4-10.png" alt="WORKDAY.INTL Function Example 2" width="964" height="421" /> WORKDAY.INTL Function Example 2[/caption]
<ul>
 	<li>The professor has stated the lesson on 3rd Mar 2020,</li>
 	<li>He needs to complete the lesson within 5 working days. Here, <strong>Sundays and the Holidays</strong> are considered as non-working days.</li>
 	<li>The WORKDAY.INTL Function <strong>=WORKDAY.INTL(B6,C6,11,B14:B16) </strong>prints the completion date as <strong>9</strong><strong>th Mar  2020.</strong></li>
 	<li>The professor will complete the lesson within <strong>9th Mar 2020.</strong></li>
</ul>
<h2 id="work-3">A Quick Synopsis:</h2>
We hope this article gives you the complete tutorial about <strong>WORKDAY.INTL</strong> Function syntax, definition, and usage in Excel 365.  We have explained the <strong>WORKDAY.INTL</strong> Function with related examples. Please comment your <strong>queries</strong> and share your <strong>suggestions</strong> in the comment section. Stay connected to get instant updates. Thank you for visiting our website <strong><a href="https://geekexcel.com/">GeekExcel</a></strong>
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a href="https://geekexcel.com/how-to-use-networkdays-intl-function-in-ms-excel-365/">NETWORKDAYS.INTL Function in Excel.</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-code-function-in-microsoft-excel-365/">CODE Function in Excel.</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-second-function-in-microsoft-excel-365/">SECOND Function in Excel.</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-year-function-in-excel-365/">YEAR Function in Excel.</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-hour-function-in-microsoft-excel-365/">HOUR Function in Excel.</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-eomonth-function-in-microsoft-excel-365/">EOMONTH Function in Excel.</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-days360-function-in-excel/">DAYS360 Function in Excel.</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-day-function-in-excel-365/">DAY Function in Excel.</a></strong></li>
</ul>