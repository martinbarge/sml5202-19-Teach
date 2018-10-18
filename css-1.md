<h1>HTML and CSS Part 1</h1>
<h2>Making Images Clickable</h2>
<p>Sometimes it can be helpful for your page visitors to view images in a larger window. This can be done by adding a <code> &lt;a href=&gt; </code> tag around the image. This is also useful if you want an image to link to another website or page in your own website.<p>
<p>Here is an example of an image from Wikipedia that is now clickable</p>
<p>
<a href="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" title="View Image Source">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" alt="image of biogeography of Europe"></a>
</p>
<div class="clearLeft"></div>

<p>Ths code for this is:</p>
<code>
&lt;a href="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" title="View Image Source"&gt;
<br>
&lt;img  src="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" alt="image of biogeography of Europe"&gt;
  &lt;/a&gt;
</code>



<a href="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" title="View Image Source">
<img class="imgLeft" style="width:70%; vertical-align:top; border:1px solid #021a40;" src="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" alt="image of biogeography of Europe"></a>

