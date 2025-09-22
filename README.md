# JavaScript Basics: DOM and Form Validation

This short guide is for absolute beginners. Open `form-dom.html` in your browser and try the examples.

## 1) DOM (Document Object Model)

- The DOM is the web page as a tree of elements.
- We can select elements and change their text, HTML, styles, and attributes.

Common actions:
- Select by id: `document.getElementById('box')`
- Select by CSS: `document.querySelector('.item')`
- Change text: `element.textContent = 'Hello'`
- Change HTML: `element.innerHTML = '<b>Hi</b>'`
- Change style: `element.style.color = 'red'`
- Listen to events: `element.addEventListener('click', handler)`

Exercises:
1. Change the text of a paragraph when a button is clicked.
2. Toggle a CSS class on a box when a button is clicked.
3. Create a list from an array (append `li` elements inside a `ul`).

## 2) Form Validation (Beginner)

Goal: Check user input before submitting.

Basic checks:
- Required field (not empty)
- Email looks like an email (very simple pattern)
- Password length (e.g., 6+ characters)

Steps:
1. Listen to the form `submit` event.
2. Stop default with `event.preventDefault()`.
3. Read values, check them, show messages next to fields.
4. If all good, show success.

Exercises:
1. Make name required.
2. Email must contain `@` and `.`.
3. Password must be at least 6 characters.
4. Confirm password must match password.


## 3) React Mini-App: Color Buttons

Goal: Build a tiny React app with four buttons: Red, Blue, Green, Yellow. When you click a button, show a message with the selected color.

How to run:
- Open `react-color-buttons.html` in your browser (uses React via CDN, no install needed).

What to learn:
- useState hook to store selected color
- Handling button clicks (onClick)
- Rendering text based on state

Try this:
- Change the message style color to match the selected color
- Add a Clear button that resets the selection
- Disable the clicked button for 1 second (optional)


