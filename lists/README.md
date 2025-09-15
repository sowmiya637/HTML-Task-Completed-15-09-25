#  Elements, Lists, Layouts & Embeds

**core HTML concepts** such as lists, block/inline elements, class & id attributes, layout with `<div>`, bookmarks, iframe embedding, and more.

### 1.  Lists

Demonstrates all 3 types of lists in HTML:

- **Ordered List (`<ol>`)** – Numbered steps  
- **Unordered List (`<ul>`)** – Bullet points  
- **Description List (`<dl>`)** – Terms and definitions  

Also includes a **nested list** with mixed list types inside another list.

### 2.  Block-level vs Inline Elements

**Block-level elements**:
- `<div>`, `<p>`, `<h1>` to `<h6>` — start on a new line, occupy full width.

**Inline elements**:
- `<span>`, `<code>`, `<b>`, `<i>` — stay within the line, take only as much space as needed.

---

### 3.  Code Representation

- Uses `<code>` element to display HTML tags as text  
  Example:  
  ```html
  <code>&lt;b&gt;</code>

### 4. Div Layout & Side-by-Side Content

Using CSS float:

.mycontainer div {
  width: 33%;
  float: left;
}

Displays three <div> sections (London, India, Rome) side by side.

### 5.HTML Bookmarks

Jump to a section using anchor + id attribute:

<a href="#section11">Jump to Section 11</a>


Scrolls to:

<h2 id="section11">Section 11</h2>
