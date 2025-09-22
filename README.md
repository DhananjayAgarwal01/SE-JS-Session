# JavaScript Session – Slides and Demos

This repo is a beginner-friendly set of slides and small HTML demos for teaching JavaScript, DOM, and a quick glimpse of React. No installation is required: open files directly in your browser.

## Contents

- `ppt.html` – Interactive presentation (keyboard and button navigation)
- Demos (open in browser):
  - `basics.html` – variables, types, simple math
  - `arrays-loops.html` – arrays and for-loops, average
  - `dom-basic.html` – get element by id, change text on click
  - `visual-bar.html` – simple bar visualization by width
  - `json-basics.html` – stringify/parse examples
  - `tiny-calculator.html` – add/subtract/multiply/divide
  - `greeting-button.html` – input + greeting message
  - `form-dom.html` – DOM basics + beginner form validation

## How to Run

1) Double‑click any `.html` file to open it in your browser.
2) For the slides, open `ppt.html`.

## Form Validation (Beginner Cheatsheet)

Checklist:
- Required fields are not empty
- Email includes `@` and `.` (basic check)
- Password length ≥ 6; confirm matches

Steps:
1. Listen to `form` submit
2. `event.preventDefault()`
3. Read values, validate, show messages near fields
4. If valid, show success

See `form-dom.html` for a working example.

## Next React Session: Glimpse

We’ll build tiny apps using React:
- Components (small UI pieces), Props (inputs), State (`useState`)
- Events (`onClick`, `onChange`), JSX rules (one parent, `{}` for values)
- Simple effect with `useEffect` demo (time permitting)

Try ahead (optional):
- Online: CodeSandbox or StackBlitz
- Local (Vite):
  - `npm create vite@latest my-react-app -- --template react`
  - `cd my-react-app && npm install && npm run dev`

## Troubleshooting

- If a demo shows nothing, open DevTools Console (F12) and check for errors.
- If code text overflows on a phone, convert to desktop site



