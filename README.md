# Markdown-Cheatsheet

Markdown editing help

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


