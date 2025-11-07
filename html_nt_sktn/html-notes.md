# 🧠 HTML Concept Notes (Beginner to Advanced)

---

## 1. Introduction to HTML

**HTML (HyperText Markup Language)** is the standard language used to structure content on the web.

A basic HTML page:
```html
<!DOCTYPE html>
<html>
<head>
  <title>My First Webpage</title>
</head>
<body>
  <h1>Welcome to My Page</h1>
  <p>This is my first HTML document.</p>
</body>
</html>
```

**Explanation:**
- `<!DOCTYPE html>` → Defines HTML5 version.  
- `<html>` → Root element.  
- `<head>` → Meta information (title, links, etc.).  
- `<body>` → Visible content of the page.

---

## 2. Headings, Paragraphs, and Line Breaks

HTML uses headings from `<h1>` to `<h6>` for titles, and `<p>` for paragraphs.

```html
<h1>Main Title</h1>
<h2>Sub Title</h2>
<p>This is a paragraph of text.</p>
<br>
<p>This text appears after a line break.</p>
```

---

## 3. Text Formatting Tags

These tags style or emphasize parts of text.

| Tag | Description | Example |
|-----|--------------|----------|
| `<b>` | Bold text | `<b>Important</b>` |
| `<i>` | Italic text | `<i>Note</i>` |
| `<u>` | Underline | `<u>Line</u>` |
| `<strong>` | Important text | `<strong>Warning!</strong>` |
| `<em>` | Emphasized text | `<em>Highlighted</em>` |
| `<mark>` | Highlighted | `<mark>Important</mark>` |
| `<small>` | Smaller text | `<small>Footnote</small>` |

---

## 4. Links and Images

### Links:
```html
<a href="https://www.example.com" target="_blank">Visit Example</a>
```

### Images:
```html
<img src="photo.jpg" alt="My photo" width="300">
```

---

## 5. Lists

### Unordered List:
```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>
```

### Ordered List:
```html
<ol>
  <li>Step 1</li>
  <li>Step 2</li>
</ol>
```

### Nested List:
```html
<ul>
  <li>Frontend
    <ul>
      <li>HTML</li>
      <li>CSS</li>
    </ul>
  </li>
</ul>
```

---

## 6. Tables

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Ali</td>
    <td>22</td>
  </tr>
</table>
```

---

## 7. Forms

```html
<form>
  <label>Name:</label>
  <input type="text" name="name" required><br>

  <label>Email:</label>
  <input type="email" name="email" required><br>

  <input type="submit" value="Submit">
</form>
```

---

## 8. Semantic HTML Tags

| Tag | Purpose |
|------|----------|
| `<header>` | Top section or navigation |
| `<nav>` | Menu or navigation links |
| `<main>` | Main content |
| `<section>` | Logical section |
| `<article>` | Self-contained content |
| `<aside>` | Sidebar |
| `<footer>` | Bottom area of page |

---

## 9. Multimedia (Audio & Video)

### Audio
```html
<audio controls>
  <source src="music.mp3" type="audio/mp3">
</audio>
```

### Video
```html
<video width="400" controls autoplay loop muted poster="thumbnail.jpg">
  <source src="movie.mp4" type="video/mp4">
</video>
```

---

## 10. Meta Tags

```html
<meta charset="UTF-8">
<meta name="description" content="Learn HTML basics with examples.">
<meta name="keywords" content="HTML, web, beginner, coding">
<meta name="author" content="Student Name">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

---

## 11. Accessibility (A11Y)

Accessibility ensures websites can be used by everyone.

```html
<label for="email">Email:</label>
<input type="email" id="email" aria-label="Email field">
```

---

## 12. HTML5 Form Validation Attributes

```html
<input type="text" required>
<input type="email" pattern=".+@gmail\.com">
<input type="number" min="1" max="100">
```

---

## 13. Fieldset and Legend

```html
<fieldset>
  <legend>Personal Info</legend>
  <input type="text" placeholder="Name">
  <input type="email" placeholder="Email">
</fieldset>
```

---

## 14. HTML5 APIs (Introduction)

| API | Description |
|-----|--------------|
| **Geolocation API** | Detects user’s location |
| **Local Storage API** | Saves data locally |
| **Drag & Drop API** | Enables drag-and-drop |

Example:
```html
<button id="getLocation">Get My Location</button>
<p id="output"></p>
```

---

## 15. Other Useful Tags

```html
<details>
  <summary>Show more</summary>
  <p>Hidden information revealed.</p>
</details>
```

---

## ✅ Summary of Key HTML Principles

- Always close your tags properly.  
- Use semantic tags for clarity.  
- Validate HTML using [W3C Validator](https://validator.w3.org/).  
- HTML defines **structure**, not **style**.
