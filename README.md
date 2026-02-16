# CS503 Visual Intelligence - Course Website

Source code for [https://vilab.epfl.ch/cs503](https://vilab.epfl.ch/cs503)

## How to Update the Website

This is a [Jekyll](https://jekyllrb.com/) static site. You edit the source files (Markdown, YAML, etc.), rebuild, and upload the output to the server.

### Prerequisites (one-time setup)

1. Install Ruby via Homebrew:
   ```bash
   brew install ruby
   ```
2. Add Homebrew Ruby to your PATH (add this to `~/.zshrc`):
   ```bash
   export PATH="/opt/homebrew/opt/ruby/bin:/opt/homebrew/lib/ruby/gems/4.0.0/bin:$PATH"
   ```
3. Install dependencies:
   ```bash
   bundle install
   ```

### Making Changes

1. **Edit source files** in the repo (see [Content Guide](#content-guide) below). **Never edit files in `_site/` directly** — that folder is auto-generated and gets wiped on every build.

2. **Preview locally:**
   ```bash
   bundle exec jekyll serve
   ```
   Then visit `http://localhost:4000/cs503` to check your changes.

3. **Build the site:**
   ```bash
   bundle exec jekyll build
   ```
   This generates the final HTML/CSS/JS in the `_site/` folder.

4. **Upload to the server:**
   - Open Cyberduck and connect to the `vilab.epfl.ch` server
   - Upload the **contents** of `_site/` into the `cs503/` folder on the server
   - The changes will be live at `https://vilab.epfl.ch/cs503`

## Content Guide

### Adding Homeworks

1. Add PDF files to `assets/homeworks/`.
2. Create a new file in `_homeworks/` (copy an existing one like `hw0.md`).
   - `title`, `release_date`, `due_date` are required fields.
   - Other fields show "to be released" if not provided.
   - Use relative paths to link assets.
   - Homeworks are sorted by `release_date`.
3. To publish, go to `main/homeworks.md` and increase the `limit_value` variable.

### Adding Lectures

1. Add slides/notes to `assets/lectures/`.
2. Create a new file in `_lectures/` (copy an existing one like `lecture1.md`).
   - `title` and `id` are required fields.
   - `lecture_n` should have `id: n` (used for sorting).
   - Other fields show "to be released" if not provided.
   - Use relative paths to link assets.
3. To publish, go to `main/lectures.md` and increase the `limit_value` variable.

### Other Content

- **Announcements:** Add/edit files in `_announcements/`
- **Staff:** Add/edit files in `_staffers/`
- **Schedules:** Add/edit files in `_schedules/`
- **General pages:** Edit Markdown files in the repo root (`index.md`, `homeworks.md`, etc.) or in `info/`
- **Site config:** `_config.yml` (title, links, etc.)
