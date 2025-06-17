# 🧑‍💻 Learn HTML Forms by Building a Registration Form

This project helped me learn how to build a fully functional and accessible HTML form. It includes text inputs, password fields, radio buttons, checkboxes, dropdowns, file upload, and a submit button — all styled with basic CSS.

## 🚀 Live Preview  
👉 [**CodePen**](https://codepen.io/onyxwizard/pen/RNPBejY)


## 📌 Project Requirements (from FreeCodeCamp)

- ✅ Create an `h1` element with the text `"Registration Form"`
- ✅ Include a short description in a `p` element
- ✅ Use a `form` with appropriate `method` and `action`
- ✅ Add required fields: first name, last name, email, and password
- ✅ Add optional fields like profile picture, age, referrer dropdown, and bio
- ✅ Include at least two radio buttons grouped together
- ✅ Add at least one checkbox (with required validation)
- ✅ Style the form using basic CSS
- ✅ Ensure accessibility and semantic structure



## 🧠 What I Learned

### 1. ✅ Creating Accessible Form Inputs
Used proper `<label>` elements linked to each input field via the `for/id` relationship for better accessibility.

```html
<label for="first-name">Enter Your First Name:
  <input id="first-name" type="text" required />
</label>
```



### 2. 🔘 Radio Buttons for Single Choice
Grouped options using the same `name` attribute so only one can be selected at a time.

```html
<label for="personal-account">
  <input id="personal-account" type="radio" name="account-type" class="inline" checked />
  Personal
</label>
<label for="business-account">
  <input id="business-account" type="radio" name="account-type" class="inline" />
  Business
</label>
```


### 3. ✅ Checkbox with Validation
Used a required checkbox to ensure users accept terms before submitting.

```html
<label for="terms-and-conditions">
  <input id="terms-and-conditions" type="checkbox" required class="inline" />
  I accept the <a href="#">terms and conditions</a>
</label>
```



### 4. 📄 Dropdown Menu (`<select>`)
Created a dropdown menu with multiple options using `<select>` and `<option>`.

```html
<select id="referrer" name="referrer">
  <option value="">(select one)</option>
  <option value="1">freeCodeCamp News</option>
  <option value="2">freeCodeCamp YouTube Channel</option>
</select>
```



### 5. 📁 File Upload Input
Used `<input type="file">` to allow users to upload a profile picture.

```html
<input id="profile-picture" type="file" name="file" />
```



### 6. 🔢 Number Input with Range
Included a number input with minimum and maximum values.

```html
<input id="age" type="number" min="13" max="120" />
```



### 7. 📝 Textarea for Bio
Used `<textarea>` for multi-line user input.

```html
<textarea id="bio" rows="3" cols="30" placeholder="I like coding on the beach..."></textarea>
```



### 8. 🎨 Basic CSS Styling
Styled the form layout and improved readability using:

- Custom colors and fonts
- Padding, margins, and rounded corners
- Flexbox alignment for inline elements

```css
input[type="submit"] {
  display: block;
  width: 60%;
  margin: 1em auto;
  height: 2em;
  font-size: 1.1rem;
  background-color: #3b3b4f;
  border-color: white;
}
```


## 🛠 Technologies Used
- **HTML5** – For form structure and semantic elements  
- **CSS3** – For layout and styling  

