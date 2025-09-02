HTML stands for Hyper Text Markup Language. It is the standard language used to create and structure the content of a webpage.
 It uses a set of tags and attributes to define the structure of the content, 
such as headings, paragraphs, links, images, tables, and forms.
- **HyperText:** This refers to the ability to create links that connect web pages to one another, making the web a connected "web" of information.
- **Markup Language:** This means you use "tags" to surround your content, giving that content meaning and structure. You are "marking up" a plain text document.

First Website: https://info.cern.ch/hypertext/WWW/TheProject.html

## 1: The Heading (<h1> to <h6>)

**What it is:** Headings are tags used to define titles and subtitles on your page. They are crucial for creating a logical hierarchy and outline for your content.

```html
<h1>Heading 1</h1>
<h2>Heading 2</h2>
<h3>Heading 3</h3>
<h4>Heading 4</h4>
<h5>Heading 5</h5>
<h6>Heading 6</h6>
```

- <h1>: The most important heading, typically used only once per page for the main title.
- <h2>: A major section heading.
- <h3>: A sub-section heading under an <h2>.
- ...and so on, down to <h6>, the least important heading.

**The Purpose:** To structure your document in a way that is understandable to both humans and machines (like search engines and screen readers). It is **not** just for making text big; it is for giving the text structural importance.

## 2. The Paragraph (<p>)

**What it is:** The paragraph tag is the most common tag you'll use. It's for grouping sentences and blocks of text together.

**The Tag:** <p>

**The Purpose:** To define a distinct paragraph of text. Browsers automatically add a little bit of space before and after a <p> element, separating it from other content. You should not use multiple line breaks; you should use multiple <p> tags.

```html
<p>This is the first paragraph. It contains several sentences about a topic.</p>
<p>This is a second, separate paragraph. The browser will display it with a space between it and the first one.</p>
```

## 3: HTML Horizontal Rules
The `<hr>` tag defines a thematic break in an HTML page, and is most often displayed as a horizontal rule.

The `<hr>` element is used to separate content (or define a change) in an HTML page:

```html
<p>This is the first topic.</p>
<hr />
<p>This is a completely different topic.</p>
```

## 4. The Line Break Tag: <br>

This tag tells the browser, "Stop writing on this line and immediately start on the next one." It's like hitting the Enter key once in a poem or an address.

- **Purpose:** Creates a single line break.
- **Example:**codeHtml
-- 
    
    ```html
    <p>221B Baker Street<br>
    London, England</p>
    ```
    

## 6. List Elements (<ul>, <ol>, <li>)

**What it is:** These tags are used to create lists. This is a perfect example of nesting.

**The Tags:**

- <ul>: An **U**nordered **L**ist. It creates a bulleted list.
- <ol>: An **O**rdered **L**ist. It creates a numbered list.
- <li>: A **L**ist **I**tem. Each item in either type of list must be wrapped in an <li> tag.

**The Purpose:** To group related items together in a list format.

**Example (Nesting in action):**

The <li> elements are nested as children inside the <ul> parent.
<ul>
  <li>Tea Bag</li>
  <li>Water</li>
  <li>Sugar</li>
  <li>Milk</li>
</ul>


<ol>
  <li>First, boil the water in a kettle.</li>
  <li>Add tea bag, sugar and milk into it</li>
  <li>Keep boiling it for 5 minutes </li>
  <li>Serve the tea by pouring it into cup</li>
</ol>
​
7: The Anchor Tag (<a>)
What it is: The Anchor tag is what makes the web "hypertext." It is used to create a hyperlink to another webpage, a file, or a location within the same page.
The Tag: <a>
The Purpose: To make text (or an image) clickable, allowing users to navigate. It requires an attribute called href (hypertext reference) to specify the destination URL.
<a href="https://www.coderarmy.in/">Vist Coder Army</a>
​
HTML Links - The target Attribute

By default, the linked page will be displayed in the current browser window. To change this, you must specify another target for the link.

The `target` attribute specifies where to open the linked document.

The `target` attribute can have one of the following values:

- `_self` - Default. Opens the document in the same window/tab as it was clicked
- `_blank` - Opens the document in a new window or tab

## 8. The Image Tag (<img>)

**What it is:** The Image tag is a **self-closing tag** used to embed an image onto your page.

**The Tag:** <img>

**The Purpose:** To display a visual image. It requires two main attributes:

- src (source): The path or URL to the image file. This is mandatory.
- alt (alternative text): A description of the image. This is vital for accessibility (screen readers for the visually impaired will read this out) and for when the image fails to load

<img src="https://cdn.britannica.com/16/234216-050-C66F8665/beagle-hound-dog.jpg" height="300px" width="300px" alt="This is Dog Photo">

















<!--  LF will be replaced by CRLF the next time Git touches it
git config --global core.autocrlf false -->