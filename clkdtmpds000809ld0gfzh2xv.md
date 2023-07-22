---
title: "How to get started with HTML5?"
datePublished: Sat Jul 22 2023 09:42:01 GMT+0000 (Coordinated Universal Time)
cuid: clkdtmpds000809ld0gfzh2xv
slug: how-to-get-started-with-html5
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1690018008229/9c6ae431-0455-4c60-8d39-3a3603b80269.png
tags: css, javascript, web-development, html, html5

---

## What is HTML?

HTML, or Hypertext Markup Language, is the foundation of web development. It’s the markup language used to create websites and is responsible for the structure, content, and layout of web pages. If you’re interested in web development or want to learn how to create a website, HTML is an excellent place to start. In this blog, I’ll be providing a step-by-step guide on how to get started with HTML.

---

## Basics of HTML

Before you dive into coding HTML, it’s important to understand the basics. HTML consists of tags, attributes, and content. Tags are used to define the structure of a web page, while attributes provide additional information about the tag. Content is the information that appears on the web page.

Here’s an example of what an HTML tag looks like:

```xml
<tagname attribute="value">Content</tagname>
```

The `<tagname>` is the name of the tag, and the attribute and value provide additional information about the tag. The content is the information that appears between the opening and closing tags.

---

## Some Important Tags in HTML

### Document Structure Tags

1. `<!DOCTYPE>`: This tag specifies the version of HTML being used in the document.
    
2. `<html>`: This tag is the root element of an HTML document.
    
3. `<head>`: This tag contains meta information about the document, such as the title, meta tags, and links to CSS files.
    
4. `<title>`: This tag specifies the title of the document, which appears in the browser's title bar.
    
5. `<body>`: This tag contains the main content of the document.
    

### Semantic Tags

1. `<header>`: This tag creates the header of a web page.
    
2. `<nav>`: This tag creates navigation links.
    
3. `<main>`: This tag contains the main content of a web page.
    
4. `<article>`: This tag creates a standalone piece of content, such as a blog post.
    
5. `<aside>`: This tag contains related content, such as a sidebar.
    
6. `<footer>`: This tag creates the footer of a web page.
    

### Script Tag

1. `<script>`: This tag contains JavaScript code.
    

### Metadata Tags

1. `<meta>`: This tag contains meta information about the document, such as keywords and description.
    

### Link Tags

1. `<a>`: This tag creates a hyperlink.
    
2. `<style>`: This tag contains CSS code.
    
3. `<link>`: This tag creates a link to an external resource, such as a CSS file.
    

### Media Tags

1. `<img>`: This tag inserts an image into the document.
    
2. `<audio>`: This tag inserts an audio file into the document.
    

### Text Tags

1. `<h1>` to `<h6>`: These tags create headings of different sizes.
    
2. `<p>`: This tag creates a paragraph.
    

### Format Tags

1. `<br>`: This tag creates a line break.
    
2. `<hr>`: This tag creates a horizontal line.
    

### List Tags

1. `<ul>`: This tag creates an unordered list.
    
2. `<ol>`: This tag creates an ordered list.
    
3. `<li>`: This tag creates a list item.
    

### Table Tags

1. `<table>`: This tag creates a table.
    
2. `<thead>`, `<tbody>`, and `<tfoot>`: These tags define the different parts of a table.
    
3. `<tr>`: This tag creates a table row.
    
4. `<th>`: This tag creates a table header cell.
    
5. `<td>`: This tag creates a table data cell.
    

### Form Tags

1. `<form>`: This tag creates a form.
    
2. `<input>`: This tag creates an input field.
    
3. `<label>`: This tag creates a label for an input field.
    
4. `<select>`: This tag creates a drop-down list.
    
5. `<option>`: This tag creates an option within a drop-down list.
    
6. `<textarea>`: This tag creates a multi-line input field.
    
7. `<button>`: This tag creates a button.
    
8. `<fieldset>`: This tag groups related form elements together.
    
9. `<legend>`: This tag creates a caption for a fieldset.
    

### Container Tags

1. `<div>`: This tag creates a division of a web page.
    
2. `<span>`: This tag creates an inline container.
    

### Embed Tag

1. `<iframe>`: This tag creates an inline frame, which can be used to embed a webpage within a webpage.
    

This is just a brief overview of some of the most commonly used HTML tags. There are many more tags available in HTML, each with its unique purpose and syntax.

---

## Step 1: Setting Up Your Development Environment

To start coding HTML, you’ll need a text editor and a web browser. There are many text editors to choose from, including Notepad, Sublime Text, and Visual Studio Code. For beginners, It is recommended to use Notepad or Visual Studio Code, as they’re free and easy to use.

---

## Step 2: Downloading some extensions

Once you’ve downloaded and installed Visual Studio Code, you can download extensions to help you with your HTML coding. Some popular extensions for HTML include:

* **HTML Snippets**: Provides shortcuts for HTML tags and attributes
    
* **Live Server**: Automatically updates your web page as you make changes to your HTML file
    
* **CSS Peek**: Allows you to quickly jump to the CSS definition of a class or ID
    
* **Auto Close Tag**: Automatically closes HTML tags as you type
    

For a more comprehensive list of extensions for developers, check out [this blog](https://neyywaar.hashnode.dev/10-must-have-vs-code-extensions-for-developers).

Once you've downloaded any necessary extensions, open up Visual Studio Code and create a new file. Save the file with a `.html` extension, such as `index.html`, and you're ready to start coding HTML!

---

## Step 3: Creating the First HTML Document

Now it’s time to create your first HTML document. Start by adding the basic structure of an HTML document:

```xml
<!DOCTYPE html>
<html>
  <head>
    <title>Your Title Here</title>
  </head>
  <body>
   <!-- Write your Code Here -->
  </body>
</html>
```

The `<!DOCTYPE html>` declaration is used to specify the version of HTML you’re using. In this case, we’re using HTML5.

The `<html>` tag is used to enclose the entire HTML document. Inside the `<html>` tag, there are two main sections: the `<head>` section and the `<body>` section.

The `<head>` section contains information about the web page, such as the title of the page, and links to external stylesheets and scripts. The `<body>` section contains the content of the web page.

---

## Step 4: Add Content to Your HTML Document

Now it’s time to add content to your HTML document. Let’s start by adding a heading and a paragraph:

```xml
<!DOCTYPE html>
<html>
  <head>
    <title>Your Title Here</title>
  </head>
  <body>
    <h1>Welcome to My Website</h1>
    <p>This is my first HTML document. Here is some text.</p>
  </body>
</html>
```

The `<h1>` tag is used to create a heading, and the `<p>` tag is used to create a paragraph. You can add as much content as you want to your HTML document.

---

## Step 5: Preview Your HTML Document

To see your HTML document in action, open it up in your web browser. Simply right-click on the file and select “Open with…” and choose your preferred web browser (Mozilla Firefox is a great browser for web developers) or use the Live Server Extension.

Congratulations! You’ve just created your first HTML document.

---

## Step 6: Continue Learning HTML

HTML is a vast subject, and there’s always more to learn. To continue learning HTML, we recommend checking out online tutorials and resources. There are many free resources available, including W3Schools and Mozilla Developer Network.

---

## Step 7: Linking CSS and JavaScript

In addition to HTML, web pages often include CSS (Cascading Style Sheets) and JavaScript to style and add interactivity to the page. To link a CSS file to your HTML document, you can add the following code to the head section of your HTML file:

```xml
<head>
  <link rel="stylesheet" type="text/css" href="styles.css">
</head>
```

This code creates a link between your HTML document and a separate CSS file named `styles.css` using the `<link>` tag. The href attribute specifies the path to your CSS file. Once you've linked your CSS file, you can add CSS code to style your HTML elements.

Similarly, to link a JavaScript file to your HTML document, you can add the following code to the head section of your HTML file:

```xml
<head>
  <script src="script.js"></script>
</head>
```

This code creates a link between your HTML document and a separate JavaScript file named `script.js` using the `<script>` tag. The src attribute specifies the path to your JavaScript file. Once you've linked your JavaScript file, you can add JavaScript code to add interactivity to your web page.

By linking CSS and JavaScript files to your HTML document, you can add additional functionality and style to your web page.

---

## Find Me on:

* **GitHub** - [github.com/Neyywaar](https://github.com/Neyywaar)
    
* **Twitter** - [twitter.com/neyywaar](https://twitter.com/neyywaar)