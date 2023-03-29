
# 1. Introduction
HTML (Hypertext Markup Language) is the standard markup language used for structuring content on the web. It consists of various elements known as tags, which are used to define the structure and presentation of a web page.

# 2. HTML Tags
An HTML tag is an element that defines the structure and presentation of content. Tags are enclosed in angle brackets (< and >). Most tags have an opening and closing pair, with the content placed between them.

For example, the paragraph tag: 

`<p>This is a paragraph.</p>`

# 3. Basic HTML File Structure
A basic HTML file contains the following elements:
- `<!DOCTYPE html>`: Declares the document type and version of HTML.
- `<html>`: The root element enclosing the entire HTML document.
- `<head>`: Contains meta information about the document, such as title, stylesheet, and scripts.
- `<title>`: Defines the title of the web page, which appears in the browser's title bar or tab.
- `<body>`: Contains the content of the web page, such as text, images, and links.

Example:

```html
<!DOCTYPE html>
<html>
<head>
  <title>My First Web Page</title>
</head>
<body>
  <h1>Hello, World!</h1>
  <p>This is a paragraph.</p>
  <a href="https://www.example.com">Visit Example.com</a>
</body>
</html>
```

# 4. Common HTML Tags
1. `<!DOCTYPE html>`: Declaration that defines the HTML version being used (HTML5 in this case).
2. `<html>`: The root element containing the entire HTML document.
3. `<head>`: Container for meta-information like the title, description, and links to CSS or scripts.
4. `<title>`: Sets the title of the web page displayed in browser tabs and `<meta>`: Defines metadata used by browsers and search engines, such as charset or viewport settings.
6. `<body>`: Contains the main content of a web page, including text, images, and other elements.
7. `<h1> to <h6>`: Headings, with `<h1>` being the largest and most important, and `<h6>` being the smallest.
8. `<p>`: Defines a paragraph, which is a block of text separated by whitespace or other block elements.
9. `<a href="">`: Anchor tag for hyperlinks. The `href` attribute specifies the destination URL.
10. `<img src="" alt="">`: Displays an image. `src` points to the image source, and `alt` provides alternative text for accessibility.
11. `<ul>`: Creates an unordered (bulleted) list, with `<li>` elements as list items.
12. `<ol>`: Creates an ordered (numbered) list, with `<li>` elements as list items.
13. `<table>`: Defines a table, with `<tr>` for rows, `<th>` for headers, and `<td>` for data cells.
14. `<form>`: Enables user input through elements like text boxes, radio buttons, and submit buttons.
15. `<input>`: Defines an input field. The `type` attribute determines the input type (e.g., `text`, `password`, `email`).
16. `<button>`: Represents a clickable button that performs an action or triggers an event.
17. `<div>`: Defines a division or section in an HTML document used for grouping and styling elements.
18. `<span>`: A inline container used to apply styles or group elements within a line or paragraph.
19. `<script>`: Contains JavaScript code that adds interactivity to a web page.
20. `<style>`: Defines internal CSS styles for elements on the page.

# 5. HTML5 Features
HTML5 introduced several new semantic elements:

- `<header>`: Represents the header of a section or the whole page.
- `<nav>`: Represents a navigation section containing links.
- `<main>`: Represents the main content of the web page.
- `<article>`: Represents a self-contained piece of content that can be reused, such as a blog post.
- `<section>`: Represents a generic section of content.
- `<footer>`: Represents the footer of a section or the whole page.

# 6. Tips for New Learners
- Use proper indenting to make your HTML code readable.
- Always close tags properly to ensure correct rendering of the web page.
- Use comments to provide documentation and context for other developers. To add a comment in HTML, use <!-- Comment text -->.
