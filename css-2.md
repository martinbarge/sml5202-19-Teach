<h1>HTML and CSS Part 2</h1>
<h2>1. Using an external stylesheet</h2>
<p>We now know we can insert style rules into HTML tags, using the <code> style="" </code> attribute.</p>
<p>However, a more efficient way to accomplish this is by using an external stylesheet. Using an external stylesheet enables us to specify a set of style rules that we can then apply within our HTML tags. The following is a brief outline of how this works:</p>
<p>OUTLINE</p>

<p>You remember from previous practice, that we can insert an image into our page, like this:</p>
<img src="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" alt="image of biogeography of Europe">
</p>
<div class="clearLeft"></div>

<p>To recap, the code for this is:</p>
<code>
&lt;img  src="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" alt="image of biogeography of Europe"&gt;
</code>
<p>And we have seen that by inserting a style rule into the tag, we can manipulate the position of the image, like this:</p> 
<img style="width:50%; border:1px solid green;" src="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" alt="image of biogeography of Europe"></a>

<p>The style rule for this is:</p>
<code> 
&lt;img style="width:50%; border:1px solid green;" src="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" alt="image of biogeography of Europe" &gt;
</code>

<p>Now we are going to see how to wrap text alongside the image, which is a good way to place an image within a paragraph of text. Here is the above image with text wrapped to the right.</p>

<p>
<img style="width:70%; border:1px solid green; float:left; margin: 0 10px 10px 0;" src="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" alt="image of biogeography of Europe">
The map to the left shows the biogeography of Europe. Biogeography is the study of the distribution of species and ecosystems in geographic space and through geological time. Organisms and biological communities often vary in a regular fashion along geographic gradients of latitude, elevation, isolation and habitat area. Phytogeography is the branch of biogeography that studies the distribution of plants. Zoogeography is the branch that studies distribution of animals. Source: <a href="https://en.wikipedia.org/wiki/Biogeography">Wikipedia</a>

</p>

<p>The style rule for the above now looks like this:</p>
<code> 
&lt;img style="width:50%; border:1px solid green; float:left; margin: 0 10px 10px 0;" src="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" alt="image of biogeography of Europe" &gt;
</code>
<p>As you can see, the style rule is becoming quite long and complex. This makes it more difficult to read, to detect errors, and is time-consuming to include in every image on your website that you wish to apply the style to.</p>
<p>So this where an external style sheet proves indispensible.</p>


<h2>Adding external style sheets.</h2>
<p>The first thing we need to do is set up the external stylesheet. An external stylesheet is simply a file containing the style rules you want your site to use. On a GitHub pages site, we have to create two new directories and the file, like this:</p>
<ol>
  <li>In your site code repository add a new file: assets/css/style.scss</li>
  <li>Insert the following lines exactly as shown to the top of the style.scss file: <img src="assets/img/scss-file-1.png"></li>
  <li>Next, add the following code below the lines shown in the image above: <img src="assets/img/imgleft-code.png"></li>
</ol>
  

