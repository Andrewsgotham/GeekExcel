---
ID: 3927
post_title: >
  How to Create Custom ADD Function in
  Excel 365?
author: Merin
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-create-custom-add-function-in-excel-365/
published: true
post_date: 2020-02-21 11:31:49
---
In spite of all the default functions provided by Excel you may need custom functions for your needs, In that case, Excel 365 allows you to create your own custom Excel functions with the help of <strong>VSB Programming Codes</strong>. Now let's see how to create<strong> custom ADD function</strong> in Excel 365.
<h2>Jump To:</h2>
<ul>
 	<li><a href="#1"><strong>"Add" function definition and syntax</strong></a></li>
 	<li><a href="#2"><strong>Instruction to create custom function "Add"</strong></a></li>
 	<li><a href="#3"><strong>VSB code for the "Add" function</strong></a></li>
 	<li><a href="#4"><strong>Guidelines to Insert "Add" function in  Excel 365</strong></a></li>
 	<li><a href="#5"><strong>Practical Examples using "Add" function</strong></a></li>
 	<li><a href="#6"><strong>A Short Summary</strong></a></li>
</ul>
<h2 id="1">"Add" Function Definition:</h2>
The Add function used to add numbers that could be any type of numbers like Integer or  Float. the syntax for add function is
<pre>=Add(Number1,Number2)</pre>
Add function Adds Number1 and Number2. and produce the result.
<h2 id="2">Instruction to create the custom function "Add":</h2>
<ul>
 	<li>Open Excel 365, And use the shortcut key <strong>ALT+F11</strong>.</li>
 	<li>Now the <strong>Microsoft Visual Basic</strong> <strong>Window</strong> will open.</li>
 	<li><strong>In the right sidebar, Right-click on the sheet1 and select the Insert option and then select the Module option.</strong></li>
 	<li>Now a new<strong> Module window</strong> will open.</li>
</ul>
[caption id="attachment_3929" align="aligncenter" width="1222"]<img class="size-full wp-image-3929" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_6-2.png" alt="VSB function add" width="1222" height="445" /> VSB Insert Module[/caption]
<h2 id="3">VSB code for the "Add" function:</h2>
<ul>
 	<li>Just type the following VSB code in the Module Window to create Add custom function in excel 365.</li>
</ul>
<pre class="code">Public Function Add(number1 As Double, number2 As Double)
Add = number1 + number2
End Function</pre>
Now, click the <strong>Menubar </strong>then click on the <strong>File Menu and Save the Workbook in visual basic</strong> and close the <strong>Visual Basic.</strong>

[caption id="attachment_3930" align="aligncenter" width="1230"]<img class="size-full wp-image-3930" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_5-1.png" alt="VSB file save " width="1230" height="362" /> VSB file save[/caption]
<h2 id="4">Guidelines to Insert "Add" function in  Excel 365:</h2>
<ul>
 	<li>Open Excel 365, Click on the <strong>Formulas</strong> T<strong>ab.</strong></li>
 	<li>Click the <strong>Insert Function fx.</strong></li>
 	<li>Now, <strong>Insert function Dialogue Box </strong>will open.</li>
 	<li>In the <strong>Select Category</strong> list box, select<strong> User Defined</strong> <strong>Catagory</strong>.</li>
 	<li>Select the <strong>Add</strong> function from the list and click the <strong>OK Button</strong></li>
</ul>
<img class="size-full wp-image-3931" style="font-size: 19px; font-weight: 600;" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_1-3.png" alt="Insert Add Function" width="1059" height="543" />

Insert Add Function
<h2 id="5">Practical Examples using "Add" function:</h2>
<ul>
 	<li>Now the <strong>F</strong><strong>unction Arguments window </strong>will open. In that, you need to enter the numbers you want to add and <strong>click the ok button</strong> then you will find the result in the output cell.</li>
</ul>
[caption id="attachment_3932" align="aligncenter" width="780"]<img class="size-full wp-image-3932" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_2-3.png" alt="Add Function Argument Window" width="780" height="400" /> Add Function Argument Window[/caption]
<ul>
 	<li>Now type the formula =Add(Number1, Number2) and it will print the result in the output cell.</li>
</ul>
[caption id="attachment_3933" align="aligncenter" width="658"]<img class="size-full wp-image-3933" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_3-2.png" alt="Add Function in Excel" width="658" height="274" /> Add Function in Excel[/caption]
<ul>
 	<li>Take the numbers <strong>14</strong> and <strong>67</strong> as an example for the Add Function. The Add Function will generate the result (<strong>81</strong>) in the output cell.</li>
</ul>
[caption id="attachment_3934" align="aligncenter" width="652"]<img class="size-full wp-image-3934" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_4-3.png" alt="Example Add Function" width="652" height="231" /> Example Add Function[/caption]

Let's take float numbers<strong> 34.7</strong> and <strong>22.5 </strong> as an example. Add function will generate the result as <strong>57.2</strong>.

[caption id="attachment_3935" align="aligncenter" width="630"]<img class="size-full wp-image-3935" src="https://geekexcel.com/wp-content/uploads/2020/02/Screenshot_7-2.png" alt="Add Function with Decimal Number " width="630" height="230" /> Add Function with Float Number[/caption]
<h2 id="6">A Quick Summary:</h2>
This article gives you the complete tutorial about using custom functions in excel. please leave a reply in case of <strong>queries</strong> and comment your valuable <strong>suggestions</strong>.