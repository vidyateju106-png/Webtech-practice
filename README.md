# Web Technology — HTML & CSS Practice

This repository contains beginner-friendly HTML and CSS practice examples demonstrating page structure, styling, layout, positioning, forms, and images.

**Folder Overview**
- **HTML**: Core HTML examples — [HTML/attributes.html](HTML/attributes.html), [HTML/Forms.html](HTML/Forms.html), [HTML/Form table.html](HTML/Form%20table.html), [HTML/Hyperlink.html](HTML/Hyperlink.html), [HTML/index.html](HTML/index.html), [HTML/media.html](HTML/media.html), [HTML/table creation.html](HTML/table%20creation.html)
- **CSS**: Styling demos — [CSS/Boxmodel.html](CSS/Boxmodel.html), [CSS/Displayprop.html](CSS/Displayprop.html), [CSS/demopos.html](CSS/demopos.html), [CSS/Shapes.html](CSS/Shapes.html), [CSS/texta&front&brdrprop.html](CSS/texta&front&brdrprop.html)
- **Image gallery**: Simple gallery examples — [Image gallery/index.html](Image%20gallery/index.html)
- **Webpage**: Example combined page — [Webpage/index.html](Webpage/index.html)

**Purpose**
- Practice fundamental HTML structure and attributes.
- Learn basic CSS selectors, the box model, positioning, and simple shapes.
- Use these examples as learning references or classroom exercises.

**HTML Concepts & Common Attributes**
- **Doctype & Structure**: Use `<!DOCTYPE html>`, `html`, `head`, `meta charset`, and `body`.
- **Links & Media**: `href` (anchors), `src` (images, scripts), `alt` (image alternative text), `title`.
- **Forms**: `action`, `method`, `name`, `type`, `value`, `placeholder`, `required`, `minlength`, `maxlength`, `checked`, `selected`.
- **IDs and Classes**: `id`, `class` for styling and JS hooks.
- **Table Attributes**: `colspan`, `rowspan`, table headers and cells.
- **Missing / Recommended HTML topics**: semantic elements (`header`, `nav`, `main`, `section`, `article`, `footer`), `meta viewport` for responsiveness, ARIA roles and accessibility notes, more input `type`s (`email`, `tel`, `url`, `date`), and client-side validation patterns.

**CSS Concepts & Properties Covered**
- **Box Model**: `margin`, `padding`, `border`, `width`, `height`, `box-sizing`.
- **Display & Visibility**: `display`, `visibility`, `overflow`.
- **Positioning**: `position`, `top`, `left`, `right`, `bottom`, `z-index`.
- **Text & Fonts**: `font-family`, `font-size`, `font-weight`, `color`, `text-align`, `line-height`, `text-decoration`.
- **Shapes & Visuals**: `border-radius`, `transform` (basic), `background-image`, `background-size`.
- **Missing / Recommended CSS topics**: CSS Flexbox and Grid (layout), `gap`, `align-items`, `justify-content`, media queries for responsive design, CSS variables (`--var`), transitions/animations, and `filter` or advanced transforms.

**How to Preview Locally**
- Open any HTML file in a browser by double-clicking or right-click → Open with → Web Browser.
- Recommended files to try first: [Webpage/index.html](Webpage/index.html), [CSS/Boxmodel.html](CSS/Boxmodel.html), [HTML/Forms.html](HTML/Forms.html).

**Suggested Improvements / Learning Steps**
- Add `meta name="viewport" content="width=device-width, initial-scale=1"` to example pages.
- Replace generic layout with semantic containers (`header`, `nav`, `main`, `footer`).
- Add small exercises: convert layout to Flexbox, then to Grid; make pages responsive with media queries.
- Add accessibility notes: meaningful `alt` text, labels tied to inputs, keyboard order, contrast checks.

**Prepare for GitHub (quick guide)**
- Initialize a git repository (if not already), add, commit, and push to a new GitHub repo. Replace `<your-remote-url>` with your repo URL.

```bash
git init
git add .
git commit -m "Initial commit — HTML & CSS practice examples"
git branch -M main
git remote add origin <your-remote-url>
git push -u origin main
```

- Recommended `.gitignore` (simple web projects):
```
# OS files
.DS_Store
Thumbs.db

# VS Code
.vscode/

# Logs
*.log
```

**License / Attribution**
- These are practice examples; add a license if you want to share them publicly (e.g., MIT).

---

If you want, I can:
- Commit and push these changes for you (I will run the git commands if you grant permission), or
- Add basic `.gitignore`, license file, and a short CONTRIBUTING.md with exercises.

Which would you like next?