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

## Next React Session: Glimpse

What you'll see next time (simple and hands-on):
- Components: small reusable UI pieces
- Props: inputs to components
- State with `useState`: data that changes and re-renders the UI
- Events: `onClick`, `onChange`
- JSX rules: one parent element, `{}` to show values
- Side effects preview: `useEffect` (very basic example)

Mini-demo ideas:
- Color buttons app (click to show selected color)
- Counter with +1 button
- Greeting component that shows the typed name

How you'll run it:
- Option A: Online playground (CodeSandbox/StackBlitz)
- Option B: Local quick start (Vite)
  - `npm create vite@latest my-react-app -- --template react`
  - `cd my-react-app && npm install && npm run dev`


