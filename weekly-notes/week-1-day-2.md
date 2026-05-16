📘 Week 1 — Day 2 Resource Note

Alphie Tech Responsive Frontend Engineering Masterclass

🎨 Introduction to CSS Fundamentals

Welcome to Day 2 of the Responsive Frontend Engineering Masterclass.

In Day 1, you learned how to structure webpages using HTML.

Today, you will learn how to make those webpages beautiful using CSS (Cascading Style Sheets).

By the end of this lesson, you should understand:

What CSS is

How CSS works

Different ways to write CSS

Selectors

Colors

Typography

Spacing

The Box Model

Display properties

Basic layouts



---

🌐 What is CSS?

CSS stands for Cascading Style Sheets.

CSS controls:

colors

spacing

layouts

fonts

positioning

responsiveness

animations


Without CSS, websites would look plain and unstyled.


---

🧠 HTML vs CSS

Technology	Purpose

HTML	Structure
CSS	Styling
JavaScript	Interactivity



---

📌 Basic CSS Syntax

selector {
    property: value;
}

Example:

h1 {
    color: blue;
}


---

🧩 Explanation

Part	Meaning

h1	Selector
color	Property
blue	Value



---

🖍️ Ways to Add CSS

There are 3 ways to write CSS.


---

1️⃣ Inline CSS

Written directly inside an HTML element.

<h1 style="color: red;">Hello World</h1>

⚠️ Not recommended for large projects.


---

2️⃣ Internal CSS

Written inside the <style> tag.

<style>
    h1 {
        color: blue;
    }
</style>


---

3️⃣ External CSS (Best Practice)

CSS is written in a separate .css file.


---

HTML File

<link rel="stylesheet" href="style.css">


---

CSS File

body {
    background-color: lightgray;
}

This is the professional approach used in real projects.


---

📂 Proper Project Structure

project-folder/
│
├── index.html
├── style.css
└── assets/


---

🎯 CSS Selectors

Selectors target HTML elements for styling.


---

📌 Element Selector

p {
    color: green;
}

Targets all paragraphs.


---

📌 Class Selector

HTML:

<p class="text">Hello</p>

CSS:

.text {
    color: blue;
}

Classes can be reused multiple times.


---

📌 ID Selector

HTML:

<section id="hero">
    Welcome
</section>

CSS:

#hero {
    background-color: black;
}

IDs should only be used once per page.


---

🎨 Colors in CSS


---

📌 Color Names

h1 {
    color: red;
}


---

📌 HEX Colors

body {
    background-color: #f4f4f4;
}


---

📌 RGB Colors

p {
    color: rgb(0, 0, 255);
}


---

🔤 Typography in CSS

Typography controls text appearance.


---

📌 Font Size

h1 {
    font-size: 40px;
}


---

📌 Font Family

body {
    font-family: Arial, sans-serif;
}


---

📌 Font Weight

h1 {
    font-weight: bold;
}


---

📌 Text Alignment

h1 {
    text-align: center;
}


---

📦 Spacing in CSS

Spacing improves readability and layout quality.


---

📌 Margin

Margin controls outer spacing.

div {
    margin: 20px;
}


---

📌 Padding

Padding controls inner spacing.

div {
    padding: 20px;
}


---

📌 Border

div {
    border: 2px solid black;
}


---

📦 The CSS Box Model

Every HTML element is treated like a box.

The box consists of:

Content
Padding
Border
Margin


---

📌 Box Model Example

.card {
    padding: 20px;
    border: 1px solid gray;
    margin: 30px;
}


---

🧱 Width and Height

.box {
    width: 300px;
    height: 200px;
}


---

🖼️ Styling Images

img {
    width: 300px;
    border-radius: 10px;
}


---

🔘 Styling Buttons

HTML:

<button>Click Me</button>

CSS:

button {
    background-color: blue;
    color: white;
    border: none;
    padding: 12px 20px;
    border-radius: 5px;
}


---

✨ Hover Effects

Hover changes styles when the mouse moves over an element.

button:hover {
    background-color: darkblue;
}


---

📐 Display Property

Controls how elements behave on the page.


---

📌 Block Elements

Take full width.

Examples:

div

p

section



---

📌 Inline Elements

Take only needed width.

Examples:

span

a

strong



---

📌 Inline-Block

Combines both behaviors.

a {
    display: inline-block;
}


---

🧭 Introduction to Layouts


---

📌 Centering Content

.container {
    width: 80%;
    margin: auto;
}


---

📌 Background Colors

body {
    background-color: #f5f5f5;
}


---

📌 Card Layout Example

HTML:

<div class="card">
    <h2>Frontend Engineering</h2>
    <p>Learning modern web development.</p>
</div>

CSS:

.card {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    width: 300px;
}


---

🧠 CSS Best Practices

✅ Use external CSS files
✅ Keep code organized
✅ Use meaningful class names
✅ Avoid excessive inline CSS
✅ Indent code properly
✅ Reuse styles with classes


---

⚠️ Common Beginner Mistakes

❌ Forgetting semicolons
❌ Missing curly braces
❌ Incorrect file linking
❌ Using spaces in class names incorrectly
❌ Styling everything individually
❌ Confusing margin and padding


---

🏗️ Mini Example Project

HTML

<!DOCTYPE html>
<html lang="en">
<head>
    <title>Profile Card</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="card">
        <img src="student.jpg" alt="Student">

        <h1>John Doe</h1>

        <p>Frontend Engineering Student</p>

        <button>Contact Me</button>
    </div>

</body>
</html>


---

CSS

body {
    background-color: #f4f4f4;
    font-family: Arial, sans-serif;
}

.card {
    width: 300px;
    background-color: white;
    padding: 20px;
    margin: 50px auto;
    text-align: center;
    border-radius: 10px;
}

img {
    width: 120px;
    border-radius: 50%;
}

button {
    background-color: black;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
}


---

🏁 Conclusion

CSS transforms plain HTML into visually appealing interfaces.

As a frontend engineer, your goal is not only to make websites work — but also to make them:

beautiful

readable

accessible

professional


Strong CSS fundamentals will make learning:

Flexbox

Grid

TailwindCSS

Framer Motion

React styling


much easier later in the course.

Focus on understanding:

selectors

spacing

layouts

structure


These fundamentals are what professional frontend systems are built upon.Basic layouts
🌐 What is CSS?

CSS stands for Cascading Style Sheets.

CSS controls:

colors
spacing
layouts
fonts
positioning
responsiveness
animations

Without CSS, websites would look plain and unstyled.

🧠 HTML vs CSS
Technology	Purpose
HTML	Structure
CSS	Styling
JavaScript	Interactivity
📌 Basic CSS Syntax
selector {
    property: value;
}

Example:

h1 {
    color: blue;
}
🧩 Explanation
Part	Meaning
h1	Selector
color	Property
blue	Value
🖍️ Ways to Add CSS

There are 3 ways to write CSS.

1️⃣ Inline CSS

Written directly inside an HTML element.

<h1 style="color: red;">Hello World</h1>

⚠️ Not recommended for large projects.

2️⃣ Internal CSS

Written inside the <style> tag.

<style>
    h1 {
        color: blue;
    }
</style>
3️⃣ External CSS (Best Practice)

CSS is written in a separate .css file.

HTML File
<link rel="stylesheet" href="style.css">
CSS File
body {
    background-color: lightgray;
}

This is the professional approach used in real projects.

📂 Proper Project Structure
project-folder/
│
├── index.html
├── style.css
└── assets/
🎯 CSS Selectors

Selectors target HTML elements for styling.

📌 Element Selector
p {
    color: green;
}

Targets all paragraphs.

📌 Class Selector

HTML:

<p class="text">Hello</p>

CSS:

.text {
    color: blue;
}

Classes can be reused multiple times.

📌 ID Selector

HTML:

<section id="hero">
    Welcome
</section>

CSS:

#hero {
    background-color: black;
}

IDs should only be used once per page.

🎨 Colors in CSS
📌 Color Names
h1 {
    color: red;
}
📌 HEX Colors
body {
    background-color: #f4f4f4;
}
📌 RGB Colors
p {
    color: rgb(0, 0, 255);
}
🔤 Typography in CSS

Typography controls text appearance.

📌 Font Size
h1 {
    font-size: 40px;
}
📌 Font Family
body {
    font-family: Arial, sans-serif;
}
📌 Font Weight
h1 {
    font-weight: bold;
}
📌 Text Alignment
h1 {
    text-align: center;
}
📦 Spacing in CSS

Spacing improves readability and layout quality.

📌 Margin

Margin controls outer spacing.

div {
    margin: 20px;
}
📌 Padding

Padding controls inner spacing.

div {
    padding: 20px;
}
📌 Border
div {
    border: 2px solid black;
}
📦 The CSS Box Model

Every HTML element is treated like a box.

The box consists of:

Content
Padding
Border
Margin
📌 Box Model Example
.card {
    padding: 20px;
    border: 1px solid gray;
    margin: 30px;
}
🧱 Width and Height
.box {
    width: 300px;
    height: 200px;
}
🖼️ Styling Images
img {
    width: 300px;
    border-radius: 10px;
}
🔘 Styling Buttons

HTML:

<button>Click Me</button>

CSS:

button {
    background-color: blue;
    color: white;
    border: none;
    padding: 12px 20px;
    border-radius: 5px;
}
✨ Hover Effects

Hover changes styles when the mouse moves over an element.

button:hover {
    background-color: darkblue;
}
📐 Display Property

Controls how elements behave on the page.

📌 Block Elements

Take full width.

Examples:

div
p
section
📌 Inline Elements

Take only needed width.

Examples:

span
a
strong
📌 Inline-Block

Combines both behaviors.

a {
    display: inline-block;
}
🧭 Introduction to Layouts
📌 Centering Content
.container {
    width: 80%;
    margin: auto;
}
📌 Background Colors
body {
    background-color: #f5f5f5;
}
📌 Card Layout Example

HTML:

<div class="card">
    <h2>Frontend Engineering</h2>
    <p>Learning modern web development.</p>
</div>

CSS:

.card {
    background-color: white;
    padding: 20px;
    border-radius: 10px;
    width: 300px;
}
🧠 CSS Best Practices

✅ Use external CSS files
✅ Keep code organized
✅ Use meaningful class names
✅ Avoid excessive inline CSS
✅ Indent code properly
✅ Reuse styles with classes

⚠️ Common Beginner Mistakes

❌ Forgetting semicolons
❌ Missing curly braces
❌ Incorrect file linking
❌ Using spaces in class names incorrectly
❌ Styling everything individually
❌ Confusing margin and padding

🏗️ Mini Example Project
HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <title>Profile Card</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>

    <div class="card">
        <img src="student.jpg" alt="Student">

        <h1>John Doe</h1>

        <p>Frontend Engineering Student</p>

        <button>Contact Me</button>
    </div>

</body>
</html>
CSS
body {
    background-color: #f4f4f4;
    font-family: Arial, sans-serif;
}

.card {
    width: 300px;
    background-color: white;
    padding: 20px;
    margin: 50px auto;
    text-align: center;
    border-radius: 10px;
}

img {
    width: 120px;
    border-radius: 50%;
}

button {
    background-color: black;
    color: white;
    padding: 10px 20px;
    border: none;
    border-radius: 5px;
}
🏁 Conclusion

CSS transforms plain HTML into visually appealing interfaces.

As a frontend engineer, your goal is not only to make websites work — but also to make them:

beautiful
readable
accessible
professional

Strong CSS fundamentals will make learning:

Flexbox
Grid
TailwindCSS
Framer Motion
React styling

much easier later in the course.

Focus on understanding:

selectors
spacing
layouts
