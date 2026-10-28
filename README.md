# BTLE ICT IV-25 Class Compendium (GitHub Pages)

A class website in place of a printed compendium. Each group has a group page and a reflection page. Each member has an individual page with reflection answers, a TESDA sample session plan, and a recorded facilitation.

## For the instructor: set up once

1. Create a GitHub account for the class, or use your own. Create a new repository named, for example, `btle-ict-iv-25`.
2. Upload every file and folder from this package to the repository (Add file, then Upload files). Keep the folder structure.
3. Open **Settings**, then **Pages**. Under Build and deployment choose **Deploy from a branch**, branch `main`, folder `/ (root)`, and Save.
4. After a minute or two the site address appears on the same page. It looks like `https://YOUR-USERNAME.github.io/btle-ict-iv-25/`.
5. Open **Settings**, then **Collaborators**, and invite each student by their GitHub username. Give them **Write** access.
6. Share the site address and the repository address with the class.

## Privacy: read this first

GitHub Pages sites are public to anyone who has the address, unless the organization pays for GitHub Enterprise Cloud. A private repository on a free plan cannot publish a Pages site. Because of this, the site is built to hold no identifiable content:

- First names or initials only, no contact details.
- Faces covered unless a person signed consent.
- Videos stay in private Google Drive files, linked from the page.
- Pages ask search engines not to index them (`noindex`), but this does not hide the site from anyone with the link.

If your school needs the site to be visible only to the class, use Google Sites or a school-hosted site instead.

## For students: how to edit your page

1. Sign in to GitHub and open the class repository.
2. Open the folder for your group (for example `g3`). Your group page is `index.md`, your reflection page is `reflection.md`, and your member page is `member-1.md` and so on.
3. Click the file, then the pencil icon.
4. Replace every `[note in brackets]` with your own work and delete the note. Keep the headings and the table layout.
5. Write a short message under **Commit changes**, such as "Group 3 Part 1 report", and click **Commit changes**.
6. Wait a minute or two, then refresh the site.

Tips for Markdown:

- A new paragraph needs a blank line before it.
- `**bold text**` makes bold. `- item` makes a bullet. `1. item` makes a numbered list.
- Tables use `|` between columns. Press Enter at the end of a row and start the next row with `|`.
- To add a photo, upload it into your group's `images` folder, then write `![Describe the photo](images/photo-1.jpg)`.
- Edit only your own group's files. If you make a mistake, open the file's **History** and restore an earlier version.

## Pages

- `index.md`: home page, schedule, and timeline
- `policies.md`: ethics, AI use, privacy, consent, and pledge
- `g1` to `g7`: each has `index.md` (group page), `reflection.md`, and `member-1.md` to `member-7.md`. Delete the member pages a group does not need.

## Run it on your own computer (optional)

Install Ruby, run `bundle install`, then `bundle exec jekyll serve` and open http://localhost:4000.
