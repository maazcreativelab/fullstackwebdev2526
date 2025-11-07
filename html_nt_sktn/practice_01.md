# 🧠 HTML Practice Notes – Level 1 (Beginner)
**Topic:** Getting Started with HTML  
**Goal:** Practice writing basic HTML pages and understand structure, tags, and attributes.

---

## 🧩 1. Understanding the Structure

Every HTML file follows this structure:

```html
<!DOCTYPE html>
<html>
  <head>
    <title>My First Web Page</title>
  </head>
  <body>
    <h1>Welcome to HTML!</h1>
    <p>This is my first paragraph.</p>
  </body>
</html>
```

**Practice Task:**  
- Create a new file named `index.html`.  
- Type the above structure.  
- Change the title to your own name.  
- Add one `<h1>` and one `<p>` tag with your own text.

💡 **Hint:**  
- Always save with `.html` extension.  
- Open the file by double-clicking it to see in browser.

---

## 🧩 2. Headings & Paragraphs

HTML gives six levels of headings (`<h1>` to `<h6>`).

**Practice Task:**  
- Write a web page that contains:  
  - One `<h1>` for the main title.  
  - Two subheadings (`<h2>` and `<h3>`).  
  - Three paragraphs (`<p>`) describing something you like.  

💡 **Hint:**  
Use `<br>` tag to add a line break if needed.  
Example:
```html
<p>I love coding.<br>It makes me creative!</p>
```

---

## 🧩 3. Lists

There are two main list types:
- **Ordered List** → `<ol>`  
- **Unordered List** → `<ul>`

**Practice Task:**  
Create a list of your favorite 5 foods:  
- First using `<ul>`  
- Then using `<ol>`

💡 **Hint:**  
Each item goes inside `<li>` tag.

Example:
```html
<ul>
  <li>Pizza</li>
  <li>Burger</li>
</ul>
```

---

## 🧩 4. Links

Links connect web pages using `<a>` tag.

**Practice Task:**  
- Create a link to **Google**, **YouTube**, and **your favorite website**.  
- Make one of them open in a **new tab**.

💡 **Hint:**  
Use `target="_blank"` to open in new tab.  
Example:
```html
<a href="https://www.google.com" target="_blank">Visit Google</a>
```

---

## 🧩 5. Images

Add an image using `<img>` tag.

**Practice Task:**  
- Add one image from your computer (use relative path).  
- Add another image from the internet (use URL).  

💡 **Hint:**  
Use `alt` attribute to describe the image.  
Example:
```html
<img src="myphoto.jpg" alt="My Photo">
```

---

## 🧩 6. Formatting Text

Practice these formatting tags:
- `<b>` (bold)
- `<i>` (italic)
- `<u>` (underline)
- `<mark>` (highlight)
- `<small>` (small text)

**Practice Task:**  
Write a paragraph describing yourself using at least **three** of the above tags.

💡 **Hint:**  
You can mix them:
```html
<p>I am <b>learning</b> <i>HTML</i> and it’s <mark>fun</mark>!</p>
```

---

## 🧩 7. Comments

Comments help you note something inside code but are invisible in the browser.

**Practice Task:**  
Add a comment in your HTML saying “This is my first web page”.

💡 **Hint:**  
```html
<!-- This is my first web page -->
```

---

## 🧩 8. Practice Challenge – Mini Project

🧱 **Project:** Create your first mini profile page.  
Include:
1. Your name in `<h1>`
2. A short paragraph about yourself  
3. A list of your hobbies (unordered list)  
4. A link to your favorite website  
5. One of your favorite images  

💡 **Bonus Hint:**  
Add a title in the `<head>` section and save as `myprofile.html`.

---

## 🌟 Extra Challenge (Optional)

Try to create a small “About My City” page:
- Use 3 headings
- 2 paragraphs
- 1 image
- 1 link
- 1 comment line  

---

## ✅ Tips for Beginners
- Always close your tags properly.  
- Indent your code for readability.  
- Keep experimenting — no one writes perfect HTML on day one.  
- Use VS Code or Notepad++ for better experience.
