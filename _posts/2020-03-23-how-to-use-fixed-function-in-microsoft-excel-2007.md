---
ID: 5396
post_title: >
  How to use FIXED Function in Microsoft
  Excel 2007?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-fixed-function-in-microsoft-excel-2007/
published: true
post_date: 2020-03-23 16:16:29
---
<h2>FIXED Function in Excel:</h2>
In this short tutorial, we will discuss the explanation, syntax, and usage of the <strong>FIXED function</strong> <strong>in</strong> <strong>Microsoft Excel 2007</strong>.
<h2>Index:</h2>
<ul>
 	<li><a href="#1"><strong>Explanation of FIXED Function</strong></a></li>
 	<li><a href="#2"><strong>FIXED Function - Basic Syntax</strong></a></li>
 	<li><a href="#3"><strong>Practical Examples of FIXED Function</strong></a></li>
 	<li><a href="#4"><strong>A Brief Summary</strong></a></li>
</ul>
<h2 id="1"><strong>Explanation of FIXED Function</strong>:</h2>
The FIXED Function in Excel <strong>converts a number with a specified number of decimals and returns as text. </strong>By default, the function will show 2 decimal places to the right of the decimal point, if you did not mention the decimals.
<h2 id="2"><strong>FIXED Function - Basic Syntax</strong>:</h2>
The fundamental syntax of <strong>FIXED </strong><strong>Function</strong> is,
<pre>=FIXED(number, [decimals], [no_commas])</pre>
<h3>Argument Description:</h3>
<ul>
 	<li><strong>Number (Required): </strong>A number that you want to round and convert into text.</li>
 	<li><strong>Decimals (Optional): </strong>Number of decimal places.</li>
 	<li><strong>No_commas (Optional):</strong> A logical value, either TRUE or FALSE. TRUE - No Commas, FALSE - Commas.</li>
</ul>
<strong>Notes:</strong>
<ul>
 	<li>
<p class="">If decimals are negative, the number is rounded to the left of the decimal point.</p>
</li>
</ul>
<h2 id="3">Practical Examples of FIXED Function:</h2>
Let's look at some practical examples of <strong>FIXED Function</strong> and explore how to use it in Microsoft Excel.

<strong>Example 1: </strong>
<ul>
 	<li>In this Example 1, we did not mention the decimal values so the FIXED Function displays 2 decimal places by default.</li>
 	<li>The input value is entered into the <strong>C5</strong> cell.</li>
 	<li>Refer to the below syntax of the <strong>FIXED function</strong> to return the output.</li>
</ul>
<pre>=FIXED(C5)</pre>
[caption id="attachment_5404" align="aligncenter" width="676"]<img class="size-full wp-image-5404" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_3-69.png" alt="Example 1" width="676" height="319" /> Example 1[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to execute the formula.</li>
 	<li>Now, the result is returned as output in the <strong>E5 </strong>cell.

[caption id="attachment_5405" align="aligncenter" width="674"]<img class="size-full wp-image-5405" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_4-54.png" alt="Example 1 - Output" width="674" height="320" /> Example 1 - Output[/caption]</li>
 	<li>In another way, you can give the input directly into the formula as shown in the below screenshot.

[caption id="attachment_5402" align="aligncenter" width="497"]<img class="size-full wp-image-5402" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_1-72.png" alt="Example 1" width="497" height="290" /> Example 1[/caption]

[caption id="attachment_5403" align="aligncenter" width="497"]<img class="size-full wp-image-5403" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_2-69.png" alt="Example 1 - Output" width="497" height="264" /> Example 1 - Output[/caption]</li>
</ul>
<strong>Example 2:</strong>
<ul>
 	<li>The input value is entered into the <strong>C5</strong> cell.</li>
 	<li>Refer to the below syntax of the <strong>FIXED function</strong> to return the output.</li>
</ul>
<pre>=FIXED(C5,4)</pre>
[caption id="attachment_5410" align="aligncenter" width="604"]<img class="size-full wp-image-5410" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_5-43.png" alt="Example 2" width="604" height="288" /> Example 2[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to execute the formula.</li>
 	<li>Now, the result is returned as output in the <strong>E5</strong> cell.

[caption id="attachment_5411" align="aligncenter" width="610"]<img class="size-full wp-image-5411" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_6-35.png" alt="Example 2 - Output" width="610" height="292" /> Example 2 - Output[/caption]</li>
 	<li>In this Example 2, we have mentioned the decimals argument as 4 so it displayed the output with 4 decimal places to the right of the decimal point.</li>
</ul>
<strong>Example 3:</strong>

In this Example 3, we have mentioned the No_commas argument as TRUE so it will not display the output with commas.

[caption id="attachment_5413" align="aligncenter" width="614"]<img class="size-full wp-image-5413" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_7-24.png" alt="Example 3" width="614" height="296" /> Example 3[/caption]

[caption id="attachment_5414" align="aligncenter" width="610"]<img class="size-full wp-image-5414" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_8-20.png" alt="Example 3 - Output" width="610" height="294" /> Example 3 - Output[/caption]

<strong>Example 4:</strong>

In this Example 4, we have mentioned the No_commas argument as FALSE so it will display the output with commas.

[caption id="attachment_5415" align="aligncenter" width="612"]<img class="size-full wp-image-5415" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_9-12.png" alt="Example 4" width="612" height="295" /> Example 4[/caption]

[caption id="attachment_5416" align="aligncenter" width="610"]<img class="size-full wp-image-5416" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_10-8.png" alt="Example 4 - Output" width="610" height="293" /> Example 4 - Output[/caption]

<strong>Example 5:</strong>

In this Example 5, we have given the input as negative value and mentioned the decimals as negative values so it displays the output to the left of the decimal point.

[caption id="attachment_5418" align="alignnone" width="924"]<img class="size-full wp-image-5418" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_11-5.png" alt="Example 5" width="924" height="410" /> Example 5[/caption]
<h2 id="4">A Brief Summary:</h2>
In this short tutorial, we have illustrated how to use <strong>FIXED Function</strong> in Excel 2007 with clear-cut practical examples. If you have any <strong>queries/doubts</strong>, kindly share it in the below comment section. Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel!!</a></strong> Keep Learning With Us!!
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a href="https://geekexcel.com/how-to-use-timevalue-function-in-microsoft-excel-365/">TIMEVALUE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-code-function-in-microsoft-excel-365/">CODE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-right-function-in-microsoft-excel-365/">RIGHT Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-find-function-in-microsoft-excel-365/">FIND Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-time-function-in-excel-365/">TIME Function in Excel</a></strong></li>
</ul>