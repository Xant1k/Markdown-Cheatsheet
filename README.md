# Markdown-Cheatsheet

Markdown editing help

https://help.github.com/categories/writing-on-github/
http://cheatsheet.aboutmde.org/#
http://mdp.tylingsoft.com/#
https://daringfireball.net/projects/markdown/syntax

Emoji: http://www.webpagefx.com/tools/emoji-cheat-sheet/


<div class="table-responsive">
    <table class="table table-striped table-bordered table-hover tablefiltrable">
    <thead>
    <tr>
        <th>Type</th>
        <th>Name</th>
        <th>Sample</th>
        <th>Rendering</th>
    </tr>
    </thead>
    <tbody>


    <tr data-rows="2">
        <td rowspan="2" data-filter-value="typographic">
            <abbr title="Typographic">T</abbr>
        </td>
        <td id="strong" rowspan="2" data-filter-value="strong">
            strong
        </td>
    
	    
		# Heading Level 1
```
# Heading Level 1
```

## Heading Level 2
```
## Heading Level 2
```

### Heading Level 3
```
### Heading Level 3
```

        <td class="large"><pre># Heading Level 1</pre></td>
        <td class="large"><p><strong>```
# Heading Level 1
```</strong></p>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>__hello__</pre></td>
        <td class="large"><p><strong>hello</strong></p>
</td>
    </tr>
        
	

    <tr data-rows="2">
        <td rowspan="2" data-filter-value="typographic">
            <abbr title="Typographic">T</abbr>
        </td>
        <td id="italic" rowspan="2" data-filter-value="italic">
            italic
        </td>
    
	    
		
        <td class="large"><pre>*hello*</pre></td>
        <td class="large"><p><em>hello</em></p>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>_hello_</pre></td>
        <td class="large"><p><em>hello</em></p>
</td>
    </tr>
        
	

    <tr data-rows="3">
        <td rowspan="3" data-filter-value="typographic">
            <abbr title="Typographic">T</abbr>
        </td>
        <td id="link" rowspan="3" data-filter-value="link">
            link
        </td>
    
	    
		
        <td class="large"><pre><http: example.com=""></http:></pre></td>
        <td class="large"><p><a href="http://example.com/">http://example.com/</a></p>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre><email@example.com></email@example.com></pre></td>
        <td class="large"><p><a href="mailto:email@example.com">email@example.com</a></p>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>[an hypertext link](http://example.com/ "Optional link title")</pre></td>
        <td class="large"><p><a href="http://example.com/" title="Optional link title">an hypertext link</a></p>
</td>
    </tr>
        
	

    <tr data-rows="1">
        <td rowspan="1" data-filter-value="typographic">
            <abbr title="Typographic">T</abbr>
        </td>
        <td id="anchor" rowspan="1" data-filter-value="anchor">
            anchor
        </td>
    
	    
		
        <td class="large"><pre>## title with anchor {#anchor}

some text

a link to [declared anchor](#anchor)</pre></td>
        <td class="large"><h2 id="title-with-anchor-anchor-">title with anchor {#anchor}</h2>
<p>some text</p>
<p>a link to <a href="#anchor">declared anchor</a></p>
</td>
    </tr>
        
	

    <tr data-rows="1">
        <td rowspan="1" data-filter-value="typographic">
            <abbr title="Typographic">T</abbr>
        </td>
        <td id="code" rowspan="1" data-filter-value="code">
            code
        </td>
    
	    
		
        <td class="large" style=""><pre>`function()`</pre></td>
        <td class="large"><p><code>function()</code></p>
</td>
    </tr>
        
	

    <tr data-rows="1">
        <td rowspan="1" data-filter-value="typographic">
            <abbr title="Typographic">T</abbr>
        </td>
        <td id="image" rowspan="1" data-filter-value="image">
            image
        </td>
    
	    
		
        <td class="large"><pre>![Alt text](http://upload.wikimedia.org/wikipedia/commons/5/5a/Wikipedia-logo-v2-fr.png "Optional image title")</pre></td>
        <td class="large"><p><img src="http://upload.wikimedia.org/wikipedia/commons/5/5a/Wikipedia-logo-v2-fr.png" alt="Alt text" title="Optional image title"></p>
</td>
    </tr>
        
	

    <tr data-rows="1">
        <td rowspan="1" data-filter-value="typographic">
            <abbr title="Typographic">T</abbr>
        </td>
        <td id="abbreviation" rowspan="1" data-filter-value="abbreviation">
            abbreviation
        </td>
    
	    
		
        <td class="large"><pre>A paragraph with the word HTML.

*[HTML]: Hyper-Text Markup Language
</pre></td>
        <td class="large"><p>A paragraph with the word HTML.</p>
<p>*[HTML]: Hyper-Text Markup Language</p>
</td>
    </tr>
        
	

    <tr data-rows="2">
        <td rowspan="2" data-filter-value="typographic">
            <abbr title="Typographic">T</abbr>
        </td>
        <td id="headers" rowspan="2" data-filter-value="headers">
            headers
        </td>
    
	    
		
        <td class="large"><pre>my title level 1
================

my title level 2
----------------

### my title level 3</pre></td>
        <td class="large"><h1 id="my-title-level-1">my title level 1</h1>
<h2 id="my-title-level-2">my title level 2</h2>
<h3 id="my-title-level-3">my title level 3</h3>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre># my title level 1
### my title level 3</pre></td>
        <td class="large"><h1 id="my-title-level-1">my title level 1</h1>
<h3 id="my-title-level-3">my title level 3</h3>
</td>
    </tr>
        
	

    <tr data-rows="3">
        <td rowspan="3" data-filter-value="typographic">
            <abbr title="Typographic">T</abbr>
        </td>
        <td id="horizontal-rule" rowspan="3" data-filter-value="horizontal-rule">
            horizontal-rule
        </td>
    
	    
		
        <td class="large"><pre>----</pre></td>
        <td class="large"><hr>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>****</pre></td>
        <td class="large"><hr>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>____</pre></td>
        <td class="large"><hr>
</td>
    </tr>
        
	

    <tr data-rows="2">
        <td rowspan="2" data-filter-value="block">
            <abbr title="Block">B</abbr>
        </td>
        <td id="blockquote" rowspan="2" data-filter-value="blockquote">
            blockquote
        </td>
    
	    
		
        <td class="large"><pre>&gt; This is my blockquote
  and a second line ...
</pre></td>
        <td class="large"><blockquote>
<p>This is my blockquote
  and a second line ...</p>
</blockquote>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>&gt; (http://source.com) This is my blockquote
  and a second line ...
</pre></td>
        <td class="large"><blockquote>
<p>(<a href="http://source.com">http://source.com</a>) This is my blockquote
  and a second line ...</p>
</blockquote>
</td>
    </tr>
        
	

    <tr data-rows="3">
        <td rowspan="3" data-filter-value="block">
            <abbr title="Block">B</abbr>
        </td>
        <td id="pre-formated" rowspan="3" data-filter-value="pre-formated">
            pre-formated
        </td>
    
	    
		
        <td class="large"><pre>    // this is my 'pre' block
    $var = val_fct();
    html <strong>tags</strong> are escaped</pre></td>
        <td class="large"><pre><code>// this is my 'pre' block
$var = val_fct();
html &lt;strong&gt;tags&lt;/strong&gt; are escaped
</code></pre></td>
    </tr>
        
		<tr>
        <td class="large"><pre>~~~~
My code here
~~~~
</pre></td>
        <td class="large"><pre><code>My code here
</code></pre></td>
    </tr>
        
		<tr>
        <td class="large"><pre>~~~~html
My code here
~~~~
</pre></td>
        <td class="large"><pre><code class="lang-html">My code here
</code></pre>
</td>
    </tr>
        
	

    <tr data-rows="1">
        <td rowspan="1" data-filter-value="block">
            <abbr title="Block">B</abbr>
        </td>
        <td id="definitions-list" rowspan="1" data-filter-value="definitions-list">
            definitions-list
        </td>
    
	    
		
        <td class="large"><pre>Word
:   Definition content (first one)
    with a two-lines text

:   Second definition for this term...
</pre></td>
        <td class="large"><p>Word
:   Definition content (first one)
    with a two-lines text</p>
<p>:   Second definition for this term...</p>
</td>
    </tr>
        
	

    <tr data-rows="3">
        <td rowspan="3" data-filter-value="block">
            <abbr title="Block">B</abbr>
        </td>
        <td id="unordered-list" rowspan="3" data-filter-value="unordered-list">
            unordered-list
        </td>
    
	    
		
        <td class="large"><pre>-   first item
-   second item
</pre></td>
        <td class="large"><ul>
<li>first item</li>
<li>second item</li>
</ul>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>+   first item
+   second item
</pre></td>
        <td class="large"><ul>
<li>first item</li>
<li>second item</li>
</ul>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>*   first item
*   second item
</pre></td>
        <td class="large"><ul>
<li>first item</li>
<li>second item</li>
</ul>
</td>
    </tr>
        
	

    <tr data-rows="1">
        <td rowspan="1" data-filter-value="block">
            <abbr title="Block">B</abbr>
        </td>
        <td id="ordered-list" rowspan="1" data-filter-value="ordered-list">
            ordered-list
        </td>
    
	    
		
        <td class="large"><pre>1.   first item
1.   second item
</pre></td>
        <td class="large"><ol>
<li>first item</li>
<li>second item</li>
</ol>
</td>
    </tr>
        
	

    <tr data-rows="1">
        <td rowspan="1" data-filter-value="block">
            <abbr title="Block">B</abbr>
        </td>
        <td id="paragraph" rowspan="1" data-filter-value="paragraph">
            paragraph
        </td>
    
	    
		
        <td class="large"><pre>This is my first paragraph.

And this is my second,
on two lines ...
</pre></td>
        <td class="large"><p>This is my first paragraph.</p>
<p>And this is my second,
on two lines ...</p>
</td>
    </tr>
        
	

    <tr data-rows="1">
        <td rowspan="1" data-filter-value="block">
            <abbr title="Block">B</abbr>
        </td>
        <td id="table" rowspan="1" data-filter-value="table">
            table
        </td>
    
	    
		
        <td class="large"><pre>[table caption]
| First Header  | Second Header | Third Header |
| ------------- | ------------: | :----------: |
| Content Cell  | Content right-aligned | Content center-aligned |
| Content Cell  | Content on two columns ||
</pre></td>
        <td class="large"><p>[table caption]
| First Header  | Second Header | Third Header |
| ------------- | ------------: | :----------: |
| Content Cell  | Content right-aligned | Content center-aligned |
| Content Cell  | Content on two columns ||</p>
</td>
    </tr>
        
	

    <tr data-rows="3">
        <td rowspan="3" data-filter-value="block">
            <abbr title="Block">B</abbr>
        </td>
        <td id="footnote" rowspan="3" data-filter-value="footnote">
            footnote
        </td>
    
	    
		
        <td class="large"><pre>A paragraph with a footnote[^footnote_one] note.

[^footnote_one]: Footnote content
</pre></td>
        <td class="large"><p>A paragraph with a footnote[^footnote_one] note.</p>
<p>[^footnote_one]: Footnote content</p>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>A paragraph with a referenced glossary term[^myterm] ...

[^myterm]: glossary: the term defined (an optional sort key)
The term definition ... which may be multi-line.
</pre></td>
        <td class="large"><p>A paragraph with a referenced glossary term[^myterm] ...</p>
<p>[^myterm]: glossary: the term defined (an optional sort key)
The term definition ... which may be multi-line.</p>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>This is a statement that should be attributed to its source [p. 23][#Doe:2006].

[#Doe:2006]: John Doe. *Some Big Fancy Book*.  Vanity Press, 2006.
</pre></td>
        <td class="large"><p>This is a statement that should be attributed to its source [p. 23][#Doe:2006].</p>
<p>[#Doe:2006]: John Doe. <em>Some Big Fancy Book</em>.  Vanity Press, 2006.</p>
</td>
    </tr>
        
	

    <tr data-rows="1">
        <td rowspan="1" data-filter-value="miscellaneous">
            <abbr title="Miscellaneous">M</abbr>
        </td>
        <td id="references" rowspan="1" data-filter-value="references">
            references
        </td>
    
	    
		
        <td class="large"><pre>A paragraph with a referenced [hypertext link][myid] and some more text embedding an
image: ![image for the test][myimage].

[myid]: http://example.com/ "Optional link title"        
[myimage]: http://upload.wikimedia.org/wikipedia/commons/5/5a/Wikipedia-logo-v2-fr.png "Optional image title"
</pre></td>
        <td class="large"><p>A paragraph with a referenced <a href="http://example.com/" title="Optional link title">hypertext link</a> and some more text embedding an
image: <img src="http://upload.wikimedia.org/wikipedia/commons/5/5a/Wikipedia-logo-v2-fr.png" alt="image for the test" title="Optional image title">.</p>
</td>
    </tr>
        
	

    <tr data-rows="12">
        <td rowspan="12" data-filter-value="miscellaneous">
            <abbr title="Miscellaneous">M</abbr>
        </td>
        <td id="escaping" rowspan="12" data-filter-value="escaping">
            escaping
        </td>
    
	    

    </tr>
        
		<tr>
        <td class="large"><pre>\* asterisk</pre></td>
        <td class="large"><p>* asterisk</p>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>\+ plus sign</pre></td>
        <td class="large"><p>+ plus sign</p>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>\- hyphen</pre></td>
        <td class="large"><p>- hyphen</p>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>\_ underscore</pre></td>
        <td class="large"><p>_ underscore</p>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>\` backtick quote</pre></td>
        <td class="large"><p>` backtick quote</p>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>\(\) parentheses</pre></td>
        <td class="large"><p>() parentheses</p>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>\[\] brackets</pre></td>
        <td class="large"><p>[] brackets</p>
</td>
    </tr>
        
		<tr>
        <td class="large"><pre>\{\} curly brackets</pre></td>
        <td class="large"><p>{} curly brackets</p>
</td>
    </tr>
        
	

    <tr data-rows="1">
        <td rowspan="1" data-filter-value="miscellaneous">
            <abbr title="Miscellaneous">M</abbr>
        </td>
        <td id="meta tags" rowspan="1" data-filter-value="meta tags">
            meta tags
            </td>
	

    </tbody>
    </table>
</div>


# Heading Level 1
```
# Heading Level 1
```

## Heading Level 2
```
## Heading Level 2
```

### Heading Level 3
```
### Heading Level 3
```

#### Heading Level 4
```
#### Heading Level 4
```

##### Heading Level 5
```
##### Heading Level 5
```

###### Heading Level 6
```
###### Heading Level 6
```

**Bold**
```
**This text will be bold**
__This text will be bold__
```

*Italic*
```
*This text will be italic*
_This text will be italic_
```

<u>Underline</u><br>
Подчеркивание не поддерживается в Markdown. Тем не менее, Markdown поддерживает HTML, так что вы можете использовать тэги, чтобы подчеркнуть текст.
```
<u>underline text</u>
```

<del>Strikethrough</del><br>
Зачеркивание не поддерживается в Markdown (если вы не используете его на GitHub, который позволяет использовать текст синтаксис для зачеркивания). Тем не менее, Markdown поддерживает HTML, так что вы можете использовать теги в зачеркиванием.
```
<del>strikethrough text</del>
~~text~~
```

Новый параграф
```
<br>
```

This is a [link to Google](http://google.com).
```
This is a [link to Google](http://google.com).
```

Image:

![Shut up](http://goo.gl/iCJCgQ)
```

![Shut up](http://goo.gl/iCJCgQ)
```

Image with a link to **http://twitter.com/chibicode**:

[![Sketch](http://goo.gl/74fTfU)](http://twitter.com/chibicode)
```

[![Sketch](http://goo.gl/74fTfU)](http://twitter.com/chibicode)
```

This is a paragraph.

- List Item 1
- List Item 2
- List Item 3


```
- List Item 1
- List Item 2
- List Item 3
```

This is another paragraph.

* List Item 1
* List Item 2
* List Item 3

```
* List Item 1
* List Item 2
* List Item 3
```

Or:

+ List Item 1
+ List Item 2
+ List Item 3

```
+ List Item 1
+ List Item 2
+ List Item 3
```

- List Item 1
    - List Item 1.1
    - List Item 1.2
        - List Item 1.2.1
    - List Item 1.3

```
- List Item 1
    - List Item 1.1
    - List Item 1.2
        - List Item 1.2.1
    - List Item 1.3
```

  - List Item 1

    Second paragraph of list item 1

    Third paragraph of list item 1

- List Item 2

    Second paragraph of list item 2

    Third paragraph of list item 2

```
  - List Item 1

    Second paragraph of list item 1

    Third paragraph of list item 1

- List Item 2

    Second paragraph of list item 2

    Third paragraph of list item 2

```

This is a paragraph.

1. List Item 1
2. List Item 2
3. List Item 3


```
1. List Item 1
2. List Item 2
3. List Item 3
```


This is a paragraph.


1. List Item 1
1. List Item 2
1. List Item 3

```
1. List Item 1
1. List Item 2
1. List Item 3
```

1. List Item
    1. List Item
    2. List Item
        1. List Item
    3. List Item

```
1. List Item
    1. List Item
    2. List Item
        1. List Item
    3. List Item
```

1. List Item 1

    Second paragraph of list item 1

    Third paragraph of list item 1

2. List Item 2

    Second paragraph of list item 2

    Third paragraph of list item 2

```
1. List Item 1

    Second paragraph of list item 1

    Third paragraph of list item 1

2. List Item 2

    Second paragraph of list item 2

    Third paragraph of list item 2
```


- [x] @mentions, #refs, [links](), **formatting**, and <del>tags</del> supported
- [x] list syntax required (any unordered or ordered list supported)
- [x] this is a complete item
- [ ] this is an incomplete item


First Header | Second Header
------------ | -------------
Content from cell 1 | Content from cell 2
Content in the first column | Content in the second column


There are many different ways to style code with GitHub's markdown. If you have inline code blocks, wrap them in backticks: `var example = true`.  If you've got a longer block of code, you can indent with four spaces:

    if (isAwesome){
      return true
    }

GitHub also supports something called code fencing, which allows for multiple lines without indentation:

```
if (isAwesome){
  return true
}
```

And if you'd like to use syntax highlighting, include the language:

```javascript
if (isAwesome){
  return true
}
```

- [x] This is a complete item
- [ ] This is an incomplete item

```
***this is bold and italic***  and ___so is this___
```

`This won't be *italic* or **bold** at all.`

1. this starts a list *with* numbers
+  this will show as number "2"
*  this will show as number "3."
9. any number, +, -, or * will keep the list going.
    * just indent by 4 spaces (or tab) to make a sub-list
        1. keep indenting for more sub lists
    * here i'm back to the second level
    
    Tables
You can create tables using pipes and dashes like this:
  First Header  | Second Header
  ------------- | -------------
  Content Cell  | Content Cell
  Content Cell  | Content Cell


[I'm an inline-style link](https://www.google.com)

[I'm an inline-style link with title](https://www.google.com "Google's Homepage")

[I'm a reference-style link][Arbitrary case-insensitive reference text]

[I'm a relative reference to a repository file](../blob/master/LICENSE)

[You can use numbers for reference-style link definitions][1]

Or leave it empty and use the [link text itself]

Some text to show that the reference links can follow later.

[arbitrary case-insensitive reference text]: https://www.mozilla.org
[1]: http://slashdot.org
[link text itself]: http://www.reddit.com



Images

Here's our logo (hover to see the title text):

Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style:
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
Here's our logo (hover to see the title text):

```javascript
var s = "JavaScript syntax highlighting";
alert(s);
```

```python
s = "Python syntax highlighting"
print s
```

```
No language indicated, so no syntax highlighting.
But let's throw in a <b>tag</b>.
```

Colons can be used to align columns.

| Tables        | Are           | Cool  |
| ------------- |:-------------:| -----:|
| col 3 is      | right-aligned |  |
| col 2 is      | centered      |    |
| zebra stripes | are neat      |     |

The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown | Less | Pretty
--- | --- | ---
*Still* | `renders` | **nicely**
1 | 2 | 3


Blockquotes

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.


---

Hyphens

***

Asterisks

___

Underscores



> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.


> ## This is a header.
>
> 1.   This is the first list item.
> 2.   This is the second list item.
>
> Here's some example code:
>
>     return shell_exec("echo $input | $markdown_script");



To make lists look nice, you can wrap items with hanging indents:

*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
    Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
    viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
    Suspendisse id sem consectetuer libero luctus adipiscing.
But if you want to be lazy, you don't have to:

*   Lorem ipsum dolor sit amet, consectetuer adipiscing elit.
Aliquam hendrerit mi posuere lectus. Vestibulum enim wisi,
viverra nec, fringilla in, laoreet vitae, risus.
*   Donec sit amet nisl. Aliquam semper ipsum sit amet velit.
Suspendisse id sem consectetuer libero luctus adipiscing.
If list items are separated by blank lines, Markdown will wrap the items in <p> tags in the HTML output. For example, this input:

*   Bird
*   Magic


1.  This is a list item with two paragraphs. Lorem ipsum dolor
    sit amet, consectetuer adipiscing elit. Aliquam hendrerit
    mi posuere lectus.

    Vestibulum enim wisi, viverra nec, fringilla in, laoreet
    vitae, risus. Donec sit amet nisl. Aliquam semper ipsum
    sit amet velit.

2.  Suspendisse id sem consectetuer libero luctus adipiscing.
It looks nice if you indent every line of the subsequent paragraphs, but here again, Markdown will allow you to be lazy:

*   This is a list item with two paragraphs.

    This is the second paragraph in the list item. You're
only required to indent the first line. Lorem ipsum dolor
sit amet, consectetuer adipiscing elit.

*   Another item in the same list.
To put a blockquote within a list item, the blockquote's > delimiters need to be indented:

*   A list item with a blockquote:

    > This is a blockquote
    > inside a list item.
To put a code block within a list item, the code block needs to be indented twice -- 8 spaces or two tabs:

*   A list item with a code block:



This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.
Will produce:

<p>This is <a href="http://example.com/" title="Title">
an example</a> inline link.</p>

<p><a href="http://example.net/">This link</a> has no
title attribute.</p>


See my [About](/about/) page for details.
Reference-style links use a second set of square brackets, inside which you place a label of your choosing to identify the link:

This is [an example][id] reference-style link.
You can optionally use a space to separate the sets of brackets:

This is [an example] [id] reference-style link.
Then, anywhere in the document, you define your link label like this, on a line by itself:

[id]: http://example.com/  "Optional Title Here"

[id]: http://example.com/longish/path/to/resource/here
    "Optional Title Here"

[link text][a]
[link text][A]
are equivalent.


[Google][]
And then define the link:

[Google]: http://google.com/

Visit [Daring Fireball][] for more information.
And then define the link:

[Daring Fireball]: http://daringfireball.net/




I get 10 times more traffic from [Google] [1] than from
[Yahoo] [2] or [MSN] [3].

  [1]: http://google.com/        "Google"
  [2]: http://search.yahoo.com/  "Yahoo Search"
  [3]: http://search.msn.com/    "MSN Search"
Using the implicit link name shortcut, you could instead write:

I get 10 times more traffic from [Google][] than from
[Yahoo][] or [MSN][].

  [google]: http://google.com/        "Google"
  [yahoo]:  http://search.yahoo.com/  "Yahoo Search"
  [msn]:    http://search.msn.com/    "MSN Search"
Both of the above examples will produce the following HTML output:

<p>I get 10 times more traffic from <a href="http://google.com/"
title="Google">Google</a> than from
<a href="http://search.yahoo.com/" title="Yahoo Search">Yahoo</a>
or <a href="http://search.msn.com/" title="MSN Search">MSN</a>.</p>
For comparison, here is the same paragraph written using Markdown's inline link style:

I get 10 times more traffic from [Google](http://google.com/ "Google")
than from [Yahoo](http://search.yahoo.com/ "Yahoo Search") or
[MSN](http://search.msn.com/ "MSN Search").
The point of reference-style links is not that they're easier to write. The point is that with reference-style links, your document source is vastly more readable. Compare the above examples: using reference-style links, the paragraph itself is only 81 characters long; with inline-style links, it's 176 characters; and as raw HTML, it's 234 characters. In the raw HTML, there's more markup than there is text.

``There is a literal backtick (`) here.``


TEXT
MultiMarkdown	Result
This text is **bold**.	This text is bold.
This text is also __bold__.	This text is also bold.
This text is *italicized*.	This text is italicized.
This text is also _italicized_.	This text is also italicized.
`This is some code.`	This is some code.
    This is a rather
    long section of code
    taking multiple lines	This is a rather
long section of code
taking multiple lines
LINKS
MultiMarkdown	Result
Link to [Google](http://google.com).	Link to Google.
Link to <http://google.com>.	Link to http://google.com.
Link to [Google][] with attributes later in the document.

Another Link to the [search engine][Google].

[Google]: http://google.com "The Google!" style="border: solid black 1px;" target="_blank"
Link to Google with attributes later in the document.



> This is the first level of quoting.

>> This is nested blockquote
that runs onto the next line.

> Back to the first level.




| First Header | Second Header |         Third Header |
| :----------- | :-----------: | -------------------: |
| First row    |      Data     | Very long data entry |
| Second row   |    **Cell**   |               *Cell* |


| First Header  | Second Header | Third Header         |
| :------------ | :-----------: | -------------------: |
| First row     | Data          | Very long data entry |
| Second row    | **Cell**      | *Cell*               |
| Third row     | Cell that spans across two columns  ||
[Table caption, works as a reference][section-mmd-tables-table1] 


| Header One | Header Two | Header Three | Header Four |
| ---------- | :--------- | :----------: | ----------: |
| Default    | Left       | Center       | Right       |

| Column 1 | Column 2 | Column 3 | Column 4 |
| -------- | :------: | -------- | -------- |
| No span  | Span across three columns    |||

