# LIST.TABLE-FORMS-CH-4
# 📋 Chapter 4: Lists, Tables & Forms

<p align="center">
  <b>Learn how to present information with lists and tables, collect user input with forms, and embed videos or webpages in HTML.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML-Lists%20%26%20Forms-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML Lists and Forms">
  <img src="https://img.shields.io/badge/Chapter-04-5B5FC7?style=for-the-badge" alt="Chapter 4">
  <img src="https://img.shields.io/badge/Level-Beginner--Friendly-2EA44F?style=for-the-badge" alt="Beginner Friendly">
</p>

<p align="center">
  <a href="#-lists">Lists</a> •
  <a href="#-tables">Tables</a> •
  <a href="#-html-forms">Forms</a> •
  <a href="#-embedding-videos">Videos</a> •
  <a href="#-iframe-tag">Iframe</a>
</p>

---

## ✨ Overview

This chapter covers HTML elements for displaying grouped information, creating tables, collecting user input, and embedding external content.

## 🎯 Topics Covered

- Ordered and unordered lists
- Tables, captions, table headings, table data, and `colspan`
- HTML forms and form elements
- Form attributes
- `class` and `id` attributes
- Checkboxes and drop-down lists
- Embedding videos
- The `<iframe>` tag

## 📌 Lists

Lists are used to display related items. HTML provides two main types of lists.

| List type | Tag | Use |
| --- | --- | --- |
| Unordered list | `<ul>` | Displays items with bullet points when order is not important. |
| Ordered list | `<ol>` | Displays numbered items when order is important. |

### Unordered List

```html
<ul>
  <li>Home</li>
  <li>About</li>
  <li>Contact</li>
</ul>
```

### Ordered List

```html
<ol>
  <li>Phone</li>
  <li>PC</li>
  <li>Laptop</li>
</ol>
```

`<li>` is used for every list item inside either an ordered or unordered list.

## 📊 Tables

The `<table>` tag is used to display information in rows and columns.

| Tag | Purpose |
| --- | --- |
| `<table>` | Creates the table. |
| `<caption>` | Adds a title to the table. |
| `<thead>` | Wraps the heading part of a table. |
| `<tbody>` | Wraps the main data part of a table. |
| `<tr>` | Creates a table row. |
| `<th>` | Creates a table header cell. |
| `<td>` | Creates a table data cell. |

### Table Example

```html
<table>
  <caption>Students Report</caption>

  <thead>
    <tr>
      <th>Name</th>
      <th>Grade</th>
    </tr>
  </thead>

  <tbody>
    <tr>
      <td>Tanmay</td>
      <td>A+</td>
    </tr>
    <tr>
      <td>John</td>
      <td>D</td>
    </tr>
  </tbody>
</table>
```

## ↔️ Colspan Attribute

The `colspan` attribute makes a table cell span across multiple columns.

```html
<th colspan="3">Tanmay</th>
```

The example above creates one table header cell that covers three columns.

## 📝 HTML Forms

The `<form>` tag creates a form that collects input from users.

```html
<form>
  <!-- Form elements go here -->
</form>
```

### Common Form Elements

| Element | Use |
| --- | --- |
| `<input>` | Takes user input. It can use types such as `text`, `checkbox`, `radio`, `button`, `submit`, `file`, and `password`. |
| `<textarea>` | Creates a multi-line text input area. |
| `<select>` | Creates a drop-down list. |
| `<option>` | Adds a choice inside a drop-down list. |

## ⚙️ Form Attributes

Form elements can use attributes to control their behaviour.

| Attribute | Purpose |
| --- | --- |
| `action` | Specifies where form data is sent for processing. |
| `method` | Specifies the submission method, such as `GET` or `POST`. |
| `name` | Gives a form element a name. |
| `placeholder` | Shows a hint inside an empty input field. |
| `value` | Sets the initial or submitted value of an element. |
| `required` | Makes an input compulsory before submitting the form. |
| `disabled` | Disables an element so the user cannot interact with it. |
| `readonly` | Lets users view, but not edit, an input value. |
| `maxlength` | Sets the maximum number of characters allowed. |
| `size` | Sets the visible width of an input in characters. |
| `multiple` | Allows multiple selections in a file input or select element. |
| `accept` | Specifies accepted file types for a file input. |
| `autofocus` | Focuses on an element when the page loads. |
| `pattern` | Sets a pattern that input must match for validation. |
| `title` | Shows extra information when the user hovers over an element. |
| `alt` | Provides alternative text for an image input. |

### Form Example

```html
<form action="/submit" method="post">
  <input
    type="text"
    name="username"
    placeholder="Enter your name"
    required
  >

  <input type="password" name="password" placeholder="Enter your password">

  <button type="submit">Submit</button>
</form>
```

## 🆔 Class and ID Attributes

The `class` and `id` attributes help identify HTML elements for styling and scripting.

```html
<div id="id1" class="group1"></div>

<div id="id2" class="group1"></div>
```

- An `id` identifies one specific element.
- A `class` can be shared by multiple elements.

## ☑️ Checkbox Input

Checkboxes allow a user to select one or more choices.

```html
<label for="id1">
  <input type="checkbox" value="class X" name="class" id="id1">
  Class X
</label>

<label for="id2">
  <input type="checkbox" value="class XI" name="class" id="id2">
  Class XI
</label>
```

When a checkbox is selected, its value is submitted with the form data.

## 🔽 Select Drop-Down List

The `<select>` tag creates a drop-down list. Each `<option>` tag represents one choice.

```html
<select name="options" id="options">
  <option value="option1">Option 1</option>
  <option value="option2">Option 2</option>
</select>
```

## 🎥 Embedding Videos

The `<video>` tag is used to embed a video in a webpage.

```html
<video src="tanmay.mp4">Error</video>
```

### Video Attributes

| Attribute | Purpose |
| --- | --- |
| `src` | Specifies the video file location. |
| `width` | Sets the width of the video player. |
| `controls` | Shows controls such as play, pause, and volume. |
| `autoplay` | Starts the video automatically when the page loads. |
| `loop` | Restarts the video after it ends. |
| `preload` | Sets whether the video should be loaded in advance. |

### Video Example

```html
<video width="640" controls autoplay loop>
  <source src="harry.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```

## 🪟 Iframe Tag

The `<iframe>` tag embeds another HTML document or webpage inside the current webpage.

```html
<iframe
  src="https://www.wikipedia.org"
  width="600"
  height="400"
></iframe>
```

## ✅ Important Points

- Use `<ul>` when list order does not matter and `<ol>` when it does.
- Use `<th>` for table headings and `<td>` for table data.
- Use `colspan` when a table cell should cover multiple columns.
- Forms collect user input using elements such as `<input>`, `<textarea>`, and `<select>`.
- Use `label` text with form controls so users know what each choice means.
- An `id` should be unique, while a `class` can be reused.
- Use `<video>` to embed videos and `<iframe>` to embed another webpage.
- You do not need to memorise every tag immediately—practice will make them familiar.

## 🚀 How to Run the Program

1. Create or open an `index.html` file.
2. Add HTML boilerplate to the file.
3. Place the examples inside the `<body>` tag.
4. Save the file.
5. Open it in a browser and test the output.

---

<p align="center">
  Made with ❤️ while creating this for beginners to learn HTML. <br>
</p>


