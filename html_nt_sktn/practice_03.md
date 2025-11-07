# 🧠 HTML Practice Notes – Level 3 (Advanced)
**Topic:** HTML5 Validation, Meta Tags, Accessibility & APIs  
**Goal:** Learn how to enhance user experience, improve SEO, and make websites accessible and modern.

---

## 🧩 1. Form Validation (HTML5 Built-in)

HTML5 includes built-in validation to check input before submission.

**Practice Task:**  
Create a **Sign-Up Form** with these fields:
- Full Name (required)
- Email (must be a valid email)
- Password (minimum 6 characters)
- Age (number between 10 and 100)
- Website (optional)
- Submit button

💡 **Hint:**  
Use these attributes:
- `required`
- `minlength`
- `min` / `max`
- `type="email"` / `type="number"`
- `pattern` for custom validation

Example:
```html
<form>
  <input type="text" name="fullname" placeholder="Full Name" required><br>
  <input type="email" placeholder="Email" required><br>
  <input type="password" minlength="6" placeholder="Password" required><br>
  <input type="number" min="10" max="100" placeholder="Age"><br>
  <input type="url" placeholder="Website"><br>
  <input type="submit" value="Sign Up">
</form>
```

🧱 **Bonus Challenge:**  
Add a phone number input and use `pattern` to only allow digits.

---

## 🧩 2. Using the `fieldset` and `legend` Tags

These tags visually group related fields in a form.

**Practice Task:**  
Group your registration form fields under two sections:
- Personal Details  
- Login Information

💡 **Hint:**  
```html
<fieldset>
  <legend>Personal Details</legend>
  <input type="text" placeholder="Full Name">
  <input type="email" placeholder="Email">
</fieldset>
```

---

## 🧩 3. Meta Tags

Meta tags provide information about the page to browsers and search engines.

**Practice Task:**  
Add meta tags to your HTML `<head>`:
- Character set: UTF-8  
- Description: Short about your page  
- Keywords: 5 relevant keywords  
- Author: Your name  
- Viewport: For mobile responsiveness

💡 **Hint:**  
```html
<meta charset="UTF-8">
<meta name="description" content="A beginner web development practice page">
<meta name="keywords" content="HTML, practice, web development, learning">
<meta name="author" content="Student Name">
<meta name="viewport" content="width=device-width, initial-scale=1.0">
```

🧱 **Bonus Challenge:**  
Add a `<link rel="icon" href="favicon.png">` for a custom browser tab icon.

---

## 🧩 4. HTML5 Structural Elements Review

Revisit and expand on:
- `<header>`  
- `<nav>`  
- `<main>`  
- `<section>`  
- `<article>`  
- `<aside>`  
- `<footer>`

**Practice Task:**  
Create a **news page layout** that includes:
- A `<header>` with site title  
- `<nav>` with links  
- `<main>` containing 2 `<article>` sections  
- `<aside>` with “Recent Updates”  
- `<footer>` with copyright info  

💡 **Hint:**  
Use placeholder text (`Lorem ipsum`) if needed.

---

## 🧩 5. Accessibility (A11Y)

Accessibility ensures web pages are usable by everyone, including screen reader users.

**Practice Task:**  
Update one of your forms:
- Add `label` tags for each input.  
- Use `alt` attributes for images.  
- Use `tabindex` to set focus order.  
- Use `aria-label` for buttons or links without visible text.

💡 **Hint:**  
```html
<label for="name">Full Name:</label>
<input id="name" type="text" aria-label="Full name field">
<img src="photo.jpg" alt="Profile photo">
```

🧱 **Bonus Challenge:**  
Try viewing your site using only the **Tab** key and make sure navigation is logical.

---

## 🧩 6. HTML5 APIs

Modern browsers support built-in APIs without JavaScript libraries.

### 🧠 Common APIs:
- **Geolocation API** – detects user’s location  
- **Local Storage** – stores data locally  
- **Drag & Drop API** – enables draggable items

**Practice Task:**  
Add a simple **Geolocation button** to show user’s location (you can only write the HTML part now).

💡 **Hint:**  
```html
<button id="getLocation">Get My Location</button>
<p id="output"></p>
```

(*The logic will be added later using JavaScript.*)

🧱 **Bonus Challenge:**  
Add a `<progress>` or `<meter>` element below the button to simulate loading or progress.

---

## 🧩 7. Multimedia Controls

Enhance audio/video tags with attributes:
- `controls`
- `autoplay`
- `loop`
- `muted`
- `poster`

**Practice Task:**  
Add a video player that:
- Displays a preview image before playing  
- Automatically plays and loops (without sound)  

💡 **Hint:**  
```html
<video width="400" controls autoplay loop muted poster="preview.jpg">
  <source src="sample.mp4" type="video/mp4">
</video>
```

---

## 🧩 8. Practice Challenge – Mini Project

🧱 **Project:** Create an **HTML5 Personal Portfolio Page**.  
Include:
1. `<header>` with your name and tagline  
2. `<nav>` with internal links (About, Skills, Contact)  
3. `<main>` with sections for each  
4. A `<form>` in Contact section  
5. `<meta>` tags and favicon in `<head>`  
6. Accessibility-friendly attributes  
7. An `<audio>` or `<video>` element  
8. A `<footer>` with copyright  

💡 **Bonus Hint:**  
Use `<a href="#sectionID">` for internal navigation links.

---

## 🌟 Extra Challenge (Optional)

Try building a **“Product Info Page”** that uses:
- `<article>` for product description  
- `<figure>` and `<figcaption>` for image  
- `<meter>` to show stock level  
- `<details>` and `<summary>` for expandable text  

---

## ✅ Tips for Advanced HTML
- Always validate your code before deployment.  
- Write semantic, accessible, and SEO-friendly HTML.  
- Avoid using inline styles — prefer CSS.  
- Remember: HTML is about structure, not design.
