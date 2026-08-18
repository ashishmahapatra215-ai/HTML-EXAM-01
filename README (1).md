# Job Application Form

A simple, single-page job application form built with HTML and CSS. Applicants can enter their personal details, select their city, describe the position they're applying for, leave a message, and upload their CV.

## Features

- First name and last name fields
- Email and phone number inputs
- City dropdown (Surat, Amrali, Rajkot, Navsari)
- Position applied for field
- Message / cover note textarea
- CV file upload
- Full-page background image with a centered, minimal layout

## Tech Stack

- HTML5
- CSS3

## Project Structure

```
job-application-form/
├── exam.html   # Form markup
├── style.css   # Styling
└── img.jpg     # Background image (not included — add your own)
```

## Getting Started

1. Download or clone this project.
2. Add a background image named `img.jpg` to the same folder as `style.css`, or update the `background-image` path in `style.css` to point to your own image.
3. Open `exam.html` in any web browser.

## Known Issues

- The CV upload field is set to `accept="image/*"`, which limits uploads to image files. Change it to something like `accept=".pdf,.doc,.docx"` to accept CV documents instead.
- The heading uses `class="Job"` while the CSS defines `.job` — since CSS class names are case-sensitive, the white text color currently isn't being applied.
- The submit button uses `typr="sumit"` instead of `type="submit"`.

## Author

**Ashish Mahapatra**
