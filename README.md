# Markdown-Cheatsheet

Markdown editing help

https://help.github.com/categories/writing-on-github/
http://cheatsheet.aboutmde.org/#
http://mdp.tylingsoft.com/#
https://daringfireball.net/projects/markdown/syntax

Emoji: http://www.webpagefx.com/tools/emoji-cheat-sheet/


<h3>1</h3>
<table class="md">
    <tr>
        <th># Heading Level 1</th>
        <th>
        ```
        # Heading Level 1
```
</th>
    </tr>
    <tr>
        <td>## Heading Level 2</td>
        <td>
        ```
## Heading Level 2
```
</td>
    </tr>
    <tr>
        <td></td>
        <td></td>
    </tr>
</table>

Headings

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

