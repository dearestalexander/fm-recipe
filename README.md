# Frontend Mentor - Recipe page solution

This is a solution to the [Recipe page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/recipe-page-KiTsR8QQKm). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [Frontend Mentor - Recipe page solution](#frontend-mentor---recipe-page-solution)
  - [Table of contents](#table-of-contents)
  - [Overview](#overview)
    - [Screenshot](#screenshot)
    - [Links](#links)
  - [My process](#my-process)
    - [Built with](#built-with)
    - [What I learned](#what-i-learned)
    - [Continued development](#continued-development)
    - [Feedbacks \& actions](#feedbacks--actions)
    - [Useful resources](#useful-resources)
  - [Author](#author)
  - [Acknowledgments](#acknowledgments)

## Overview

### Screenshot

![desktop](/screenshots/desktop.png)
![desktop](/screenshots/mobile.png)

### Links

- Solution URL: [Github Repository](https://github.com/dearestalexander/fm-recipe)
- Live Site URL: [Github Pages Live View](https://dearestalexander.github.io/fm-recipe/)

## My process

- Create styles.css file & add style guidelines as notes
- Set up colors and paragraph font as variables (font converted to rem)
- Add `<link>` elements for google fonts to index.html `<head>`
- Set up github repository
- Draft HTML
- Draft CSS
  - Had a couple of iterations of working on the CSS to try to make it clean and use BEM

### Built with

Vanilla HTML and CSS
Mobile first approach
Attempted to make it responsive and easy to adjust with variables
Block element method CSS naming

### What I learned

I was able to use width: min() to avoid the need for @media for mobile screens
It was the first time I properly used tables, so read up a but about table formats
Had to mess around a bit with the list items. Learned the various ways to format markers.

### Continued development

There's one weird issue I noticed with this that I couldn't resolve. The format of the fony of the ordered list bullet does not look like Outfit, but it shows up correctly as outfit in the inspector. I tried various ways to make sure the font was being properly applied to the marker, but can't figure out whey it's wrong.

### Feedbacks & actions

@grace-snow:

Adjust mobile design back to match spec; make content flush with top of screen, remove border on image

- Used @media to:
  - Adjust margin-top and border-radius on the frame
  - Added a class to the image to represent mobile style with adjusted margin and width
  - Also adjusted body color to match main color, so I keep could footer, but retain design spec look

The alt text on that image needs to communicate the same meaning and value as the image. There are good posts in the resources channel about this.

- Adjusted to, "A bright photograph of a golden yellow omelette. It is served folded over a mix of vegetables on a stone coloured plate placed on a counter top"

Bold emphasis text should be in strong tags not span.

- Adjusted to `<strong>`
- (initially wasn't sure they 'importance' of the words in bold matched the W3C guidance for strong)

The table header cells must be coded as header cells (th) not data cells (td). Ideally, they should also include scope="row" to make it clear they are row and not column headers.

- Thanks for this, I hadn't read up enough on tables, this was helpful

Your table borders look different to the design I think.

- Made some adjustments, I think it's close now?

The line height doesn't look right on the paragraphs. Check that. Usually line height is unitless and set on the body which would cascade down to paragraphs automatically.

- Thanks good tip, that simplified my CSS a bit. I think it looks closer now.

Get into the habit of including a full modern CSS reset in every project. Andy Bell's one would be more suited to this kind of site.

- I've read through five or six of them, still a bit confused which to use for vanilla html & css. Many seem to be adjusted to specific needs of the author. Will look back into this.

### Useful resources

## Author

- Website - [Alexander Roan](https://www.alexroan.com)
- Frontend Mentor - [@dearestalexander](https://www.frontendmentor.io/profile/dearestalexander)
- Twitter - [@xander_roan](https://x.com/xander_roan)

## Acknowledgments
