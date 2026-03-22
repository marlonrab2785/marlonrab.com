# marlonrab.com — Deploy Instructions

## File Structure
```
public_html/
├── index.html                        ← Main website file
├── Marlon_Rabago_Resume_2026.pdf     ← CV download
└── images/
    └── marlon-photo.jpg              ← Your profile photo
```

## Steps to deploy on Hostinger

1. Log in to Hostinger → Go to **File Manager**
2. Navigate to `public_html/`
3. Delete or backup any existing `index.html`
4. Upload these files:
   - `index.html`
   - `Marlon_Rabago_Resume_2026.pdf`
5. Create folder `images/` inside `public_html/`
6. Upload your profile photo as `marlon-photo.jpg` inside `images/`
   - Recommended: square photo, minimum 200x200px
   - The photo from your CV works great

## Photo
The site expects: `images/marlon-photo.jpg`
If you want a different filename, edit line ~1091 in index.html:
```html
<img src="images/YOUR-FILENAME.jpg" alt="Marlon Rábago" ...>
```

## Contact Form
Already configured with Web3Forms.
Emails will be sent to: rabagoheredia@gmail.com

## That's it!
Your site should be live at www.marlonrab.com
