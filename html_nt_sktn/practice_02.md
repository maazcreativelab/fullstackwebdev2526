# 🧠 HTML Practice Notes – Level 2 (Intermediate)
**Topic:** Tables, Forms, Semantic Tags & Media  
**Goal:** Learn to organize data, collect user input, and use semantic & multimedia elements.

---

## 🧩 1. Tables

Tables organize data into rows and columns using `<table>`, `<tr>`, `<th>`, and `<td>`.

**Practice Task:**  
Create a table showing your weekly study schedule.  
Include columns: **Day**, **Subject**, and **Hours**.

💡 **Hint:**  
Use `<th>` for headings and `<td>` for data cells.  
Example:
```html
<table border="1">
  <tr>
    <th>Day</th>
    <th>Subject</th>
    <th>Hours</th>
  </tr>
  <tr>
    <td>Monday</td>
    <td>HTML</td>
    <td>2</td>
  </tr>
</table>
```

🧱 **Bonus Challenge:**  
Add a **caption** on top of your table and make one cell **bold** using `<b>`.

---

## 🧩 2. Forms

Forms collect user input using `<form>` and input elements.

**Practice Task:**  
Create a small registration form with:
- Name (text input)
- Email (email input)
- Password (password input)
- Gender (radio buttons)
- Skills (checkboxes)
- Submit button

💡 **Hint:**  
Each field uses the `<input>` tag with different `type` attributes.  
Example:
```html
<form>
  Name: <input type="text"><br>
  Email: <input type="email"><br>
  Password: <input type="password"><br>
  <input type="submit" value="Register">
</form>
```

🧱 **Bonus Challenge:**  
Add a `<select>` dropdown for “Country” with at least 3 options.

---

## 🧩 3. Textarea

For longer input (like comments), use `<textarea>`.

**Practice Task:**  
Add a “Feedback” section to your form using a `<textarea>` tag.

💡 **Hint:**  
You can set rows and columns:
```html
<textarea rows="4" cols="40" placeholder="Write your feedback here..."></textarea>
```

---

## 🧩 4. Semantic Tags

Semantic tags give meaning to web page sections — making them easier to understand by browsers and search engines.

**Common Semantic Tags:**
- `<header>` → top area of the page
- `<nav>` → navigation links
- `<section>` → a section of content
- `<article>` → a self-contained block (e.g., blog post)
- `<footer>` → bottom area (contact info, copyright)

**Practice Task:**  
Create a simple blog layout:
1. `<header>` with site title  
2. `<nav>` with 3 links  
3. `<section>` with an `<article>` (title and paragraph)  
4. `<footer>` with your name and year  

💡 **Hint:**  
Use headings and paragraphs inside `<article>` to make it readable.

---

## 🧩 5. Audio and Video

Use HTML5 tags to embed media.

**Practice Task:**  
Add:
- An **audio** clip with controls.  
- A **video** from your computer or a public link.  

💡 **Hint:**  
```html
<audio controls>
  <source src="music.mp3" type="audio/mpeg">
</audio>

<video width="320" height="240" controls>
  <source src="video.mp4" type="video/mp4">
</video>
```

🧱 **Bonus Challenge:**  
Add a fallback message for browsers that don’t support these tags.

---

## 🧩 6. Inline Frame (iframe)

`<iframe>` allows embedding another web page inside your page.

**Practice Task:**  
Embed a YouTube video or Google Map on your web page.

💡 **Hint:**  
You can copy the embed code directly from YouTube’s “Share → Embed” option.  
Example:
```html
<iframe width="560" height="315" src="https://www.youtube.com/embed/example"></iframe>
```

---

## 🧩 7. Grouping Content with Div & Span

- `<div>`: groups block-level elements  
- `<span>`: groups inline text  

**Practice Task:**  
Create a small section using `<div>` that contains your photo, name, and a short description.  
Highlight one word in color using `<span>` and `style` attribute.

💡 **Hint:**  
```html
<div>
  <h2>Student Profile</h2>
  <p>Hello, I’m learning <span style="color:blue;">HTML</span>.</p>
</div>
```

---

## 🧩 8. Practice Challenge – Mini Project

🧱 **Project:** Create a **“Contact Us” page** using what you learned.
Include:
1. A `<header>` and `<nav>` bar  
2. A short `<section>` about your site  
3. A `<form>` with name, email, subject, message  
4. An embedded Google Map in `<iframe>`  
5. A `<footer>` with contact info

💡 **Bonus Hint:**  
Use `<fieldset>` and `<legend>` around your form to make it neat.

---

## 🌟 Extra Challenge (Optional)

Try to create a **“Student Registration Portal”** page:
- Use `<form>` for inputs  
- Add a table showing available courses  
- Include a logo using `<img>`  
- Use `<footer>` with © copyright  

---

## ✅ Tips for Intermediate Level
- Use indentation for better readability.  
- Validate your HTML at [https://validator.w3.org/](https://validator.w3.org/)  
- Keep your file names lowercase and without spaces.  
- Explore semantic layout instead of too many `<div>` tags.
