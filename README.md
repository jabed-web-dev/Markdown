# Welcome to Markdown


### Table of contents
   * [Headers](#Headers)
   * [Emphasis](#Emphasis)
   * [Blockquote](#Blockquote)
   * [Details](#Details)
   * [Inline Code](#Inline-Code)
   * [Horizontal Rule](#Horizontal-Rule)
   * [Lists](#Lists)
   * [Link](#Link)
   * [Line Break](#Line-Break)
   * [Image](#Image)
   * [Videos](#Videos)
   * [Emoji](#Emoji)
   * [Code Blocks](#Code-Blocks)
   * [Tables](#Tables)
   * [Task List](#Task-List)
   * [GitHub User name](#GitHub-User-name)
   * [Backslash Escapes](#Backslash-Escapes)
   * [Comments](#Comments)

<!-- Headers -->
# Headers

```md
# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6
```

# Header 1
## Header 2
### Header 3
#### Header 4
##### Header 5
###### Header 6

```md
Alternatively, for H1 and H2, an underline-ish style:

Header 1
=

Header 2
-
```

Alternatively, for H1 and H2, an underline-ish style:

Header 1
=
Header 2
-

<!-- Emphasis -->
# Emphasis

```md
Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~Scratch~ and ~~Scratch this.~~
```

Emphasis, aka italics, with *asterisks* or _underscores_.

Strong emphasis, aka bold, with **asterisks** or __underscores__.

Combined emphasis with **asterisks and _underscores_**.

Strikethrough uses two tildes. ~Scratch~ and ~~Scratch this~~


<!-- Blockquote -->
# Blockquote

```md
> blockquote \
> Dorothy followed her through many of the beautiful rooms in her castle.
```

> Blockquote \
> Dorothy followed her through many of the beautiful rooms in her castle.


<!-- Details -->
# Details

~~~md
#### Details
<details>
  <summary>Click to expand!</summary>
  <blockquote>
    
```js
  function sum(a, b) {
    return a + b;
  }
```
  </blockquote>
</details>

#### Nested details
<details><summary>JavaScript</summary><blockquote>
<details><summary>Variable</summary><blockquote>

```js
var
let
const
```
</blockquote></details>
<details><summary>Boolean</summary><blockquote>

```js
true
false
```
</blockquote></details>
</blockquote></details>
~~~

#### Details
<details>
  <summary>Click to expand!</summary>
  <blockquote>
    
```js
  function sum(a, b) {
    return a + b;
  }
```
  </blockquote>
</details>

#### Nested details
<details><summary>JavaScript</summary><blockquote>
<details><summary>Variable</summary><blockquote>

```js
var
let
const
```
</blockquote></details>
<details><summary>Boolean</summary><blockquote>

```js
true
false
```
</blockquote></details>
</blockquote></details>

<!-- Inline Code -->
# Inline Code

```md
` or ``
The `createServer()` method of `http` creates a new HTTP server and returns it.
`var` `let` `const`
``console.log(`Hello World`)``
```

The `createServer()` method of `http` creates a new HTTP server and returns it. \
`var` `let` `const` \
``console.log(`Hello World`)``

<!-- Horizontal Rule -->
# Horizontal Rule

```md
---
___
```

---
___

<!-- Lists -->
# Lists

```md
Unordered list use asterisks (*), minuses (-) and pluses (+)

* Unordered list can use asterisks
- Or minuses
+ Or pluses

    You can have properly indented paragraphs within list items. Notice the blank line above,
    and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

1. First ordered list item
2. Another item
    * Unordered sub-list. 
    * Unordered sub-list. 
3. Actual numbers don't matter, just that it's a number
    1. Ordered sub-list
    2. Ordered sub-list
4. And another item.

To have a line break without a paragraph, you will need to use two trailing spaces.
Note that this line is separate, but within the same paragraph.

    (This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)
```


Unordered list use asterisks (*), minuses (-) and pluses (+)

* Unordered list can use asterisks
- Or minuses
+ Or pluses

    You can have properly indented paragraphs within list items. Notice the blank line above,
    and the leading spaces (at least one, but we'll use three here to also align the raw Markdown).

1. First ordered list item
2. Another item
    * Unordered sub-list. 
    * Unordered sub-list. 
3. Actual numbers don't matter, just that it's a number
    1. Ordered sub-list
    2. Ordered sub-list
4. And another item.

To have a line break without a paragraph, you will need to use two trailing spaces.
Note that this line is separate, but within the same paragraph.

    (This is contrary to the typical GFM line break behaviour, where trailing spaces are not required.)


<!-- Link -->
# Link

```md
Inline-style:

Format: `[link text](url "title")`

https://github.com - automatic!

[GitHub](http://github.com "GitHub")


Reference-style: 

Format: `[name] url "title"`

[url]: https://github.com/jabed-dev "Jabed Hossain"

[Jabed Hossain][url]

[jabed-dev][url]
```

Inline-style:

Format: `[link text](url "title")`

https://github.com - automatic!

[GitHub](http://github.com "GitHub")


Reference-style: 

Format: `[name] url "title"`

[url]: https://github.com/jabed-dev "Jabed Hossain"

[Jabed Hossain][url]

[jabed-dev][url]


<!-- Line Break -->
# Line Break

```md
 \ or <br>
 
[Lists](#Lists)
[Link](#Link)

[Lists](#Lists) \
[Link](#Link)

For compatibility, use trailing backslash (\) or the <br> HTML tag at the end of the line.
```

[Lists](#Lists)
[Link](#Link)

[Lists](#Lists) \
[Link](#Link)

For compatibility, use trailing backslash (\ ) or the <br> HTML tag at the end of the line.

<!-- Image -->
# Image 

```md
Inline-style:

Format: ![Alt massage](url "title")

![GitHub](https://github.githubassets.com/images/modules/open_graph/github-mark.png "GitHub")

Image resize: <img src="url" alt="GitHub" width="200" height="150">

<img src="https://github.githubassets.com/images/modules/open_graph/github-mark.png" alt="GitHub" width="200" height="150">

Reference-style: 
Format: [name] url "title"

[image-name]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Markdown"

![Markdown Image][image-name]

![markdown Image][image-name]

link with image

[![Alt massage](image url)](link url)

[![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png "https://github.com")](https://github.com)
```

Inline-style:

Format: `![Alt massage](url "title")`

![GitHub](https://github.githubassets.com/images/modules/open_graph/github-mark.png "GitHub")

Image resize: `<img src="url" alt="GitHub" width="350" height="200">`

<img src="https://github.githubassets.com/images/modules/open_graph/github-mark.png" alt="GitHub" width="350" height="200">

Reference-style: 
Format: `[name] url "title"`

[image-name]: https://github.com/adam-p/markdown-here/raw/master/src/common/images/icon48.png "Markdown"

![Markdown Image][image-name]
![markdown Image][image-name]
![markdown Image][image-name]

link with image

`[![Alt massage](image url)](link url)`

[![Octocat](https://github.githubassets.com/images/icons/emoji/octocat.png "https://github.com")](https://github.com)


<!-- Videos -->
# Videos

```md
Formate-1: [![Alternate Text](image-url)](video-url "Link Title")

Formate-2: <a href="video-url" title="Link Title"><img src="image-url" alt="Alternate Text" width="" height=""></a>

## Markdown Crash Course
[![Markdown Crash Course](https://i.ytimg.com/vi_webp/HUBNt18RFbo/maxresdefault.webp)](https://www.youtube.com/embed/HUBNt18RFbo "Markdown Crash Course")
```

### Markdown Crash Course
[![Markdown Crash Course](https://i.ytimg.com/vi_webp/HUBNt18RFbo/maxresdefault.webp)](https://www.youtube.com/embed/HUBNt18RFbo "Markdown Crash Course")


<!-- Emoji -->
# Emoji 

```md
GitHub supports 
Emoji URL: https://gist.github.com/rxaviers/7360908 

Format:  :emoji-name:

emoji!
:+1: :sparkles: :camel: :tada:
:rocket: :metal: :octocat: :star:
```

GitHub supports 
Emoji URL: https://gist.github.com/rxaviers/7360908 

Format: `:emoji-name:`

Emoji! \
:+1: :sparkles: :camel: :tada: :rocket: :metal: :octocat: :star:


<!-- Code Blocks -->
# Code Blocks

~~~md

Formate 1: ```
          code here..
          ```
            
Formate 2: ~~~
            code here..
           ~~~

Syntax-1 not language highlight: 

```
  code here..
```

Syntax-2 language highlight: 

```language name here
  code here..
```
~~~

Syntax 1:
```
let number = 20;
function test() {
    console.log("look ma’, no spaces"); 
}
```

Syntax 2:
```javascript
let number = 20;
function test() {
    console.log("look ma’, no spaces"); 
}
```

<!-- Tables -->
# Tables

```md
Header-1 | Header-1 | Header-3
-------- | -------- | --------
Item-1   | Item-2   | Item-3
Item-4   | Item-5   | Item-6
Item-7   | Item-8   | Item-9
Item-7   | Item-8   | Item-9
```
Header-1 | Header-1 | Header-3
-------- | -------- | --------
Item-1   | Item-2   | Item-3
Item-4   | Item-5   | Item-6
Item-7   | Item-8   | Item-9
Item-7   | Item-8   | Item-9

<!-- Task List -->
# Task List

```md
- [x] Write the press release
- [ ] Update the website
- [x] Contact the media 
```
- [x] Write the press release
- [ ] Update the website
- [x] Contact the media 


<!-- GitHub User name -->
# GitHub User name

```md
[@jabed-dev](https://github.com/jabed-dev "Jabed Hossain")
```

[@jabed-dev](https://github.com/jabed-dev "Jabed Hossain")


<!-- Backslash Escapes -->
# Backslash Escapes

```md
Markdown allows you to use backslash escapes to generate literal characters which would
otherwise have special meaning in Markdown’s formating syntax.

\*literal asterisks\*
\_literal asterisks\_
\`literal asterisks\`
```

Markdown allows you to use backslash escapes to generate literal characters which would
otherwise have special meaning in Markdown’s formating syntax.

\*literal asterisks\* \
\_literal asterisks\_ \
\`literal asterisks\`

<!-- Comments -->
# Comments

```md
<!-- comments here.. -->
```

[Table of contents](#Table-of-contents)

