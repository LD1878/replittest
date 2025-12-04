# JURO Spain SCSS Design System - Export for GitHub

This folder contains all the files from the professional UX design system, flattened for easy transfer to your GitHub repo.

## File List (19 files total)

| # | Export Filename | Copy To | Description |
|---|-----------------|---------|-------------|
| 1 | `SCSS_01_variables.scss` | `_sass/_variables.scss` | Design tokens (colors, spacing, typography) |
| 2 | `SCSS_02_mixins.scss` | `_sass/_mixins.scss` | Reusable SCSS patterns |
| 3 | `SCSS_03_base.scss` | `_sass/_base.scss` | Reset and base typography |
| 4 | `SCSS_04_layout.scss` | `_sass/_layout.scss` | Grid and layout utilities |
| 5 | `SCSS_05_header.scss` | `_sass/_header.scss` | Navigation styles |
| 6 | `SCSS_06_hero.scss` | `_sass/_hero.scss` | Hero section |
| 7 | `SCSS_07_buttons.scss` | `_sass/_buttons.scss` | Button components |
| 8 | `SCSS_08_cards.scss` | `_sass/_cards.scss` | Card components |
| 9 | `SCSS_09_forms.scss` | `_sass/_forms.scss` | Form elements |
| 10 | `SCSS_10_footer.scss` | `_sass/_footer.scss` | Footer styles |
| 11 | `SCSS_11_animations.scss` | `_sass/_animations.scss` | Animations and transitions |
| 12 | `SCSS_12_utilities.scss` | `_sass/_utilities.scss` | Utility classes |
| 13 | `SCSS_13_blog.scss` | `_sass/_blog.scss` | Blog post styles |
| 14 | `ASSETS_main.scss` | `assets/css/main.scss` | Main stylesheet (imports all partials) |
| 15 | `LAYOUT_default.html` | `_layouts/default.html` | Main page layout |
| 16 | `INCLUDE_head.html` | `_includes/head.html` | Document head (meta, fonts, CSS) |
| 17 | `INCLUDE_header.html` | `_includes/header.html` | Site navigation |
| 18 | `INCLUDE_footer.html` | `_includes/footer.html` | Footer with JS for mobile menu |

## Step-by-Step: How to Add to Your GitHub Repo

### Method 1: Copy Files One by One (Recommended)

1. Open each file in this folder
2. Copy the contents
3. In your GitHub repo, navigate to the destination path
4. Create or edit the file and paste the contents
5. Commit each file

### Method 2: Rename and Upload

1. Download files from this folder
2. Rename each file (remove the prefix):
   - `SCSS_01_variables.scss` → `_variables.scss`
   - `ASSETS_main.scss` → `main.scss`
   - `LAYOUT_default.html` → `default.html`
   - etc.
3. Upload to the correct folders in your repo

## Order to Copy Files

1. **First**: Copy all 13 SCSS files to your `_sass/` folder
2. **Second**: Copy `ASSETS_main.scss` to your `assets/css/main.scss`
3. **Third**: Copy the HTML templates to their respective folders
4. **Finally**: Commit and let GitHub Pages rebuild your site

## Important Notes

- The SCSS uses the Inter font (loaded via Google Fonts in head.html)
- Mobile navigation requires the JavaScript in footer.html
- All colors are controlled in `_variables.scss` for easy customization
- Blog styles included for your blog section
- The design uses your Spanish brand colors: Red (#E30613), Gold (#FFD700), Cream (#FFF8F0)
