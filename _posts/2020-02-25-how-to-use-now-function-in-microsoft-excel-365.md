---
ID: 4021
post_title: >
  How to use NOW Function in Microsoft
  Excel 365?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-now-function-in-microsoft-excel-365/
published: true
post_date: 2020-02-25 11:44:51
---
<h2>NOW Function in Excel:</h2>
<strong>NOW</strong> function will be useful when you want to display the <strong>current date and time</strong> on a worksheet. In this short tutorial, we will describe the definition, syntax, and usage of the NOW function in Microsoft Excel 365.
<h2>Index:</h2>
<ul>
 	<li><a href="#now-1"><strong>NOW function - Definition</strong></a></li>
 	<li><a href="#now-2"><strong>Fundamental Syntax of NOW Function</strong></a></li>
 	<li><a href="#now-3"><strong>Practical Examples of NOW Function</strong></a></li>
 	<li><a href="#now-4"><strong>A Short Summary</strong></a></li>
</ul>
<h2 id="now-1">NOW function - Definition:</h2>
The <strong>NOW</strong> Function in Excel returns the <strong>current date and time</strong>.  You can make use of this NOW function to compute a value based on the current date &amp; time. The returned value of the NOW function will be updated every time you open or refresh the worksheet. If your Excel cell format was General before the NOW function was entered, MS Excel alters the cell format to match it with the format of the date &amp; time of your regional settings.
<h2 id="now-2">Fundamental Syntax of NOW Function:</h2>
The fundamental syntax of NOW function is,
<pre>=NOW()</pre>
<ul>
 	<li>The NOW function takes no arguments but requires empty parentheses.</li>
</ul>
<h2 id="now-3">Practical Examples of NOW Function:</h2>
Let's look at some examples of <b>NOW function</b> and explore how to use it in Microsoft Excel.

<strong>Example 1: Returns the current date &amp; time</strong>
<ul>
 	<li>In order to return the current date and time, you have to just enter the NOW function as below.

[caption id="attachment_4029" align="aligncenter" width="704"]<img class="size-full wp-image-4029" src="https://geekexcel.com/wp-content/uploads/2020/02/EXCEL_prxno5QxX0.png" alt="NOW function in MS Excel" width="704" height="334" /> NOW function in MS Excel[/caption]</li>
 	<li>Now, click <strong>Enter </strong>to return the current date and time in the E3 cell.

[caption id="attachment_4030" align="aligncenter" width="729"]<img class="size-full wp-image-4030" src="https://geekexcel.com/wp-content/uploads/2020/02/EXCEL_PN0KKbvsjM.png" alt="Example 1 - Output" width="729" height="333" /> Example 1 - Output[/caption]</li>
 	<li>The spreadsheet will continue to show this value until the worksheet recalculates.</li>
 	<li>Use F9 to update or recalculate the value in the worksheet.</li>
</ul>
<strong>Example 2: Date &amp; Time after 12 hours </strong>
<ul>
 	<li>Enter the formula as in the E5 cell in order to calculate the date &amp; time after 12 hours.

[caption id="attachment_4038" align="aligncenter" width="777"]<img class="size-full wp-image-4038" src="https://geekexcel.com/wp-content/uploads/2020/02/after-12.png" alt="Example 2 - Time Calculation" width="777" height="356" /> Example 2 - Time Calculation[/caption]</li>
</ul>
<ul>
 	<li>Click Enter to display the output in the E5 cell.

[caption id="attachment_4039" align="aligncenter" width="776"]<img class="size-full wp-image-4039" src="https://geekexcel.com/wp-content/uploads/2020/02/output-after-12.png" alt="Example 2 - Output " width="776" height="385" /> Example 2 - Output[/caption]</li>
</ul>
<strong>Example 3: Returns date &amp; time after 3 days</strong>
<ul>
 	<li>Enter the formula as in the E5 cell in order to calculate the date &amp; time after 3 days.

[caption id="attachment_4047" align="aligncenter" width="844"]<img class="size-full wp-image-4047" src="https://geekexcel.com/wp-content/uploads/2020/02/3-days.png" alt="Example 3" width="844" height="384" /> Example 3[/caption]</li>
 	<li>Click Enter to display the output in the E5 cell.

[caption id="attachment_4048" align="aligncenter" width="843"]<img class="size-full wp-image-4048" src="https://geekexcel.com/wp-content/uploads/2020/02/3-days-output.png" alt="Example 3 - Output" width="843" height="357" /> Example 3 - Output[/caption]

<strong>Example 4: Returns date &amp; time - Before 1 day </strong></li>
 	<li>Enter the formula as illustrated in the formula bar in order to return the date &amp; time before 1 day.

[caption id="attachment_4049" align="aligncenter" width="777"]<img class="size-full wp-image-4049" src="https://geekexcel.com/wp-content/uploads/2020/02/example-4.png" alt="Example 4 - Output" width="777" height="308" /> Example 4 - Output[/caption]</li>
</ul>
<strong>Notes:</strong>
<ul>
 	<li>Time values are a part of a date value and illustrated by a decimal number (for example, half of a day (12:00 PM) is represented as (0.5).</li>
 	<li>If you enter '+' sign with the decimal value, it will add it to the current date &amp; time and display the result. If you enter '-' sign, it will lessen it from the current date &amp; time.</li>
 	<li>#VALUE! error – It occurs, if you enter the value which is not a valid Excel time.</li>
</ul>
<h2 id="now-4"><strong>A Short Summary:</strong></h2>
In the above short article, we have described the usage of the <b>NOW </b>function in Excel for the calculation of the current date and time. Kindly share your valuable <strong>comments</strong> to keep us motivated all the time.