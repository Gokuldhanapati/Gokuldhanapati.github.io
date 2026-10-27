# Gokul Dhanapati – personal website

Every page file is named after what it contains:

| File | Page |
|---|---|
| index.html | Home: intro, DNA–bee drawing, PhD guide link |
| research.html | Research |
| research-methods.html | Learning notes: Research Methods |
| bioinformatics.html | Learning notes: Bioinformatics |
| phd-guide.html | How to get a fully funded PhD in the USA (+ Q&A) — Instagram bio link |
| contact.html | Contact form |
| css/style.css | All styling. Colours are at the top under "COLOURS" (burgundy bar #5e1a2c, cream background #fdfbf7, beige cards #f1e7d8, buttons #8a2a3f) |
| js/main.js | Mobile menu and small helpers |
| assets/img/ | Compressed photos and logos |
| assets/bioinfo/ | Linux commands page, FastQC report, demo FASTQ files |

## Two things to switch on

1. **Questions on the PhD guide** – sign up at https://cusdis.com, add the website, copy the App ID, and paste it into `data-app-id="PASTE_YOUR_APP_ID"` in phd-guide.html.
2. **Contact form** – sign up at https://formspree.io, create a form, and paste the form ID into `var FORMSPREE_ID = "";` near the bottom of contact.html. Also replace `YOUR_EMAIL@msstate.edu`.

## Adding a new page to the menu
The menu is written at the top of every page. If you add a page, add the same `<a href="...">` line in each file's `<nav id="site-nav">` and footer.

## Instagram link
https://gokuldhanapati.github.io/phd-guide.html
