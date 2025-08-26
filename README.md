# Frontend Mentor - FAQ Accordion Solution🔗
This is my solution to the [FAQ accordion coding challenge](https://) on Frontend Mentor.

## Overview ✨

### The Challenge

The goal was to build a fully functional and responsive FAQ accordion component. The key requirements were to:

- Hide and show the answer for each question when clicked.

- Implement proper keyboard navigation for accessibility.

- Ensure the layout is optimized for both desktop and mobile screen sizes.

- Add hover and focus states for all interactive elements.

### Preview

![Screenshot](./assets/images/preview.jpg) 

## 🛠️ Technologies Used
- **HTML5** - For the semantic structure of the FAQ list.
- **JavaScript (ES6)** - To handle the click events and toggle the visibility of the answers.
- **CSS3** - For all styling and responsive design.
- **Flexbox** - Used for aligning the question text and the plus/minus icon.

## My Process 🛠️
### 1. HTML Structure 📋
I created a semantic HTML structure with:

- A main `<main>` container for the FAQ card.

- A div for each FAQ item, containing the question and answer.

- A `<button>` element for the question, which acts as the interactive element.

- A `p` or `div` for the hidden answer.

### 2. Styling 🎨
- **Mobile-first approach** 📱
- **Typography** Imported and applied custom fonts
- **Layout**  used Flexbox to create the main two-column layout for each question item, ensuring the text and the icon are perfectly aligned. This avoids the problems that come with using float.
- **Background** The double background effect was achieved by applying a solid color to the body and a pattern image using the background-image property, with background-repeat: no-repeat and background-size to position it correctly.
- **Accordion Icon** The + and – signs are created using a pseudo-element (::after) on the button. I used a fixed width and height with border-radius: 50% to ensure they remain perfect circles at all times.

### 3. Interactive Elements with JavaScript ⚡
- I used **document.querySelectorAll()** to select all accordion buttons.
- A **click event listener** was added to each button.
- When a button is clicked, a class (e.g., .active) is toggled on its parent element.
- The content property of the **::after pseudo-element** was toggled to switch between **+** and **–** symbols.

## 📚 What I Learned
- **Flexbox vs. Float:** I solidified my understanding of why Flexbox is a superior solution to float for modern layouts, especially for aligning items and avoiding overflow issues.
- **Perfect Circles:** I learned the importance of setting equal width and height on an element before applying `border-radius: 50%` to guarantee a perfect circle.
- **Pseudo-elements:** I gained more experience using pseudo-elements like `::after` for decorative and functional purposes, such as creating the accordion icons.
- **Basic JavaScript for UI:** I reinforced my ability to write clean, effective JavaScript to handle user interactions and toggle CSS classes.

## 🔗 Links
- **🌐 Live Site URL**: [Add your live site URL here]

### **👥 Solved by M Olaya** 
<a href="https://www.linkedin.com/in/molaya">LinkedIn</a> 