# Week 3: HTML Foundations - Detailed Notes

## Session 1: HTML Basics & Document Structure

### Introduction to HTML
HTML (**HyperText Markup Language**) is the foundation of web development. It structures content on a webpage using elements and tags.

### Basic HTML Document Structure
Every HTML document follows a standard structure:

```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>My First Web Page</title>
</head>
<body>
    <h1>Welcome to My Web Page</h1>
    <p>This is my first webpage. I am learning HTML!</p>
</body>
</html>
```

### Breakdown of Tags:
- `<!DOCTYPE html>` - Declares the document type as HTML5.
- `<html lang="en">` - Root element that contains all HTML content. The `lang` attribute specifies the language of the page.
- `<head>` - Contains metadata (information about the document).
  - `<meta charset="UTF-8">` - Ensures proper text encoding for special characters.
  - `<meta name="viewport" content="width=device-width, initial-scale=1.0">` - Makes the page responsive on different screen sizes.
  - `<title>` - Sets the title shown in the browser tab.
- `<body>` - Holds all visible content of the webpage.
  - `<h1>` - Main heading.
  - `<p>` - Paragraph text.

### Student Activity
Students create a basic HTML page with a title, heading, and paragraph.

---

## Session 2: Working with Headings, Paragraphs, and Text Formatting

### Headings & Paragraphs
Headings structure content into sections:
```html
<h1>Main Heading</h1>
<h2>Subheading</h2>
<h3>Section Title</h3>
<h4>Smaller Title</h4>
<h5>Subtitle</h5>
<h6>Smallest Heading</h6>
```
**Best Practice:** Use `<h1>` only once per page for SEO.

Paragraphs create readable content:
```html
<p>This is a paragraph with some text.</p>
```

### Text Formatting Tags
- **Bold Text:** `<b>Bold</b>` (visual only) vs. `<strong>Strong</strong>` (semantic importance)
- **Italic Text:** `<i>Italic</i>` (visual only) vs. `<em>Emphasized</em>` (semantic importance)
- **Example:**
  ```html
  <p>This is <b>bold</b> and this is <strong>important</strong>.</p>
  <p>This is <i>italic</i> and this is <em>emphasized</em>.</p>
  ```

### Lists
- **Unordered List (`<ul>`)**
  ```html
  <ul>
      <li>HTML</li>
      <li>CSS</li>
      <li>JavaScript</li>
  </ul>
  ```
- **Ordered List (`<ol>`)**
  ```html
  <ol>
      <li>Wake up</li>
      <li>Eat breakfast</li>
      <li>Start learning HTML</li>
  </ol>
  ```

### Student Activity
Students format text and create lists about themselves.

---

## Session 3: Adding Links & Images

### Links (`<a>` Tag)
- **External Links:**
  ```html
  <a href="https://www.w3schools.com" target="_blank">Visit W3Schools</a>
  ```
  - `target="_blank"` opens in a new tab.
- **Internal Links:**
  ```html
  <a href="about.html">About Me</a>
  ```
  - Links to another page within the website.

### Images (`<img>` Tag)
- **Image from Root Folder:**
  ```html
  <img src="myimage.jpg" alt="My Image">
  ```
- **Image from a Subfolder:**
  ```html
  <img src="images/photo.jpg" alt="A Photo">
  ```
- **Image from a URL:**
  ```html
  <img src="https://www.example.com/image.jpg" alt="An Image from the Web">
  ```
- **Setting Image Size:**
  ```html
  <img src="myimage.jpg" width="300" height="200" alt="Resized Image">
  ```
- **Importance of `alt` Attribute:**
  - Describes images for screen readers.
  - Helps when images fail to load.

### Student Activity
Students add different types of links and images to their webpage.

---

## Session 4: Mini Project & Review

### Project Overview: Creating an About Me Page
Students will create a **personal webpage** with:
1. **Title & Heading**
2. **Bio Paragraph**
3. **A List** (hobbies, interests, etc.)
4. **An External Link**
5. **At Least One Image**

### Example Structure:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>About Me</title>
</head>
<body>
    <h1>Hi, I'm [Your Name]!</h1>
    <p>I am learning HTML and building my first webpage.</p>

    <h2>My Hobbies</h2>
    <ul>
        <li>Reading</li>
        <li>Gaming</li>
        <li>Coding</li>
    </ul>

    <a href="https://www.example.com" target="_blank">Visit my favorite website</a>
    <img src="images/myphoto.jpg" alt="A picture of me">
</body>
</html>
```

### Student Activity
- **Students build their own page.**
- **Pair up and review each other’s work.**

### Wrap-Up & Homework
- **Q&A session.**
- **Optional:** Add CSS styles to personalize the page.
- **Pre-reading:** Semantic HTML & Forms.



