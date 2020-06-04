---
ID: 4820
post_title: >
  How to Validate Maximum Length of a Text
  in Microsoft Excel 365?
author: Merin
post_excerpt: ""
layout: post
permalink: >
  https://geekexcel.com/how-to-validate-maximum-length-of-a-text-in-microsoft-excel-365/
published: true
post_date: 2020-03-11 16:59:01
---
<strong>Validate a Text Length: </strong>Excel comes up with several<strong> Data Validation</strong> options to validate your data in Excel. In this article, we will guide you to <strong>validate the maximum length of the text</strong> <strong>in Excel 365.</strong>
<h2>Index:</h2>
<ul>
 	<li><a href="#val-1"><strong>Validate a Text Length in Excel</strong></a></li>
 	<li><a href="#val-2"><strong>A Short Summary</strong></a></li>
</ul>
<h2 id="val-1">Validate a Text Length in Excel:</h2>
<ul>
 	<li>Open a New Excel sheet.</li>
 	<li>Consider the following example, select the columns where you want to apply the data validation.</li>
</ul>
<ul>
 	<li>The <strong>Data Validation Option</strong> is available on the <strong>Data Menu</strong>. Just click on the <strong>Data Validation Option.</strong></li>
</ul>
[caption id="attachment_4831" align="aligncenter" width="1354"]<img class="size-full wp-image-4831" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_6-20.png" alt="Data Validation Option" width="1354" height="461" /> Data Validation Option[/caption]
<ul>
 	<li>The <strong>Data Validation window</strong> will open.</li>
 	<li>In the<strong> settings tab</strong>, you can find the <strong>validation criteria.</strong></li>
 	<li>Click on the <strong>drop-down</strong> and then select the <strong>Text Length</strong> option.</li>
</ul>
[caption id="attachment_4830" align="alignnone" width="1365"]<img class="wp-image-4830 size-full" style="font-size: 19px; font-weight: 600;" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_2-37.png" alt="Select Text Length" width="1365" height="453" /> Select Text Length[/caption]
<ul>
 	<li>Click on the <strong>drop-down</strong> of the <strong>Data</strong> section and then select <strong>between</strong> option.</li>
</ul>
[caption id="attachment_4834" align="aligncenter" width="1365"]<img class="size-full wp-image-4834" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_7-13.png" alt="Select between Option" width="1365" height="389" /> Select between Option[/caption]
<ul>
 	<li>We have mentioned the <strong>maximum length</strong> for the text as <strong>10</strong> and the <strong>minimum length </strong>as <strong>2</strong></li>
</ul>
[caption id="attachment_4840" align="aligncenter" width="1363"]<img class="size-full wp-image-4840" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_11-3.png" alt="max and min length for the text" width="1363" height="394" /> max and min length for the text[/caption]
<ul>
 	<li>You can customize the <strong>Input Message</strong> and <strong>Error Alert</strong> as per your convenience. Otherwise, click <strong>OK.</strong></li>
</ul>
[caption id="attachment_4839" align="alignnone" width="1365"]<img class="wp-image-4839 size-full" style="font-size: 19px; font-weight: 600;" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_8-10.png" alt="max and min length for the text" width="1365" height="411" /> Click OK[/caption]
<ul>
 	<li><strong>Input Message: </strong>This message will be displayed when you click on the cell.</li>
</ul>
[caption id="attachment_4841" align="aligncenter" width="1365"]<img class="size-full wp-image-4841" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_10-4.png" alt="Input Message" width="1365" height="438" /> Input Message[/caption]

[caption id="attachment_4842" align="aligncenter" width="1364"]<img class="size-full wp-image-4842" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_12-1.png" alt="Input Message Example" width="1364" height="344" /> Input Message Example[/caption]
<ul>
 	<li><strong>Error Message:</strong> This message will be displayed in the error dialogue box.</li>
</ul>
[caption id="attachment_4843" align="aligncenter" width="1365"]<img class="size-full wp-image-4843" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_9-4.png" alt="Error Message" width="1365" height="415" /> Error Message[/caption]
<ul>
 	<li>Finally, click <strong>OK</strong> in the <strong>Data Validation</strong> window.</li>
 	<li>Let's validate the length of the text by the following examples.</li>
</ul>
[caption id="attachment_4875" align="aligncenter" width="1280"]<img class="size-full wp-image-4875" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_18.png" alt="Data Validation Example" width="1280" height="349" /> Data Validation Example[/caption]

If the names are entered as per the given validation rules then Excel will not show any error.

[caption id="attachment_4844" align="aligncenter" width="1365"]<img class="size-full wp-image-4844" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_13-1.png" alt="Data Validation example 1" width="1365" height="286" /> Data Validation example 1[/caption]
<ul>
 	<li>The given <strong>minimum value for the text length</strong> is <strong>2</strong> so that if you enter any word above <strong>2</strong> characters the Excel will show you an error. For example, when you enter the text <strong>S</strong> in the <strong>NAME</strong> column then Excel will show you an error as <strong>"NOT A VALID NAME".</strong></li>
</ul>
[caption id="attachment_4845" align="alignnone" width="1363"]<img class="wp-image-4845 size-full" style="font-size: 19px; font-weight: 600;" src="https://geekexcel.com/wp-content/uploads/2020/03/Screenshot_14.png" alt="Data Validation example 2" width="1363" height="351" /> Data Validation example 2[/caption]
<ul>
 	<li>The given <strong>maximum value for the text length</strong> is <strong>8</strong> so that if you enter any word above <strong>8</strong> characters the Excel will show you an error. For example, when you enter the text <strong>ROSLIN PARKER</strong> in the <strong>NAME</strong> column then Excel will show you an error as <strong>"NOT A VALID NAME".</strong></li>
</ul>
<h2 id="val-2">A Short Summary:</h2>
<p style="text-align: left;">We hope that the above article demonstrated the concept of <strong>Validating the Maximum Text Length in Excel 365. </strong>Excel allows the user to validate their data with the help of the <strong>Data Validation</strong> feature. Please share your <strong>queries/suggestions</strong> in the comment section. Thank you for visiting our website <a href="https://geekexcel.com/"><strong>GeekExcel</strong></a>.</p>

<h2>Related Article:</h2>
<ol>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/how-to-format-a-text-number-as-a-subscript-in-excel-365/" target="_blank" rel="noopener noreferrer">How to Format a Text/Number as a Subscript in Excel 365?</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/how-to-top-align-a-text-in-microsoft-excel-365/" target="_blank" rel="noopener noreferrer">How to Top Align a Text in Microsoft Excel 365?</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/how-to-merge-or-combine-cells-in-microsoft-excel-365/" target="_blank" rel="noopener noreferrer">How to Merge or Combine Cells in Microsoft Excel 365?</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/how-to-rotate-a-cell-text-in-microsoft-excel-365/" target="_blank" rel="noopener noreferrer">How to Rotate a Cell Text in Microsoft Excel 365?</a></strong></li>
 	<li><strong><a class="LinkSuggestion__Link-sc-1mdih4x-2 jZPuuT" href="https://geekexcel.com/how-to-use-format-painter-in-microsoft-excel-365/" target="_blank" rel="noopener noreferrer">How to Use Format Painter in Microsoft Excel 365?</a></strong></li>
</ol>