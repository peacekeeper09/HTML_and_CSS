
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
- Headings: `<h1>` to `<h6>` (h1 being the largest and h6 the smallest)
- Paragraph: `<p>`
- Links: `<a href="URL">Link text</a>`
- Images: `<img src="imageURL" alt="Image description">`
- Lists: ` <ul>` for unordered lists, <ol> for ordered lists, and `<li>` for list items
- Tables: `<table>`, `<tr>` (table row), `<th>` (table header), and `<td>` (table data)

# 5. HTML5 Features
HTML5 introduced several new semantic elements:

- <header>: Represents the header of a section or the whole page.
- <nav>: Represents a navigation section containing links.
- <main>: Represents the main content of the web page.
- <article>: Represents a self-contained piece of content that can be reused, such as a blog post.
- <section>: Represents a generic section of content.
- <footer>: Represents the footer of a section or the whole page.

# 6. Tips for New Learners
- Use proper indenting to make your HTML code readable.
- Always close tags properly to ensure correct rendering of the web page.
- Use comments to provide documentation and context for other developers. To add a comment in HTML, use <!-- Comment text -->.
