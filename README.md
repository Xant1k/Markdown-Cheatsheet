# Markdown-Cheatsheet

Markdown editing help

Emoji: http://www.webpagefx.com/tools/emoji-cheat-sheet/

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

Images
To include an image, just put a "!" in front of a text link:
![alternate text](https://sourceforge.net/images/icon_linux.gif)


alternate text
The "alternate text" will show up if the browser can't load the image.
You can also use a title if you want, like this:
![tiny arrow](https://sourceforge.net/images/icon_linux.gif "tiny arrow")


tiny arrow
To reference an attached image, just use the img macro. You can add more attributes:
[[img src=attached-image.jpg alt=foobar]]


Videos
To embed a YouTube video, use the `embed` macro (only YouTube is supported at this time):
[[embed url=http://www.youtube.com/watch?v=6YbBmqUnoQM]]

Escapes and HTML
What if you want to just show asterisks, not italics?
* this shows up in italics: *a happy day*
* this shows the asterisks: \*a happy day\*


To show a literal <b> or an unknown tag like <foobar> you need escape it with HTML entities: :
<b>this will be bold</b>
you should escape &lt;unknown&gt; tags
&copy; special entities work
&amp;copy; if you want to escape it

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



Alternatively, for H1 and H2, an underline-ish style:

Alt-H1

Alt-H2
