# Web Development With AI 🚀

## Introduction
Welcome to **Web Development With AI** 🎉  
In this class, we are learning how websites are built using **HTML** and **CSS**.  
We also explored how AI tools can help developers learn faster, write cleaner code, and solve problems easily.

This README contains simple notes, examples, and resources that will help students revise everything covered in class.

---

# 📘 What is HTML?
HTML stands for **HyperText Markup Language**.

HTML is used to create the **structure** of a webpage.
It works like the **skeleton** of a website.

With HTML, we can create:
- Headings
- Paragraphs
- Images
- Links
- Tables
- Forms
- Videos
- Audio
- And much more...

---

# 🏗 Basic Structure of an HTML Document

```html
<!DOCTYPE html>
<html>
<head>
  <title>My First Website</title>
</head>
<body>

  <h1>Hello World</h1>
  <p>This is my first webpage.</p>

</body>
</html>
```

## Explanation
- `<!DOCTYPE html>` → Tells the browser this is an HTML5 document.
- `<html>` → Root element of the webpage.
- `<head>` → Contains meta information.
- `<title>` → Website title shown in browser tab.
- `<body>` → Main visible content of the webpage.

---

# 🧩 Common HTML Elements

## Headings

```html
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<h3>Small Heading</h3>
```

## Paragraph

```html
<p>This is a paragraph.</p>
```

## Lists

### Unordered List

```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>
```

### Ordered List

```html
<ol>
  <li>Wake up</li>
  <li>Study</li>
  <li>Practice</li>
</ol>
```

## Links

```html
<a href="https://google.com">Visit Google</a>
```

## Images

```html
<img src="image.jpg" alt="Nature Image" width="300">
```

## Tables

```html
<table border="1">
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>

  <tr>
    <td>Ali</td>
    <td>20</td>
  </tr>
</table>
```

---

# 🏷 HTML Attributes

Attributes give extra information to HTML elements.

## Common Attributes

| Attribute | Purpose |
|---|---|
| `id` | Unique identity |
| `class` | Group elements |
| `style` | Inline styling |
| `src` | Image/video source |
| `href` | Link destination |
| `alt` | Alternative text |
| `width` | Element width |
| `height` | Element height |
| `placeholder` | Input hint |
| `disabled` | Disable input |

## Example

```html
<input type="text" placeholder="Enter your name">
```

---

# 🧠 Semantic HTML Elements

Semantic elements improve readability and SEO.

## Examples

```html
<header></header>
<nav></nav>
<main></main>
<section></section>
<article></article>
<aside></aside>
<footer></footer>
```

## Why Semantic HTML?
- Cleaner code
- Better accessibility
- Better SEO
- Easy to understand

---

# ✍ Text Formatting Tags

| Tag | Purpose |
|---|---|
| `<b>` | Bold text |
| `<strong>` | Important text |
| `<i>` | Italic text |
| `<em>` | Emphasized text |
| `<mark>` | Highlight text |
| `<small>` | Small text |
| `<del>` | Deleted text |
| `<ins>` | Inserted text |
| `<sub>` | Subscript |
| `<sup>` | Superscript |

## Example

```html
<p>
  <b>Bold</b>
  <i>Italic</i>
  <mark>Highlight</mark>
</p>
```

---

# 🎨 What is CSS?

CSS stands for **Cascading Style Sheets**.

CSS is used to design and style webpages.

- HTML = Structure
- CSS = Design

HTML is the skeleton.
CSS is the skin.

---

# 🔗 Relationship Between HTML & CSS

HTML creates content.
CSS makes it beautiful.

Without CSS, websites look plain.
With CSS, websites become attractive and responsive.

---

# 🖌 Ways to Add CSS

## 1. Inline CSS

```html
<p style="color:red;">Hello</p>
```

## 2. Internal CSS

```html
<style>
  p {
    color: blue;
  }
</style>
```

## 3. External CSS

### HTML File

```html
<link rel="stylesheet" href="style.css">
```

### CSS File

```css
p {
  color: green;
}
```

---

# 🎯 CSS Syntax

```css
selector {
  property: value;
}
```

## Example

```css
h1 {
  color: red;
}
```

---

# 🎯 CSS Selectors

## Element Selector

```css
p {
  color: red;
}
```

## Class Selector

```css
.center {
  text-align: center;
}
```

## ID Selector

```css
#heading {
  color: blue;
}
```

---

# 📦 CSS Box Model

Every HTML element is like a box.

The box model contains:

- Content
- Padding
- Border
- Margin

## Example

```css
div {
  margin: 20px;
  padding: 20px;
  border: 2px solid black;
}
```

---

# 📐 CSS Positioning

## Static
Default positioning.

## Relative
Moves relative to its normal position.

## Absolute
Moves relative to nearest parent.

## Fixed
Stays fixed on screen.

---

# 💪 Flexbox

Flexbox helps align items easily.

```css
.container {
  display: flex;
  justify-content: center;
  align-items: center;
}
```

## Flexbox Game 🎮
We also explored:

- Flexbox Froggy

Practice here:
- https://flexboxfroggy.com/

---

# 🧱 CSS Grid

CSS Grid helps create layouts using rows and columns.

```css
.container {
  display: grid;
  grid-template-columns: 1fr 1fr;
}
```

## Grid Game 🎮
Practice here:
- https://cssgridgarden.com/

---

# 🔤 CSS Text Properties

## Font Family

```css
p {
  font-family: Arial;
}
```

## Font Size

```css
p {
  font-size: 20px;
}
```

## Text Align

```css
p {
  text-align: center;
}
```

## Line Height

```css
p {
  line-height: 30px;
}
```

---

# 🌈 Colors in CSS

## HEX Colors

```css
color: #ff0000;
```

## RGB Colors

```css
color: rgb(255,0,0);
```

## RGBA Colors

```css
color: rgba(255,0,0,0.5);
```

## HSL Colors

```css
color: hsl(0,100%,50%);
```

---

# 🖼 Background Properties

```css
body {
  background-color: lightblue;
  background-image: url("bg.jpg");
}
```

---

# ✨ Pseudo Classes

Pseudo classes target special states.

## Example

```css
a:hover {
  color: red;
}
```

## Common Pseudo Classes

- `:hover`
- `:focus`
- `:active`
- `:first-child`
- `:last-child`
- `:nth-child()`

---

# 🎬 CSS Transitions

Transitions create smooth effects.

```css
div {
  transition: width 2s;
}
```

---

# 🎥 CSS Animations

```css
div {
  animation: move 4s infinite;
}

@keyframes move {
  from {
    left: 0px;
  }

  to {
    left: 200px;
  }
}
```

---

# 🖼 Adding Images

```html
<img src="nature.jpg" alt="Nature" width="300">
```

---

# 🎵 Adding Audio

```html
<audio controls>
  <source src="audio.mp3" type="audio/mp3">
</audio>
```

---

# 🎥 Adding Video

```html
<video width="400" controls>
  <source src="video.mp4" type="video/mp4">
</video>
```

---

# ▶ Embedding YouTube Video

```html
<iframe width="560" height="315"
src="https://www.youtube.com/embed/VIDEO_ID">
</iframe>
```

---

# 📝 HTML Forms

## Example Form

```html
<form>

  <label>Name</label>
  <input type="text" placeholder="Enter name">

  <br><br>

  <label>Message</label>
  <textarea></textarea>

  <br><br>

  <button>Submit</button>

</form>
```

## Form Elements

- `<input>`
- `<textarea>`
- `<select>`
- `<option>`
- `<button>`
- `<label>`

---

# 📱 HTML Best Practices

## Always Remember

✅ Use proper indentation  
✅ Write clean code  
✅ Use semantic tags  
✅ Add alt text to images  
✅ Keep code readable  
✅ Use meaningful class names  
✅ Avoid unnecessary code  

---

# 🤖 Using AI in Web Development

In our class, we also learned how AI can help developers.

AI can help with:

- Writing HTML & CSS faster
- Fixing bugs
- Generating layouts
- Improving design ideas
- Learning concepts quickly
- Creating responsive sections
- Explaining errors

But remember:

⚠️ AI is a helper, not a replacement for practice.
The more you practice yourself, the better developer you become.

---

# 🌍 Hosting Websites

We also learned how to make websites live using Netlify.

## Steps

1. Create account on Netlify
2. Upload project folder
3. Deploy website
4. Share live link

Netlify Website:
- https://www.netlify.com/

---

# 🎮 Games & Practice Resources

## HTML & CSS Practice

### Flexbox Froggy
- https://flexboxfroggy.com/

### CSS Grid Garden
- https://cssgridgarden.com/

### CSS Diner
- https://css-diner.netlify.app/

### CSS Battle
- https://cssbattle.dev/

### Flukeout
- https://flukeout.github.io/

### Unfold
- https://rupl.github.io/unfold/

### PlayCode
- https://playcode.io/css

---

# 📚 Useful Learning Resources

## MDN Docs
- https://developer.mozilla.org/en-US/docs/Web/CSS

## W3Schools HTML
- https://www.w3schools.com/html/

## W3Schools CSS
- https://www.w3schools.com/css/default.asp

## W3C CSS Docs
- https://www.w3.org/Style/CSS/Overview.en.html

## Google Fonts
- https://fonts.google.com/

## Adobe Fonts
- https://fonts.adobe.com/

---

# 💡 Final Advice for Students

Learning web development becomes easy when you:

- Practice daily
- Build small projects
- Experiment with code
- Use AI wisely
- Learn by creating
- Make mistakes and fix them

The more websites you build, the more confidence you gain 🚀

Keep practicing and keep building 💻✨

---

# ❤️ Web Development With AI

Happy Coding Everyone 🚀

