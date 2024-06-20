# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

## Overview

### Screenshot

![](./screenshot.png)

### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### Initial thoughts

This looks like a relatively simple component, with a bunch of nested containers with lists and a table. I haven't worked with tables in quite a while, so I'll be interesting to work with them again, especially styling tables. I was originally thinking of possibly using Flex Grid for this exercise, but I think Flexbox might be more suited for the purpose. I'll be trying to use Figma to measure the elements, based purely on the design .jpg, as I do not have access to the Figma design files.

After having studied HTML semantics more, I've decided to opt not to include a header in my HTML, as the page content would presumably be presented on a page with some sort of navbar, instead of having the header be nested inside `<main>`.

### What I learned

This project turned out to be far more challenging than I had originally anticipated. There were lots of little elements, which didn't react the way I expected them to, once I started trying to recreate the mobile version of the site, with the desktop version as a starting point.

For example, I learned that styling the bulletpoints/numbers of lists was more complicated than I thought. Not that I didn't come up with a solution for it, but especially making sure that the bullet points center vertically with a multi-line `<li>` was a good bit more tricky than I thought it would've been.

I ended up solving this issue, by removing the bullet point entirely and then adding it back in with `content: "\25CF";`. This allowed me to style it like any other text element, and together with some flexbox properties, I was able to make it work.

I also learned a lot about semantic HTML, and found myself redoing certain sections a bunch of times, to ensure that I didn't just have a solution, but that I had a solution that is hopefully fairly accessible.

### Continued development

I ended up not using CSS Grid for the project, so that is something I would very much like to use on the next project I work on, if it makes sense. I'm feeling fairly comfortable with Flexbox at this point, so I'd like to push myself out of my comfort zone on this.

I'm quite proud of my growing understanding of specificity when it comes to CSS, but I would like to still keep improving. Additionally, I'd love to start learning how to create CSS that's more DRY or optimized in general. Ideally I want my code to be easy to read and easy to maintain, both for me and others.

### Useful resources

- [WebAIM HTML Semantics Cheat Sheet](https://webaim.org/resources/htmlcheatsheet/HTML%20Semantics%20and%20Accessibility%20Cheat%20Sheet.pdf) - I found this .pdf from WebAIM to be very informative, and helped me understand how to work with Semantic HTML and how assistive technologies might interact with various HTML elements.

## Author

- Frontend Mentor - [@SaruMakes](https://www.frontendmentor.io/profile/sarumakes)
