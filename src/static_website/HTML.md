# HTML

**H**yper**T**ext **M**arkup **L**anguage (HTML)

the standard markup language that tells web browsers what to display

for an example, visit any website, right click the page and `inspect element` or `view page source`. you will see that page's HTML.

HTML consists of `elements` which make up a webpage, and `tags` to give `content` meaning

diagram here

## Tutorial

create a new file `hello.html` and open it in a web browser, it will be a blank page.

in a text editor, open the file and add:

```html
<p>Hello</p>
```

save `hello.html` and refresh the page, you should see Hello

this `hello.html` document defines a web page with a paragraph that contains 'Hello'

we can add more to it:

```html
<h1>My Website</h1>
<p>Hello</p>
<p>today I ran to the park</p>
```

save and refresh

now this web page has a heading 'My Website', and 2 paragraphs.

there are a lot of HTML elements, but you dont need to know them all, you can find a list in the [MDN web docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element)

### Nesting Elements

elements can be put *inside* other elements. this is called `nesting`

```html
<h1>My Website</h1>
<p>Hello</p>
<p>today I <strong>ran</strong> to the park</p>
```

the `strong` element is nested inside the 2nd `p` element

```html
<h1>My Website</h1>
<p>Hello</p>
<p>today I <strong>ran</strong> to the park</p>
<footer>
    <p>2022</p>
</footer>
```

a `p` element nested inside a `footer` element.

note how the `p` inside the `footer` is indented, you *could* put it all in one line like 
```html
<footer><p>2022</p></footer>
```
and the browser still renders it exactly the same, but to make it easier for yourself and others to understand the website by reading the code, its best to indent when it is nested

..so why didnt we nest the `strong` element inside the `p` element?

### Block vs Inline Elements

* Block elements create a new line, creating a block, hence *block*
* Inline elements do not create a new line, hence *inline*

Blocks are generally structural elements like headings, paragraphs, lists, sections.

Inlines are generally nested inside blocks.

```html
<em>first</em>
<em>second</em>
<em>third</em>

<p>fourth</p>
<p>fifth</p>
<p>sixth</p>
```

put this example in a `.html` file and see how it renders

### Empty Elements

some elements omit a closing tag and content

an example is the `img` tag

```html
<img src="https://yzalv.in/manual/smooth_brain.png">
```

notice how the `img` tag contains `src=...` in it. this is an `attribute`

### Attributes

attributes contain extra information about an element

```html
<a href="https://google.com">a link to google</a>
```

the `a` tag stands for `anchor`. anchors are used to make it's content link to somewhere, like another webpage or another website.

in this example clicking the text will link to google's home page.

### HTML Structure

you can have webpages without the following structure and they will work fine, but its a good idea to follow existing conventions

```html
<!DOCTYPE html>
<html lang="en-US">
  <head>
    <meta charset="utf-8">
    <title>My test page</title>
  </head>
  <body>
    <p>This is my page</p>
  </body>
</html>
```

1. `<html></html>`: wraps all content on the page
2. `<head></head>`: wraps all content you want to include on the page but *not display*, such as search engine keywords, page description for search results, linked CSS and JS, etc.
3. `<body></body>`: wraps all content that *displays* on the page.

## Lab

hopefully know and understand HTML now, so let try build something

![Basic Website](basic_website.png)

this is screenshot of webpage that is only html, it is like a personal profile

your task is to create the same/similar thing (but about yourself)

remember you only need to remember the *concepts*, if you need to you can google everything if unsure

eg `how do i create a numbered list HTML`

and you can refer to the [MDN web docs](https://developer.mozilla.org/en-US/docs/Web/HTML/Element) for help with finding and using the right HTML elements