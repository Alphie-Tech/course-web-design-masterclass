# 📘 Week 1 — Day 1 Resource Note

## Alphie Tech Responsive Frontend Engineering Masterclass

# 🌐 Introduction to HTML Fundamentals

Welcome to your first frontend engineering lesson.

In this lesson, you will learn the foundational building blocks of every website on the internet using **HTML (HyperText Markup Language).**

By the end of this lesson, you should understand:

* How HTML works
* How web pages are structured
* HTML elements and tags
* Attributes
* Semantic HTML
* Tables
* Forms
* Buttons
* Comments

---

# 📖 What is HTML?

HTML stands for **HyperText Markup Language**.

It is the standard language used to structure webpages.

HTML does **not** create styling or animations.

Instead, HTML defines:

* headings
* paragraphs
* images
* links
* buttons
* forms
* sections
* layouts

Think of HTML as the **skeleton of a website**.

---

# 🧱 Basic Structure of an HTML Document

```html id="xy2v8t"
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Website</title>
</head>
<body>

    <h1>Welcome to My Website</h1>
    <p>This is my first webpage.</p>

</body>
</html>
```

---

# 🧠 Explanation of the Structure

| Tag               | Purpose                         |
| ----------------- | ------------------------------- |
| `<!DOCTYPE html>` | Declares this document as HTML5 |
| `<html>`          | Root element of the webpage     |
| `<head>`          | Contains metadata and settings  |
| `<body>`          | Contains visible content        |

---

# 🏷️ HTML Elements

An HTML element usually consists of:

```html id="3z7kql"
<tagname>Content</tagname>
```

Example:

```html id="6q9nwo"
<p>This is a paragraph</p>
```

---

# 🔤 Common HTML Elements

## Headings

```html id="d4tq6g"
<h1>Main Heading</h1>
<h2>Sub Heading</h2>
<h3>Smaller Heading</h3>
```

---

## Paragraph

```html id="fzfrpj"
<p>This is a paragraph.</p>
```

---

## Links

```html id="j4xg3n"
<a href="https://google.com">Visit Google</a>
```

---

## Images

```html id="ej7n0d"
<img src="image.jpg" alt="A beautiful image">
```

---

## Lists

### Unordered List

```html id="gqk4dn"
<ul>
    <li>HTML</li>
    <li>CSS</li>
    <li>JavaScript</li>
</ul>
```

### Ordered List

```html id="m2lh9v"
<ol>
    <li>Wake up</li>
    <li>Code</li>
    <li>Sleep</li>
</ol>
```

---

# 🧩 HTML Attributes

Attributes provide additional information about HTML elements.

They are written inside the opening tag.

---

# 📌 Syntax of Attributes

```html id="r6h2pk"
<tagname attribute="value">Content</tagname>
```

---

# ✅ Common HTML Attributes

| Attribute | Purpose                     |
| --------- | --------------------------- |
| `href`    | Specifies link destination  |
| `src`     | Specifies image source      |
| `alt`     | Alternative text for images |
| `class`   | Adds reusable styling hooks |
| `id`      | Gives unique identity       |
| `title`   | Tooltip text                |
| `target`  | Specifies where link opens  |

---

# 📌 Attribute Examples

## href

```html id="wt6mk7"
<a href="https://github.com">GitHub</a>
```

---

## target

```html id="qbn5zu"
<a href="https://github.com" target="_blank">
    Open GitHub
</a>
```

`_blank` opens the link in a new tab.

---

## class and id

```html id="m4lf0s"
<p class="text">Hello World</p>

<section id="hero">
    Welcome
</section>
```

---

## alt Attribute

```html id="1d7vkg"
<img src="student.jpg" alt="Student smiling">
```

The `alt` attribute improves accessibility.

---

# 💬 HTML Comments

Comments are notes written inside code that browsers ignore.

Useful for:

* reminders
* explanations
* organizing sections

---

# 📌 Comment Syntax

```html id="4l9vcn"
<!-- This is a comment -->
```

---

# ✅ Example

```html id="7w3pmd"
<!-- Navigation starts here -->
<nav>
    <a href="#">Home</a>
</nav>
```

---

# 🔘 HTML Buttons

Buttons allow users to perform actions.

---

# 📌 Basic Button

```html id="h2nq8e"
<button>Click Me</button>
```

---

# 📌 Button Inside a Link

```html id="d8mv4w"
<a href="https://github.com">
    <button>Visit GitHub</button>
</a>
```

---

# 📌 Button Types

| Type     | Purpose            |
| -------- | ------------------ |
| `button` | General purpose    |
| `submit` | Submits forms      |
| `reset`  | Resets form fields |

---

# 📝 HTML Forms

Forms collect user information.

Examples:

* login forms
* registration forms
* contact forms

---

# 📌 Basic Form Structure

```html id="u2g7pl"
<form>

</form>
```

---

# 📌 Input Field

```html id="p4f0ke"
<input type="text">
```

---

# 📌 Label Element

```html id="xt8bqm"
<label for="name">Name</label>
<input type="text" id="name">
```

Labels improve accessibility.

---

# 📌 Common Input Types

| Input Type | Purpose             |
| ---------- | ------------------- |
| `text`     | Text input          |
| `email`    | Email address       |
| `password` | Password field      |
| `number`   | Numeric input       |
| `date`     | Date selection      |
| `checkbox` | Multiple selections |
| `radio`    | Single selection    |

---

# 📌 Complete Form Example

```html id="6lx0am"
<form>

    <label for="fullname">Full Name</label>
    <input type="text" id="fullname">

    <br><br>

    <label for="email">Email</label>
    <input type="email" id="email">

    <br><br>

    <label for="password">Password</label>
    <input type="password" id="password">

    <br><br>

    <button type="submit">Register</button>

</form>
```

---

# 📊 HTML Tables

Tables display data in rows and columns.

---

# 📌 Basic Table Structure

```html id="mx2r1j"
<table>

</table>
```

---

# 📌 Table Elements

| Element   | Purpose       |
| --------- | ------------- |
| `<table>` | Creates table |
| `<tr>`    | Table row     |
| `<th>`    | Table heading |
| `<td>`    | Table data    |

---

# 📌 Example Table

```html id="4tq8fd"
<table border="1">

    <tr>
        <th>Name</th>
        <th>Course</th>
        <th>Level</th>
    </tr>

    <tr>
        <td>John</td>
        <td>Frontend</td>
        <td>Beginner</td>
    </tr>

    <tr>
        <td>Sarah</td>
        <td>React</td>
        <td>Intermediate</td>
    </tr>

</table>
```

---

# 🧭 Semantic HTML Elements

Semantic HTML gives meaning to webpage structure.

This improves:

* accessibility
* SEO
* code readability
* maintainability

---

# ❌ Non-semantic Example

```html id="r4nv6k"
<div>
    <div>
        <div>Content</div>
    </div>
</div>
```

This tells us nothing about the content.

---

# ✅ Semantic Example

```html id="gx0w7m"
<header>
    <nav></nav>
</header>

<main>
    <section>
        <article></article>
    </section>
</main>

<footer></footer>
```

This structure is meaningful and professional.

---

# 📌 Common Semantic Elements

| Element     | Purpose             |
| ----------- | ------------------- |
| `<header>`  | Top section         |
| `<nav>`     | Navigation links    |
| `<main>`    | Main content        |
| `<section>` | Content section     |
| `<article>` | Independent content |
| `<aside>`   | Sidebar content     |
| `<footer>`  | Bottom section      |

---

# 📌 Example Semantic Layout

```html id="2o7lkr"
<body>

    <header>
        <h1>My Blog</h1>
    </header>

    <nav>
        <a href="#">Home</a>
        <a href="#">About</a>
    </nav>

    <main>

        <section>
            <h2>Latest Articles</h2>

            <article>
                <h3>Learning HTML</h3>
                <p>HTML is the foundation of web development.</p>
            </article>

        </section>

    </main>

    <footer>
        <p>Copyright 2026</p>
    </footer>

</body>
```

---

# 🧠 Best Practices for Beginners

✅ Use semantic HTML whenever possible
✅ Indent your code properly
✅ Use meaningful names
✅ Always include `alt` for images
✅ Keep code organized
✅ Use comments carefully
✅ Avoid unnecessary nesting

---

# ⚠️ Common Beginner Mistakes

❌ Forgetting closing tags
❌ Incorrect file paths
❌ Using too many `<br>` tags
❌ Confusing `id` and `class`
❌ Poor indentation
❌ Forgetting quotes around attributes

---

# 🏁 Conclusion

HTML is the foundation of frontend engineering.

Every website — from simple blogs to advanced applications — starts with HTML structure.

Mastering HTML properly will make learning CSS, JavaScript, React, and modern frameworks much easier.

Your goal this week is not speed.

Your goal is:

* understanding structure
* writing clean code
* thinking like a developer

Build consistently. Improve gradually.
