# SEO.HTML-CH-5
We will focus only on HTML standpoint of SEO. We will not be looking into keyword building and content optimization aspect of SEO.

🔎 Chapter 5: SEO with HTML

<p align="center">
  <b>Learn the HTML techniques that help search engines understand a webpage and improve the user experience.</b>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/HTML-SEO-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML SEO">
  <img src="https://img.shields.io/badge/Chapter-05-5B5FC7?style=for-the-badge" alt="Chapter 5">
  <img src="https://img.shields.io/badge/Focus-On--Page%20SEO-2EA44F?style=for-the-badge" alt="On-page SEO">
</p>

<p align="center">
  <a href="#-what-is-seo">What is SEO?</a> •
  <a href="#-types-of-seo">Types</a> •
  <a href="#-html-seo-techniques">Techniques</a> •
  <a href="#-html-example">Example</a>
</p>

---

## ✨ What Is SEO?

**SEO** stands for **Search Engine Optimization**. It is the process of making a webpage easier for search engines to understand and present in search results.

This chapter focuses only on the **HTML side of SEO**. It does not cover keyword research, link building, or content optimization.

## 🧭 Types of SEO

| Type | Meaning |
| --- | --- |
| **On-page SEO** | Improvements made directly on a webpage, including HTML structure and metadata. HTML developers can work on this. |
| **Off-page SEO** | Improvements made outside the webpage. |

## 🛠️ HTML SEO Techniques

HTML developers can support SEO with the following techniques.

### 1. Title Tag

Use a clear and descriptive `<title>` tag that accurately describes the page.

```html
<title>Example Page - SEO Best Practices</title>
```

The title is usually shown in the browser tab and can appear as the page title in search results.

### 2. Meta Description

Use a meta description to provide a short summary of the page content.

```html
<meta
  name="description"
  content="This is an example page demonstrating SEO best practices in HTML."
>
```

### 3. URL Slug

Use clean and readable URLs that describe the page content.

```text
Good: /html-seo-best-practices
```

A readable URL helps people and search engines understand what the page is about.

### 4. Meta Author Tag

You can include the author's name in a meta tag.

```html
<meta name="author" content="Tanmay">
```

### 5. Favicon

A favicon is the small icon shown in a browser tab. It helps users recognise a website.

```html
<link rel="icon" href="favicon.ico" type="image/x-icon">
```

### 6. Image Optimization

Optimise images by compressing them to reduce page-load time and adding descriptive `alt` text.

```html
<img src="html-logo.png" alt="HTML5 logo">
```

The `alt` attribute helps explain the image when it cannot be displayed.

### 7. Optimise Resources

Remove unused HTML, CSS, and JavaScript files. Minifying and compressing resources can reduce page-load time.

### 8. Semantic HTML

Use meaningful HTML tags to organise page content logically.

```html
<header>
  <nav>
    <!-- Navigation links -->
  </nav>
</header>

<article>
  <!-- Main article content -->
</article>

<footer>
  <!-- Footer content -->
</footer>
```

Semantic HTML can improve SEO indirectly by making the webpage easier for search engines and users to understand.

## 🧱 HTML Example

This example combines the essential HTML SEO tags from this chapter.

```html
<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <meta name="viewport" content="width=device-width, initial-scale=1.0">

  <title>Example Page - SEO Best Practices</title>
  <meta
    name="description"
    content="This is an example page demonstrating SEO best practices in HTML."
  >
  <meta name="author" content="Tanmay">

  <link rel="icon" href="favicon.ico" type="image/x-icon">
</head>

<body>
  <header>
    <h1>SEO Best Practices</h1>
  </header>

  <main>
    <article>
      <p>HTML can help search engines understand page content.</p>
    </article>
  </main>

  <footer>
    <p>Created for HTML SEO learning.</p>
  </footer>
</body>
</html>
```

## ✅ Important Points

- Add one clear and descriptive `<title>` tag to each page.
- Write a concise meta description that summarises the page.
- Keep URLs clean and readable.
- Use a favicon to support recognition and usability.
- Compress images and write useful `alt` text.
- Remove unused resources to help the page load faster.
- Use semantic tags such as `<header>`, `<nav>`, `<article>`, and `<footer>`.
- Focus on helping users and search engines understand the page structure.

## 🚀 How to Use These SEO Tags

1. Open your `index.html` file.
2. Add the title, meta description, author, and favicon tags inside `<head>`.
3. Use semantic HTML elements inside `<body>`.
4. Add descriptive `alt` text to your images.
5. Save the file and open it in a browser.

---

<p align="center">
  Made with ❤️ while creating some concept for beginner.
</p>

