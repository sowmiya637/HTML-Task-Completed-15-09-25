 styling, spanning, responsive layout techniques, and more using pure HTML and CSS.

### 1.  Employee Data Table

A styled table with:

- `colspan`: Merges two header cells for "Name"
- `border-style: dotted`: Custom borders
- Hover effect using `:hover` on rows
- Alternating background color for even rows and columns
- Center-aligned table using `margin: 0 auto;`

```html
<th colspan="2">Name</th>
<tr>:hover { background-color: #D6EEEE; }

### 2. Vertical Table (Definition Style)

Simple 2-column vertical layout where the left column is a label and the right column is content.

<tr>
  <th>Dept</th>
  <td>IT</td>
</tr>

Used for displaying details like:

Department
Contact
Address

### 3. Row Spanning

Table with a cell that spans multiple rows using rowspan.
<th rowspan="3">Name</th>
Used when a single header applies to multiple entries beneath it.

### 4.  Colgroup Styling

A calendar-style table demonstrating the use of <colgroup> to apply different background colors for grouped columns.

<colgroup>
  <col span="4" style="background-color: #87c5c5">
  <col span="3" style="background-color: #c17cde">
</colgroup>
This allows for styling entire columns without applying styles individually to each <td>.
