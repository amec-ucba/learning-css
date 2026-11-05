# 🎨 Learning CSS

Start learning CSS by following along with a series of videos and styling six practice
pages: colors, fonts, spacing, borders, backgrounds, and page structure.

**Course:** AMEC 2050C
**Points:** 15

## 🎯 Overview

So far, our coding has focused on HTML, which gives a web page structure and meaning.
**CSS**, or **Cascading Style Sheets**, is what lets us control how that HTML content
looks.

CSS is where web pages start to feel more visual and interesting. In this exercise, you
will learn how to change colors, fonts, spacing, borders, backgrounds, and page
structure. You will also learn how CSS connects to HTML and why it is usually better to
keep content and presentation separate.

This is a follow-along coding exercise. Watch the videos in order, pause when needed, and
type the code yourself in Visual Studio Code.

> [!IMPORTANT]
> **The companion videos for this exercise are in Canvas**, on the assignment page. They
> walk you through every step, so watch them there instead of working from this file
> alone.

## 🧠 What You Will Learn

By completing this exercise, you will practice how to:

- Write CSS rules using selectors, properties, and values
- Create an internal style sheet with the `style` element
- Style the `body` element and see how inheritance works
- Use grouped selectors, descendant selectors, and class selectors
- Use the box model: margin, padding, border, and background color
- Use semantic container elements such as `header` and `main`
- Link a reset style sheet and your own external CSS file
- Build a page wrapper that controls the width and alignment of your content

## 💡 Important CSS Concepts

### HTML vs. CSS

HTML describes what the content **is**. CSS describes how that content should **look**.

For example, HTML can say, "this is the main heading." CSS can say, "make the main
heading larger, green, centered, and spaced away from the content below."

### CSS Rules

A CSS rule usually includes a **selector** and one or more **declarations**. The selector
chooses what part of the page you want to style. The declarations say what should change.

```css
h1 {
  color: olive;
}
```

In that example, `h1` is the selector, `color` is the property, and `olive` is the value.

### The Cascade

The cascade means that styles can inherit, combine, override, and build on one another.
The order of your CSS rules, the type of selector you use, and the relationship between
elements can all affect what appears in the browser.

### The Box Model

Every HTML element lives inside a box. The CSS box model includes:

- **Content:** the actual text, image, or other material
- **Padding:** space inside the box, between the content and the border
- **Border:** the edge of the box
- **Margin:** space outside the box, between that element and other elements

## 🎬 Watch the Videos in Canvas and Follow Along

The screencast videos are on this assignment's page in **Canvas**, not in this repo. Watch
them **in order** and follow along in Visual Studio Code. Pause whenever you need time to
finish a step. It is normal to pause, rewind, and rewatch parts of a coding
demonstration.

Each video builds on the previous one, so please don't skip ahead.

| Video | Page | What you will do |
| --- | --- | --- |
| **Part 1 — Creating Your First CSS Rules** | `css01.html` | Create an internal style sheet and write your first CSS rules. Select elements and change properties such as color and font size. |
| **Part 2 — Body Styles, Inheritance, and Multiple Selectors** | `css02.html` | Style the `body` element, work with background color and fonts, and see how inheritance affects elements inside the page. Practice grouped and descendant selectors. |
| **Part 3 — Class Selectors** | `css03.html` | Create reusable styles with class selectors and apply them to specific elements with the `class` attribute. |
| **CSS Box Model Introduction** | — | An overview of content, padding, border, and margin before you start Part 4. |
| **Part 4 — The Box Model** | `css04.html` | Use margin, padding, border, background colors, and rounded corners to make boxes visible and easier to understand. |
| **Part 5 — Semantic Containers** | `css05.html` | Use semantic container elements such as `header` and `main`, and review the difference between `head`, `header`, and headings like `h1`. |
| **Part 6.1 — Reset CSS and External CSS Files** | `css06.html` | Connect the reset style sheet, create your own external CSS file, and link it to your HTML page. |
| **Part 6.2 — Wrapper and Page Layout Practice** | `css06.html` | Create a page wrapper using a `div` with a class, and use it to control the width and alignment of the page content. |

> [!IMPORTANT]
> **A few steps in this repo are different from the videos.** Follow the videos for the
> CSS, and follow this repo for getting your files and submitting:
>
> - **Getting the starter files:** don't download a ZIP. Create your own repo from this
>   template and open it with GitHub Desktop, as described in the
>   [README](README.md#-getting-started).
> - **Submitting:** don't zip your folder or upload a file. Publish your pages to GitHub
>   Pages and submit a pull request URL in Canvas, as described in the
>   [README](README.md#-submitting-the-assignment).

> [!IMPORTANT]
> Open the entire project **folder** in VS Code, not a single HTML file. Your HTML pages
> need to find `reset.css` and your own CSS file, and that depends on your file and
> folder structure. Don't rename or move the starter files.

## 📂 Starter Files

| File | Purpose |
| --- | --- |
| `index.html` | The exercise home page. It links to all six practice pages and explains CSS basics. You don't need to edit it. |
| `css01.html` – `css06.html` | The practice pages. You will style one page per video. |
| `reset.css` | A reset style sheet that removes browser default styles. You will link it in Part 6.1. Don't edit it. |

## ✅ Before You Submit

Check the following:

- [ ] `css01.html` has an internal style sheet with CSS rules that change color and font size
- [ ] `css02.html` styles the `body` and uses grouped and descendant selectors
- [ ] `css03.html` uses class selectors applied with the `class` attribute
- [ ] `css04.html` uses margin, padding, border, background color, and rounded corners
- [ ] `css05.html` uses semantic containers such as `header` and `main`
- [ ] `css06.html` links `reset.css` **before** your own external CSS file
- [ ] `css06.html` uses a wrapper `div` with a class to control the page width and alignment
- [ ] Every page still opens from the links on `index.html`
- [ ] You saved all your files
- [ ] The pages are live on GitHub Pages and the URL is in your pull request

## 🧮 Grading

| Criteria | Full credit | Points |
| --- | --- | --- |
| **Part 1 — First CSS Rules** (`css01.html`) | An internal style sheet in the `head` with working rules that change color and font size. | 2 |
| **Part 2 — Body Styles and Selectors** (`css02.html`) | The `body` is styled with a background color and font, and the page uses grouped and descendant selectors. | 2 |
| **Part 3 — Class Selectors** (`css03.html`) | Class selectors are written with a period in the CSS and applied with the `class` attribute in the HTML. | 2 |
| **Part 4 — The Box Model** (`css04.html`) | Margin, padding, border, background color, and rounded corners are all used and visible. | 2 |
| **Part 5 — Semantic Containers** (`css05.html`) | Content is organized in semantic containers such as `header` and `main`, and they are styled. | 2 |
| **Part 6.1 — Reset and External CSS** (`css06.html`) | `reset.css` and your own external CSS file are both linked, in the correct order, and your styles appear. | 2 |
| **Part 6.2 — Wrapper and Layout** (`css06.html`) | A wrapper `div` with a class controls the width and alignment of the page content. | 2 |
| **Submission** | The pages are live on GitHub Pages, and an open pull request with its template filled in is submitted in Canvas. | 1 |
| **Total** | | **15** |

## 🛠️ Troubleshooting

If something is not working, check these common issues first:

- Did you save the file in VS Code?
- Did you forget a semicolon in your CSS?
- Did you forget a closing curly brace `}`?
- Is your CSS inside the `style` element if you are using an internal style sheet?
- Is your external CSS file linked correctly?
- Is the file name spelled correctly?
- Is `reset.css` linked before your own CSS file?
- If a class selector is not working, did you use a period in the CSS and a `class`
  attribute in the HTML?

**Having problems with the videos?**

- **Getting a warning about third-party cookies?** Try using Chrome. Safari's default
  security settings may prevent embedded Canvas videos from playing unless those settings
  are changed.
- **Getting an "Access Denied" error?** Refresh your browser. In many cases, the videos
  will load correctly after the page reloads.

## 📚 Resources

- [MDN — CSS basics](https://developer.mozilla.org/en-US/docs/Learn_web_development/Getting_started/Your_first_website/Styling_the_content)
- [MDN — CSS selectors](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Basic_selectors)
- [MDN — The box model](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Box_model)
- [MDN — The cascade, specificity, and inheritance](https://developer.mozilla.org/en-US/docs/Learn_web_development/Core/Styling_basics/Handling_conflicts)
- [HTML Color Codes — Color names](https://htmlcolorcodes.com/color-names/)
- [W3C CSS Validation Service](https://jigsaw.w3.org/css-validator/#validate_by_input) —
  paste your CSS in to catch typos and missing braces

---

The AI policy and submission instructions are in the [README](README.md).
