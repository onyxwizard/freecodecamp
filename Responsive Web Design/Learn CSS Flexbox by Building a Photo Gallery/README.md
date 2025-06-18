
# 🖼️ Learn CSS Flexbox by Building a Photo Gallery

In this project, I built a responsive photo gallery using only HTML and CSS. This helped me understand how to use **CSS Flexbox** for layout design — including alignment, spacing, and responsiveness.

## 🚀 Live Preview  
👉 [**CodePen**](https://codepen.io/onyxwizard/pen/wBaEggK)

## 🧠 What I Learned

### ✅ Introduction to Flexbox
- Used `display: flex` to turn a container into a Flexbox layout.
- Learned how Flexbox makes it easy to align and space items in one direction.

```css
.flex-container {
  display: flex;
}
```



### 📐 Controlling Layout Direction
- Changed the layout of child elements using `flex-direction`.
- Experimented with `row`, `column`, and wrapping behavior using `flex-wrap`.

```css
.flex-container {
  flex-direction: row;
  flex-wrap: wrap;
}
```


### 🧱 Responsive Image Grid
- Created a responsive image layout using percentage-based widths.
- Ensured images scale nicely across different screen sizes.

```css
.image {
  width: 25%;
  padding: 10px;
  box-sizing: border-box;
}
```

### 🌍 Centering Content
- Centered the entire gallery using Flexbox properties on a parent container.

```css
.gallery {
  display: flex;
  justify-content: center;
  flex-wrap: wrap;
}
```



### 📏 Spacing Between Items
- Used `gap` inside the Flex container to add consistent spacing between images without extra margins.

```css
.flex-container {
  gap: 10px;
}
```



### 📸 Styling Images
- Applied borders, shadows, and object-fit to ensure all images look uniform.

```css
img {
  width: 100%;
  height: auto;
  border-radius: 8px;
  box-shadow: 0 4px 8px rgba(0,0,0,0.1);
}
```



### 🧼 Clean Code Organization
- Used semantic class names like `.gallery`, `.flex-container`, and `.image`.
- Kept styles clean and readable for future edits or enhancements.



## 🛠 Technologies Used
- **HTML5** – For structure and layout  
- **CSS3** – For styling and Flexbox layout  
