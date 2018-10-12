<h1>HTML Part 2: More text layouts</h1>
<h2>Images</h2>
<p>You can reference images from other web hosts, or you can upload an image to your GitHub repository and reference that.<p>
<p>First we will reference an image hosted on Wikipedia</p>
<img src="https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg" alt="image of biogeography of Europe">
<p>The code for inserting images is: &lt;img src="URL OF IMAGE" alt="DESCRIPTION OF IMAGE" &gt;</p>
<p>In the example above, the image src is https://upload.wikimedia.org/wikipedia/commons/3/39/Europe_biogeography_countries.svg </p>
<p>You will notice that the image fills the width of the content area. This is okay for this exercise. Later we will look at how to modify the width settings of the image.</p>

<hr>

<h2>2. Description lists</h2>
<p>Description lists are good for giving definitions</p>
<dl>
  <dt>soliloquy</dt>
  <dd>In drama, where a character speaks to themselves, representing their inner thoughts or feelings and in the process relaying them to the audience (but not to other characters.)</dd>
  <dt>monologue</dt>
  <dd>In drama, where a character speaks their thoughts out loud to share them with the audience and any other characters present.</dd>
  <dt>aside</dt>
  <dd>In drama, where a character shares a comment only with the audience for humorous or dramatic effect. This is usually a feeling, thought, or piece of additional background information.</dd>
</dl>
<p>The code for inserting description lists is similar to that for ordered and unordered lists. But it uses three tags: &lt;dl&gt; ... &lt;/dl&gt;</p>, which opens and closes the list. Then &lt;dt&gt;...&lt;/dt&gt;, which inserts the description term. Inside the dt tag you insert the description definition tag to provide the description: &lt;dd&gt;...&lt;/dd&gt;</p>

<hr>
<h2>3. Tables</h2>
<p>Tables are an orderly way to present information.</p>
<p>Here is an example of a simple verb table:</p>
<table>
  <tr><th>Infinitive</th><th>Past simple</th><th>Past participle</th></tr>
  <tr>
    <td>to go</td><td>went</td><td>gone/been</td>
  </tr>
   <tr>
    <td>to have</td><td>had</td><td>had</td>
  </tr>
  <tr>
    <td>to come</td><td>came</td><td>come</td>
  </tr>
  </table>
  

<hr>

<h2>4. Block quotes</h2>
<p>Using the blockquote tag places quoted text in a pleasingly formatted way. <b>Note:</b> If your quote is in verse form, you will need to use the &lt;br&gt; tag to break the lines.</p>
<p>Here is an example of a verse of poetry in a block quote:</p>

<blockquote cite="https://en.wikipedia.org/wiki/To_be,_or_not_to_be">
  <p>Along the Road</p>
  <p>
    &ldquo;I walked a mile with Pleasure;<br>
    She chatted all the way;<br>
    But left me none the wiser<br>
    For all she had to say.
  </p>
  <p>I walked a mile with Sorrow;<br>
    And ne’er a word said she;<br>
    But, oh! The things I learned from her,<br>
    When Sorrow walked with me.&rdquo;
    </p>
  <p>-Robert Browning Hamilton</p>
</blockquote>
<hr>

<h2>5. Superscript</h2>
<p>Useful for dates</p>
<p>My birthday is on the 25<sup>th</sup> of May 2001.</p>
<hr>

<h2>6. Accented and Non-Latin Characters</h2>
<p>GitHub pages use the UTF-8 Character set. This means you can type accented letters directly into your page and it will display correctly</p>
<p>Examples:</p>
<ul>
    <li lang="pl">jabłko</li>
    <li lang="ru">Доброе утро</li>
    <li lang="zh-Hans">你好</li>
</ul>
<p>However, if you recall, in order for screen reading software to pronounce the words correctly, you need to add the &lt;lang="X"&gt; attribute to the tag, where X is the abbreviated language code.<br>
  <b>For example:</b> In the list above, the tag for the Polish word is &lt;li lang="pl"&gt;, where pl is the abbreviated language code for Polish. The language code for the Russian word is "ru" and for the Chinese word "zh-Hans". A full listing of the language codes is provided on the <a href="https://www.w3schools.com/tags/ref_language_codes.asp">W3Schools Website</a>.
</p>

<hr>

