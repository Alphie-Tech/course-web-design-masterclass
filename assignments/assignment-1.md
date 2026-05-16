# Week 1 Cumulative Learning Assignment
## Monday - Friday: Mastering HTML & CSS Fundamentals

**Objective:** Solidify your understanding of HTML and CSS fundamentals through daily progressive exercises. By Friday, you'll have built a complete, styled project that demonstrates mastery of all concepts from Days 1 and 2.

---

## 📅 Monday: HTML Review + Semantic HTML Elements

### Part 1: HTML Foundations Review (30 minutes)

**Task:** Create a file called `monday-html-review.html` with the following requirements:

1. Create a valid HTML5 document with:
   - Proper DOCTYPE declaration
   - `<html lang="en">` tag
   - Complete `<head>` section with:
     - Meta charset (UTF-8)
     - Meta viewport
     - Proper title

2. In the `<body>`, create a structured document that includes:
   - A main heading (`<h1>`)
   - Multiple subheadings (`<h2>`, `<h3>`)
   - At least 3 paragraphs of text
   - An unordered list
   - An ordered list
   - A table with at least 3 rows and 3 columns
   - An image with descriptive alt text
   - Hyperlinks to at least 2 websites

**Review Questions:**
- Why is the `<meta charset="UTF-8">` tag important?
- What is the purpose of the `alt` attribute on images?
- How do search engines use heading tags?

### Part 2: Semantic HTML (30 minutes)

**Task:** Read the following sections from [MDN HTML Documentation](https://developer.mozilla.org/en-US/docs/Web/HTML):
- Semantic HTML section
- HTML Semantic Elements article

Then, create a file called `monday-semantic.html` that includes these semantic elements:

- `<header>` - Page header section
- `<nav>` - Navigation menu
- `<main>` - Main content area
- `<article>` - Article or blog post content
- `<section>` - Themed grouping of content
- `<aside>` - Sidebar or supplementary content
- `<footer>` - Page footer

**Requirements:**
- Use at least 5 of these semantic elements correctly
- Add meaningful content to each section
- Include comments explaining why each element is semantic

**Reflection:**
- What is the difference between `<div>` and `<section>`?
- When should you use `<article>` vs `<section>`?
- How do semantic elements help with accessibility?

---

## 🎨 Tuesday: CSS Selectors Mastery

### Part 1: All CSS Selector Types (1 hour)

**Task:** Create a file called `tuesday-selectors.html` with an internal `<style>` tag that demonstrates and practices ALL selector types:

**Include examples of:**

1. **Element Selector** - Style all `<p>` tags with a specific color
2. **Class Selector** - Create 3 classes (.primary, .secondary, .highlight) and use them
3. **ID Selector** - Create 1 ID (#main-content) and style it
4. **Descendant Selector** - Style `<p>` tags only inside a specific container
5. **Child Selector** - Style direct children only (e.g., `div > p`)
6. **Attribute Selector** - Style elements based on attributes:
   - `[type="text"]` - style text inputs
   - `[href*="example"]` - style links containing "example"
7. **Pseudo-classes:**
   - `:hover` - style on mouse hover
   - `:focus` - style when focused
   - `:nth-child(n)` - style specific children
   - `:first-child` and `:last-child`
8. **Pseudo-elements:**
   - `::first-letter`
   - `::before` and `::after`
9. **Combinator Selectors:**
   - Adjacent sibling selector (`+`)
   - General sibling selector (`~`)

**Requirements:**
- Each selector type must be clearly labeled with a comment
- HTML content must demonstrate the selector being applied
- Use meaningful colors and styling to make the effects visible

**Practice Exercise:**
Create a simple blog post HTML structure and use various selectors to style:
- Visited vs unvisited links differently
- Alternate row colors in a table
- First paragraph with larger font

---

## 🏗️ Wednesday: HTML Forms & Input Elements

### Part 1: Form Fundamentals (45 minutes)

**Task:** Read [MDN HTML Forms Documentation](https://developer.mozilla.org/en-US/docs/Learn/Forms)

Then create a file called `wednesday-forms.html` that includes a comprehensive form with:

**Essential Elements:**
- `<form>` wrapper with action and method attributes
- Text input (`<input type="text">`)
- Email input (`<input type="email">`)
- Password input (`<input type="password">`)
- Number input (`<input type="number">`)
- Date input (`<input type="date">`)
- Textarea for longer text
- Select dropdown with multiple `<option>` elements
- Radio buttons (at least 2 options)
- Checkboxes (at least 3 options)
- Submit button
- Reset button
- Labels associated with each form element using `<label>` and `for` attribute

**Requirements:**
- All form elements must have proper `<label>` tags
- Use `name` attributes on all inputs
- Add `placeholder` text to at least 3 inputs
- Include `required` attribute on at least 2 fields
- Use `maxlength` on at least one text input

**Part 2: Form Styling (45 minutes)

**Task:** Create a file called `wednesday-forms-styled.html` and style the form with CSS to make it:

- Professional and clean looking
- Include padding and margin for spacing
- Style form labels, inputs, and buttons
- Add hover effects to buttons
- Use a background color for the form container
- Style the inputs with borders and focus states
- Make the submit button stand out with a different color
- Use flexbox or grid to organize form layout (if you've learned it)

**Bonus Challenge:**
- Add a success message that displays when form is submitted (using HTML only for now)
- Style form validation feedback

---

## 🎯 Thursday: Advanced CSS & The Box Model Deep Dive

### Part 1: Box Model Mastery (1 hour)

**Task:** Create a file called `thursday-box-model.html` with internal CSS demonstrating:

**Create 4 different card designs to show:**

1. **Card 1: Understanding Margin**
   - Multiple cards with different margins to show outer spacing
   - Demonstrate margin collapse
   - Use negative margins (advanced)

2. **Card 2: Understanding Padding**
   - Various padding sizes
   - Show how padding affects clickable areas
   - Create a button with generous padding

3. **Card 3: Borders & Border-Radius**
   - Different border styles (solid, dashed, dotted, double)
   - Different border widths
   - Border-radius for rounded corners
   - Box-shadow for depth

4. **Card 4: Width & Height**
   - Fixed width/height
   - Max-width and min-width concepts
   - How content overflow is handled

**Requirements:**
- Add visual guides or comments showing padding/margin/border areas
- Include shorthand properties (e.g., `margin: 10px 20px;`)
- Demonstrate edge cases and common mistakes

### Part 2: Advanced CSS Techniques (1 hour)

**Task:** Create a file called `thursday-advanced-css.html` demonstrating:

**1. Display Properties:**
- Block display behavior
- Inline vs inline-block
- How each affects layout

**2. Background Properties:**
- Background colors
- Background images
- Background gradients (linear-gradient, radial-gradient)
- Background size, position, and repeat

**3. Text Styling Advanced:**
- Text decoration (underline, overline, line-through)
- Text shadow
- Letter spacing and line height
- Text transform (uppercase, lowercase, capitalize)

**4. Transitions & Transformations (Introduction):**
- CSS transitions on hover
- Basic scale and rotate transforms
- Opacity changes

**Requirements:**
- Create visual demonstrations for each technique
- Include comments explaining what each property does
- Show before/after effects

---

## 🚀 Friday: Capstone Project - Personal Portfolio Card

### Objective
Create a complete, professionally styled personal portfolio card that demonstrates mastery of all HTML and CSS concepts from Days 1 and 2.

### Requirements

**Part 1: Project Structure (30 minutes)**

Create a project folder with:
```
portfolio-card/
├── index.html
├── style.css
├── assets/
│   └── (images folder)
```

**Part 2: HTML Structure (30 minutes)**

Your `index.html` should include:

1. **Semantic HTML Structure:**
   - `<header>` section
   - `<main>` section with content
   - `<footer>` section

2. **Content Requirements:**
   - A profile image (can use a placeholder)
   - Your name as main heading
   - A brief bio/about section
   - Skills section (use a list)
   - A contact form with:
     - Name field
     - Email field
     - Message textarea
     - Submit button
   - Links to social media or projects
   - Footer with copyright information

3. **HTML Best Practices:**
   - Proper semantic elements
   - All images have alt text
   - All form inputs have labels
   - Proper heading hierarchy
   - Well-organized and readable code

**Part 3: CSS Styling (1 hour)**

Style your portfolio card to be:

1. **Professional & Visually Appealing:**
   - Cohesive color scheme (pick 2-3 main colors)
   - Good typography (readable fonts, appropriate sizes)
   - Proper spacing using margin and padding
   - Clean layout with good visual hierarchy

2. **Box Model Implementation:**
   - Proper margins between sections
   - Padding inside containers
   - Borders and border-radius for cards
   - Box shadows for depth

3. **Interactive Elements:**
   - Hover effects on buttons
   - Hover effects on links
   - Focus states on form inputs
   - Smooth transitions

4. **Responsive Basics:**
   - Ensure it looks good at different screen sizes
   - Use `width: 100%` where appropriate
   - Mobile-friendly padding and margins

5. **Advanced CSS (Optional):**
   - Use gradients for backgrounds
   - Add transitions to interactive elements
   - Use CSS transforms for effects

### Part 4: Quality Checklist (15 minutes)

Before submitting, verify:

**HTML:**
- ✅ Valid HTML5 with proper DOCTYPE
- ✅ All required semantic elements present
- ✅ All images have alt attributes
- ✅ All form inputs have associated labels
- ✅ Code is properly indented
- ✅ No syntax errors

**CSS:**
- ✅ External stylesheet properly linked
- ✅ Box model properties correctly applied
- ✅ At least 3 different selector types used
- ✅ Consistent color scheme throughout
- ✅ Hover/focus states implemented
- ✅ No conflicting or redundant styles

**User Experience:**
- ✅ Content is readable and clear
- ✅ Form is functional and labeled
- ✅ Links are distinguishable
- ✅ Buttons are easily clickable
- ✅ Overall design is professional

### Bonus Challenges (Optional)

1. **Add a navigation bar** with links to different sections
2. **Create alternate color schemes** using CSS custom properties (variables)
3. **Add a project gallery section** with multiple portfolio items styled as a grid
4. **Implement CSS animations** like fade-in effects on page load
5. **Add a testimonial section** with styled quote elements
6. **Create a skills progress bar** using CSS (visual styling only)

---

## 📚 Learning Resources to Reference Throughout the Week

- [MDN HTML Reference](https://developer.mozilla.org/en-US/docs/Web/HTML)
- [MDN CSS Reference](https://developer.mozilla.org/en-US/docs/Web/CSS)
- [MDN Semantic HTML](https://developer.mozilla.org/en-US/docs/Glossary/Semantic_HTML)
- [MDN CSS Selectors](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Selectors)
- [MDN CSS Box Model](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Box_Model)
- [MDN HTML Forms](https://developer.mozilla.org/en-US/docs/Learn/Forms)

---

## 🎓 Mastery Checklist

By the end of Friday, you should be able to:

### HTML Concepts
- ✅ Write valid, semantic HTML5 documents
- ✅ Use all major heading levels appropriately
- ✅ Create lists (ordered, unordered, definition lists)
- ✅ Embed images with proper alt text
- ✅ Create and structure tables
- ✅ Build functional forms with various input types
- ✅ Use semantic elements (`<header>`, `<nav>`, `<main>`, `<article>`, `<section>`, `<aside>`, `<footer>`)
- ✅ Create navigation menus with links

### CSS Concepts
- ✅ Use element, class, ID, and attribute selectors
- ✅ Understand specificity and selector precedence
- ✅ Apply colors using names, HEX, and RGB
- ✅ Control typography (font-family, font-size, font-weight, line-height)
- ✅ Use the CSS Box Model (margin, border, padding, content)
- ✅ Implement spacing for professional layouts
- ✅ Style buttons, links, and form elements
- ✅ Create hover effects and pseudo-classes
- ✅ Use pseudo-elements for advanced styling
- ✅ Understand display properties (block, inline, inline-block)
- ✅ Create cohesive designs with color schemes
- ✅ Make interfaces responsive and accessible

---

## 📝 Submission Guidelines

1. **Organize your work:**
   - Create a `week-1-assignments` folder
   - Place each day's work in separate subfolders (monday/, tuesday/, etc.)
   - Place friday's capstone project in its own folder

2. **File naming:**
   - Use lowercase, descriptive names
   - Use hyphens instead of spaces (e.g., `thursday-box-model.html`)

3. **Code quality:**
   - Properly indent all code
   - Use meaningful class and ID names
   - Add comments for complex sections
   - Use external CSS for larger projects

4. **Testing:**
   - Open all files in a browser
   - Test all interactive elements
   - Check for visual consistency

---

## 🏆 Success Criteria

**Excellent Completion:**
- All daily assignments completed with quality code
- Capstone project is polished and professional-looking
- Code demonstrates understanding of HTML and CSS concepts
- Form elements are properly labeled and accessible
- Consistent visual design throughout the project
- No broken links or missing images

**Good Completion:**
- Most assignments completed
- Core concepts demonstrated
- Code is functional and readable

**Needs Improvement:**
- Incomplete assignments
- Code has syntax errors
- Concepts not yet mastered

---

## 💡 Tips for Success

1. **Read the documentation** - Don't just copy code. Understand *why* things work.
2. **Practice daily** - Spend consistent time each day on these assignments.
3. **Use browser developer tools** - Right-click and "Inspect" to see how styles are applied.
4. **Experiment** - Try changing values to see what happens.
5. **Test frequently** - Check your work in the browser after each change.
6. **Ask questions** - If something doesn't make sense, research it!
7. **Review previous work** - Look back at what you've learned to reinforce concepts.
8. **Don't copy-paste blindly** - Type out code to build muscle memory.

---

## 📞 Common Questions

**Q: Can I use online resources to help with the assignments?**
A: Yes! Use MDN, CSS-Tricks, and other learning resources. Just make sure you understand what you're writing.

**Q: Do I need to make the projects look fancy?**
A: No. Focus on learning the concepts first. Visual polish comes with practice.

**Q: What if I get stuck?**
A: Review the Day 1 and Day 2 notes, check MDN documentation, and try breaking the problem into smaller pieces.

**Q: Should I use frameworks like Bootstrap?**
A: Not yet. Master plain HTML and CSS first. Frameworks will be easier to learn later.

---

**Good luck with your assignments! By Friday, you'll have a solid foundation in HTML and CSS. 🚀**
