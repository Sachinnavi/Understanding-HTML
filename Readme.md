# HTML Tags Categorized by Purpose

HTML tags can be grouped by what they are used for. This helps you understand the structure of a webpage and the role of each element.

---

## 1. Text Content Tags
These tags are used for writing and formatting text.

- `h1` to `h6` — headings
- `p` — paragraph
- `span` — inline text container
- `strong` — important text
- `b` — bold text
- `em` — emphasized text
- `i` — italic text
- `small` — smaller text
- `mark` — highlighted text
- `del` — deleted text
- `ins` — inserted text
- `sub` — subscript
- `sup` — superscript
- `blockquote` — long quotation
- `q` — short quotation
- `cite` — citation
- `code` — code snippet
- `pre` — preformatted text
- `br` — line break
- `hr` — horizontal rule

Example:
```html
<h1>Hello World</h1>
<p>This is <strong>important</strong> text.</p>
```

---

## 2. Link and Navigation Tags
These tags are used to connect pages, files, or sections.

- `a` — hyperlink
- `link` — link to external resources like CSS
- `nav` — navigation section
- `button` — clickable button
- `area` — clickable area inside an image map
- `base` — base URL for relative links

Example:
```html
<a href="https://example.com">Visit Website</a>
<nav>
  <a href="#home">Home</a>
  <a href="#about">About</a>
</nav>
```

---

## 3. Image and Graphic Tags
These tags are used for images, visuals, and graphics.

- `img` — image
- `picture` — image source container
- `source` — multiple image/video/audio sources
- `figure` — image with caption
- `figcaption` — caption for a figure
- `svg` — scalable vector graphics
- `canvas` — drawing area for JavaScript graphics

Example:
```html
<img src="image.jpg" alt="Nature image">
<figure>
  <img src="flower.jpg" alt="Flower">
  <figcaption>A beautiful flower</figcaption>
</figure>
```

---

## 4. Audio and Video Tags
These tags are used for playing media files.

- `audio` — audio player
- `video` — video player
- `source` — media source file
- `track` — subtitles or captions

Example:
```html
<audio controls>
  <source src="song.mp3" type="audio/mpeg">
</audio>

<video controls width="500">
  <source src="movie.mp4" type="video/mp4">
</video>
```

---

## 5. File and Embedded Content Tags
These tags are used for documents, plugins, and embedded files.

- `a download` — downloadable file link
- `object` — embedding external content
- `embed` — external application or file
- `iframe` — embedded webpage or document
- `input type="file"` — file chooser
- `form` — form container

Example:
```html
<a href="report.pdf" download>Download PDF</a>
<input type="file">
<iframe src="https://example.com"></iframe>
```

---

## 6. Map and Geographic Content
These are related to maps or location-based content.

- `map` — image map container
- `area` — clickable region in a map
- `img` — often used with map
- `iframe` — used to embed map services like Google Maps

Example:
```html
<img src="world-map.jpg" usemap="#worldmap">
<map name="worldmap">
  <area shape="rect" coords="0,0,100,100" href="asia.html" alt="Asia">
</map>
```

> For real interactive maps, developers often use `iframe` or JavaScript map APIs.

---

## 7. Form and Input Tags
These tags are used to collect user input.

- `form` — user input form
- `input` — text, password, email, checkbox, radio, file, etc.
- `textarea` — multiline text input
- `label` — label for an input
- `button` — submit or action button
- `select` — dropdown list
- `option` — dropdown option
- `fieldset` — grouped form fields
- `legend` — caption for fieldset

Example:
```html
<form>
  <label for="name">Name:</label>
  <input type="text" id="name" name="name">
  <button type="submit">Submit</button>
</form>
```

---

## 8. Table Tags
Used for displaying structured data in rows and columns.

- `table` — table container
- `tr` — table row
- `th` — table header cell
- `td` — table data cell
- `thead` — table head
- `tbody` — table body
- `tfoot` — table footer
- `caption` — table title
- `colgroup` — column group
- `col` — column definition

Example:
```html
<table>
  <tr>
    <th>Name</th>
    <th>Age</th>
  </tr>
  <tr>
    <td>Ali</td>
    <td>22</td>
  </tr>
</table>
```

---

## 9. Structural and Layout Tags
These tags organize a webpage's structure.

- `div` — generic container
- `section` — standalone section
- `article` — independent content block
- `header` — page or section header
- `footer` — page or section footer
- `main` — main content of the page
- `aside` — related content or sidebar
- `details` — expandable details block
- `summary` — summary of details

Example:
```html
<header>
  <h2>Website Header</h2>
</header>
<main>
  <section>
    <h3>About Us</h3>
    <p>Welcome to our site.</p>
  </section>
</main>
```

---

## 10. List Tags
These tags create ordered or unordered lists.

- `ul` — unordered list
- `ol` — ordered list
- `li` — list item
- `dl` — description list
- `dt` — description term
- `dd` — description details

Example:
```html
<ul>
  <li>HTML</li>
  <li>CSS</li>
  <li>JavaScript</li>
</ul>
```

---

## Quick Summary

- Text: `h1`, `p`, `span`, `strong`
- Image: `img`, `figure`, `svg`
- Link: `a`, `nav`, `link`
- Audio: `audio`, `source`
- Video: `video`, `track`
- File: `a download`, `object`, `embed`, `input type="file"`
- Map/Geographic: `map`, `area`, `iframe`
- Form: `form`, `input`, `button`, `label`
- Table: `table`, `tr`, `th`, `td`
- Structure: `div`, `section`, `header`, `main`

---

This list gives a practical classification of HTML tags based on purpose and use case.
