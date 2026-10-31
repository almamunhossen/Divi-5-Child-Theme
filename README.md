# Divi Child Theme

A child theme for the Divi theme by Elegant Themes.

- **Version:** 1.0.0
- **Author:** [Al Mamun Hossen](https://almamunhossen.com)
- **Theme URI:** https://almamunhossen.com

## Requirements

- WordPress 6.0 or higher
- Divi (parent theme) installed

## Installation

1. Install and activate the Divi parent theme.
2. Go to **Appearance → Themes → Add New → Upload Theme**.
3. Upload `divi-child.zip` and click **Activate**.

## Files

| File | Purpose |
|------|---------|
| `style.css` | Theme header and your custom CSS |
| `functions.php` | Loads the parent and child styles and the custom JS |
| `js/custom.js` | Your custom JavaScript (jQuery) |

## Customizing

- Add CSS at the bottom of `style.css`.
- Add PHP at the bottom of `functions.php`.
- Add JavaScript inside `js/custom.js`.

## Note

The `Template:` line in `style.css` must match the **folder name** of the parent theme in `wp-content/themes/`.
