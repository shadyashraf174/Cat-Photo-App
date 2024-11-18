# CatPhotoApp HTML Code Documentation 

#### learned it from [freeCodeCamp](https://www.freecodecamp.org/) || See it Live at [CodePen](https://codepen.io/shady-ashraf/pen/MWNdWKa)
###### HTML tags give a webpage its structure. You can use HTML tags to add photos, buttons, and other elements to your webpage. In this course, you'll learn the most common HTML tags by building your own cat photo app.

---
This HTML document creates a simple webpage for a fictional "CatPhotoApp." The page includes various sections, such as cat photos, lists of things cats like and dislike, and a form to submit cat-related information. Here’s a detailed breakdown of each component:

---

#### `<html lang="en">`
The `<html>` element represents the root of the HTML document, with the `lang` attribute set to "en" (English).

---

### `<head>`
The `<head>` section contains metadata and essential information for the document:

- `<meta charset="utf-8">`: Sets the character encoding to UTF-8 for full support of characters and symbols.
- `<title>CatPhotoApp</title>`: Defines the title of the webpage that appears on the browser tab.

---

### `<body>`
The `<body>` contains the main visible content of the webpage. It’s organized into several sections:

---

#### `<main>`
The `<main>` element holds the primary content of the webpage.

1. **Heading**:
   - `<h1>CatPhotoApp</h1>`: A top-level heading displaying the title of the app.

---

### Sections Inside `<main>`

#### 1. **Cat Photos Section**

- **Heading**: `<h2>Cat Photos</h2>` indicates this is a section about cat photos.
- **Paragraphs**:
  - Contains a link `<a>` to a cat image with the text "cute cats."
  - Another `<a>` tag opens the link in a new tab (`target="_blank"`) to a gallery of cat photos.
- **Image**:
  - `<img>` displays an image of a relaxing cat, linked to another webpage.

---

#### 2. **Cat Lists Section**

This section includes unordered and ordered lists that show cats' preferences.

- **Subheadings**:
  - `<h3>Things cats love:</h3>` introduces an unordered list of things cats love.
- **Unordered List (`<ul>`)**:
  - Contains list items (`<li>`) like "cat nip," "laser pointers," and "lasagna."
- **Figure and Figcaption**:
  - `<figure>` element wraps an image and a `<figcaption>`, which captions the image saying "Cats *love* lasagna."

- **Subheadings**:
  - `<h3>Top 3 things cats hate:</h3>` introduces an ordered list of things cats hate.
- **Ordered List (`<ol>`)**:
  - Contains items like "flea treatment," "thunder," and "other cats."
- **Figure and Figcaption**:
  - A second `<figure>` shows an image of multiple cats with a caption, "Cats **hate** other cats."

---

#### 3. **Cat Form Section**

This section provides a form for users to submit information about their cats.

- **Form Element**:
  - `<form action="https://freecatphotoapp.com/submit-cat-photo">`: Specifies the action URL where form data will be submitted.

- **Fieldset and Legend**:
  - Groups related elements within the form for readability.
  
- **Radio Buttons**:
  - Asks if the cat is indoor or outdoor using `<input type="radio">`, and only one option can be selected at a time.
  - Default selection is "Indoor" (`checked` attribute).

- **Checkboxes**:
  - Asks about the cat's personality, allowing multiple options to be selected (Loving, Lazy, Energetic).
  - "Loving" is pre-selected with `checked`.

- **Text Input**:
  - `<input type="text" name="catphotourl" placeholder="cat photo URL" required>`: An input field for users to add a cat photo URL, with `required` making it mandatory to fill.

- **Submit Button**:
  - `<button type="submit">Submit</button>`: A button to submit the form data.

---

### `<footer>`
The footer contains a message about copyright.

- **Paragraph**:
  - `<p>No Copyright - <a href="https://www.freecodecamp.org">freeCodeCamp.org</a></p>` displays a message with a link to freeCodeCamp.

---

### Summary of Elements Used

- **Structural Elements**: `<html>`, `<head>`, `<body>`, `<main>`, `<section>`, `<footer>`
- **Text and Heading Elements**: `<title>`, `<h1>`, `<h2>`, `<h3>`, `<p>`
- **Interactive Elements**: `<form>`, `<input>`, `<button>`
- **List Elements**: `<ul>`, `<ol>`, `<li>`
- **Media Elements**: `<img>`, `<figure>`, `<figcaption>`
- **Links**: `<a>`

![image](https://github.com/user-attachments/assets/5e049992-ffcb-42b3-a289-e66f8010e12e)


This HTML structure provides a user-friendly layout, accessible navigation links, and an organized form for user interaction with the CatPhotoApp page.
