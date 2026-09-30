[README.md](https://github.com/user-attachments/files/32880074/README.md)
# Ours, on what terms?

PLS 210 · Presentation 1 · Nazarbayev University · Fall 2026

A single-page, horizontally scrolling slide deck. Everything is in `index.html`:
inline CSS, JS and SVG, with no build step and no frameworks. The only external
resource is Google Fonts.

## Publish with GitHub Pages

1. Create a new GitHub repository and upload `index.html` and this `README.md`
   to the `main` branch, in the repository root.
2. In the repository, open **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to **Deploy from a branch**.
4. Choose branch **main** and folder **/ (root)**, then click **Save**.
5. After a minute or two the site is live at
   `https://<your-username>.github.io/<repository-name>/`.

Link to a single slide by adding its number to the URL, for example `…/#slide-3`.

## Presenting

| Action         | Keys / input                                          |
| -------------- | ----------------------------------------------------- |
| Next slide     | → · Space · Page Down · mouse wheel · swipe left      |
| Previous slide | ← · Shift+Space · Page Up · mouse wheel · swipe right |
| First / last   | Home / End                                            |
| Jump to slide  | click a tick on the bottom line                       |

The browser back button returns to the previous slide.

## Editing

- All slide text is in `index.html` between the comments
  `✏️ SLIDE CONTENT` and `✏️ SLIDE CONTENT ENDS HERE`. Each slide is one
  `<section>` marked with a comment like `<!-- ===== SLIDE 3: RESEARCH QUESTION ===== -->`.
- Placeholders such as `[Your name]` are highlighted in yellow. Replace the whole
  `<mark class="ph">…</mark>` element with your own text.
- To add or remove a slide, copy or delete a `<section class="slide">` block and
  give each section a unique `id="slide-N"`. The tennis-ball indicator updates
  on its own.
