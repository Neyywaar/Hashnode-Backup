---
title: "Supercharged HTML Cheatsheet"
datePublished: Thu Jan 18 2024 11:51:43 GMT+0000 (Coordinated Universal Time)
cuid: clrj5iu3f000009l1fd4o2s8a
slug: supercharged-html-cheatsheet
cover: https://cdn.hashnode.com/res/hashnode/image/upload/v1705578328994/09a03b3a-750b-4546-ae48-7828ada9cd7c.png
ogImage: https://cdn.hashnode.com/res/hashnode/image/upload/v1705578691912/c6b0c0c0-7957-493d-9f89-156727855170.png
tags: html5, cheatsheet, html-tags

---

## Boilerplate

```xml
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Document</title>
</head>
<body>
    
</body>
</html>
```

---

## Headings

There are six headings available in HTML, `<h1>` is the largest among all, and `<h6>` is the smallest.

### &lt;h1&gt; Tag

```xml
<h1>Heading 1</h1>
```

### &lt;h2&gt; Tag

```xml
<h2>Heading 2</h2>
```

### &lt;h3&gt; Tag

```xml
<h3>Heading 3</h3>
```

### &lt;h4&gt; Tag

```xml
<h4>Heading 4</h4>
```

### &lt;h5&gt; Tag

```xml
<h5>Heading 5</h5>
```

### &lt;h6&gt; Tag

```xml
<h6>Heading 6</h6>
```

---

## Container

Container tags are the tags that contain some data such as text, image, etc. There are several container tags in HTML.

### &lt;div&gt; tag

The div tag or division tag is used to make blocks or divisions in the document.

```xml
<div> This is div block </div>
```

### &lt;span&gt; tag

The span is a container for inline content

```xml
<span> This is span block </span>
```

### &lt;p&gt; tag

The p tag is used to create a paragraph in HTML.

```xml
<p> This is a paragraph </p>
```

### &lt;pre&gt; tag

The pre tag represents pre-formatted text.

```xml
<pre> Hello World! </pre>
```

### &lt;code&gt; tag

The code tag is used to represent source codes in HTML.

```xml
<code>
    printf("Hello World!);
</code>
```

---

## Text Formatting

Text formatting tags in HTML allow you to apply various styles and effects to text. Here are some commonly used text formatting tags:

### &lt;u&gt; tag

Represents underlined text.

```xml
<u>underlined</u>
```

### &lt;b&gt; tag

Represents bolded text.

```xml
<b>bolded</b>
```

### &lt;i&gt; tag

Represents italicized text.

```xml
<i>ilaticized</i>
```

### &lt;strong&gt; tag

Represents strong importance or emphasis. Typically displayed as bold text.

```xml
<strong>important</strong>
```

### &lt;em&gt; tag

Represents emphasized text. Typically displayed as italicized text.

```xml
<em>emphasized</em>
```

### &lt;s&gt; tag

Represents strikethrough text.

```xml
<s>strikethrough</s>
```

### &lt;mark&gt; tag

Represents text highlighted for reference or notation.

```xml
<mark>highlighted</mark>
```

### &lt;sub&gt; tag

Represents subscript text.

```xml
H<sub>2</sub>O
```

### &lt;sup&gt; tag

Represents superscript text.

```xml
x<sup>2</sup>
```

These tags can be used individually or combined to achieve various text formatting effects in your HTML documents. Keep in mind that the presentation of these elements can be influenced by CSS styles applied to your document.

---

## List Tags

Lists in HTML can take various forms, such as numerical, alphabetic, bullet points, or other symbols. HTML allows you to define the type of list and specify individual list items to ensure a well-organized document.

### &lt;ol&gt; Tag

This tag is used to create ordered lists, where each list item is numbered.

```xml
<ol>
    <li>Item 1</li>
    <li>Item 2</li>
    <li>Item 3</li>
</ol>
```

### &lt;ul&gt; Tag

This tag is used to create unordered lists, where each list item is preceded by a bullet point or another marker.

```xml
<ul>
    <li>Item A</li>
    <li>Item B</li>
    <li>Item C</li>
</ul>
```

### &lt;li&gt; Tag

This tag is used to define individual items within a list.

```xml
<ul>
    <li>Apple</li>
    <li>Orange</li>
    <li>Banana</li>
</ul>
```

### &lt;dl&gt; Tags

The &lt;dl&gt; tag is used to create description lists. The `<dt>` tag is used to define the term (label), and the `<dd>` tag is used to define the description.

```xml
<dl>
    <dt>Term 1</dt>
    <dd>Description 1</dd>
    <dt>Term 2</dt>
    <dd>Description 2</dd>
</dl>
```

---

## Media Tags

In HTML, media tags are used to embed and control various types of media, such as images, audio, and video. Here are some common media-related tags in HTML:

### &lt;img&gt; Tag

This tag is used to embed images on a webpage.

```xml
<img src="image.jpg" alt="Description of the image">
```

### &lt;audio&gt; Tag

This tag is used to embed audio content on a webpage.

```xml
<audio controls><source src="audio.mp3" type="audio/mp3"></audio>
```

### &lt;video&gt; Tag

This tag is used to embed video content on a webpage.

```xml
<video><source src="video.mp4" type="video/mp4"></video>
```

---

## Table Tag

This tag in HTML is used to create tables on a web page. Tables are useful for organizing and presenting data in a structured format.

```xml
<table>
    <thead>
        <tr>
            <th>Header 1</th>
            <th>Header 2</th>
        </tr>
    </thead>
    <tbody>
        <tr>
            <td>Row 1, Cell 1</td>
            <td>Row 1, Cell 2</td>
        </tr>
        <tr>
            <td>Row 2, Cell 1</td>
            <td>Row 2, Cell 2</td>
        </tr>
    </tbody>
</table>
```

---

## Link Tags

### &lt;a&gt; Tag

This tag creates hyperlinks in HTML.

```xml
 <a href="https://www.example.com">Visit Example.com</a>
```

### &lt;style&gt; Tag

This tag is used to embed CSS (Cascading Style Sheets) code directly within an HTML document.

```xml
<style>
    body {
        background-color: #f4f4f4;
        font-family: Arial, sans-serif;
    }
</style>
```

### &lt;link&gt; Tag

This tag is typically used in the `<head>` section of an HTML document to link external resources, such as CSS files.

```xml
  <link rel="stylesheet" type="text/css" href="styles.css">
```

---

## Form Tags

This tag in HTML is used to create an HTML form that allows users to input data and submit it to a server for processing. Forms are essential for user interaction on websites, such as login forms, registration forms, search forms, and more.

```xml
<form action="/submit" method="post">
    <label for="username">Username:</label>
    <input type="text" id="username" name="username">

    <label for="password">Password:</label>
    <input type="password" id="password" name="password">

    <input type="submit" value="Submit">
</form>
```

---

## Form Elements

HTML provides various form elements that allow users to input data and interact with web pages.

### Text Input

```xml
<input type="text" id="username" name="username" required>
```

### Password Input

```xml
<input type="password" id="password" name="password" required>
```

### Textarea

```xml
<textarea id="message" name="message" rows="4" cols="50" required></textarea>
```

### File Input

```xml
<input type="file" id="fileInput" name="fileInput">
```

### Number Input

```xml
<input type="number" id="quantity" name="quantity" min="1" max="10">
```

### Date Input

```xml
<input type="date" id="birthday" name="birthday">
```

### Email Input

```xml
<input type="email" id="email" name="email" required>
```

### Radio Buttons

```xml
<input type="radio" id="male" name="gender" value="male">
<label for="male">Male</label>

<input type="radio" id="female" name="gender" value="female">
<label for="female">Female</label>
```

### Checkboxes

```xml
<input type="checkbox" id="subscribe" name="subscribe" value="yes">
<label for="subscribe">Subscribe to newsletter</label>
```

### Select Dropdown

```xml
<label for="country">Country:</label>
<select id="country" name="country" required>
    <option value="usa">United States</option>
    <option value="canada">Canada</option>
    <option value="uk">United Kingdom</option>
</select>
```

### Submit Button

```xml
<input type="submit" value="Submit">
```

### Reset Button

```xml
<input type="reset" value="Reset">
```

---

## Embed Tag

This tag in HTML is used to embed an inline frame, allowing you to display another HTML document within the current document. It is commonly used to embed external content such as videos, maps, or other webpages.

### &lt;iframe&gt; Tag

```xml
<iframe src="https://www.example.com" width="600" height="400" title="Embedded Content"></iframe>
```

---

## Comment

Comments allow you to leave notes in your code, which are ignored by browsers.

```xml
<!-- This is a comment. -->
```


---

## Find Me on:

* **GitHub** - [github.com/Neyywaar](https://github.com/Neyywaar)
    
* **Twitter** - [twitter.com/neyywaar](https://twitter.com/neyywaar)