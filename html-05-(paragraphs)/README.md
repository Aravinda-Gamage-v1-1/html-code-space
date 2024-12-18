### HTML Paragraphs
A paragraph always starts on a new line, and is usually a block of text.

The HTML `<p>` element defines a paragraph.
```
<p> This is a paragraph </p>
<p> This is a paragraph </p>
```

### HTML Display
You cannot be sure how HTML will be displayed.

Large or small screens, and resized windows will create different results.

With HTML, you cannot change the display by adding extra spaces or extra lines in your HTML code.

The browser will automatically remove any extra spaces and lines when the page is displayed
```
<p>
This paragraph
contains a lot of lines
in the source code,
but the browser
ignores it.
</p>

<p>
This paragraph
contains         a lot of spaces
in the source         code,
but the        browser
ignores it.
</p>
```

### HTML Horizontal Rules
The `<hr>` tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.

The `<hr>` element is used to separate content (or define a change) in an HTML page
```
<h1>This is heading 1</h1>
<p>This is some text.</p>
<hr>
<h2>This is heading 2</h2>
<p>This is some other text.</p>
<hr>
```

### HTML Line Breaks
The HTML `<br>` element defines a line break.

Use `<br>` if you want a line break (a new line) without starting a new paragraph
```
<p>This is<br>a paragraph<br>with line breaks.</p>
```
### The HTML `<pre>` Element
The HTML `<pre>` element defines preformatted text.

The text inside a `<pre>` element is displayed in a fixed-width font (usually Courier), and it preserves both spaces and line breaks
```
<pre>
  My Bonnie lies over the ocean.

  My Bonnie lies over the sea.

  My Bonnie lies over the ocean.

  Oh, bring back my Bonnie to me.
</pre>
```