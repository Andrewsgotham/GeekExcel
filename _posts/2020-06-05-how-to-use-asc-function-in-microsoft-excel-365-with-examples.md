---
ID: 7591
post_title: >
  How to use ASC Function in Microsoft
  Excel 365? (With Examples)
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-asc-function-in-microsoft-excel-365-with-examples/
published: true
post_date: 2020-06-05 17:43:13
---
<h2>ASC Function in Excel:</h2>
In this short tutorial, we will discuss the explanation, syntax, and usage of the <strong>ASC function</strong> <strong>in</strong> <strong>Microsoft Excel 365</strong>.
<h2>Index:</h2>
<ul>
 	<li><a href="#1"><strong>Explanation of ASC Function</strong></a></li>
 	<li><a href="#2"><strong>ASC Function - Basic Syntax</strong></a></li>
 	<li><a href="#3"><strong>Practical Examples of ASC Function</strong></a></li>
 	<li><a href="#4"><strong>A Brief Summary</strong></a></li>
</ul>
<h2 id="1"><strong>Explanation of ASC Function</strong>:</h2>
The ASC Function in Excel <strong>changes the full-width (double-byte) characters within a character string to half-width (single-byte) characters</strong>. This function is mainly useful for <strong>Double-byte character set (DBCS) languages</strong>. The DBCS is nothing but, a character encoding in which all characters are encoded in two bytes.
<ul>
 	<li><strong>Single-byte characters</strong> - Alphabetic characters, numeric characters, and symbols are called single-byte characters. <strong>Example: Excel</strong></li>
 	<li><strong>Double-byte characters</strong> - Chinese, Korean, Japanese characters are double-byte characters as they are twice as wide as normal alphabetic characters. <strong>Example: ひらがな</strong></li>
</ul>
<h2 id="2"><strong>ASC Function - Basic Syntax</strong>:</h2>
The fundamental syntax of <strong>ASC </strong><strong>Function</strong> is,
<pre>=ASC(text)</pre>
<h3>Argument Description:</h3>
<ul>
 	<li><strong>Text (Required):</strong> The text that you want to change. It can also be a reference to a cell that contains the text.</li>
</ul>
<strong>Note:</strong> If the text does not contain any full-width letters, then the text will not change.
<h2 id="3">Practical Examples of ASC Function:</h2>
Let's look at some practical examples of <strong>ASC Function</strong> and explore how to use it in Microsoft Excel.

<strong>Example 1: Single-byte Characters</strong>
<ul>
 	<li>In this Example 1, the input value is entered into the <strong>B6</strong> cell.</li>
 	<li>Refer to the below syntax of the <strong>ASC function</strong> to return the output.</li>
</ul>
<pre>=ASC(B6)</pre>
[caption id="attachment_7592" align="aligncenter" width="763"]<img class="size-full wp-image-7592" src="https://geekexcel.com/wp-content/uploads/2020/06/asc1.png" alt="Example 1" width="763" height="363" /> Example 1[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to execute the formula.</li>
 	<li>Now, the result is returned as output in the <strong>D6 </strong>cell.

[caption id="attachment_7593" align="alignnone" width="760"]<img class="size-full wp-image-7593" src="https://geekexcel.com/wp-content/uploads/2020/06/asc2.png" alt="Example 1 - Output" width="760" height="338" /> Example 1 - Output[/caption]</li>
 	<li>In this example, we have given the single-byte characters into the ASC function so it is not changed.</li>
 	<li>In another way, you can give the input directly into the formula as shown below.</li>
</ul>
<pre>=ASC(GeekExcel)</pre>
<div class="mceTemp"></div>
<strong>Example 2: Double-byte Characters</strong>
<ul>
 	<li>In this Example 2, the input value is entered into the <strong>B7</strong> cell.</li>
 	<li>Refer to the below syntax of the <strong>ASC function</strong> to return the output.</li>
</ul>
<pre>=ASC(B7)</pre>
[caption id="attachment_7594" align="aligncenter" width="830"]<img class="size-full wp-image-7594" src="https://geekexcel.com/wp-content/uploads/2020/06/asc3.png" alt="Example 2" width="830" height="361" /> Example 2[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to execute the formula.</li>
 	<li>Now, the result is returned as output in the <strong>D7 </strong>cell.

[caption id="attachment_7595" align="aligncenter" width="775"]<img class="size-full wp-image-7595" src="https://geekexcel.com/wp-content/uploads/2020/06/asc4.png" alt="Example 2 - Output" width="775" height="364" /> Example 2 - Output[/caption]</li>
 	<li>In this example, we have given the double-byte characters into the ASC function so it is changed into single-byte characters.</li>
</ul>
<strong>Example 3: Double-byte Characters</strong>

In this example 3, we have changed the full-width (double-byte) characters into half-width (single-byte) characters. Refer to the image below.

[caption id="attachment_7598" align="aligncenter" width="831"]<img class="size-full wp-image-7598" src="https://geekexcel.com/wp-content/uploads/2020/06/asc5.png" alt="Example 3" width="831" height="366" /> Example 3[/caption]
<h2 id="4">A Brief Summary:</h2>
In this short tutorial, we have illustrated how to use <strong>ASC Function</strong> in Excel 365 with clear-cut practical examples. If you have any <strong>queries/doubts</strong>, kindly share it in the below comment section. Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel!!</a></strong> Keep Learning With Us!!
<h2>Related Articles:</h2>
<ul>
 	<li><strong><a href="https://geekexcel.com/how-to-use-timevalue-function-in-microsoft-excel-365/">TIMEVALUE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-code-function-in-microsoft-excel-365/">CODE Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-right-function-in-microsoft-excel-365/">RIGHT Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-find-function-in-microsoft-excel-365/">FIND Function in Excel</a></strong></li>
 	<li><strong><a href="https://geekexcel.com/how-to-use-time-function-in-excel-365/">TIME Function in Excel</a></strong></li>
</ul>