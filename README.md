
# 1. HTML
HTML (Hypertext Markup Language) is the standard markup language used for structuring content on the web. It consists of various elements known as tags, which are used to define the structure and presentation of a web page.

## 2. HTML Tags
An HTML tag is an element that defines the structure and presentation of content. Tags are enclosed in angle brackets (< and >). Most tags have an opening and closing pair, with the content placed between them.

For example, the paragraph tag: 

`<p>This is a paragraph.</p>`

## 3. Basic HTML File Structure
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

## 4. Common HTML Tags
1. `<!DOCTYPE html>`: Defines the document type and version of HTML.

2. `<html>`: The root element that contains all other HTML elements.

3. `<head>`: Contains metadata and links to external resources like stylesheets and scripts.

4. `<title>`: Sets the webpage's title shown in browser tabs and bookmarks.

5. `<meta>`: Provides metadata about the webpage, like encoding and viewport settings.

6. `<link>`: Associates external resources like CSS stylesheets with the webpage.

7. `<script>`: Includes JavaScript code or links to external JavaScript files.

8. `<body>`: Wraps the main content of the webpage.

9. `<h1>` to `<h6>`: Define headings with varying levels of importance (h1 is the highest).

10. `<p>`: Defines a paragraph.

11. `<a>`: Creates hyperlinks to other webpages or files.

12. `<img>`: Embeds images into the webpage using "src" attribute to reference the image file.

13. `<ul>` & `<ol>`: Create unordered (bulleted) and ordered (numbered) lists, respectively.

14. `<li>`: Defines list items within a `<ul>` or `<ol>` tag.

15. `<table>`: Creates a table with rows and columns.

16. `<tr>`: Defines a row within a table.

17. `<th>`: Defines header cells in a table.

18. `<td>`: Defines standard cells within a table row.

19. `<form>`: Encapsulates input fields and controls for user input and submission.

20. `<input>`: Represents various input types, like text, checkboxes, radio buttons, etc.

21. `<button>`: Represents a clickable button, often used within forms or for interactive functionality.

22. `<div>`: A generic container for grouping and styling content.

23. `<span>`: An inline-level container for grouping and styling content.

24. `<style>`: Contains CSS code to style the webpage.

25. `<br>`: Inserts a line

## 5. HTML5 Features
HTML5 introduced several new semantic elements:

- `<header>`: Represents the header of a section or the whole page.
- `<nav>`: Represents a navigation section containing links.
- `<main>`: Represents the main content of the web page.
- `<article>`: Represents a self-contained piece of content that can be reused, such as a blog post.
- `<section>`: Represents a generic section of content.
- `<footer>`: Represents the footer of a section or the whole page.

## 6. Tips for New Learners
- Use proper indenting to make your HTML code readable.
- Always close tags properly to ensure correct rendering of the web page.
- Use comments to provide documentation and context for other developers. To add a comment in HTML, use <!-- Comment text -->.


# CSS
CSS stands for Cascading Style Sheets and is used to style and format HTML elements. CSS allows you to control the layout, color, font, and other visual aspects of your web pages.

## CSS Syntax:
CSS uses a selector to target HTML elements and a set of properties to define how the selected element should be styled. Here's an example of the basic syntax:

```
selector {
  property1: value1;
  property2: value2;
}
  ```

The selector can be an HTML element, a class, an ID, or a combination of these. The properties and values control the appearance of the selected element.

## CSS Selectors:
CSS selectors are used to target specific HTML elements to apply styles. Here are some of the most commonly used selectors:

- Element Selector: Targets all instances of a specific HTML element. For example, p targets all paragraphs.
- Class Selector: Targets all instances of an element with a specific class attribute. For example, .my-class targets all elements with the class my-class.
- ID Selector: Targets a single element with a specific ID attribute. For example, #my-id targets the element with the ID my-id.
- Descendant Selector: Targets an element that is a descendant of another element. For example, ul li targets all li elements that are descendants of a ul.

## CSS Properties:
CSS properties are used to control the appearance of HTML elements. Here are some of the most commonly used properties:

- color: Sets the text color.
- font-family: Sets the font family.
- font-size: Sets the font size.
- font-weight: Sets the font weight.
- background-color: Sets the background color.
- padding: Sets the padding around an element.
- margin: Sets the margin around an element.
- border: Sets the border around an element.
- text-align: Sets the text alignment.
- display: Sets how an element is displayed.

## CSS Box Model:
The CSS box model describes the layout of an HTML element. The box model consists of the content area, padding, border, and margin. Understanding the box model is important for controlling the layout of your web pages.

## CSS Layouts:
CSS layouts are used to control the positioning of HTML elements on a web page. There are several different types of layouts, including:

Fixed Layout: Elements are positioned at fixed locations on the page.
Fluid Layout: Elements are sized based on percentages of the screen width.
Responsive Layout: Elements adjust their size and position based on the screen size and orientation.


## CSS Units:
CSS uses several different units of measurement to specify sizes and distances. Here are some of the most commonly used units:

Pixels (px): A fixed size.
Percentages (%): A percentage of the parent element's size.
Em: A relative size based on the font size of the parent element.
Rem: A relative size based on the font size of the root element.
Viewport Units (vw, vh, vmin, vmax): A relative size based on the size of the viewport.


## CSS Pseudo-classes:
CSS pseudo-classes are used to target elements based on their state or position in the document. Here are some of the most commonly used pseudo-classes:

- :hover: Targets an element when the mouse is over it.
- :active: Targets an element when it is clicked.
- :focus: Targets an element when it has focus.
- :first-child: Targets the first child element of a parent element.
- :last-child: Targets the last child element of a parent element.
- :nth-child(n): Targets the nth child element of a parent element.
- :nth-of-type(n): Targets the nth element of a certain type of a parent element.


## CSS Pseudo-elements:
CSS pseudo-elements are used to style specific parts of an element. Here are some of the most commonly used pseudo-elements:

- ::before: Adds content before an element.
- ::after: Adds content after an element.
- ::first-letter: Targets the first letter of a block-level element.
- ::first-line: Targets the first line of a block-level element.

## CSS Box-shadow and Text-shadow:
CSS box-shadow and text-shadow are properties that allow you to add shadows to HTML elements. Here's an example of the syntax:

```
box-shadow: h-offset v-offset blur spread color;
text-shadow: h-offset v-offset blur color;
```
The h-offset and v-offset values control the horizontal and vertical positioning of the shadow, the blur value controls the blur radius, the spread value controls the size of the shadow, and the color value controls the color of the shadow.

## CSS Transitions and Animations:
CSS transitions and animations are used to create dynamic effects on HTML elements. Here's an example of the syntax:

```
transition: property duration timing-function delay;
animation: name duration timing-function delay iteration-count direction;
```
The property value is the property you want to animate, the duration value is the length of the animation, the timing-function value controls the speed of the animation, the delay value is the delay before the animation starts, the name value is the name of the animation, the iteration-count value controls how many times the animation should repeat, and the direction value controls the direction of the animation.

## Conclusion:
CSS is a powerful tool for controlling the appearance of your web pages. With the knowledge of CSS syntax, selectors, properties, box model, layouts, units, pseudo-classes, pseudo-elements, box-shadow and text-shadow, transitions and animations, you can create beautiful and dynamic web pages.




