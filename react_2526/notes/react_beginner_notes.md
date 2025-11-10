# React Beginner Notes

## 1. What is React?
React is a JavaScript library for building user interfaces, especially single-page applications (SPAs). It focuses on creating fast, interactive UI components.

### Why React?
- Fast updates using Virtual DOM
- Reusable components
- Easy to scale large applications
- Strong community support

---

## 2. How React Works
### DOM vs Virtual DOM
- **DOM (Traditional JS)**: Slow when updating frequently.
- **Virtual DOM (React)**: A lightweight copy of the real DOM. React updates only the changed parts → faster performance.

---

## 3. Setting Up React
### Option 1: CDN (Quick Practice)
```html
<script src="https://unpkg.com/react/umd/react.development.js"></script>
<script src="https://unpkg.com/react-dom/umd/react-dom.development.js"></script>
```

### Option 2: Vite (Preferred)
```bash
npm create vite@latest myapp --template react
npm install
npm run dev
```

---

## 4. React Components
React applications are built using components.

### Functional Component Example
```jsx
function Welcome() {
  return <h1>Hello Students!</h1>;
}
export default Welcome;
```

---

## 5. JSX Basics
JSX lets you write HTML inside JavaScript.

### JSX Rules
- Must return **one parent element**
- Use `className` instead of `class`
- Use `{ }` for JavaScript expressions

Example:
```jsx
let name = "Maaz";
return <p>Hello {name}</p>;
```

---

## 6. Props (Component Inputs)
Props allow data to be passed from parent to child.

```jsx
function Greeting(props) {
  return <h2>Hello {props.name}</h2>;
}
```
Usage:
```jsx
<Greeting name="Ali" />
```

---

## 7. State (Component Data)
State is used for data that changes inside the component.

```jsx
import { useState } from "react";

function Counter() {
  const [count, setCount] = useState(0);

  return (
    <>
      <p>Count: {count}</p>
      <button onClick={() => setCount(count + 1)}>Increase</button>
    </>
  );
}
```

---

## 8. Handling Events
```jsx
<button onClick={handleClick}>Click Me</button>
```

---

## 9. Conditional Rendering
```jsx
{isLoggedIn ? <p>Welcome!</p> : <p>Please Login</p>}
```

---

## 10. Lists & Keys
```jsx
const items = ["Apple", "Banana", "Orange"];
return items.map((item, index) => <p key={index}>{item}</p>);
```

---

## 11. useEffect Hook (Side Effects)
```jsx
useEffect(() => {
  console.log("Mounted");
}, []);
```

---

## 12. Forms in React
```jsx
const [text, setText] = useState("");

return (
  <input value={text} onChange={(e) => setText(e.target.value)} />
);
```

---

## 13. Folder Structure
```
src/
  components/
  App.jsx
  main.jsx
```

---

## 14. Common Beginner Mistakes
- Using `class` instead of `className`
- Forgetting to wrap JSX inside one parent
- Directly modifying state instead of using setter

---

## 15. Beginner-friendly React Projects
- Counter App
- Todo List
- Calculator
- Color Changer
- Basic Form
- Fetch API Users List

---

Let me know if you want Level 2 React notes, exercises, or beginner projects!