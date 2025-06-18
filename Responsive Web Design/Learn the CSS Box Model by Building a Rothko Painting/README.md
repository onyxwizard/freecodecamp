# 🎨 Learn the CSS Box Model by Building a Rothko Painting

In this project, I recreated a simplified version of a Mark Rothko painting using only HTML and CSS. This helped me understand how the **CSS Box Model** works — including `width`, `height`, `margin`, `padding`, and `background-color`.



## 🚀 Live Preview  
👉 [**CodePen**](https://codepen.io/onyxwizard/pen/raVZaVo)

## 🧠 What I Learned

### ✅ Understanding the CSS Box Model
- Gained hands-on experience with how every element is structured in CSS:
  - **Content**
  - **Padding**
  - **Border**
  - **Margin**

### 📐 Controlling Dimensions
- Used `width` and `height` to define the size of each colored rectangle.
- Practiced sizing elements without relying on images or external assets.

```css
.rect1 {
  width: 300px;
  height: 100px;
}
```



### 🖌 Styling Backgrounds
- Applied solid background colors using `background-color`.
- Experimented with color combinations to mimic Rothko’s abstract style.

```css
.rect1 {
  background-color: #FF0000;
}
```



### 🧱 Using Divs as Shapes
- Created multiple rectangles using `<div>` elements.
- Positioned them using `margin` and `display: block`.

```html
<div class="rect1"></div>
<div class="rect2"></div>
<div class="rect3"></div>
```



### 📏 Margin & Spacing
- Used `margin: 0 auto;` to center rectangles horizontally.
- Adjusted spacing between rectangles using `margin-top` and `margin-bottom`.

```css
.rect1 {
  margin: 0 auto;
  margin-top: 50px;
}
```



### 🎨 Centering Content
- Centered the entire canvas inside a container using Flexbox.

```css
.container {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  min-height: 100vh;
}
```


### 🧼 Clean Code Organization
- Grouped related styles together.
- Named classes like `.rect1`, `.rect2`, etc., for clarity.
- Kept comments minimal but meaningful.


## 🛠 Technologies Used
- **HTML5** – For structure and layout  
- **CSS3** – For styling and positioning  
