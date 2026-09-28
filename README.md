# CSCI 120 Portfolio Website — Starter Template

This is a starter template for your personal, public-facing portfolio/resume website. It's plain HTML and CSS on purpose, so you can see and understand everything the browser is actually doing.

## What's in this template

```
your-repo/
├── index.html      <- the page itself: all the text and structure
├── style.css       <- all the colors, spacing, and layout
├── assets/         <- put images, your resume PDF, etc. here
└── README.md       <- this file
```

## Part 1 — Understand the two files

**`index.html`** holds the content and structure: your name, your About paragraph, your project descriptions, your contact links. Every placeholder you need to change is marked with an HTML comment starting with `TODO`, like this:

```html
<!-- TODO: replace with your name -->
<h1>Hi, I'm Your Name.</h1>
```

Open `index.html` in a text editor and search for the word `TODO` (most editors have a "Find" feature, Ctrl+F / Cmd+F) to find every spot that needs your information.

**`style.css`** controls how it looks.  If you want to make it your own, the very top of the file has a block that looks like this:

```css
:root {
  --color-primary: #1d4ed8;   /* try changing this to a color you like */
  ...
}
```

Change a color there and it updates everywhere that color is used on the page.

## Part 2 — Preview your changes locally

After editing `index.html`, you can see your changes locally: find `index.html` in your file browser and double-click it. It will open in your default web browser. Refresh the browser tab after each save to see your latest edit.

## Part 3 — Git and GitHub, in plain terms

You'll use three git commands frequently. Here's what each one actually does, in order:

1. **`git add <file>`** — "stage" a file, meaning: include this file's changes in the next snapshot I'm about to save. (`git add .` stages every changed file at once.)
2. **`git commit -m "a short message"`** — actually save that snapshot, with a message describing what changed. Think of a commit as a labeled save point you can always go back to.
3. **`git push`** — upload your saved commits from your computer to GitHub, so they show up in your repository online (and, once Pages is turned on, on your live website).

A typical work session looks like this, run from a terminal inside your project folder:

```
git add .
git commit -m "Add my About section and first project"
git push
```

You'll do this every time you want your live site to reflect your latest edits — editing the file alone does **not** update your website; you have to commit and push.

## Part 4 — Get your own copy of this template
clone this repo which will look like:
   ```
git clone https:/github.com/cs120-ExploringCS/project1-website.git
 ```

**Important — repository visibility:** GitHub Pages only works automatically
on a **public** repository if you're on a free GitHub account.

