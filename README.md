# Professor Messer's CompTIA A+ (220-1101) Study Notes

This repository contains my personal study notes for Professor Messer's CompTIA A+ Core 1 (220-1101) video course. The notes are structured as a simple, clean, and offline-accessible website, making it easy to study on any device with a web browser.

## ✨ Features

*   **Clean & Minimalist Design:** A simple, distraction-free layout that focuses on readability.
*   **External CSS:** The entire visual style is controlled by two CSS files, making it easy to update the look of all pages at once.
*   **Responsive Layout:** The design works well on both desktop and mobile browsers.
*   **Easy Navigation:** A central index page links to all lessons, and each lesson page has "Previous" and "Next" buttons for sequential studying.
*   **Ready for Expansion:** The template-based structure makes it simple to add new lessons as you progress through the course.

## 📂 File Structure

The repository is organized to be as simple and maintainable as possible.

.
├── README.md # You are here!
├── index.html # The main table of contents page for all notes.
├── index-style.css # The stylesheet for ONLY the index.html page.
├── style.css # The stylesheet for ALL individual lesson note pages.
├── template.html # The base template for creating new lesson notes.
├── 1.1.html # The notes for lesson 1.1.
├── 1.2.html # The notes for lesson 1.2.
└── ... # etc.

code
Code
download
content_copy
expand_less
IGNORE_WHEN_COPYING_START
IGNORE_WHEN_COPYING_END
*   `index.html`: The homepage. **This is the file you will update every time you add a new lesson.**
*   `style.css`: The single CSS file that styles every lesson page (e.g., `1.1.html`, `1.2.html`, etc.).
*   `index-style.css`: A separate CSS file just for the homepage to keep its layout distinct.
*   `template.html`: A blank template you can copy to create a new lesson page.

## 🚀 How to Add a New Lesson

Follow these steps to add notes for a new video. Let's assume you are adding notes for **Lesson 1.2**.

### Step 1: Create the New Lesson File

1.  Make a copy of `template.html`.
2.  Rename the copy to match the new lesson number (e.g., `1.2.html`).

### Step 2: Add Your Content

Open the new `1.2.html` file in a text editor and update the following sections:
1.  **Update the `<title>`:** Change `<title>Lesson Title - A+ Core 1 (X.X)</title>` to `<title>Mobile Device Displays - A+ Core 1 (1.2)</title>`.
2.  **Update the Header:** Change the `<h1>` and `<p>` tags to reflect the new lesson's title and number.
3.  **Add the Notes:** Replace the placeholder content inside the `.section` divs with your detailed notes from the video. You can copy and paste the `<div class="section">...</div>` block as many times as you need for different topics within the video.
4.  **Update Navigation Buttons:** In the footer, update the `href` links for the "Previous" and "Next" buttons.
    *   The "Previous" button should link to `1.1.html`.
    *   The "Next" button should link to `1.3.html`.

### Step 3: Update the Index Page

Finally, open `index.html` and add a link to your newly created page. Find the correct topic section (e.g., `1.0 Mobile Devices`) and add a new list item:

```html
<!-- Inside index.html -->
<div class="topic-section">
    <h2>1.0 Mobile Devices</h2>
    <ul class="subtopic-list">
        <li><a href="1.1.html">1.1 Laptop Hardware</a></li>
        <!-- Add this new line -->
        <li><a href="1.2.html">1.2 Mobile Device Displays</a></li> 
    </ul>
</div>

That's it! Your new notes are now integrated into the site.

🎨 Customization

The visual style can be easily changed by editing the CSS variables at the top of style.css and index-style.css.

code
Css
download
content_copy
expand_less
IGNORE_WHEN_COPYING_START
IGNORE_WHEN_COPYING_END
:root {
    --bg-color: #ffffff;
    --text-color: #212529;
    --heading-color: #343a40;
    --accent-color: #007bff;
    --subtle-border-color: #dee2e6;
    --highlight-bg-color: #f1f3f5;
}
🙏 Acknowledgements

These notes are based entirely on the excellent content created by Professor Messer. This project is for personal study and is not affiliated with Professor Messer in any way.

Professor Messer's Website

Professor Messer's YouTube Channel

code
Code
download
content_copy
expand_less
IGNORE_WHEN_COPYING_START
IGNORE_WHEN_COPYING_END
