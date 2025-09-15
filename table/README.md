# Styling, Spanning, and Responsive Layout with HTML & CSS

Demonstrating styling, spanning, and responsive table layout techniques using pure **HTML** and **CSS**.

---

### 1. **Employee Data Table**

A styled table with:

* **`colspan`**: Merges two header cells for "Name"
* **Custom Borders**: Using `border-style: dotted`
* **Hover Effect**: Change row background color on hover
* **Alternating Colors**: Different background for even rows/columns
* **Center Aligned**: Using `margin: 0 auto;`

```html
<table style="border-collapse: collapse; margin: 0 auto;">
  <tr>
    <th colspan="2">Name</th>
    <th>Department</th>
    <th>Email</th>
  </tr>
  <tr>
    <td>John</td>
    <td>Doe</td>
    <td>IT</td>
    <td>john@example.com</td>
  </tr>
  <tr>
    <td>Jane</td>
    <td>Smith</td>
    <td>HR</td>
    <td>jane@example.com</td>
  </tr>
</table>

<style>
table, th, td {
  border: 1px dotted black;
  padding: 8px;
  text-align: center;
}
tr:hover {
  background-color: #D6EEEE;
}
tr:nth-child(even) {
  background-color: #f2f2f2;
}
th {
  background-color: #ccc;
}
</style>
```

---

### 2. **Vertical Table (Definition Style)**

A simple 2-column vertical layout table for displaying details:

* Department
* Contact
* Address

```html
<table style="border: 1px solid #ccc; margin: 0 auto;">
  <tr>
    <th>Dept</th>
    <td>IT</td>
  </tr>
  <tr>
    <th>Contact</th>
    <td>+91 9876543210</td>
  </tr>
  <tr>
    <th>Address</th>
    <td>123 Main Street, Coimbatore</td>
  </tr>
</table>
```

---

### 3. **Row Spanning**

Demonstrating `rowspan` where one cell spans multiple rows:

```html
<table border="1" style="border-collapse: collapse; margin: 0 auto;">
  <tr>
    <th rowspan="3">Name</th>
    <td>John</td>
  </tr>
  <tr>
    <td>Jane</td>
  </tr>
  <tr>
    <td>Smith</td>
  </tr>
</table>
```

---

### 4. **Colgroup Styling**

Using `<colgroup>` to style entire column groups (ideal for calendar-like tables):

```html
<table border="1" style="border-collapse: collapse; margin: 0 auto;">
  <colgroup>
    <col span="4" style="background-color: #87c5c5">
    <col span="3" style="background-color: #c17cde">
  </colgroup>
  <tr>
    <th>Mon</th>
    <th>Tue</th>
    <th>Wed</th>
    <th>Thu</th>
    <th>Fri</th>
    <th>Sat</th>
    <th>Sun</th>
  </tr>
  <tr>
    <td>1</td>
    <td>2</td>
    <td>3</td>
    <td>4</td>
    <td>5</td>
    <td>6</td>
    <td>7</td>
  </tr>
</table>
```
