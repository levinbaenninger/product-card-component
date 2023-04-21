# Frontend Mentor - Product preview card component solution

This is a solution to the [Product preview card component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/product-preview-card-component-GO7UmttRfa). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

-   [Overview](#overview)
    -   [The challenge](#the-challenge)
    -   [Links](#links)
-   [My process](#my-process)
    -   [Built with](#built-with)
    -   [What I learned](#what-i-learned)
    -   [Continued development](#continued-development)
-   [Author](#author)

## Overview

### The challenge

Users should be able to:

-   View the optimal layout depending on their device's screen size
-   See hover and focus states for interactive elements

### Links

-   Solution URL: [GitHub](https://github.com/levinbaenninger/product-card-component)
-   Live Site URL: [Netlify](https://your-live-site-url.com)

## My process

### Built with

-   Semantic HTML5 markup
-   CSS
-   Flexbox
-   Mobile-first workflow

### What I learned

I learned how to change images depending on the device's size:

```html
<div class="img-container">
	<img
		src="/images/image-product-desktop.jpg"
		id="main-img"
		alt="picture of the product" />
</div>
```

```css
@media screen and (max-width: 767px) {
	#main-img {
		content: url('images/image-product-mobile.jpg');
	}
}

@media screen and (min-width: 768px) {
	#main-img {
		content: url('images/image-product-desktop.jpg');
	}
}
```

### Continued development

I want to work on my skills in the responsive design. I am still not comfortable with writing responsive CSS.

## Author

-   Frontend Mentor - [@levinbaenninger](https://www.frontendmentor.io/profile/levinbaenninger)
-   Twitter - [@levinbaenninger](https://twitter.com/levinbaenninger)
