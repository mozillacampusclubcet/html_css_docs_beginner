# A Simple Document

The following is the basic structure of any webpage you actually see.
<pre>
<code class="language-markup">&lt;!DOCTYPE html>
&lt;html>
&lt;head>
&lt;title>Page Title&lt;/title>
&lt;/head>
&lt;body>

&lt;h1>My First Heading&lt;/h1>
&lt;p>My first paragraph.&lt;/p>

&lt;/body>
&lt;/html></code></pre>

### Explanation

#### <!DOCTYPE html>

Once the web browser gets the information from a web server, it has to parse and render the HTML5 page to the user. By default, most web browsers render the response from a webserver as an HTML document unless it is specified otherwise.

To declare a document as an HTML5 document we have to start the document with the declaration tag:
<pre><code class="language-markup">&lt;!DOCTYPE html></code></pre>

Different versions of HTML uses different versions of the declaration tag for the purpose.

#### &lt;html>

All the other tags of HTML should go inside the <code>&lt;html></code> tag and the <code>&lt;/html></code> so that it is properly rendered as an HTML webpage.

<pre><code class="language-markup">&lt;!DOCTYPE html>
&lt;html>
The other tags go in here.
&lt;/html></code></pre>

#### &lt;head>

<code>&lt;head></code> tag identifies the head section of a webpage.

<pre><code class="language-markup">&lt;!DOCTYPE html>
&lt;html>
&lt;head>
The &lt;title> and friends go in here.
&lt;/head>
The other tags go in here.
&lt;/html></code></pre>
