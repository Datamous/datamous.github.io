# datamous.github.io

The Datamous website (GitHub Pages).

- `/` home page: free cheat sheet + books
- `/cheatsheet/` the link printed in the book: sign-up page. The form posts to Kit (form ID 10077352); to switch email tools, change the form `action` in `cheatsheet/index.html`.
- `/cheatsheet/thanks/` download page: the sign-up form sends people here right after they enter their email (`?start=1` starts the PDF download; no confirmation email, Kit auto-confirms) (`cheatsheet/pandas-data-cleaning-cheat-sheet.pdf`, built in the book project's `marketing/cheatsheet/`). Not indexed by search engines.
- `cheatsheet/email-hero.jpg` image in the Kit confirmation email (made by the book project's `marketing/cheatsheet/make_email_image.py`). That email is switched off for now (instant download), so the image is only kept for later.
- `/chart-chooser/` second sign-up page (link printed in the data visualization book): same Kit form, sends people to `/chart-chooser/thanks/?start=1` (`chart-chooser-cheat-sheet.pdf`, built in that book project's `marketing/cheatsheet/`; images by its `make_images.py`).
- `/privacy/` privacy policy. `privacy/index.html` itself is the source of truth (names Kit and GitHub Pages); edit it there.
