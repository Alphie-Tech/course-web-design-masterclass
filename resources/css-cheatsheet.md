# 🎨 CSS Cheatsheet – Alphie Tech Responsive Frontend Engineering Masterclass (10 Weeks)

CSS (Cascading Style Sheets) is used to style HTML elements.

---

# 📦 Basic Syntax

```css
selector {
  property: value;
}
```

Example:

```css
h1 {
  color: blue;
}
```

---

# 🎯 Selectors

## Element Selector

```css
p {
  color: red;
}
```

---

## Class Selector

```css
.card {
  background: white;
}
```

HTML:

```html
<div class="card"></div>
```

---

## ID Selector

```css
#hero {
  height: 100vh;
}
```

HTML:

```html
<section id="hero"></section>
```

---

# 🎨 Colors

```css
color: red;
color: #ff0000;
color: rgb(255, 0, 0);
```

---

# 🔤 Text Styling

```css
font-size: 16px;
font-weight: bold;
font-family: Arial, sans-serif;
text-align: center;
line-height: 1.5;
```

---

# 📦 Box Model

```css
width: 300px;
height: 200px;

padding: 20px;
border: 2px solid black;
margin: 30px;
```

---

# 🧱 Display

```css
display: block;
display: inline;
display: inline-block;
display: flex;
display: grid;
display: none;
```

---

# 📍 Positioning

```css
position: static;
position: relative;
position: absolute;
position: fixed;
position: sticky;
```

---

# 📐 Flexbox

## Enable Flexbox

```css
display: flex;
```

---

## Direction

```css
flex-direction: row;
flex-direction: column;
```

---

## Alignment

```css
justify-content: center;
align-items: center;
```

---

## Space Between

```css
justify-content: space-between;
```

---

# 🟦 CSS Grid

## Enable Grid

```css
display: grid;
```

---

## Columns

```css
grid-template-columns: 1fr 1fr;
```

---

## Gap

```css
gap: 20px;
```

---

# 📱 Responsive Design

## Media Query

```css
@media (max-width: 768px) {
  body {
    background: red;
  }
}
```

---

# ✨ Hover Effects

```css
button:hover {
  background: black;
  color: white;
}
```

---

# 🎬 Transitions

```css
transition: all 0.3s ease;
```

---

# 🔄 Transform

```css
transform: scale(1.1);
transform: rotate(45deg);
transform: translateX(20px);
```

---

# 🌈 Backgrounds

```css
background: red;

background-image: url("image.jpg");

background-size: cover;

background-position: center;
```

---

# 🔲 Border Radius

```css
border-radius: 10px;
```

---

# 🌫️ Shadows

```css
box-shadow: 0 4px 10px rgba(0,0,0,0.2);
```

---

# 🖼️ Images

```css
img {
  width: 100%;
  object-fit: cover;
}
```

---

# 🔥 Useful Units

| Unit | Meaning |
|---|---|
| px | Pixels |
| % | Percentage |
| rem | Relative to root font size |
| em | Relative to parent |
| vh | Viewport height |
| vw | Viewport width |

---

# 🧠 Common Beginner Mistakes

❌ Forgetting semicolons

```css
color: red
```

✅ Correct:

```css
color: red;
```

---

❌ Wrong selector

```css
button {
}
```

when HTML has:

```html
<div class="button"></div>
```

✅ Correct:

```css
.button {
}
```

---

# 🚀 Pro Tip

Learn these deeply:
- Flexbox
- Positioning
- Spacing
- Responsive design

These four areas alone separate beginners from competent frontend developers.

---

# 📚 Practice Daily

CSS is learned by:
- building
- breaking things
- fixing things
- repetition

Code every day.