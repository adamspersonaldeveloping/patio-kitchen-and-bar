## Credits

- **Patio Kitchen & Bar** for original content and images
- **Unsplash.com** for high-quality stock photos (licensed under the Unsplash License)

## Notes

- Please optimize any new images before adding them (recommended: 1200px max width, JPEG/WebP format).
- For SEO, make sure to update the meta titles and descriptions in each HTML file.
- For any content updates (like menus, events, or announcements), edit the appropriate sections in the HTML.

## How to Update Content

If you want to update the text or images on the website, here’s a simple guide:

### 1. **Updating Text (e.g., Menu, About Section, etc.):**

- Open the `index.html` file in a text editor (e.g., Sublime Text, VS Code, etc.).
- Scroll to the section you want to update (look for sections labeled with comments like `<!-- About Section -->` or `<!-- Menu Section -->`).
- Simply edit the text between the `<p>` or `<h1>` tags.
- Save the file once you’re done.

### 2. **Adding or Changing Photos:**

- **Upload New Images**:
  - Place your new photos in the `/images/patio-photos/` folder for original Patio images, or `/images/unsplash-photos/` for stock images.
  - Ensure the photo is optimized (under 1MB, 1200px max width, JPEG or WebP format).
- **Update Image References**:
  - In `index.html`, look for `<img src="...">` tags.
  - Change the `src` to match the name of your new image (e.g., `<img src="images/patio-photos/new-photo.jpg">`).
- **Changing Image Sizes**:
  - You can adjust the size directly in HTML by adding `width` and `height` attributes like this: `<img src="image.jpg" width="600" height="400">`.

### 3. **Adding New Sections (e.g., Blog, Specials, Events):**

- Simply copy a section of HTML code from another part of the page.
- Paste it where you want the new section to appear.
- Customize the content as needed — add new images, text, or links.

### 4. **Publish Changes:**

- Once you’re happy with the updates, upload the modified files to your web hosting platform (e.g., via FTP, GitHub, or drag-and-drop into a service like Netlify or Vercel).

---

## Deployment

Since it’s a static site, just drag and drop it into your hosting platform, or push it to GitHub and connect it to your host.

---

**Built with love (and cold drinks) for the team at Patio 🍻**
