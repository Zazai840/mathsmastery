# MathsMastery

One-page tutoring website for Abdul — A-Level & GCSE Maths and Physics.

## Run it

Open `index.html` in any browser. No build step, no dependencies.

## Files

- `index.html` — the whole site (HTML, CSS and JS in one file)
- `assets/abdul.jpg` — profile photo (EXIF-corrected, web-sized)

## Contact form

The enquiry form posts to [FormSubmit](https://formsubmit.co) and delivers to
`zazenquiries@gmail.com`. **The first time someone submits the form, FormSubmit
emails that address an activation link — click it once and all future
submissions arrive normally.** Submit a test enquiry yourself after deploying
to trigger this.

The "Request a Call by Email" button and footer links use plain `mailto:` and
work immediately.

## Deploying

Any static host works — drag the folder into [Netlify Drop](https://app.netlify.com/drop),
or push to GitHub and enable GitHub Pages. The form's redirect-back-after-submit
only activates on a real domain (it is skipped automatically when opened as a
local file).
