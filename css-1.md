<h1>HTML and CSS Part 1</h1>
<h2>1. Making Images Clickable</h2>
<p>Sometimes it can be helpful for your page visitors to view images in a larger window. This can be done by adding a <code> &lt;a href=""  </code> tag around the image. This is also useful if you want an image to link to another website or page in your own website.<p>
<p>Here is an example of an image from Wikipedia that is now clickable</p>
<p>
<a href="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" title="View Image Source">
<img src="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" alt="image of biogeography of Europe"></a>
</p>
<div class="clearLeft"></div>

<p>Ths code for this is:</p>
<code>
&lt;a href="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" title="View Image Source"&gt;
  
  
&lt;img  src="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" alt="image of biogeography of Europe"&gt;


&lt;/a&gt;
</code>
<p>Look at the above lines of code carefully. Notice the order in which the tags are placed:</p> 

<ol>
<li>We open the familiar link tag: <code> &lt;a href="" </code> and include the URL of the image source. Notice also that we can add a <code> title= </code> attribute to the tag. The title attribute specifies text that appears over the image when the user hovers their mouse on the image.</li>
<li>Next, we have the familiar image tag: <code> &lt;img src="" </code>. You will notice that in this case the URL to the image is the same as in the href tag.</li>
<li>Finally, we must close the <code> &lt;/a&gt; </code> tag.</li>
</ol>

<h2>2. Changing the size of the image on the page.</h2>
<p>Sometimes we might want our image to occupy less space on the page. This can be done by adding a style attribute to the tag.</p>
<p>Here is an example of a simple style attribute added to the image tag that specifies the image to occupy only 70% of the width of the page content area: <code> style="width:70%; </code>.</p>

<p>In the example above, the word <code>width</code> is known as a style <strong>property</strong>, and the number <code>70%</code> is called the <strong>value</strong>. Notice that the propery and value are separated by a colon (:). </p>

<p> The Mozilla Developer Network provides a <a href="https://developer.mozilla.org/en-US/docs/Web/CSS/Reference#Keyword_index">full reference for all possible style properties</a>. <b>But you don't need to worry about learning them all! Just a few are useful for our purposes.</b></p>
<p>We can add other properties and values to our style entry. For example: <code> style="width:70%; border:1px solid green; </code>. Adding the 'border' property specifies a border around the image. In this example, the border property is followed by 3 values: <code> 1px solid green </code>. This means the border will be a solid green line, one pixel thick.</p>
<p>Notice that to add a new property to the style, we need to put a semi-colon after the previous property:value pair.</p>
<p>So the full code for our image tag would now look like this:</p>
<code> 
&lt;img style="width:70%; border:1px solid green;" src="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" alt="image of biogeography of Europe" &gt;
</code>

<p>And the result is this:</p>
<p>
<a href="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" title="View Image Source">
<img style="width:70%; border:1px solid green;" src="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" alt="image of biogeography of Europe"></a>
</p>

<h3>Centering the image on the page.</h3>
<p>This time, the image is centred.</p>
<a href="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" title="View Image Source">
<img style="width:70%; border:1px solid green; margin-left:15%;" src="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" alt="image of biogeography of Europe"></a>
<p>To centre the image, it's necessary to make a small calculation. In our example, this is as follows:</p>


<p style="margin-left:1rem; margin-right:1rem; padding:.3rem; background-color:#f6f8fc;">
page content width = 100%<br>
image width = 70%<br>
remaining content width = 30%<br>
So,to centre image we need:<br>
15% + 70% + 15% = 100%
</p>
<p>In our image, we specified the width to be 70%. This means the image uses 70% of the 100% content area available. By default, the image is positioned to the left of the content area. This means that to right of the image, 30% of the page width is blank. So, to centre the image, we need to put a space of 15% to the left of the image.</p> 
  
<p>To do this, we use a style property known as <code> margin-left </code> with a value of 15% (half of the blank space).</p>
<p>The <code> margin-left </code> property specifies a distance of x between the left-hand edge of the image and the left-hand edge of the  content area - just like a margin on a paper page.</p> 
<p>So, here is the modified image style code:</p>
<code> 
&lt;img style="width:70%; border:1px solid green; margin-left:15%" src="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" alt="image of biogeography of Europe" &gt;
</code>

