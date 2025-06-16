# 🌈 Learn CSS Colors by Building a Set of Colored Markers

In this project, I created a set of three colorful markers using HTML and CSS. This helped me understand how to apply and manipulate colors effectively in web design.


## 🚀 Live Preview  
👉 [**CodePen**](https://codepen.io/onyxwizard/pen/RNPBgda)


## 📚 What I Learned

### 1. 🎨 Named Colors
**What it means:**  
Using simple English names like `red`, `blue`, or `green` to define colors in CSS.

**Why it's useful:**  
Easy to remember and great for basic color applications.

**Sample Snippet:**
```css
.marker:nth-child(1) {
  background-color: red;
}
```



### 2. 🔤 Hexadecimal (HEX) Color Codes
**What it means:**  
A six-digit code starting with `#` that represents combinations of red, green, and blue.

**Why it's useful:**  
Offers precise control over color shades and is widely used in web development.

**Sample Snippet:**
```css
.marker:nth-child(2) {
  background-color: #e32528; /* A specific shade of red */
}
```



### 3. 🎨 RGB Color Values
**What it means:**  
Colors defined using `rgb()` function with values between 0–255 for Red, Green, and Blue.

**Why it's useful:**  
Allows you to create custom colors dynamically and adjust transparency with `rgba()`.

**Sample Snippet:**
```css
.marker:nth-child(3) {
  background-color: rgb(128, 0, 0); /* Dark red */
}
```



### 4. 🖌 Background Styling
**What it means:**  
Applying color to the background of elements using the `background-color` property.

**Why it's useful:**  
Essential for designing buttons, cards, banners, and other UI components.

**Sample Snippet:**
```css
.marker {
  width: 200px;
  height: 25px;
  background-color: yellow;
}
```



### 5. 🧱 Class-Based Styling
**What it means:**  
Using classes to apply consistent styles across multiple elements.

**Why it's useful:**  
Promotes reusability and makes your CSS more organized and maintainable.

**Sample Snippet:**
```html
<div class="marker"></div>
<div class="marker"></div>
<div class="marker"></div>
```



### 6. 📐 Flexbox for Layout
**What it means:**  
Used `display: flex` to align and center the marker elements on the page.

**Why it's useful:**  
Flexbox is a powerful layout tool for creating responsive and dynamic designs.

**Sample Snippet:**
```css
.container {
  display: flex;
  justify-content: space-around;
  align-items: center;
  height: 100vh;
}
```



### 7. 🧼 Clean & Organized Code
**What it means:**  
Wrote well-structured and commented CSS to improve readability and future edits.

**Why it's useful:**  
Makes it easier to debug and update your code later on.

**Sample Snippet:**
```css
/* Style for all markers */
.marker {
  width: 200px;
  height: 25px;
}

/* First marker - named color */
.marker:nth-child(1) {
  background-color: red;
}
```



## 🛠 Technologies Used
- **HTML5**
- **CSS3**
