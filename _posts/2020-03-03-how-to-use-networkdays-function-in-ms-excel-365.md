---
ID: 4231
post_title: >
  How to use NETWORKDAYS Function in MS
  Excel 365?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-networkdays-function-in-ms-excel-365/
published: true
post_date: 2020-03-03 11:03:00
---
<h2>NETWORKDAYS Function in Excel:</h2>
Here, we discuss the description, basic syntax and usage of the NETWORKDAYS Function in MS Excel 365.
<h2>Index:</h2>
<ul>
 	<li><strong><a href="#net-1">NETWORKDAYS Function - Description</a></strong></li>
 	<li><a href="#net-2"><strong>Basic Syntax of NETWORKDAYS Function</strong></a></li>
 	<li><a href="#net-3"><strong>Examples of NETWORKDAYS Function</strong></a></li>
 	<li><strong><a href="#net-4">Verdict</a></strong></li>
</ul>
<h2 id="net-1"><strong>NETWORKDAYS function - Description:</strong></h2>
The <strong>NETWORKDAYS Function</strong> returns the <strong>number of working days between two dates</strong>. You will be needed to give start_date and end_date so that the function will calculate the number of working days and produce the output. This function will automatically exclude Saturdays and Sundays while calculating the number of working days. You can also specify the dates of holidays so that it will be treated as non-working days and it will not be included in the output.
<h2 id="net-2"><strong>Basic Syntax of </strong><strong>NETWORKDAYS </strong><strong>Function:</strong></h2>
<pre>=NETWORKDAYS(start_date,end_date,[holidays])</pre>
<h3><strong>Parameters Explanation:</strong></h3>
<ul>
 	<li><strong>Start date (Required): </strong>The start date to be used in the calculation.</li>
 	<li><strong>End date (Required): </strong>The end date to be used in the calculation.</li>
 	<li><strong>Holidays (Optional): </strong>It is the list of holidays to exclude from calculation.</li>
</ul>
<h3>Note:</h3>
<ul>
 	<li><strong>#VALUE! Error:</strong>  NETWORKDAYS Function will return #VALUE! error if any argument is not a valid date.</li>
</ul>
<h2 id="net-3"><strong>Examples of </strong><strong>NETWORKDAYS </strong><strong>Function:</strong></h2>
Let's look at some examples of <strong>NETWORKDAYS</strong><b> function</b> and explore how to use it in Microsoft Excel.

<strong>Example 1: Number of working days calculation - Excel automatically excludes Saturdays &amp; Sundays</strong>
<ul>
 	<li>Input values of start_date &amp; end_date are entered in B4 and D4 cells.</li>
 	<li>Then, you have to enter the below formula to display the output of number of working days.</li>
</ul>
<pre>=NETWORKDAYS(B4,D4)</pre>
[caption id="attachment_4235" align="aligncenter" width="604"]<img class="size-full wp-image-4235" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_1-2.png" alt="NETWORKDAYS Function Excel" width="604" height="311" /> NETWORKDAYS Function Excel[/caption]
<ul>
 	<li>Click Enter to display the output in the F4 cell.

[caption id="attachment_4236" align="aligncenter" width="602"]<img class="size-full wp-image-4236" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_2-1.png" alt="Example 1 - Output" width="602" height="311" /> Example 1 - Output[/caption]</li>
 	<li>In total, January (31) &amp; February (29) comprised of 60 days. Excel subtracted Saturdays &amp; Sundays of both months that is 17 days from 60 days and returned the output as 43 number of working days.</li>
</ul>
<strong>Example 2: Number of working days by excluding a given holiday. </strong>
<ul>
 	<li>Input values of start_date, end_date &amp; holiday are entered in B4, D4, and F4 cells.</li>
 	<li>Then, you have to enter the below formula to display the number of working days by excluding a holiday.</li>
</ul>
<pre>=NETWORKDAYS(B4,D4,F4)</pre>
[caption id="attachment_4237" align="aligncenter" width="741"]<img class="size-full wp-image-4237" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_3-2.png" alt="Example 2" width="741" height="335" /> Example 2[/caption]
<ul>
 	<li>Click Enter to display the output in the H4 cell.

[caption id="attachment_4238" align="aligncenter" width="744"]<img class="size-full wp-image-4238" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_4-1.png" alt="Example 2 - Output" width="744" height="311" /> Example 2 - Output[/caption]

<strong>Note:</strong> You don't have to mention any holiday date of Saturdays or Sundays separately in the holiday parameter as Excel will already exclude those Saturdays &amp; Sundays in the calculation.</li>
</ul>
<strong>Example 3: Number of working days by excluding four given holidays. </strong>
<ul>
 	<li>Repeat the above steps in order to calculate the number of working days by excluding holidays. In order to select more than one cell for holiday argument, first, you just need to click on the F4 cell then hold on the shift key and click on F7 cell so that the entire four cells will be selected as F4: F7.

[caption id="attachment_4239" align="aligncenter" width="821"]<img class="size-full wp-image-4239" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_5-1.png" alt="Example 3" width="821" height="361" /> Example 3[/caption]

[caption id="attachment_4240" align="aligncenter" width="741"]<img class="size-full wp-image-4240" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_6-1.png" alt="Example 3 - Output" width="741" height="361" /> Example 3 - Output[/caption]</li>
</ul>
<h2 id="net-4"><strong>Verdict:</strong></h2>
In the above short article, we have illustrated the definition, basic syntax, and usage of the <strong>NETWORKDAYS function</strong> with a few practical examples. If you have any <strong>queries/suggestions</strong>, kindly share it in the below comment box. Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel!!</a></strong> Keep Learning!!
<h2>Related Articles:</h2>
<ul>
 	<li><a href="https://geekexcel.com/how-to-use-month-function-in-microsoft-excel-365/"><strong>MONTH Function in Excel</strong></a></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-date-function-in-microsoft-excel-365/">DATE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-asin-function-in-microsoft-excel-365/">ASIN Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-minute-function-in-excel-365/">MINUTE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-hour-function-in-microsoft-excel-365/">HOUR Function in Excel</a></strong></li>
 	<li><a href="https://geekexcel.com/how-to-use-time-function-in-excel-365/"><strong>TIME Function in Excel</strong></a></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-datevalue-function-in-excel-365/">DATEVALUE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-days-function-in-excel-365/">DAYS Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-find-average-using-aggregate-function/">AGGREGATE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-days360-function-in-excel/">DAYS360 Function in Excel</a></strong></li>
</ul>