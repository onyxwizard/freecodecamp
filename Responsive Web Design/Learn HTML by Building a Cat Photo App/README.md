# 📚 **Knowledge Base: Learn HTML by Building a Cat Photo App**

Welcome to your **HTML Knowledge Base**! 🎉 This guide captures everything you learned while building the Cat Photo App from freeCodeCamp. Use it for review or share it with others!

🚀 Live Demo [CodePen](https://codepen.io/onyxwizard/pen/ZYEgKJy)

[![Cat Photo App Preview](https://cdn.freecodecamp.org/curriculum/cat-photo-app/running-cats.jpg)](https://codepen.io/onyxwizard/pen/ZYEgKJy)

A playful cat to inspire your coding journey! 🐱💻  

## 📑 **Table of Contents**
1. [Introduction to HTML](#🌟-introduction-to-html)  
2. [Headings and Paragraphs](#📜-headings-and-paragraphs)  
3. [Semantic Elements](#🔍-semantic-elements)  
4. [Images and Links](#🖼️🔗-images-and-links)  
5. [Lists and Forms](#📋📝-lists-and-forms)  
6. [Accessibility](#♿-accessibility)  
7. [Meta and Setup](#🌐-meta-and-page-setup)  



## HTML Fundamentals 🌟

1.  **Elements & Tags**
    
    *   HTML uses **opening tags** (`<tag>`) and **closing tags** (`</tag>`) to define elements.
    *   Text/content lives between these tags.
    
2.  **Headings** 📜
    
    *   Headings (`h1` to `h6`) indicate content hierarchy.
        *   `h1` = Highest importance (use **only one per page** ).
        *   Lower numbers = Higher priority (e.g., `h2` < `h1`).
    
3.  **Paragraphs** ✍️
    
    *   The `<p>` tag creates text paragraphs.
    *   Use **only one `<h1>` per page** and nest lower headings under higher ones.  
    * The `<p>` tag creates paragraphs:  

    ```html
    <p>This is a paragraph.</p>
    ```
    
4.  **Comments** 🤫
    
    *   Use `<!-- Comment -->` to add notes (ignored by browsers).

 

```html
<h1>Main Title</h1>
<h2>Subheading</h2>
<h3>Section Title</h3>
```


### 📜 **Headings and Paragraphs**
- **Comments** start with `<!--` and end with `-->` (ignored by browsers):  
```html
<!-- This is a comment -->
```

- **Indentation**: Nested elements are indented with 2 spaces for readability:  
```html
<main>
  <h1>Title</h1>
</main>
```


## 🔍 **Semantic Elements**
1.  **Purpose**
    
    *   Semantic tags (e.g., `<main>`, `<section>`, `<footer>`) improve **SEO** and **accessibility** by clarifying content structure.
    
2.  **Key Tags**
    
    *   `<main>`: Unique page content (not repeated elsewhere).
    *   `<section>`: Groups related content (e.g., blog sections).
    *   `<footer>`: Contains metadata (copyright, links).
    
3.  **Nesting & Indentation**
    
    *   Indent nested elements with **2 spaces** for readability.
  
```html
<main>
  <section>
    <h2>Section Title</h2>
    <p>Content here...</p>
  </section>
</main>
<footer>
  <p>© 2023 Cat Photo App</p>
</footer>
```
- **`<figure>` and `<figcaption>`**:  
```html
<figure>
  <img src="cat.jpg" alt="A cat">
  <figcaption>A cute cat!</figcaption>
</figure>
```


## 🖼️🔗 **Images and Links**
1.  **Images**
    
    *   Use `<img>` (a **void element** ) with:
        *   `src`: Image URL.
        *   `alt`: Text for accessibility/screen readers.
        ```html
        <img src="cat.jpg" alt="A cat">
        ```
    
2.  **Links**
    
    *   Use `<a>` with `href` for URLs.
    *   Add `target="_blank"` to open links in a new tab.
    *   Wrap images/text in `<a>` to turn them into links.

    - **Links** use `<a>` with `href`:  
    ```html
    <a href="https://example.com">Visit Example</a>
    ```
    - Open links in a **new tab** with `target="_blank"`:  
    ```html
    <a href="https://example.com" target="_blank">New Tab</a>
    ```


## 📋📝 **Lists and Forms**

1.  **Lists**
    *   **Unordered** (`<ul>`): Bullet points.
    *   **Ordered** (`<ol>`): Numbered lists.
    
2.  **Forms**
    
    *   Use `<form>` with `action` to specify submission URLs.
    *   **Input Types** :
        
        *   Text fields (`<input type="text">`).
        *   Radio buttons (mutually exclusive selection).
        *   Checkboxes (multiple selections).
        
    *   **Attributes** :
        
        *   `name`: Identifies form data.
        *   `placeholder`: Hint text.
        *   `required`: Prevents empty submissions.
        
    *   **Labels** : Use `<label for="id">` to associate text with inputs.
    
3.  **Fieldset & Legend**
    
    *   Group related form elements with `<fieldset>` and describe them with `<legend>`.

- **Unordered List** (`<ul>`):  
```html
<ul>
  <li>Milk</li>
  <li>Cheese</li>
</ul>
```
- **Ordered List** (`<ol>`):  
```html
<ol>
  <li>Step 1</li>
  <li>Step 2</li>
</ol>
```
- **Forms** use `<form>` and `action`:  
```html
<form action="/submit-url">
  <input type="text" name="email" placeholder="Enter email">
  <button type="submit">Submit</button>
</form>
```
- **Radio Buttons** (grouped with `name`):  
```html
<input type="radio" name="meal" value="breakfast"> Breakfast
<input type="radio" name="meal" value="lunch"> Lunch
```

## ♿ **Accessibility**

*   **Alt Text** : Mandatory for images to aid screen readers.
    - **Alt text**: Always add `alt` to images:  
    ```html
    <img src="cat.jpg" alt="A playful cat">
    ```
*   **Labels** : Link labels to inputs with `for` and `id` for usability.
    - **Labels**: Use `for` to associate labels with inputs:  
    ```html
    <label for="email">Email:</label>
    <input id="email" type="text">
    ```
*   **Checked/Selected** : Use `checked` to pre-select radio/checkboxes.
    - **Checkboxes**: Allow multiple selections:  
    ```html
    <input type="checkbox" name="subscribe"> Subscribe
    ```


## 🌐 **Meta and Page Setup**
1.  **Document Structure**
    
    *   `<!DOCTYPE html>`: Declares HTML5.
    *   `<html>`: Root element (use `lang="en"` for language).
    *   `<head>`: Contains metadata:
        *   `<title>`: Browser tab name.
        *   `<meta charset="UTF-8">`: Character encoding.
    
2.  **Body**
    
    *   All visible content lives in `<body>`.

- **`<head>` metadata**:  
```html
<head>
  <meta charset="UTF-8">
  <title>Cat Photo App</title>
</head>
```
- **`<!DOCTYPE html>`**: Declares the document as HTML5:  
```html
<!DOCTYPE html>
<html lang="en">
  <!-- Page content -->
</html>
```

### Key Takeaways 🚀

*   **Hierarchy** : Structure content with headings and semantic tags.
*   **Accessibility** : Prioritize alt text, labels, and semantic HTML.
*   **Forms** : Use `name`, `placeholder`, and validation attributes.
*   **Best Practices** : Indent code, use comments, and follow SEO principles.


**Final Notes** 🚀  
This knowledge base covers HTML fundamentals. Keep experimenting to master web development! 💻

---