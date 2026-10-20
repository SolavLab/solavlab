# Adding the OLAFO landing page to solavlab.github.io

## A. One-time: create the private Google Form
1. forms.google.com -> new blank form. Add these questions (same order):
   Full name, Age, Email, Phone, City, Injury type, Injury date (date), Surgery date (date),
   Notes (paragraph), Consent (checkboxes, one option: "אישר/ה").
2. Form menu (3 dots) -> "Get pre-filled link". Type any dummy answer in every question, click "Get link", open it.
   In the URL you will see `entry.123456789=...` for each question. Write down each number.
3. Open the form's normal link and replace the end `/viewform...` with `/formResponse`.
   That is the FORM_ACTION value.
4. In `olafo.md`, replace `FORM_ACTION` and the ten `entry.000000000X` values.
5. Responses tab -> link to Google Sheets. Keep the form and sheet private (don't share links).

## B. Getting the page into the lab repo (GitHub)
You can't edit SolavLab/solavlab directly unless Dana adds you as a collaborator. Two options:
- Collaborator (simplest): ask to be added; then create a branch + Pull Request.
- Fork: click "Fork" on the repo page -> edit in your copy -> "Contribute -> Open pull request".

Steps (in the browser, no command line):
1. Fork the repo (button top-right). You now have github.com/eshraqs/solavlab.
2. In your fork: Add file -> Upload files. Upload `olafo.md` to the repo root, and the two images
   into `assets/img/olafo/` (type the folder path when uploading/creating).
3. Open `_layouts/default.html` -> pencil icon. Under the `<title>` line add:
   `{% if page.noindex %}<meta name="robots" content="noindex, nofollow" />{% endif %}`
4. Commit to a new branch (e.g. `olafo-landing`), then click "Open pull request".
5. Dana reviews and merges. Page appears at https://solavlab.github.io/solavlab/olafo-7k3q9x/ after ~1-2 min.

## C. Keeping the page hidden
- Not linked anywhere on the site (don't add it to the nav) and has `noindex`, so Google won't list it.
- The URL has a random suffix (`/olafo-7k3q9x/`), so it can't be guessed. Share it only with the people you recruit.
- "Hidden" is not "password-protected": anyone with the link can open it, and the file itself is visible in the public repo.
  That is fine because the page holds no participant data; submissions go only to your private Google Form.
