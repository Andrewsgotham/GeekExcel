---
ID: 4381
post_title: >
  How to Use MID Function in Microsoft
  Excel 365?
author: Merin
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-mid-function-in-microsoft-excel-365/
published: true
post_date: 2020-03-05 15:28:09
---
<strong>MID Function: </strong>It <strong>extracts</strong> the number (starting from the left side) or characters from the given string. You can <strong>customize</strong> the <strong>position</strong> and the <strong>number of characters</strong> that you want to extract from the given string. The <strong>MID</strong> Function will extract digits from the given number as well. In this article, we will describe the <strong>MID Function</strong> in MS Excel 365 with syntax and examples.
<h2>Jump To:</h2>
<ul>
 	<li><a href="#mid-1"><strong>MID Function Syntax</strong></a></li>
 	<li><a href="#mid-2"><strong>MID Function with Examples </strong></a></li>
 	<li><a href="#mid-3"><strong>A Short Synopsis</strong></a></li>
</ul>
<h2 id="mid-1">MID Function Syntax:</h2>
<pre>=MID(text,start_num,num_chars)</pre>
<strong>Text:</strong> The String or Text.

<strong>start_num:</strong> Position of the first character you want to extract from the given string. For example, the start_num for the first character is in the text is 1.

<strong>num_chars</strong>: Number of characters you want from the specified position of the Text.

<strong>Note: </strong>The MID function considers <strong>space</strong> as a character.
<h2 id="mid-2">MID Function with Examples:</h2>
Let's take a look at the following examples of <strong>MID</strong> Function in Excel.
<h3>Example 1:</h3>
[caption id="attachment_4400" align="aligncenter" width="1097"]<img class="wp-image-4400 size-full" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_4-13.png" alt="MID Function Example 1" width="1097" height="517" /> MID Function Example 1[/caption]
<ul>
 	<li>In the above example, the <strong>MID</strong> Function retrieves the first 7<strong> </strong>characters from the given string. To calculate the <strong>MID FUNCTION, </strong>we have to mention the start and end position of the string and the formula is <strong>=MID(C7,1,7). </strong></li>
 	<li>Now, the function shows the result as <b>MID FUN</b>.</li>
 	<li>Here, the <strong>MID</strong> function considers <strong>space</strong> as a character.</li>
</ul>
<h3>Example 2:</h3>
<ul>
 	<li>In this example, the <strong>MID</strong> Function retrieves 10 characters from the 7th position of the given string "<strong>EXCEL FUNCTION". </strong>We have to use the formula as <strong style="font-size: 19px;">=MID(C8,7,10).</strong></li>
 	<li>Here, the total length of the retrieved string is 8, but the num_char value is 10 so the <strong>MID</strong> Function fills the space for the remaining 2 positions and prints the result as <strong>FUNCTION</strong>.</li>
</ul>
[caption id="attachment_4403" align="alignnone" width="1097"]<img class="wp-image-4403 size-full" style="font-size: 19px; font-weight: 600;" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_1-18.png" alt="MID Function Example 2" width="1097" height="502" /> MID Function Example 2[/caption]
<h3>Example 3:</h3>
<ul>
 	<li>Here, the <strong>MID</strong> Function extracts 10 numbers from the 6th position of the given number<strong> 0427-234567</strong> and the Formula is <strong>=MID(C9,6,10). </strong></li>
 	<li>Here, the total length of the retrieved number is 6, but the num_char value is 10 so the <strong>MID</strong> Function fills the space for the remaining 4 positions.</li>
 	<li>Now, the MID Function prints the result as <b>234567</b>.</li>
</ul>
[caption id="attachment_4407" align="aligncenter" width="1092"]<img class="size-full wp-image-4407" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_2-13.png" alt="MID Function Example 3" width="1092" height="489" /> MID Function Example 3[/caption]
<h3>Example 4:</h3>
<ul>
 	<li>Here, the given string is <strong>"S</strong><strong>TRING".</strong> The total length of the given string is 6 but the specified <strong>starting position is 30</strong> so the <strong>MID</strong> Function prints<strong> nothing </strong>in the result cell.</li>
</ul>
[caption id="attachment_4411" align="aligncenter" width="1091"]<img class="size-full wp-image-4411" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_3-15.png" alt="MID Function Example 4" width="1091" height="534" /> MID Function Example 4[/caption]
<h2 id="mid-3">A Short Synopsis:</h2>
This article gives you the complete tutorial about the <strong>MID Function in Excel 365</strong>. We have demonstrated MID Function with the related examples. Stay connected to get instant updates. Please leave your <strong>Queries</strong> in the comment section, we will resolve your queries ASAP. Share your <strong>Feedback</strong> as well. Thank you for visiting our website <a href="https://geekexcel.com/"><strong>GeekExcel</strong></a>.
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a href="https://geekexcel.com/how-to-use-minute-function-in-excel-365/">MINUTE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-day-function-in-excel-365/">DAY Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-days-function-in-excel-365/">DAYS Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-edate-function-in-excel-365/">EDATE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-days360-function-in-excel/">DAYS360Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-networkdays-function-in-ms-excel-365/">NETWORKDAYS Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-code-function-in-microsoft-excel-365/">CODE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-networkdays-intl-function-in-ms-excel-365/">NETWORK.INTL Function in Excel</a></strong></li>
</ul>