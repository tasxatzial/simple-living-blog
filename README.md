# Simple living blog

A simple website about minimalism in life.

This project is part of the [Learn Responsive Web Design](https://scrimba.com/learn/responsive) course on [Scrimba](https://scrimba.com).

[Live version](https://tasxatzial.github.io/simple-living-blog/src/index.html)

## Implementation

* Responsive + responsive image markup.
* Accessible.
* Mobile first approach.

While my implementation follows the course content loosely, it isn't an exact match of the design or the implementation shown in the course. I created the project from scratch and made some intentional changes with the aim of improving upon the provided design. Here's a non-exhaustive list:

* The sidebar with the recent posts has been removed from the posts page as it contained the exact same content.
* `aria-*` attributes have been added throughout the page. The original page on Scrimba did not have any.
* The 'recent posts' page has been removed as it was pretty much identical to the home page.
* Text font size, color, weight, and line height have been adjusted to make them more consistent across the page.
* The date of each post will now appear immediately below the post title, instead of below the post image (which is outside the normal flow of text).
* The 'continue reading' text now has an underline to make it more obvious that it is a link.
* The main page title and nav links are now correctly center-aligned.
* The main page title has been changed to better match the page content.
* The height of the footer was too large and has been reduced.
* The sidebar in the 'about me' section has been adjusted. The images are now larger, and there is proper spacing between them and the text.

## Dependencies

The project is written in HTML, CSS, JavaScript.

The following dependencies require an online connection:

* [:focus-visible](https://github.com/WICG/focus-visible) polyfill.
* [Picturefill](https://scottjehl.github.io/picturefill/) polyfill.

## Run locally

Download the 'src' folder and open 'index.html' in the browser.

## Screenshots

See [screenshots](screenshots/).

For comparison purposes, I've added extra screenshots that show the original Scrimba implementation. Note that the final built page on Scrimba is missing a `<meta name="viewport">` tag and was displaying incorrectly on mobile. This has been fixed for the purposes of taking screenshots.
