# Markdown-Cheatsheet

Markdown editing help

Emoji: http://www.webpagefx.com/tools/emoji-cheat-sheet/

Headings

# Heading Level 1
>
```
# Heading Level 1
```

## Heading Level 2
>
```
## Heading Level 2
```

### Heading Level 3
>
```
### Heading Level 3
```

#### Heading Level 4
>
```
#### Heading Level 4
```

##### Heading Level 5
>
```
##### Heading Level 5
```

###### Heading Level 6
>
```
###### Heading Level 6
```

---

**Bold**
>
```
**This text will be bold**
__This text will be bold__
```

*Italic*
>
```
*This text will be italic*
_This text will be italic_
```

<u>Underline</u>
Подчеркивание не поддерживается в Markdown. Тем не менее, Markdown поддерживает HTML, так что вы можете использовать тэги <U>, чтобы подчеркнуть текст.
>
```
<u>underline text</u>
```

<del>Strikethrough</del>
Зачеркивание не поддерживается в Markdown (если вы не используете его на GitHub, который позволяет использовать текст ~~ ~~ синтаксис для зачеркивания). Тем не менее, Markdown поддерживает HTML, так что вы можете использовать <Del> теги в зачеркиванием.
>
```
<del>strikethrough text</del>
~~text~~
```

Новый параграф

>
```
<br>
```


This is a [link to Google](http://google.com).

This is a **[link to Apple](http://apple.com)** in bold text.


Image:

![Shut up](http://goo.gl/iCJCgQ)

Image with a link to **http://twitter.com/chibicode**:

[![Sketch](http://goo.gl/74fTfU)](http://twitter.com/chibicode)


Here's a quote from Albert Einstein:

> Two things are infinite: **the universe** and **human stupidity**; and I'm not sure about the universe.


Here's a quote from Marilyn Monroe:

> I'm selfish, impatient and a little insecure. I make mistakes, I am out of control and at times hard to handle.

> But if you can't handle me at my worst, then you sure as hell don't deserve me at my best.


This is a paragraph.

- List Item 1
- List Item 2
- List Item 3

This is another paragraph.

* List Item 1
* List Item 2
* List Item 3

Or:

+ List Item 1
+ List Item 2
+ List Item 3

- List Item 1
    - List Item 1.1
    - List Item 1.2
        - List Item 1.2.1
    - List Item 1.3
    
  
  - List Item 1

    Second paragraph of list item 1

    Third paragraph of list item 1

- List Item 2

    Second paragraph of list item 2

    Third paragraph of list item 2
    
 
 This is a paragraph.

1. List Item 1
2. List Item 2
3. List Item 3

This is a paragraph.


1. List Item 1
1. List Item 2
1. List Item 3


1. List Item
    1. List Item
    2. List Item
        1. List Item
    3. List Item
    
1. List Item 1

    Second paragraph of list item 1

    Third paragraph of list item 1

2. List Item 2

    Second paragraph of list item 2

    Third paragraph of list item 2
    

This is paragraph 1.

---

This is paragraph 2.


Usage: `hello("chibicode")`

```ruby
def hello(name)
  puts "Hello #{name}!"
end
```

```javascript
function fancyAlert(arg) {
  if(arg) {
    $.facebox({div:'#foo'})
  }
}
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


GitHub supports many extras in Markdown that help you reference and link to people. If you ever want to direct a comment at someone, you can prefix their name with an @ symbol: Hey @kneath — love your sweater!

But I have to admit, tasks lists are my favorite:

- [x] This is a complete item
- [ ] This is an incomplete item

When you include a task list in the first comment of an Issue, you will see a helpful progress bar in your list of issues. It works in Pull Requests, too!

And, of course emoji! :sparkles: :camel: :boom:


To use text for the link, write it:
[like this](http://someurl)
Output:
like this
You can add a *title* (which shows up under the cursor):
[like this](http://someurl "this title shows up when you hover")
Output:
like this
Reference Links
You can also put the [link URL][1] below the current paragraph
like [this][2].

   [1]: http://url
   [2]: http://another.url "A funky title"
Output:
You can also put the link URL below the current paragraph
like this.
Here the text "link URL" gets linked to "http://url", and the lines showing "[1]: http://url" won't show anything.
Or you can use a [shortcut][] reference, which links the text "shortcut" to the link named "[shortcut]" on the next paragraph.
Or you can use a [shortcut][] reference, which links the text
"shortcut" to the link named "[shortcut]" on the next paragraph.

[shortcut]: http://goes/with/the/link/name/text
Output:
Or you can use a shortcut reference, which links the text
"shortcut" to the link named "[shortcut]" on the next paragraph.
Artifact Links
Any forge resource (artifact) can be linked with surrounding square brackets, e.g. [MyPage] or [#123]. These artifact links can take several forms.
Simple Links
Most commonly, the artifact identifier can simply be surrounded with square brackets. Here are some examples:
[MyWikiPage]       # Wiki - name of wiki page
[#123]             # Tracker - ticket number
[r10721]           # SVN - revision number
[3b9d48]           # Git & Mercurial - first 6 characters of revision hash
[2012/02/my-post]  # Blog - post slug, including YYYY/MM/ prefix
[a6d38f98]         # Discussion Thread - thread id
[a6d38f98#42f8]    # Discussion Post - thread_id#post_id

Two-part Links
To link to an artifact in a specific tool, use the form: `[tool:artifact]`, where `tool` is the name of the tool as it appears in the URL. Two-part links are useful when you have two tools of the same type installed. For example, let's say you have a 'bugs' tracker and a 'features' tracker installed, and you want to link to the first ticket in each:
[bugs:#1]
[features:#1]

Three-part Links
To link to an artifact in another project, use the form: `[project:tool:artifact]`, where `project` is the name of the project as it appears in the URL. For example:
[allura:wiki:Home]

To link to an artifact in a subproject, use the form: `[project/subproject:tool:artifact]`, where `subproject` is the name of the subproject as it appears in the URL. For example:
[allura/sub:code:3b9d48]

Basic Text Formatting
Use * or _ to emphasize things:
*this is in italic*  and _so is this_

**this is in bold**  and __so is this__

***this is bold and italic***  and ___so is this___
Output:
this is in italic and so is this
this is in bold and so is this
this is bold and italic and so is this
You can strike through text using HTML like this:
<s>this is strike through text</s>
Output:
this is strike through text
A carriage return
makes a line break.

Two carriage returns make a new paragraph.
Output:
A carriage return
makes a line break.
Two carriage returns make a new paragraph.
Blockquotes
Use the > character in front of a line, just like in email
> Use it if you're quoting a person, a song or whatever.

> You can use *italic* or lists inside them also.
And just like with other paragraphs,
all of these lines are still
part of the blockquote, even without the > character in front.

To end the blockquote, just put a blank line before the following
paragraph.
Output:
Use it if you're quoting a person, a song or whatever.
You can use italic or lists inside them also.
And just like with other paragraphs,
all of these lines are still
part of the blockquote, even without the > character in front.
To end the blockquote, just put a blank line before the following
paragraph.
Preformatted Text
If you want some text to show up exactly as you write it, without Markdown doing anything to it, just indent every line by at least 4 spaces (or 1 tab). As an alternative to indenting, you can make a code block use 3 or more tildes (~) or backticks (`) on a line before and after the text (syntax details). See examples in the Code Highlighting section.
    This line won't *have any markdown* formatting applied.
    I can even write <b>HTML</b> and it will show up as text.
    This is great for showing program source code, or HTML or even
    Markdown. <b>this won't show up as HTML</b> but
    exactly <i>as you see it in this text file</i>.

Within a paragraph, you can use backquotes to do the same thing.
`This won't be *italic* or **bold** at all.`
Output:
This line won't *have any markdown* formatting applied.
I can even write <b>HTML</b> and it will show up as text.
This is great for showing program source code, or HTML or even
Markdown. <b>this won't show up as HTML</b> but
exactly <i>as you see it in this text file</i>.
Within a paragraph, you can use backquotes to do the same thing.
This won't be *italic* or **bold** at all.
Lists
* an asterisk starts an unordered list
* and this is another item in the list
+ or you can also use the + character
- or the - character

To start an ordered list, write this:

1. this starts a list *with* numbers
+  this will show as number "2"
*  this will show as number "3."
9. any number, +, -, or * will keep the list going.
    * just indent by 4 spaces (or tab) to make a sub-list
        1. keep indenting for more sub lists
    * here i'm back to the second level
Output:
an asterisk starts an unordered list
and this is another item in the list
or you can also use the + character
or the - character
To start an ordered list, write this:
this starts a list with numbers
this will show as number "2"
this will show as number "3."
any number, +, -, or * will keep the list going.
just indent by 4 spaces (or tab) to make a sub-list
keep indenting for more sub lists
here i'm back to the second level
Tables
You can create tables using pipes and dashes like this:
  First Header  | Second Header
  ------------- | -------------
  Content Cell  | Content Cell
  Content Cell  | Content Cell
Output:
First Header	Second Header
Content Cell	Content Cell
Content Cell	Content Cell
You can use markdown syntax within table cells for formatting:
  First Header   | Second Header
  -------------  | -------------
  *Content Cell* | Content Cell
  Content Cell   | Content Cell
Output:
First Header	Second Header
Content Cell	Content Cell
Content Cell	Content Cell
You can also create tables using HTML code.
Headers
Just put 1 or more dashes or equals signs (--- or ===) below the title.
This is a huge header
==================

this is a smaller header
------------------
Output:
This is a huge header
this is a smaller header
Horizontal Rule
Just put three or more *'s or -'s on a line:
----------------
Output:
Or, you can use single spaces between then, like this:
* * *
Output:
or
- - - - - - -
Output:
Make sure you have a blank line above the dashes, though, or else:
you will get a header
---
Output:
you will get a header
Images
To include an image, just put a "!" in front of a text link:
![alternate text](https://sourceforge.net/images/icon_linux.gif)
Output:
alternate text
The "alternate text" will show up if the browser can't load the image.
You can also use a title if you want, like this:
![tiny arrow](https://sourceforge.net/images/icon_linux.gif "tiny arrow")
Output:
tiny arrow
To reference an attached image, just use the img macro. You can add more attributes:
[[img src=attached-image.jpg alt=foobar]]
Output:
foobar
Videos
To embed a YouTube video, use the `embed` macro (only YouTube is supported at this time):
[[embed url=http://www.youtube.com/watch?v=6YbBmqUnoQM]]
Output:

Escapes and HTML
What if you want to just show asterisks, not italics?
* this shows up in italics: *a happy day*
* this shows the asterisks: \*a happy day\*
Output:
this shows up in italics: a happy day
this shows the asterisks: *a happy day*
The backslashes will disappear and leave the asterisks. You can do the same with any of the characters that have a special meaning
for Markdown.
Many simple HTML tags are allowed, for example <b> And unknown tags will be dropped. To show a literal <b> or an unknown tag like <foobar> you need escape it with HTML entities: :
<b>this will be bold</b>
you should escape &lt;unknown&gt; tags
&copy; special entities work
&amp;copy; if you want to escape it
Output:
this will be bold
you should escape <unknown> tags
© special entities work
&copy; if you want to escape it
HTML tags that are block-level like <div> can be used, but if there is markdown formatting within it, you must add a "markdown" attribute: <div markdown> Some safe attributes are also allowed, permitting basic styling and layout: <div markdown style="float:left">
Individual ampersands (&) and less-than signs (<) are fine, they will be shown as expected.
More Headers
More ways of doing headers:
# this is a huge header #
## this is a smaller header ##
### this is even smaller ###
#### more small ####
##### even smaller #####
###### smallest still: `<h6>` header
Output:
this is a huge header
this is a smaller header
this is even smaller
more small
even smaller
smallest still: <h6> header
You can use up to 6 # characters at the beginning of the line.
Table of Contents
You can display a list of links to jump to headers in a document. Sub-headers will be nested.
[TOC]

# Section 1
## Sub-section 1
# Section 2
Output:
Section 1
Sub-section 1
Section 2
Section 1
Sub-section 1
Section 2
Code Highlighting
The code highlighting syntax uses CodeHilite and is colored with Pygments. It follows the same syntax as regular Markdown code blocks, with ways to tell the highlighter what language to use for the code block.
The language will be detected automatically, if possible. Or you can specify it on the first line with 3 colons and the language name.
    :::python
    import abc
Output:
import abc
If the first line of the codeblock contains a shebang, the language is derived from that and line numbers are used. If shebang line contains a full path, it will be included in the output. If it does not contain a path (a single / or even a space), then that shebang line will be omitted from output.
    #!/usr/bin/python
    import abc
Output:
1
2
#!/usr/bin/python
import abc
If using a code block of tildes or backticks, you can also specify the language on the first divider line
~~~html
<a href="#">My code</a>
~~~
```html
<a href="#">My code</a>
```
Output:
<a href="#">My code</a>
Many languages are supported. See all the "short names" listed in the Pygments docs.
Includes
You can embed another wiki page directly:
[[include ref=SamplePage]]
No example output is available for this one because it only works on real wiki pages. Try it in your wiki!
Also, you can embed a file directly from a repository! Just skip the ref parameter and pass repository, path and optional revision:
[[include repo=code path=README]]

[[include repo=myproject:code path=/ew/forms.py rev=fa61e7]]

[[include repo=p:myproject:code path=/ew/forms.py]]
Repo could be specified in three ways:
app
project:app
neighborhood:project:app
Where app is a repository's mount point, project is a project's shortname and neighborhood is a neighborhood's prefix that appears in url.
Neighborhood Notifications
You can list updates from all projects in a neighborhood by tool type. Max_number (default is 5) and sort (default is pubdate) are optional:
[[neighborhood_feeds tool_name=wiki max_number=10 sort=pubdate]]
Neighborhood Blog Posts
You can view blog posts from all projects in a neighborhood. Max_number (default is 5) and sort (default is timestamp) are optional:
[[neighborhood_blog_posts max_number=10 sort=timestamp]]
Project Blog Posts
You can view blog posts from all blogs in a project. Max_number (default is 5), mount point (leave empty to view posts from all blog tools in a project), and sort (default is timestamp) are optional:
[[project_blog_posts max_number=10 sort=timestamp mount_point=news]]
Download Button
You can display a download button that links to the best download available for the active project. Please note that if you use this macro and there is no download associated with your project, the button will not appear.
[[download_button]]
Gittip Button
You can display a Gittip button in your wiki. You will need to provide your gittip handle in the username parameter.
[[gittip_button username=foo]]
Project Member List
You can display a list of project members. By default the list is limited to 20 members, and a link is provided to a page with the full list.
[[members]]
Project Screenshots
You can show all the screenshots for the current project as thumbnails that are linked to the full-size image.
[[project_screenshots]]


Headers

# H1
## H2
### H3
#### H4
##### H5
###### H6

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1
======

Alt-H2
------
H1

H2

H3

H4

H5

H6

Alternatively, for H1 and H2, an underline-ish style:

Alt-H1

Alt-H2


Emphasis

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~~Scratch this.~~
Emphasis, aka italics, with asterisks or underscores.

Strong emphasis, aka bold, with asterisks or underscores.

Combined emphasis with asterisks and underscores.

Strikethrough uses two tildes. Scratch this.


Lists

(In this example, leading and trailing spaces are shown with with dots: ⋅)

1. First ordered list item
2. Another item
⋅⋅* Unordered sub-list.
1. Actual numbers don't matter, just that it's a number
⋅⋅1. Ordered sub-list
4. And another item.

⋅⋅⋅You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

⋅⋅⋅To have a line break without a paragraph, you will need to use two trailing spaces.⋅⋅
⋅⋅⋅Note that this line is separate, but within the same paragraph.⋅⋅
⋅⋅⋅(This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

* Unordered list can use asterisks
- Or minuses
+ Or pluses
First ordered list item
Another item
Unordered sub-list.
Actual numbers don't matter, just that it's a number
Ordered sub-list
And another item.

You can have properly indented paragraphs within list items. Notice the blank line above, and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

To have a line break without a paragraph, you will need to use two trailing spaces. Note that this line is separate, but within the same paragraph. (This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)

Unordered list can use asterisks
Or minuses
Or pluses

foo
bar
baz
faz
foo2

foo
bar
baz
faz
foo2

foo

bar
baz
faz
foo

bar
baz
faz
Lists in a list item:
Indented four spaces.
indented eight spaces.
Four spaces again.
Multiple paragraphs in a list items: It's best to indent the paragraphs four spaces You can get away with three, but it can get confusing when you nest other things. Stick to four.

We indented the first line an extra space to align it with these paragraphs. In real use, we might do that to the entire list so that all items line up.

This paragraph is still part of the list item, but it looks messy to humans. So it's a good idea to wrap your nested paragraphs manually, as we did with the first two.

Blockquotes in a list item:

Skip a line and indent the >'s four spaces.
Preformatted text in a list item:

Skip a line and indent eight spaces.
That's four spaces for the list
and four to trigger the code block.
Inline HTML

To reboot your computer, press ctrl+alt+del.


Links

There are two ways to create links.

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
I'm an inline-style link

I'm an inline-style link with title

I'm a reference-style link

I'm a relative reference to a repository file

You can use numbers for reference-style link definitions

Or leave it empty and use the link text itself

Some text to show that the reference links can follow later.


Images

Here's our logo (hover to see the title text):

Inline-style:
![alt text](https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 1")

Reference-style:
![alt text][logo]

[logo]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Logo Title Text 2"
Here's our logo (hover to see the title text):

Inline-style: alt text

Reference-style: alt text


Code and Syntax Highlighting

Code blocks are part of the Markdown spec, but syntax highlighting isn't. However, many renderers -- like Github's and Markdown Here -- support syntax highlighting. Which languages are supported and how those language names should be written will vary from renderer to renderer. Markdown Here supports highlighting for dozens of languages (and not-really-languages, like diffs and HTTP headers); to see the complete list, and how to write the language names, see the highlight.js demo page.

Inline `code` has `back-ticks around` it.
Inline code has back-ticks around it.

Blocks of code are either fenced by lines with three back-ticks ```, or are indented with four spaces. I recommend only using the fenced code blocks -- they're easier and only they support syntax highlighting.

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
var s = "JavaScript syntax highlighting";
alert(s);
s = "Python syntax highlighting"
print s
No language indicated, so no syntax highlighting in Markdown Here (varies on Github).
But let's throw in a <b>tag</b>.

Tables

Tables aren't part of the core Markdown spec, but they are part of GFM and Markdown Here supports them. They are an easy way of adding tables to your email -- a task that would otherwise require copy-pasting from another application.

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
Colons can be used to align columns.

Tables	Are	Cool
col 3 is	right-aligned	
col 2 is	centered	
zebra stripes	are neat	
The outer pipes (|) are optional, and you don't need to make the raw Markdown line up prettily. You can also use inline Markdown.

Markdown	Less	Pretty
Still	renders	nicely
1	2	3

Blockquotes

> Blockquotes are very handy in email to emulate reply text.
> This line is part of the same quote.

Quote break.

> This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can *put* **Markdown** into a blockquote.
Blockquotes are very handy in email to emulate reply text. This line is part of the same quote.
Quote break.

This is a very long line that will still be quoted properly when it wraps. Oh boy let's keep writing to make sure this is long enough to actually wrap for everyone. Oh, you can put Markdown into a blockquote.

Inline HTML

You can also use raw HTML in your Markdown, and it'll mostly work pretty well.

<dl>
    <dt>Definition list</dt>
    <dd>Is something people use sometimes.</dd>

    <dt>Markdown in HTML</dt>
    <dd>Does *not* work **very** well. Use HTML <em>tags</em>.</dd>
</dl>
Definition list
Is something people use sometimes.
Markdown in HTML
Does *not* work **very** well. Use HTML tags.

Horizontal Rule

Three or more...

---

Hyphens

***

Asterisks

___

Underscores
Three or more...

Hyphens

Asterisks

Underscores


Line Breaks

My basic recommendation for learning how line breaks work is to experiment and discover -- hit <Enter> once (i.e., insert one newline), then hit it twice (i.e., insert two newlines), see what happens. You'll soon learn to get what you want. "Markdown Toggle" is your friend.

Here are some things to try out:

Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a *separate paragraph*.

This line is also a separate paragraph, but...
This line is only separated by a single newline, so it's a separate line in the *same paragraph*.
Here's a line for us to start with.

This line is separated from the one above by two newlines, so it will be a separate paragraph.

This line is also begins a separate paragraph, but... This line is only separated by a single newline, so it's a separate line in the same paragraph.

(Technical note: Markdown Here uses GFM line breaks, so there's no need to use MD's two-space line breaks.)


Youtube videos

They can't be added directly but you can add an image with a link to the video like this:

<a href="http://www.youtube.com/watch?feature=player_embedded&v=YOUTUBE_VIDEO_ID_HERE
" target="_blank"><img src="http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg"
alt="IMAGE ALT TEXT HERE" width="240" height="180" border="10" /></a>
Or, in pure Markdown, but losing the image sizing and border:

[![IMAGE ALT TEXT HERE](http://img.youtube.com/vi/YOUTUBE_VIDEO_ID_HERE/0.jpg)](http://www.youtube.com/watch?v=YOUTUBE_VIDEO_ID_HERE)
Referencing a bug by #bugID in your git commit links it to the slip. For example #1.

Task List

 foo
 foo
 foo
 foo
[test]: http://google.com/ "Google"

A heading

Just a note, I've found that I can't test my markdown parser vs others. For example, both markdown.js and showdown code blocks in lists wrong. They're also completely [inconsistent][test] with regards to paragraphs in list items.

A link. Not anymore.

This will make me fail the test because markdown.js doesnt acknowledge arbitrary html blocks =/
List Item 1

List Item 2

New List Item 1 Hi, this is a list item.
New List Item 2 Another item Code goes here. Lots of it...
New List Item 3 The last item
List Item 3 The final item.

List Item 4 The real final item.

Paragraph.

bq Item 1
bq Item 2
New bq Item 1
New bq Item 2 Text here
Another blockquote! I really need to get more creative with mockup text.. markdown.js breaks here again
Another Heading

Hello world. Here is a link. And an image alt.

Code goes here.
Lots of it...
A list within a blockquote:

asterisk 1
asterisk 2
asterisk 3
This is strong and em.

So is this word.

This is strong and em.

So is this word.

Unordered

Asterisks tight:

asterisk 1
asterisk 2
asterisk 3
Asterisks loose:

asterisk 1

asterisk 2

asterisk 3

Pluses tight:

Plus 1
Plus 2
Plus 3
Pluses loose:

Plus 1

Plus 2

Plus 3

Minuses tight:

Minus 1
Minus 2
Minus 3
Minuses loose:

Minus 1

Minus 2

Minus 3

Ordered

Tight:

First
Second
Third
and:

One
Two
Three
Loose using tabs:

First

Second

Third

and using spaces:

One

Two

Three

Multiple paragraphs:

Item 1, graf one.

Item 2. graf two. The quick brown fox jumped over the lazy dog's back.

Item 2.

Item 3.

Nested

Tab
Tab
Tab
Here's another:

First
Second:
Fee
Fie
Foe
Third
Same thing but with paragraphs:

First

Second:

Fee
Fie
Foe
Third

This was an error in Markdown 1.0.1:

this

sub
that

foo

bar
foo
Markdown: Syntax

Main
Basics
Syntax
License
Dingus
Overview
Philosophy
Inline HTML
Automatic Escaping for Special Characters
Block Elements
Paragraphs and Line Breaks
Headers
Blockquotes
Lists
Code Blocks
Horizontal Rules
Span Elements
Links
Emphasis
Code
Images
Miscellaneous
Backslash Escapes
Automatic Links
Note: This document is itself written using Markdown; you can [see the source for it by adding '.text' to the URL][src].

[src]: /projects/markdown/syntax.text

Overview

Philosophy

Markdown is intended to be as easy-to-read and easy-to-write as is feasible.

Readability, however, is emphasized above all else. A Markdown-formatted document should be publishable as-is, as plain text, without looking like it's been marked up with tags or formatting instructions. While Markdown's syntax has been influenced by several existing text-to-HTML filters -- including Setext, [atx] [2], [Textile] [3], [reStructuredText] [4], [Grutatext] [5], and [EtText] [6] -- the single biggest source of inspiration for Markdown's syntax is the format of plain text email.

1: http://docutils.sourceforge.net/mirror/setext.html [2]: http://www.aaronsw.com/2002/atx/ [3]: http://textism.com/tools/textile/ [4]: http://docutils.sourceforge.net/rst.html [5]: http://www.triptico.com/software/grutatxt.html [6]: http://ettext.taint.org/doc/

To this end, Markdown's syntax is comprised entirely of punctuation characters, which punctuation characters have been carefully chosen so as to look like what they mean. E.g., asterisks around a word actually look like *emphasis*. Markdown lists look like, well, lists. Even blockquotes look like quoted passages of text, assuming you've ever used email.

Inline HTML

Markdown's syntax is intended for one purpose: to be used as a format for writing for the web.

Markdown is not a replacement for HTML, or even close to it. Its syntax is very small, corresponding only to a very small subset of HTML tags. The idea is not to create a syntax that makes it easier to insert HTML tags. In my opinion, HTML tags are already easy to insert. The idea for Markdown is to make it easy to read, write, and edit prose. HTML is a publishing format; Markdown is a writing format. Thus, Markdown's formatting syntax only addresses issues that can be conveyed in plain text.

For any markup that is not covered by Markdown's syntax, you simply use HTML itself. There's no need to preface it or delimit it to indicate that you're switching from Markdown to HTML; you just use the tags.

The only restrictions are that block-level HTML elements -- e.g. <div>, <table>, <pre>, <p>, etc. -- must be separated from surrounding content by blank lines, and the start and end tags of the block should not be indented with tabs or spaces. Markdown is smart enough not to add extra (unwanted) <p> tags around HTML block-level tags.

For example, to add an HTML table to a Markdown article:

This is a regular paragraph.

<table>
    <tr>
        <td>Foo</td>
    </tr>
</table>

This is another regular paragraph.
Note that Markdown formatting syntax is not processed within block-level HTML tags. E.g., you can't use Markdown-style *emphasis* inside an HTML block.

Span-level HTML tags -- e.g. <span>, <cite>, or <del> -- can be used anywhere in a Markdown paragraph, list item, or header. If you want, you can even use HTML tags instead of Markdown formatting; e.g. if you'd prefer to use HTML <a> or <img> tags instead of Markdown's link or image syntax, go right ahead.

Unlike block-level HTML tags, Markdown syntax is processed within span-level tags.

Automatic Escaping for Special Characters

In HTML, there are two characters that demand special treatment: < and &. Left angle brackets are used to start tags; ampersands are used to denote HTML entities. If you want to use them as literal characters, you must escape them as entities, e.g. &lt;, and &amp;.

Ampersands in particular are bedeviling for web writers. If you want to write about 'AT&T', you need to write 'AT&amp;T'. You even need to escape ampersands within URLs. Thus, if you want to link to:

http://images.google.com/images?num=30&q=larry+bird
you need to encode the URL as:

http://images.google.com/images?num=30&amp;q=larry+bird
in your anchor tag href attribute. Needless to say, this is easy to forget, and is probably the single most common source of HTML validation errors in otherwise well-marked-up web sites.

Markdown allows you to use these characters naturally, taking care of all the necessary escaping for you. If you use an ampersand as part of an HTML entity, it remains unchanged; otherwise it will be translated into &amp;.

So, if you want to include a copyright symbol in your article, you can write:

&copy;
and Markdown will leave it alone. But if you write:

AT&T
Markdown will translate it to:

AT&amp;T
Similarly, because Markdown supports inline HTML, if you use angle brackets as delimiters for HTML tags, Markdown will treat them as such. But if you write:

4 < 5
Markdown will translate it to:

4 &lt; 5
However, inside Markdown code spans and blocks, angle brackets and ampersands are always encoded automatically. This makes it easy to use Markdown to write about HTML code. (As opposed to raw HTML, which is a terrible format for writing about HTML syntax, because every single < and & in your example code needs to be escaped.)

Block Elements

Paragraphs and Line Breaks

A paragraph is simply one or more consecutive lines of text, separated by one or more blank lines. (A blank line is any line that looks like a blank line -- a line containing nothing but spaces or tabs is considered blank.) Normal paragraphs should not be intended with spaces or tabs.

The implication of the "one or more consecutive lines of text" rule is that Markdown supports "hard-wrapped" text paragraphs. This differs significantly from most other text-to-HTML formatters (including Movable Type's "Convert Line Breaks" option) which translate every line break character in a paragraph into a <br /> tag.

When you do want to insert a <br /> break tag using Markdown, you end a line with two or more spaces, then type return.

Yes, this takes a tad more effort to create a <br />, but a simplistic "every line break is a <br />" rule wouldn't work for Markdown. Markdown's email-style [blockquoting][bq] and multi-paragraph [list items][l] work best -- and look better -- when you format them with hard breaks.

[bq]: #blockquote [l]: #list

Headers

Markdown supports two styles of headers, Setext and [atx] [2].

Setext-style headers are "underlined" using equal signs (for first-level headers) and dashes (for second-level headers). For example:

This is an H1
=============

This is an H2
-------------
Any number of underlining ='s or -'s will work.

Atx-style headers use 1-6 hash characters at the start of the line, corresponding to header levels 1-6. For example:

# This is an H1

## This is an H2

###### This is an H6
Optionally, you may "close" atx-style headers. This is purely cosmetic -- you can use this if you think it looks better. The closing hashes don't even need to match the number of hashes used to open the header. (The number of opening hashes determines the header level.) :

# This is an H1 #

## This is an H2 ##

### This is an H3 ######
Blockquotes

Markdown uses email-style > characters for blockquoting. If you're familiar with quoting passages of text in an email message, then you know how to create a blockquote in Markdown. It looks best if you hard wrap the text and put a > before every line:

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
> consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
> Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.
>
> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
> id sem consectetuer libero luctus adipiscing.
Markdown allows you to be lazy and only put the > before the first line of a hard-wrapped paragraph:

> This is a blockquote with two paragraphs. Lorem ipsum dolor sit amet,
consectetuer adipiscing elit. Aliquam hendrerit mi posuere lectus.
Vestibulum enim wisi, viverra nec, fringilla in, laoreet vitae, risus.

> Donec sit amet nisl. Aliquam semper ipsum sit amet velit. Suspendisse
id sem consectetuer libero luctus adipiscing.
Blockquotes can be nested (i.e. a blockquote-in-a-blockquote) by adding additional levels of >:

> This is the first level of quoting.
>
> > This is nested blockquote.
>
> Back to the first level.
Blockquotes can contain other Markdown elements, including headers, lists, and code blocks:

> ## This is a header.
>
> 1.   This is the first list item.
> 2.   This is the second list item.
>
> Here's some example code:
>
>     return shell_exec("echo $input | $markdown_script");
Any decent text editor should make email-style quoting easy. For example, with BBEdit, you can make a selection and choose Increase Quote Level from the Text menu.

Lists

Markdown supports ordered (numbered) and unordered (bulleted) lists.

Unordered lists use asterisks, pluses, and hyphens -- interchangably -- as list markers:

*   Red
*   Green
*   Blue
is equivalent to:

+   Red
+   Green
+   Blue
and:

-   Red
-   Green
-   Blue
Ordered lists use numbers followed by periods:

1.  Bird
2.  McHale
3.  Parish
It's important to note that the actual numbers you use to mark the list have no effect on the HTML output Markdown produces. The HTML Markdown produces from the above list is:

<ol>
<li>Bird</li>
<li>McHale</li>
<li>Parish</li>
</ol>
If you instead wrote the list in Markdown like this:

1.  Bird
1.  McHale
1.  Parish
or even:

3. Bird
1. McHale
8. Parish
you'd get the exact same HTML output. The point is, if you want to, you can use ordinal numbers in your ordered Markdown lists, so that the numbers in your source match the numbers in your published HTML. But if you want to be lazy, you don't have to.

If you do use lazy list numbering, however, you should still start the list with the number 1. At some point in the future, Markdown may support starting ordered lists at an arbitrary number.

List markers typically start at the left margin, but may be indented by up to three spaces. List markers must be followed by one or more spaces or a tab.

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
will turn into:

<ul>
<li>Bird</li>
<li>Magic</li>
</ul>
But this:

*   Bird

*   Magic
will turn into:

<ul>
<li><p>Bird</p></li>
<li><p>Magic</p></li>
</ul>
List items may consist of multiple paragraphs. Each subsequent paragraph in a list item must be intended by either 4 spaces or one tab:

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

        <code goes here>
It's worth noting that it's possible to trigger an ordered list by accident, by writing something like this:

1986. What a great season.
In other words, a number-period-space sequence at the beginning of a line. To avoid this, you can backslash-escape the period:

1986\. What a great season.
Code Blocks

Pre-formatted code blocks are used for writing about programming or markup source code. Rather than forming normal paragraphs, the lines of a code block are interpreted literally. Markdown wraps a code block in both <pre> and <code> tags.

To produce a code block in Markdown, simply indent every line of the block by at least 4 spaces or 1 tab. For example, given this input:

This is a normal paragraph:

    This is a code block.
Markdown will generate:

<p>This is a normal paragraph:</p>

<pre><code>This is a code block.
</code></pre>
One level of indentation -- 4 spaces or 1 tab -- is removed from each line of the code block. For example, this:

Here is an example of AppleScript:

    tell application "Foo"
        beep
    end tell
will turn into:

<p>Here is an example of AppleScript:</p>

<pre><code>tell application "Foo"
    beep
end tell
</code></pre>
A code block continues until it reaches a line that is not indented (or the end of the article).

Within a code block, ampersands (&) and angle brackets (< and >) are automatically converted into HTML entities. This makes it very easy to include example HTML source code using Markdown -- just paste it and indent it, and Markdown will handle the hassle of encoding the ampersands and angle brackets. For example, this:

    <div class="footer">
        &copy; 2004 Foo Corporation
    </div>
will turn into:

<pre><code>&lt;div class="footer"&gt;
    &amp;copy; 2004 Foo Corporation
&lt;/div&gt;
</code></pre>
Regular Markdown syntax is not processed within code blocks. E.g., asterisks are just literal asterisks within a code block. This means it's also easy to use Markdown to write about Markdown's own syntax.

Horizontal Rules

You can produce a horizontal rule tag (<hr />) by placing three or more hyphens, asterisks, or underscores on a line by themselves. If you wish, you may use spaces between the hyphens or asterisks. Each of the following lines will produce a horizontal rule:

* * *

***

*****

- - -

---------------------------------------

_ _ _
Span Elements

Links

Markdown supports two style of links: inline and reference.

In both styles, the link text is delimited by [square brackets].

To create an inline link, use a set of regular parentheses immediately after the link text's closing square bracket. Inside the parentheses, put the URL where you want the link to point, along with an optional title for the link, surrounded in quotes. For example:

This is [an example](http://example.com/ "Title") inline link.

[This link](http://example.net/) has no title attribute.
Will produce:

<p>This is <a href="http://example.com/" title="Title">
an example</a> inline link.</p>

<p><a href="http://example.net/">This link</a> has no
title attribute.</p>
If you're referring to a local resource on the same server, you can use relative paths:

See my [About](/about/) page for details.
Reference-style links use a second set of square brackets, inside which you place a label of your choosing to identify the link:

This is [an example][id] reference-style link.
You can optionally use a space to separate the sets of brackets:

This is [an example] [id] reference-style link.
Then, anywhere in the document, you define your link label like this, on a line by itself:

[id]: http://example.com/  "Optional Title Here"
That is:

Square brackets containing the link identifier (optionally indented from the left margin using up to three spaces);
followed by a colon;
followed by one or more spaces (or tabs);
followed by the URL for the link;
optionally followed by a title attribute for the link, enclosed in double or single quotes.
The link URL may, optionally, be surrounded by angle brackets:

[id]: <http://example.com/>  "Optional Title Here"
You can put the title attribute on the next line and use extra spaces or tabs for padding, which tends to look better with longer URLs:

[id]: http://example.com/longish/path/to/resource/here
    "Optional Title Here"
Link definitions are only used for creating links during Markdown processing, and are stripped from your document in the HTML output.

Link definition names may constist of letters, numbers, spaces, and punctuation -- but they are not case sensitive. E.g. these two links:

[link text][a]
[link text][A]
are equivalent.

The implicit link name shortcut allows you to omit the name of the link, in which case the link text itself is used as the name. Just use an empty set of square brackets -- e.g., to link the word "Google" to the google.com web site, you could simply write:

[Google][]
And then define the link:

[Google]: http://google.com/
Because link names may contain spaces, this shortcut even works for multiple words in the link text:

Visit [Daring Fireball][] for more information.
And then define the link:

[Daring Fireball]: http://daringfireball.net/
Link definitions can be placed anywhere in your Markdown document. I tend to put them immediately after each paragraph in which they're used, but if you want, you can put them all at the end of your document, sort of like footnotes.

Here's an example of reference links in action:

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

With Markdown's reference-style links, a source document much more closely resembles the final output, as rendered in a browser. By allowing you to move the markup-related metadata out of the paragraph, you can add links without interrupting the narrative flow of your prose.

Emphasis

Markdown treats asterisks (*) and underscores (_) as indicators of emphasis. Text wrapped with one * or _ will be wrapped with an HTML <em> tag; double *'s or _'s will be wrapped with an HTML <strong> tag. E.g., this input:

*single asterisks*

_single underscores_

**double asterisks**

__double underscores__
will produce:

<em>single asterisks</em>

<em>single underscores</em>

<strong>double asterisks</strong>

<strong>double underscores</strong>
You can use whichever style you prefer; the lone restriction is that the same character must be used to open and close an emphasis span.

Emphasis can be used in the middle of a word:

un*fucking*believable
But if you surround an * or _ with spaces, it'll be treated as a literal asterisk or underscore.

To produce a literal asterisk or underscore at a position where it would otherwise be used as an emphasis delimiter, you can backslash escape it:

\*this text is surrounded by literal asterisks\*
Code

To indicate a span of code, wrap it with backtick quotes (`). Unlike a pre-formatted code block, a code span indicates code within a normal paragraph. For example:

Use the `printf()` function.
will produce:

<p>Use the <code>printf()</code> function.</p>
To include a literal backtick character within a code span, you can use multiple backticks as the opening and closing delimiters:

``There is a literal backtick (`) here.``
which will produce this:

<p><code>There is a literal backtick (`) here.</code></p>
The backtick delimiters surrounding a code span may include spaces -- one after the opening, one before the closing. This allows you to place literal backtick characters at the beginning or end of a code span:

A single backtick in a code span: `` ` ``

A backtick-delimited string in a code span: `` `foo` ``
will produce:

<p>A single backtick in a code span: <code>`</code></p>

<p>A backtick-delimited string in a code span: <code>`foo`</code></p>
With a code span, ampersands and angle brackets are encoded as HTML entities automatically, which makes it easy to include example HTML tags. Markdown will turn this:

Please don't use any `<blink>` tags.
into:

<p>Please don't use any <code>&lt;blink&gt;</code> tags.</p>
You can write this:

`&#8212;` is the decimal-encoded equivalent of `&mdash;`.
to produce:

<p><code>&amp;#8212;</code> is the decimal-encoded
equivalent of <code>&amp;mdash;</code>.</p>
Images

Admittedly, it's fairly difficult to devise a "natural" syntax for placing images into a plain text document format.

Markdown uses an image syntax that is intended to resemble the syntax for links, allowing for two styles: inline and reference.

Inline image syntax looks like this:

![Alt text](/path/to/img.jpg)

![Alt text](/path/to/img.jpg "Optional title")
That is:

An exclamation mark: !;
followed by a set of square brackets, containing the alt attribute text for the image;
followed by a set of parentheses, containing the URL or path to the image, and an optional title attribute enclosed in double or single quotes.
Reference-style image syntax looks like this:

![Alt text][id]
Where "id" is the name of a defined image reference. Image references are defined using syntax identical to link references:

[id]: url/to/image  "Optional title attribute"
As of this writing, Markdown has no syntax for specifying the dimensions of an image; if this is important to you, you can simply use regular HTML <img> tags.

Miscellaneous

Automatic Links

Markdown supports a shortcut style for creating "automatic" links for URLs and email addresses: simply surround the URL or email address with angle brackets. What this means is that if you want to show the actual text of a URL or email address, and also have it be a clickable link, you can do this:

<http://example.com/>
Markdown will turn this into:

<a href="http://example.com/">http://example.com/</a>
Automatic links for email addresses work similarly, except that Markdown will also perform a bit of randomized decimal and hex entity-encoding to help obscure your address from address-harvesting spambots. For example, Markdown will turn this:

<address@example.com>
into something like this:

<a href="&#x6D;&#x61;i&#x6C;&#x74;&#x6F;:&#x61;&#x64;&#x64;&#x72;&#x65;
&#115;&#115;&#64;&#101;&#120;&#x61;&#109;&#x70;&#x6C;e&#x2E;&#99;&#111;
&#109;">&#x61;&#x64;&#x64;&#x72;&#x65;&#115;&#115;&#64;&#101;&#120;&#x61;
&#109;&#x70;&#x6C;e&#x2E;&#99;&#111;&#109;</a>
which will render in a browser as a clickable link to "address@example.com".

(This sort of entity-encoding trick will indeed fool many, if not most, address-harvesting bots, but it definitely won't fool all of them. It's better than nothing, but an address published in this way will probably eventually start receiving spam.)

Backslash Escapes

Markdown allows you to use backslash escapes to generate literal characters which would otherwise have special meaning in Markdown's formatting syntax. For example, if you wanted to surround a word with literal asterisks (instead of an HTML <em> tag), you can backslashes before the asterisks, like this:

\*literal asterisks\*
Markdown provides backslash escapes for the following characters:

\   backslash
`   backtick
*   asterisk
_   underscore
{}  curly braces
[]  square brackets
()  parentheses
#   hash mark
+   plus sign
-   minus sign (hyphen)
.   dot
!   exclamation mark
Foo [bar][].

Foo bar.

[bar]: /url/ "Title with "quotes" inside"

This is the [simple case].

[simple case]: /simple

This one has a [line break].

This one has a [line break] with a line-ending space.

[line break]: /foo

[this] [that] and the [other]

[this]: /this [that]: /that [other]: /other

Here's a simple block:

foo
This should be a code block, though:

<div>
    foo
</div>
As should this:

<div>foo</div>
Now, nested:

foo
This should just be an HTML comment:

Multiline:

Code block:

<!-- Comment -->
Just plain comment, with trailing spaces on the line:

Code:

<hr />
Hr's:

var gulp = require('gulp');
var myth = require('gulp-myth');

gulp.task('default', function () {
    return gulp.src('src/app.css')
        .pipe(myth())
        .pipe(gulp.dest('dist'));
});


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

Another link to the search engine.

Send me an email at <address@example.com>.	Send me an email at address@example.com.
HEADINGS
MultiMarkdown	Result
# First Header	
First Header
## Second Header ##	
Second Header
### Third Header	
Third Header
BLOCKQUOTES
MultiMarkdown	Result
Here is the a normal paragraph.

> This is the first level of quoting.

>> This is nested blockquote
that runs onto the next line.

> Back to the first level.

Notice the spaces when we start a new paragraph or separate the different blockquotes.	
Here is the a normal paragraph.

This is the first level of quoting.

This is nested blockquote that runs onto the next line.

Back to the first level.

Notice the spaces when we start a new paragraph or separate the different blockquotes.

IMAGES AND FIGURES
MultiMarkdown	Result
This is the simplest example of an ![image](mmd.png) embedded in a paragraph.	This is the simplest example of an image embedded in a paragraph.
This is an image example with a title attribute ![Alternate Message](mmd.png "This is a title") embedded in a paragraph.	This is an image example with a title attribute Alternate Message embedded in a paragraph.
This is the same image ![image3][] but with the attributes placed later on in the document.

[image3]: mmd.png "This is where the title goes" height=22px width=60px	This is the same image image3 but with the attributes placed later on in the document.
When an image is placed in a paragraph by itself, it is wrapped in a <figure> tag.

![This is the figure caption][fig_id]

[fig_id]: mmd.png "This is where the title goes" height=45px width=120px

When an image is placed in a paragraph, it is wrapped in a <figure> tag.

This is the figure caption
This is the figure caption
LISTS
MultiMarkdown	Result
* Milk
* Bread
* Cheese
  * Cheddar
  * Camembert
* Rice	
Milk
Bread
Cheese
Cheddar
Camembert
Rice
1. Milk
2. Bread
3. Cheese
  1. Cheddar
  2. Camembert
4. Rice	
Milk
Bread
Cheese
Cheddar
Camembert
Rice
TABLES
MultiMarkdown	Result
Here is as example of [table][simple_table] followed by a more complex [example][reference_table] from the [documentation](https://github.com/fletcher/MultiMarkdown/wiki/MultiMarkdown-Syntax-Guide "MultiMarkdown Syntax Guide")

| First Header | Second Header |         Third Header |  
| :----------- | :-----------: | -------------------: |  
| First row    |      Data     | Very long data entry |  
| Second row   |    **Cell**   |               *Cell* |  
[simple_table]
|              | Grouping                    ||  
| First Header | Second Header | Third Header |  
| ------------ | :-----------: | -----------: |  
| Content      | *Long Cell*                 ||  
| Content      | **Cell**      | Cell         |  
| New section  | More          | Data         |  
[Prototype table][reference_table]
Here is as example of table followed by a more complex example from the documentation

simple_table
First Header	Second Header	Third Header
First row	Data	Very long data entry
Second row	Cell	Cell
Prototype table
Grouping
First Header	Second Header	Third Header
Content	Long Cell
Content	Cell	Cell
New section	More	Data
FOOTNOTES
MultiMarkdown	Result
Here is some text containing a footnote[^somesamplefootnote]. You can then continue your thought...

[^somesamplefootnote]: Here is the text of the footnote itself.

Even go to a new paragraph and the footnotes with go to the bottom of the document[^documentdetails].

[^documentdetails]: Depending on the final form of your document, of course. See the documentation and experiment.

    This footnote has a second paragraph.	
Here is some text containing a footnote[1]. You can then continue your thought…

Even go to a new paragraph and the footnotes with go to the bottom of the document[2].

Here is the text of the footnote itself.  ↩

Depending on the final form of your document, of course. See the documentation and experiment. ↩

This footnote has a second paragraph.

This is an example of an inline footnote.[^This is the *actual* footnote.]	
This is an example of an inline footnote.[1]

This is the actual footnote.  ↩

CROSS REFERENCE
MultiMarkdown	Result
You can place a link to a point in your document like this [one][], or [another][] place in the doc.

## one ##

A simple subheading in a larger document with the same name as the referring tag.

## Another place in the document [another] ##

Another place in the document that is referenced by the [another] tag in the heading
You can place a link to a point in your document like this one or another place in the doc.

one
A simple subheading in a larger document with the same name as the referring tag.

Another place in the document
Another place in the document that is referenced by the [another] tag in the heading

CITATIONS
MultiMarkdown	Result
Let's cite a fake book.[p. 42][#fake]

[#fake]: John Doe. *A Totally Fake Book*. Vanity Press, 2006.	
Let’s cite a fake book.[p. 42, 1]

John Doe. A Totally Fake Book. Vanity Press, 2006.

DEFINITION LISTS
MultiMarkdown	Result
When you are making you definitions you should note the white space.
Apple
:   Pomaceous fruit of plants of the genus Malus in 
    the family Rosaceae.

    Also the makers of really great products.

Banana
:   1. A delicious fruit that can be hazardous
    if left on the ground.

    2. A fruit that comes with it's own packaging

Orange
:   The fruit of an evergreen tree of the genus Citrus.
When you are making you definitions you should note the white space.

Apple
Pomaceous fruit of plants of the genus Malus in the family Rosaceae.

Also the makers of really great products.

Banana
A delicious fruit that can be hazardous if left on the ground.

A fruit that comes with it’s own packaging

Orange
The fruit of an evergreen tree of the genus Citrus.
MATH
MultiMarkdown	Result
\\[ {e}^{i\pi }+1=0 \\]	
e i π + 1 = 0
$${e}^{i\pi }+1=0$$	
e i π + 1 = 0
A formula, \\( {e}^{i\pi }+1=0 \\), inside a paragraph.	
A formula, e i π + 1 = 0 , inside a paragraph.

A formula, ${e}^{i\pi }+1=0$ , inside a paragraph. (Note space after the '$')	
A formula, e i π + 1 = 0 , inside a paragraph.

x^2,y	
x2,y

x^2,y^	
x2,y

x~z,y	
xz,y

x~z,y~	
xz,y

GLOSSARY
MultiMarkdown	Result
Let's reference a glossary term.[^glossary]

[^glossary]:glossary: Glossary     A section at the end ...	
Let’s reference a glossary term.[1]

Glossary:
A section at the end …  ↩

CRITICMARKUP
MultiMarkdown	Result
This is {--is --}a test.	
This is is a test.

This {++is ++}a test.	
This is a test.

This {~~isn't~>is~~} a test.	
This isn’tis a test.

This is a {==test==}.	
This is a test.

This is a test{>>What is it a test of?<<}.	
This is a test.

FENCED CODE BLOCKS
MultiMarkdown	Result
```
This is a fenced
code block
```	
This is a fenced
code block
```perl
# Demonstrate Syntax Highlighting if you link to highlight.js #
# http://softwaremaniacs.org/soft/highlight/en/
print "Hello, world!\n";
$a = 0;
while ($a < 10) {
print "$a...\n";
$a++;
}
```	
# Demonstrate Syntax Highlighting if you link to highlight.js #
# http://softwaremaniacs.org/soft/highlight/en/
print "Hello, world!\n";
$a = 0;
while ($a < 10) {
    print "$a...\n";
    $a++;
}
METADATA VARIABLES
MultiMarkdown	Result
foo: bar

Let's make a reference to [%foo]	
Let’s make a reference to bar

ACKNOWLEDGEMENTS
MultiMarkdown Syntax Guide

https://github.com/fletcher/human-markdown-reference
Based on the Human Markdown Reference by Édouard Brière.

https://github.com/edouard/human-markdown-reference
Modified for MultiMarkdown syntax by the MMD Community.

For the first interaction examples were used from the following websites.

Byword:
http://bywordapp.com/markdown/guide.html
PHP Markdown Extra:
http://michelf.com/projects/php-markdown/extra
MultiMarkdown Guide:
https://github.com/fletcher/MultiMarkdown/blob/master/Documentation/MultiMarkdown%20User%27s%20Guide.md


