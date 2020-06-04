---
ID: 5121
post_title: >
  How to use EXACT Function in Microsoft
  Excel 365?
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-exact-function-in-microsoft-excel-365/
published: true
post_date: 2020-03-18 14:08:41
---
<h2>EXACT Function in Excel:</h2>
This article describes the explanation, basic syntax, and usage of the <strong>EXACT function</strong> in Microsoft Excel 365.
<h2>Jump To:</h2>
<ul>
 	<li><a href="#1"><strong>Explanation of EXACT Function</strong></a></li>
 	<li><a href="#2"><strong>EXACT Function - </strong></a><strong><a href="#month-2">Basic Syntax</a></strong></li>
 	<li><a href="#3"><strong>Practical Examples of </strong></a><strong><a href="#month-3">EXACT Function</a></strong></li>
 	<li><a href="#4"><strong>A Brief Synopsis</strong></a></li>
</ul>
<h2 id="1"><strong>Explanation of EXACT Function:</strong></h2>
The <strong>EXACT Function</strong> in Excel <strong>compares two text strings</strong> and <strong>returns TRUE if they are the same or else returns FALSE. </strong>This function is case-sensitive.
<h2 id="2"><strong>EXACT Function - </strong><strong>Basic Syntax:</strong></h2>
<pre>=EXACT(text1, text2)</pre>
<h3><strong>Argument Description:</strong></h3>
<ul>
 	<li><strong>Text1 (Required): </strong>First text value.</li>
 	<li><strong>Text2 (Required): </strong>Second text value.</li>
</ul>
<h2 id="3"><strong>Practical Examples of Exact Function:</strong></h2>
Let's look at some examples of this function and explore how it works in Microsoft Excel.

<strong>Example 1: Comparison of two similar texts</strong>
<ul>
 	<li>The first &amp; second text inputs are entered in the cells <strong>C5 and D5</strong>.</li>
 	<li>Then, we have entered the below formula in order to compare the text strings.</li>
</ul>
<pre>=EXACT(C5,D5)</pre>
[caption id="attachment_5137" align="aligncenter" width="649"]<img class="size-full wp-image-5137" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_3-52.png" alt="Example 1" width="649" height="338" /> Example 1[/caption]
<ul>
 	<li>Now, we have to click <strong>Enter</strong> to show the output in the <strong>F5</strong> cell.

[caption id="attachment_5138" align="aligncenter" width="651"]<img class="size-full wp-image-5138" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_4-40.png" alt="Example 1 - Output" width="651" height="314" /> Example 1 - Output[/caption]</li>
 	<li>Here, in this example, we have given two similar strings so the output returned as TRUE.</li>
 	<li>In another way, we can give input values directly while entering the formula. Kindly refer to the below screenshots.</li>
</ul>
[caption id="attachment_5139" align="aligncenter" width="650"]<img class="size-full wp-image-5139" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_1-56.png" alt="Input Values" width="650" height="313" /> Input Values[/caption]

[caption id="attachment_5140" align="aligncenter" width="572"]<img class="size-full wp-image-5140" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_2-54.png" alt="Output" width="572" height="312" /> Output[/caption]

<strong>Example 2: Comparison of two texts which are not same</strong>
<ul>
 	<li>The first &amp; second text inputs are entered in the cells <strong>C5 and D5</strong>.</li>
 	<li>Then, we have entered the below formula in order to compare the text strings.</li>
</ul>
<pre>=EXACT(C5,D5)</pre>
<ul>
 	<li>Click <strong>Enter</strong> to display the output in the <strong>F5</strong> cell.</li>
</ul>
[caption id="attachment_5141" align="aligncenter" width="650"]<img class="size-full wp-image-5141" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_5-32.png" alt="Example 2" width="650" height="308" /> Example 2[/caption]
<ul>
 	<li>In this example 2, the output is returned as FALSE because the Text1 is started with uppercase 'O'. The EXACT function considers the lower &amp; upper case while comparing two strings, if they are same returns TRUE, otherwise returns FALSE.</li>
</ul>
<strong>Example 3:</strong>
<ul>
 	<li>In this example, check the output that returned as FALSE because the given two text inputs differ in upper and lower cases. Even, if there is any space in the text, it will return as FALSE.</li>
</ul>
[caption id="attachment_5142" align="aligncenter" width="650"]<img class="size-full wp-image-5142" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_6-27.png" alt="Example 3" width="650" height="361" /> Example 3[/caption]
<h2 id="4"><strong>Verdict:</strong></h2>
In the above short article, we have described the explanation, basic syntax, and usage of the <strong>EXACT</strong> <strong>function</strong> with the examples. Drop your valuable <strong>queries/feedback</strong> in the below comment section.

Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel!!</a></strong> Keep Learning with us!!
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a href="https://geekexcel.com/how-to-use-left-function-in-microsoft-excel-365/">LEFT Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-weeknum-function-in-microsoft-excel-365/">WEEKNUM Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-yearfrac-function-in-microsoft-excel-365/">YEARFRAC Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-month-function-in-microsoft-excel-365/">MONTH Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-clean-function-in-microsoft-excel-365/">CLEAN Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-timevalue-function-in-microsoft-excel-365/">TIMEVALUE Function in Excel</a></strong></li>
</ul>