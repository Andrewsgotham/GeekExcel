---
ID: 3985
post_title: >
  How to Use Logical Function AND in Excel
  365?
author: Merin
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-use-logical-function-and-in-excel-365/
published: true
post_date: 2020-02-24 11:52:38
---
AND Logical Function: Logical Functions are used to compare data from different cells. <strong>AND Logical Function</strong> checks <strong>M</strong><strong>ultiple Conditions</strong> and returns <strong>TRUE </strong>if all the conditions are evaluated as true otherwise returns <strong>FALSE.</strong>
<h3>Jump To:</h3>
<ul>
 	<li><a href="#and-1"><strong>AND Function Definition and Syntax</strong></a></li>
 	<li><strong><a href="#and-2">AND Function with Formula Description</a></strong></li>
 	<li><strong><a href="#and-3">AND Function with related examples</a></strong></li>
 	<li><strong><a href="#and-4">A Short Summary</a></strong></li>
</ul>
<h2 id="and-1">AND Logical Function Definition and Syntax:</h2>
The AND function is the most popular Logic Function. Technically AND will check all the conditions you specify and returns <strong>TRUE</strong> only when if all the conditions evaluated as true otherwise if anyone condition failed then <strong>AND</strong> function will return <strong>FALSE. </strong>You can use AND Function if you want to check several conditions. The syntax for the Excel AND function is as follows:
<pre>=AND(logical1, [logical2], …)</pre>
<h2 id="and-2">AND Function with Formula Description:</h2>
Let's evaluate AND function formula

[caption id="attachment_4010" align="aligncenter" width="717"]<img class="size-full wp-image-4010" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_6-7.png" alt="A Store Particulars" width="717" height="243" /> A Store Particulars[/caption]
<h3>Formula:</h3>
<strong>=AND(B5="Orange",C5&gt;D5) ----&gt; </strong>Returns TRUE only when B5 cell contains "Orange" and C5 is greater then D5. Otherwise, return FALSE.
<strong>=AND(B6="Apple",C6=50,C6&gt;D6)----&gt; </strong>Returns TRUE only when B6 cell contains "Orange" and C6 contains the value of 50 C6 is greater then D6. Otherwise returns FALSE.
<h2 id="and-3">AND Function with Related Examples:</h2>
Look at the following example that will demonstrate to you the usage AND Function in Excel.
<strong>Example-1:</strong>

[caption id="attachment_4011" align="aligncenter" width="700"]<img class="size-full wp-image-4011" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_7-5.png" alt="AND Function Example-1" width="700" height="313" /> AND Function Example-1[/caption]

In the first condition, the <strong>B5</strong> cell holds the value of <strong>Orange</strong> and the cell value of <strong>C5</strong> (<strong>50</strong>) is greater than <strong>D5</strong> (<strong>40</strong>) both the conditions are true so the AND Function returns <strong>TRUE</strong> as the Output.

<strong>Example-2:</strong>

[caption id="attachment_4012" align="aligncenter" width="717"]<img class="size-full wp-image-4012" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_8-3.png" alt="AND Function Example-2" width="717" height="292" /> AND Function Example-2[/caption]

In the second condition, the <strong>B6</strong> cell holds the value of <strong>Apple</strong> and the cell value of <strong>C6</strong> (<strong>50</strong>) value is equal to <strong>50. </strong>and the cell value of <strong>C6 (50) </strong> is greater than <strong>D6</strong> (<strong>3</strong><strong>0</strong>) all the three conditions are true so the AND Function returns <strong>TRUE</strong> as the Output.

<strong>Example-3:</strong>

[caption id="attachment_4013" align="aligncenter" width="716"]<img class="size-full wp-image-4013" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_9-2.png" alt="AND Function Example-3" width="716" height="310" /> AND Function Example-3[/caption]

In the third condition, the <strong>B7</strong> cell holds the value of <strong>Graphs</strong> and the cell value of <strong>C7</strong> (<strong>50</strong>) is not greater than <strong>D7</strong> (<strong>5</strong><strong>0</strong>) the cell values are not equal. If anyone condition is False then the AND Function will return <b>FALSE </b>as the Output.
<h2 id="and-4">A Short Summary:</h2>
This Article demonstrates the syntax, definition, and the formula usage of <strong>AND Function in Excel 365.</strong> We have discussed the AND Logical Function usages with the practical examples. Stay connected to get instant updates and leave your <strong>Q</strong><strong>ueries/Suggestions</strong> in the comment box.