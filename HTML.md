# HTML Tags Cheat Sheet

- [Structural Tags](#structural-tags)
    - [Headings](#headings)
    - [Paragraph](#paragraph)
    - [Links/Anchors](#linksanchors)
    - [Navigation and Footer Tags](#navigation-and-footer-tags)
    - [List Tags](#list-tags)
    - [Forms Tags](#forms-tags)
    - [Buttons](#buttons)
    - [Line Break and Horizontal Rule](#line-break-and-horizontal-rule)
    - [Generic Containers](#generic-containers)
- [Text Styling Tags](#text-styling-tags)
- [Common Attributes](#common-attributes)


## Structural Tags

### Headings
- `<h1> <h2> <h3> <h4> <h5> <h6>`
  - Used to define headings in decreasing order of importance, where `<h1>` is the most important and `<h6>` is the least.

### Paragraph
- `<p>`
  - Used to define a paragraph of text.

### Links/Anchors
- `<a>`: Anchor 
  - Used to create hyperlinks to other web pages or resources.
  - Hyperlinks created by the `href=""` attribute 
    - Example 1: `<a href="#">Stays Here</a>`
    - Example 2: `<a href="https://www.google.com/">Google.com</a>`

### Navigation and Footer Tags
- `<nav>`: Navigation
  - Used to define a section of a web page that contains navigation links or menus.
- `<footer>`: Footer
  - Defines the footer section of a web page, typically containing copyright information, contact details, or other supplementary content that appears at the bottom of the page.

### List Tags 
- `<ul>`: Unordered List
  - Defines an unordered (bulleted) list of items typically used for navigation menus.
- `<ol>`: Ordered List
  - Defines an ordered (numbered) list of items, sometimes used for navigation menus with specific item order.
- `<li>`: List Item
  - Used to define individual list items within `<ul>` or `<ol>` lists.

### Forms Tags
- `<form>`: Form
  - Creates an interactive form that allows users to input data and submit it to a server for processing.
- `<input>`: Input Field
  - Defines an input field for users to enter data, such as text, numbers, or checkboxes.
- `<textarea>`: Text Area
  - Provides a multiline text input field for longer text entries.
- `<select>`: Dropdown List
  - Creates a dropdown list or select box for users to choose from predefined options.
- `<label>`: Label
  - Associates a label with an input field, making it more accessible and user-friendly.

### Buttons
- `<button>`: Button
  - Defines a clickable button that can trigger an action when clicked, often used in forms.

### Line Break and Horizontal Rule
- `<br>`: Line Break
  - Inserts a line break within text, typically used in situations where whitespace alone won't create a new line.
- `<hr>`: Horizontal Rule
  - Creates a thematic break or horizontal line to separate content.

### Generic Containers
- `<div>`: Division
  - Used as a generic container to group and structure content or elements together for styling or scripting purposes. 
  - It does not convey any specific meaning on its own but is a versatile building block for web page layout and organization
  - Bootstrap components and grid generally use `<div>` tags.
- `<span>`: Inline Container
  - Provides a generic inline container that can be styled with CSS or used for scripting purposes.

## Text Styling Tags

- `<strong>`: Strong
  - Indicates strong importance or emphasis for text content.
- `<em>`: Emphasis
  - Indicates slight emphasis or importance for text content, typically displayed in italics.
- `<s>`: Strikethrough
  - Renders text with a strikethrough effect to indicate that it's no longer relevant or accurate.
- `<blockquote>`: Block Quote
  - Used to define a block of quoted text from another source.
- `<q>`: Inline Quote
  - Used to enclose a short inline quotation.
- `<abbr>`: Abbreviation
  - Defines an abbreviation or acronym, providing a title attribute for expanded text.
- `<cite>`: Citation
  - Used to reference the title of a creative work, such as a book or movie.
- `<code>`: Code
  - Indicates that the enclosed text is computer code, typically displayed in a monospace font.
- `<pre>`: Preformatted Text
  - Preserves whitespace and line breaks, often used for displaying code or other text that requires exact formatting.
- `<sup>`: Superscript
  - Formats text as a superscript, often used for footnotes or mathematical exponents.
- `<sub>`: Subscript
  - Formats text as a subscript, often used in chemical formulas or mathematical notation.
- `<del>`: Deleted Text
  - Indicates text that has been deleted or removed from a document.
- `<ins>`: Inserted Text
  - Indicates text that has been added or inserted into a document.
- `<mark>`: Marked Text
  - Highlights or marks a portion of text for reference or emphasis.

## Common Attributes

- `class` Attribute
  - Used to assign one or more class names to an HTML element, allowing CSS styling and JavaScript targeting.
  - Example: `<div class="container">...</div>`

- `id` Attribute
  - Provides a unique identifier for an HTML element, often used for targeted styling or JavaScript interactions.
  - Example: `<div id="header">...</div>`

- `src` Attribute
  - Specifies the source URL or file path for elements like images, audio, and video.
  - Example: `<img src="image.jpg" alt="Description">`

- `alt` Attribute
  - Provides alternative text for elements like images, enhancing accessibility and SEO.
  - Example: `<img src="image.jpg" alt="Description">`

- `type` Attribute
  - Specifies the type of an input element, such as text, number, checkbox, or radio button.
  - Example: `<input type="text">`

- `target` Attribute
  - In anchor (`<a>`) elements, specifies where the linked content should be opened (e.g., in a new tab or the same window).
  - Example: `<a href="https://www.example.com" target="_blank">Visit Example</a>`

- `placeholder` Attribute
  - Provides a hint or example of the expected input in input and textarea elements.
  - Example: `<input type="text" placeholder="Enter your name">`

- `value` Attribute
  - Sets the initial or default value of input elements.
  - Example: `<input type="text" value="Default Text">`

- `required` Attribute
  - Indicates that a form field must be filled out before submitting the form.
  - Example: `<input type="text" required>`

- `disabled` Attribute
  - Used to disable interaction with form elements like buttons and input fields.
  - Example: `<input type="text" disabled>`



