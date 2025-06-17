# 📝 Learn HTML Forms by Building a Registration Form

In this project, I built a clean and accessible registration form using only **HTML and basic CSS**, following the FreeCodeCamp curriculum. This helped me understand how to structure forms, handle user input, and improve accessibility.

## 🚀 Live Preview  
👉 [**CodePen**](https://codepen.io/onyxwizard/pen/OPVwoxz)



## 🧠 What I Learned (with Code Snippets)

### 1. 📄 Creating the `<form>` Structure
- Used the `<form>` element to wrap all input fields.
- Set `action="/register"` as a placeholder for where the form data would go when submitted.

```html
<form action="/register">
  <!-- All form inputs here -->
</form>
```



### 2. 🧱 Using `<fieldset>` and `<legend>`
- Grouped related inputs using `<fieldset>`.
- Added `<legend>` to describe the purpose of each group.

```html
<fieldset>
  <legend>Personal Information</legend>
  <!-- Input fields here -->
</fieldset>
```



### 3. ✏️ Text Inputs: Name, Email, Password
- Created standard text inputs for name, email, and password.
- Used `required` to ensure fields are filled before submission.

```html
<label for="first-name">First Name:
  <input id="first-name" type="text" required />
</label>

<label for="email">Email:
  <input id="email" type="email" required />
</label>

<label for="new-password">Password:
  <input id="new-password" type="password" pattern="[a-z0-5]{8,}" required />
</label>
```



### 4. 🔘 Radio Buttons for Account Type
- Used `<input type="radio">` for selecting one option from many.
- Grouped options under the same `name` attribute so only one can be selected at a time.

```html
<label><input type="radio" name="account-type" /> Personal Account</label>
<label><input type="radio" name="account-type" /> Business Account</label>
```



### 5. ✅ Checkbox for Accepting Terms
- Used `<input type="checkbox">` for accepting terms and conditions.
- Also added `required` to make it mandatory.

```html
<label><input type="checkbox" required /> I accept the terms and conditions.</label>
```



### 6. 🏷 Proper Use of `<label>` with `for/id`
- Linked each label to its corresponding input using `for` and `id`.

```html
<label for="last-name">Last Name:
  <input id="last-name" type="text" />
</label>
```



### 7. 📤 Submit Button
- Created a submit button using `<input type="submit">`.

```html
<input type="submit" value="Create Account" />
```


### 8. 🎨 Basic CSS Styling
- Centered the form using Flexbox.
- Styled layout, fonts, spacing, and background.

```css
body {
  font-family: 'Trebuchet MS', sans-serif;
  background: #f2f2f2;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
}
```

```css
form {
  background: white;
  padding: 30px;
  max-width: 400px;
  width: 100%;
  box-shadow: 0 0 10px rgba(0,0,0,0.1);
}
```



## 🛠 Technologies Used
- **HTML5** – For semantic structure and form controls  
- **CSS3** – For layout and styling  
