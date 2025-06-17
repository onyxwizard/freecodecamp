# 📝 Build a Survey Form

In this project, I built a responsive survey form with various input types like text, email, number, radio buttons, checkboxes, dropdowns, and a submit button. This helped me understand how to structure forms, apply HTML5 validation, and create accessible user interfaces.

## 🚀 Live Preview  
👉 [**CodePen**](https://codepen.io/onyxwizard/pen/RNPBejY)



## 🧠 What I Learned (with Code Snippets)

### 1. 🧾 Page Title & Description
- Used an `<h1>` with `id="title"` for the main heading.
- Added a `<p>` with `id="description"` to briefly explain the purpose of the form.

```html
<h1 id="title">Survey Form</h1>
<p id="description">Let us know how we can improve freeCodeCamp.</p>
```



### 2. 📄 Creating the Form
- Created a `<form>` element with `id="survey-form"` as the container for all inputs.

```html
<form id="survey-form">
  <!-- All form fields go here -->
</form>
```



### 3. ✏️ Text Input: Name
- Added a required text input for name with:
  - A label (`id="name-label"`)
  - Placeholder text
  - Required attribute

```html
<label id="name-label">Name
  <input type="text" id="name" placeholder="Enter your name" required />
</label>
```


### 4. 📧 Email Input
- Used `type="email"` for valid email entry.
- Included a label and required field.

```html
<label id="email-label">Email
  <input type="email" id="email" placeholder="Enter your email" required />
</label>
```


### 5. 🔢 Number Input with Validation
- Added `type="number"` with `min` and `max` attributes to restrict input range.
- Included placeholder and label.

```html
<label id="number-label">Age
  <input type="number" id="number" min="10" max="99" placeholder="Age" required />
</label>
```



### 6. 🔘 Radio Buttons for Single Choice
- Grouped multiple `<input type="radio">` elements using the same `name` attribute.
- Each had a `value`, `name`, and associated label.

```html
<label><input type="radio" name="role" value="student" /> Student</label>
<label><input type="radio" name="role" value="developer" /> Developer</label>
```



### 7. ✅ Checkboxes for Multiple Choices
- Used `<input type="checkbox">` for optional selections.
- Each checkbox had a `value` attribute.

```html
<label><input type="checkbox" value="coding" /> Coding</label>
<label><input type="checkbox" value="design" /> Design</label>
```



### 8. 📤 Dropdown Select Menu
- Used `<select>` with `id="dropdown"` and multiple `<option>` choices.

```html
<label>Which option best describes you?
  <select id="dropdown">
    <option value="">(select one)</option>
    <option value="beginner">Beginner</option>
    <option value="intermediate">Intermediate</option>
  </select>
</label>
```


### 9. 📝 Textarea for Comments
- Included a `<textarea>` for additional feedback.

```html
<label>Any comments?
  <textarea rows="4" cols="50" placeholder="Enter your comment here..."></textarea>
</label>
```



### 10. ✅ Submit Button
- Created a submit button inside the form with `id="submit"` and `type="submit"`.

```html
<input type="submit" id="submit" value="Submit" />
```



### 11. 🎨 Basic CSS Styling
- Styled layout, fonts, spacing, and centered the form using Flexbox.

```css
body {
  font-family: 'Arial', sans-serif;
  background: #f4f4f4;
  display: flex;
  justify-content: center;
  padding: 40px;
}
```

```css
form {
  background: white;
  padding: 20px;
  border-radius: 8px;
  width: 100%;
  max-width: 500px;
}
```



## 🛠 Technologies Used
- **HTML5** – For semantic structure and form controls  
- **CSS3** – For layout and styling  