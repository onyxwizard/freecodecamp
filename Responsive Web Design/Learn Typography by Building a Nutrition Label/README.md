# 🥪 Learn Typography by Building a Nutrition Label

In this project, I built a clean and visually appealing nutrition label using only HTML and CSS. This helped me understand how to style text effectively using **typography**, including font families, weights, sizes, spacing, and layout alignment.


## 🚀 Live Preview  
👉 [**CodePen**](https://codepen.io/onyxwizard/pen/zxGJZOy)



## 📌 Project Summary

This is my solution to the **freeCodeCamp "Learn Typography by Building a Nutrition Label"** challenge.

I created a structured and styled nutrition facts table from scratch using semantic HTML and custom CSS — focusing on **typographic hierarchy**, **readability**, and **visual balance**.



## 🧠 What I Learned

### ✅ Using Semantic HTML Structure
- Used `<header>`, `<div>`, and `<p>` elements to structure the nutrition label.
- Grouped related content inside `<div class="daily-value">` for clarity and styling control.

```html
<header>
  <h1>Nutrition Facts</h1>
  <p>8 servings per container</p>
</header>
```



### 🖋 Font Styling & Typography
- Practiced using `font-family`, `font-weight`, `font-size`, and `line-height`.
- Used bold and regular weights to create visual hierarchy.

```css
h1 {
  font-weight: 800;
  font-size: 1.3em;
}
```


### 🔤 Text Alignment and Spacing
- Aligned text with `text-align: right` for serving info.
- Controlled spacing between lines using `margin` and `padding`.

```css
p {
  margin: 0;
  padding: 0;
}
```



### 🎨 Color and Contrast
- Used `color` to apply different shades of black and gray for better readability.
- Styled percentage values in bold and added separators using borders.

```css
.bold {
  font-weight: 700;
}

.small-text {
  font-size: 0.85em;
}
```



### 🧱 Divider Lines for Visual Hierarchy
- Created divider lines using `border-bottom` to separate sections.

```css
.divider {
  border-bottom: 1px solid #888989;
  margin: 2px 0;
}
```


### 🧮 Percentage Layouts
- Grouped nutritional facts and percentages together using nested `<span>` elements for alignment.

```html
<p><span><span class="bold">Cholesterol</span> 0mg</span><span class="bold">0%</span></p>
```



### 🧼 Clean Code Organization
- Used consistent indentation and meaningful class names like `.bold`, `.small-text`, and `.divider`.
- Made sure the HTML was readable and the CSS easy to maintain or extend.


## 🛠 Technologies Used
- **HTML5** – For structure and layout  
- **CSS3** – For typography, layout, and styling  


