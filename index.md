<h1>Section 1:</h1>
<h2>Introduction to HTML</h2>
<p>Paragraph 1: HTML stands for HyperText Markup Language. It's the fundamental structural language of web pages.</p>
<p>Paragraph 2: HTML is quite easy to learn. All you have to remember is to write your code carefully, making sure you open and close tags correctly. These are tags <code>&lt;h1&gt; &lt;/h1&gt;</code> <code>&lt;p&gt; &lt;/p&gt;</code>. However, some tags do not close. E.G. The code for making a single line break is <code>&lt;br&gt;</code>. It looks like<br>this.<br>And this. <br> A horizontal line is <code>&lt;hr&gt;</code>, which looks like this:<hr> </p>

<h1>Section 2:</h1> 
<h2>Basic text formatting with HTML</h2>
<p>Other useful formatting tags are:</p>
  <ul>
    <li><code>&lt;strong&gt; &lt;/strong&gt;</code> for creating <strong>bold text</strong></li>
    <li><code>&lt;em&gt; &lt;/em&gt;</code> for creating <em>italic text</em></li>
     <li><code>&lt;u&gt; &lt;/u&gt;</code> for creating <u>underlined text</u>. It is generally used for indicating errors (e.g. <u>rong </u>spelling)</li>
    </ul>
<hr>
<h1>Section 3:</h1> 
<h2>Making lists with HTML</h2>
<p>You will notice that in Section 2 above, I used a bullet list to layout the points.</p>
<p>There are two types of list you can make: unordered lists (bullets), and ordered lists (numbers).</p>
<p>The HTML for unordered lists (bullets) is this:</p>
<p><code>&lt;ul&gt; &lt;li&gt;First item &lt;/li&gt; &lt;li&gt;Second item &lt;/li&gt; &lt;/ul&gt;</code></p>
<p>Here is an example of a to-do list:</p>
<ul>
    <li>Check my email.</li>
    <li>Do some research.</li>
    <li>Do my homework.</li>
    </ul>
    
<p>The HTML for ordered lists (numbers) is this:</p>
<p><code>&lt;ol&gt; &lt;li&gt;First item &lt;/li&gt; &lt;li&gt;Second item &lt;/li&gt; &lt;/ol&gt;</code></p>
<p>Here is an example of my top three favourite books:</p>
<ol>
    <li>A Short History of Tractors in Ukrainian.</li>
    <li>The Curious Incident of the Dog in the Night-Time.</li>
    <li>Sophie's World.</li>
    </ol>
<p>So that's it for lists for now.</p>
<hr>

<h1>Section 4:</h1> 
<h2>Inserting links in your HTML</h2>
<p>It's easy to insert a link. But before you do, it's important to understand the difference between <strong><em>relative</em></strong> and <strong><em>absolute</em></strong> links.</p>
<h3>Absolute Links</h3>
<p>An absolute link uses the full URL address of the page you want to link to. This is necessary if you are linking to a page outside of your own website.</p><p> For example: I want to link to the W3Schools HTML Tutorial. Here is the address: <span style="color:green;" https://www.w3schools.com/html/html_basic.asp</span></p>
<p>Here is the code for inserting this link:</p>


