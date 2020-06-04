---
ID: 7575
post_title: 'Excel TEXTJOIN Function &#8211; Definition with Examples!!'
author: Katy
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/excel-textjoin-function-definition-with-examples/
published: true
post_date: 2020-06-04 17:22:45
---
<h2>TEXTJOIN Function in Excel:</h2>
Here, in this article, we will illustrate the definition, syntax, and usage of the <strong>TEXTJOIN function</strong> in Microsoft Excel 365.
<h2>Jump To:</h2>
<ul>
 	<li><a href="#1"><strong>Definition of TEXTJOIN Function</strong></a></li>
 	<li><a href="#2"><strong>TEXTJOIN Function - Syntax</strong></a></li>
 	<li><a href="#3"><strong>Examples of TEXTJOIN Function</strong></a></li>
 	<li><a href="#4"><strong>Verdict</strong></a></li>
</ul>
<h2 id="1"><strong>Definition of TEXTJOIN Function</strong>:</h2>
The Excel TEXTJOIN Function concatenates or joins values with a given delimiter separating each value. This function will efficiently concatenate the ranges if the delimiter is an empty text string.
<h2 id="2"><strong>TEXTJOIN Function - Syntax</strong>:</h2>
The basic syntax of <strong>TEXTJOIN </strong><strong>Function</strong> is,
<pre>=TEXTJOIN(delimiter, ignore_empty, text1, [text2], …)</pre>
<h3>Argument Explanation:</h3>
<ul>
 	<li><strong>Delimiter (Required): </strong>The string or separator that is inserted between each text value. It can be empty/one or more characters enclosed by double-quotes.</li>
 	<li><strong>Ignore_empty (Required): </strong>TRUE - Ignores empty cells. FALSE - Include empty cells.</li>
 	<li><strong>Text 1 (Required): </strong>Text value that needs to be concatenated. It can be a text string or a range of cells or an array of strings.</li>
 	<li>Text 2 (Optional): Second text value or range.</li>
</ul>
<h2 id="3">Examples of TEXTJOIN Function:</h2>
Let's look at some practical examples of <strong>TEXTJOIN Function</strong> and explore how to use it in Microsoft Excel.

<strong>Example 1: Joining Two Text Strings</strong>
<ul>
 	<li>In this basic example, we would like to join the texts in <strong>B4 and C4</strong> cells.</li>
 	<li>Here, we have given ignore_empty argument as TRUE to ignore the empty cells.</li>
 	<li>Refer to the below syntax of the <strong>TEXTJOIN function</strong> to return the output in the given format.</li>
</ul>
<pre>=TEXTJOIN("-",TRUE,B4,C4)</pre>
[caption id="attachment_7580" align="aligncenter" width="667"]<img class="size-full wp-image-7580" src="https://geekexcel.com/wp-content/uploads/2020/06/tj1.png" alt="Example 1" width="667" height="334" /> Example 1[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to execute the formula.

[caption id="attachment_7581" align="aligncenter" width="591"]<img class="size-full wp-image-7581" src="https://geekexcel.com/wp-content/uploads/2020/06/tj2.png" alt="Example 1- Output" width="591" height="315" /> Example 1- Output[/caption]</li>
 	<li>Now, the result is returned as output in the <strong>E4</strong> cell.</li>
</ul>
<strong>Example 2: To join cells in the range with no delimiter</strong>
<ul>
 	<li>Here, we are going to join cells in the range (B5: C7) without mentioning the delimiter.</li>
 	<li>Refer to the below syntax of the <strong>TEXTJOIN function</strong> to return the output in the given format.</li>
 	<li>Here, we have given ignore_empty argument as FALSE to include the empty cells.</li>
</ul>
<pre>=TEXTJOIN("",FALSE, B5:C7)</pre>
[caption id="attachment_7582" align="aligncenter" width="675"]<img class="size-full wp-image-7582" src="https://geekexcel.com/wp-content/uploads/2020/06/tj3.png" alt="Example 2" width="675" height="361" /> Example 2[/caption]
<ul>
 	<li>Click <strong>Enter</strong> to execute the formula.</li>
 	<li>Now, the result is returned as output in the <strong>E5</strong> cell.

[caption id="attachment_7583" align="aligncenter" width="677"]<img class="size-full wp-image-7583" src="https://geekexcel.com/wp-content/uploads/2020/06/tj4.png" alt="Example 2- Output" width="677" height="312" /> Example 2- Output[/caption]</li>
 	<li>As we have mentioned to include empty cells, so you can space between the texts in the output.</li>
</ul>
<h2 id="4">Verdict:</h2>
The above article illustrated how to use <strong>TEXTJOIN Function</strong> in Excel with clear-cut practical examples. If you found this article useful, kindly share your <strong>comments</strong> in the below section. Thanks for visiting <strong><a href="https://geekexcel.com/">Geek Excel!!</a></strong> Keep Learning!!
<h2>Related Articles:</h2>
<ul>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/how-to-use-text-function-in-microsoft-excel-365/" target="_blank" rel="noopener noreferrer">How to use TEXT Function in Microsoft Excel 365?</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/use-indirect-function-in-microsoft-excel-365-in-easy-ways/" target="_blank" rel="noopener noreferrer">Use INDIRECT Function in Microsoft Excel 365 In Easy Ways!!</a></li>
 	<li><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/how-to-use-char-function-in-microsoft-excel-365/" target="_blank" rel="noopener noreferrer">How to use CHAR Function in Microsoft Excel 365?</a></li>
</ul>