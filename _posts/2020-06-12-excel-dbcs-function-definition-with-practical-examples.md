---
ID: 8160
post_title: 'Excel DBCS Function &#8211; Definition with Practical Examples!!'
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/excel-dbcs-function-definition-with-practical-examples/
published: true
post_date: 2020-06-12 12:16:06
---
<h2>DBCS Function in Excel:</h2>
Here, in this article, we will illustrate the definition, syntax, and usage of the <strong>DBCS function</strong> in Microsoft Excel 365.
<h2>Jump To:</h2>
<ul>
 	<li><a href="#1"><strong>Definition of DBCS Function</strong></a></li>
 	<li><a href="#2"><strong>DBCS Function - Syntax</strong></a></li>
 	<li><a href="#3"><strong>Examples of DBCS Function</strong></a></li>
 	<li><a href="#4"><strong>Verdict</strong></a></li>
</ul>
<h2 id="1"><strong>Definition of DBCS Function</strong>:</h2>
The <strong>DBCS function</strong> in Excel <strong>converts half-width (single-byte) letters within a character string to full-width (double-byte) characters</strong>. This function is helpful for multiple languages and unique characters. You can also refer to the <a href="https://geekexcel.com/how-to-use-asc-function-in-microsoft-excel-365-with-examples/"><strong>ASC Function in Excel</strong></a> that changes full-width characters into half-width characters.
<ol>
 	<li><strong>Half-width characters</strong> - Numeric characters, alphabetic characters, and symbols are called half-width or single-byte characters. <strong>Example: Hello</strong></li>
 	<li><strong>Full-width characters</strong> - Japanese, Chinese, Korean characters are full-width or double-byte characters as they are twice as wide as normal alphabetic characters. <strong>Example:中华字海</strong></li>
</ol>
<h2 id="2"><strong>DBCS Function - Syntax</strong>:</h2>
The basic syntax of <strong>DBCS </strong><strong>Function</strong> is,
<pre>=DBCS(text)</pre>
<h3>Argument Explanation:</h3>
<ul>
 	<li><strong>Text (Required):</strong> The text that you want to change. It can also be a reference to a cell that contains the text.</li>
</ul>
<strong>Note:</strong> If the text does not contain any half-width letters, then the text will not change.
<h2 id="3">Examples of <strong>DBCS </strong>Function:</h2>
Let's look at some practical examples of <strong>DBCS </strong><strong>Function</strong> and explore how to use it in Microsoft Excel.

<strong>Example 1: Half-width Characters</strong>
<ul>
 	<li>In this example, the input value is entered into the <strong>B4</strong> cell.</li>
 	<li>You have to follow the below syntax of the DBCS function to get the output.</li>
</ul>
<pre>=DBCS(B4)</pre>
[caption id="attachment_8174" align="aligncenter" width="885"]<img class="size-full wp-image-8174" src="https://geekexcel.com/wp-content/uploads/2020/06/db1.png" alt="Example 1" width="885" height="362" /> Example 1[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to execute the formula.</li>
 	<li>Now, the result is returned as output in the <strong>D4 </strong>cell.

[caption id="attachment_8175" align="aligncenter" width="880"]<img class="size-full wp-image-8175" src="https://geekexcel.com/wp-content/uploads/2020/06/db2.png" alt="Example 1 - Output" width="880" height="367" /> Example 1 - Output[/caption]</li>
 	<li>In this example 1, we have given the half-width characters into the DBCS function so it is changed to full-width characters.</li>
 	<li>In another way, you can give the input directly into the formula as shown below.</li>
</ul>
<pre>=DBCS("Hello")</pre>
<strong>Example 2: Full-width Characters</strong>
<ul>
 	<li>In this Example 2, the input value is entered into the <strong>B5</strong> cell.</li>
 	<li>Refer to the below syntax of the <strong>DBCS function</strong> to return the output.</li>
</ul>
<pre>=DBCS(B5)</pre>
[caption id="attachment_8176" align="aligncenter" width="886"]<img class="size-full wp-image-8176" src="https://geekexcel.com/wp-content/uploads/2020/06/db3.png" alt="Example 2" width="886" height="340" /> Example 2[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to execute the formula.</li>
 	<li>Now, the result is returned as output in the <strong>D5 </strong>cell.

[caption id="attachment_8177" align="aligncenter" width="883"]<img class="size-full wp-image-8177" src="https://geekexcel.com/wp-content/uploads/2020/06/db4.png" alt="Example 2 - Output" width="883" height="339" /> Example 2 - Output[/caption]</li>
 	<li>We have given the full-width characters into the DBCS function so it is not changed.</li>
</ul>
<h2 id="4">Verdict:</h2>
The above article illustrated how to use <strong>DBCS </strong><strong>Function</strong> in Excel 365 with clear-cut practical examples. If you found this article useful, kindly share your <strong>comments</strong> in the below section. Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel!!</a></strong> Keep Learning!!
<h2>Related Articles:</h2>
<ul>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/how-to-use-isref-function-in-microsoft-excel-365/" target="_blank" rel="noopener noreferrer"><strong>How To Use ISREF Function in Microsoft Excel 365?</strong></a></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/how-to-use-switch-function-in-microsoft-excel-365/" target="_blank" rel="noopener noreferrer">How to use SWITCH Function in Microsoft Excel 365?</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/use-istext-function-in-microsoft-excel-365-in-easy-ways/" target="_blank" rel="noopener noreferrer">Use ISTEXT Function in Microsoft Excel 365 In Easy Ways!!</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/how-to-use-dollar-function-in-microsoft-excel-365/" target="_blank" rel="noopener noreferrer">How to use DOLLAR Function in Microsoft Excel 365?</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/use-or-function-in-microsoft-excel-365-in-easy-ways/" target="_blank" rel="noopener noreferrer">Use OR Function in Microsoft Excel 365 In Easy Ways!!</a></strong></li>
</ul>