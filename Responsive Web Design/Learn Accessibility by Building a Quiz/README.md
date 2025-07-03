## ✅ Learn Accessibility by Building a Quiz

### 🧠 Project Overview

This project, **"Learn Accessibility by Building a Quiz"**, demonstrates how to build a fully accessible quiz form using **only HTML and CSS**. It emphasizes creating an inclusive user experience through semantic structure and thoughtful styling.

🔗 [**CodePen**](https://codepen.io/onyxwizard/pen/EajemOX)



### 🔧 Features

- Accessible multiple-choice quiz
- Semantic HTML5 elements
- Keyboard navigable interface
- Visually styled focus indicators
- Responsive layout using Flexbox
- No JavaScript used – purely HTML & CSS



### 📚 CSS Concepts and Properties Learned

While building this quiz, I applied and deepened my understanding of the following **CSS properties and concepts**, especially in the context of accessibility and responsive design:

#### 🎨 Layout & Structure

| Property | Use |
|--------|-----|
| `display: flex;` | Created flexible, responsive layouts using Flexbox. |
| `flex-direction` | Controlled the direction of flex items (row/column). |
| `justify-content` | Aligned items along the main axis. |
| `align-items` | Vertically aligned flex items within a container. |
| `gap` | Added consistent spacing between flex/grid items without extra margins. |

#### 🖱️ Focus and Interaction

| Property | Use |
|--------|-----|
| `:focus` | Styled focus states for keyboard users. |
| `outline` | Customized or removed default outlines for better visual clarity (while ensuring accessibility). |
| `outline-offset` | Adjusted space between focused element and its outline. |

#### 🌈 Visual Design and Accessibility

| Property | Use |
|--------|-----|
| `color` | Ensured sufficient contrast between text and background. |
| `background-color` | Chose accessible color combinations. |
| `font-family` | Used readable fonts. |
| `font-size` | Set legible font sizes for all users. |
| `line-height` | Improved readability with proper line spacing. |
| `padding`, `margin` | Provided spacing around elements for better usability. |
| `border` | Styled borders for visual clarity where needed. |
| `box-sizing: border-box;` | Made layout calculations more predictable. |

#### 📱 Responsive Design

| Property | Use |
|--------|-----|
| `@media` queries | Adjusted layout and styles based on screen size. |
| `max-width`, `min-width` | Controlled responsiveness of containers. |
| `width`, `height` | Scaled elements appropriately across devices. |

#### 🧩 Misc. Styling

| Property | Use |
|--------|-----|
| `cursor` | Indicated interactive elements (e.g., buttons). |
| `transition` | Smoothed hover/focus state changes. |
| `opacity` | Highlighted selected answers. |
| `pointer-events` | Controlled clickability of elements when necessary. |
| `text-align` | Centered text and content for better alignment. |



### 📦 Technologies Used

- **HTML5** – For semantic markup and accessible forms
- **CSS3** – For layout, visual feedback, and responsive behavior



### 📁 File Structure

```
/Learn-Accessibility-by-Building-a-Quiz/
│
├── index.html        # Accessible HTML structure
└── style.css         # Styling with accessibility considerations
```



### 🧪 How to Use

1. Open `index.html` in any modern browser.
2. Navigate the quiz using mouse or keyboard.
3. Select one answer per question and click "Submit".
4. The result will be displayed below the form.



### 🛠 Tips for Future Enhancements

If you plan to add interactivity later with JavaScript:
- Keep using accessible ARIA attributes.
- Ensure dynamic updates are announced via `aria-live`.
- Maintain keyboard navigation and focus management.
