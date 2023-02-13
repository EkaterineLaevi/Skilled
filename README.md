# Frontend Mentor - Skilled e-learning landing page solution

This is a solution to the [Skilled e-learning landing page challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/skilled-elearning-landing-page-S1ObDrZ8q). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of content

## Overview

### The challenge

- find the optimal layout depending on device's screen size (mobile, tablet and desktop)
- using hover for buttons
- making display column and row  depends on screen size

### Screenshot

![](./screenshot.jpg)



### Links

- Solution URL: [Add solution URL here](https://your-solution-url.com)
- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

### Built with

- HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid
- Mobile-first workflow
- Font styles


### What I learned

Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

```html
<div id="grid">
            <div class="check">
                <a class="check-course" href="#">...</a>
            </div>
            <div class="marg block">
                <img class="first" src="">
                <h2 class="heading">...</h2>
                <p class="description">.....
                </p>
                <a class="click" href="#">....</a>
            </div>
            <div class="block ">
                <img class="first" src="...">
                <h2 class="heading">...</h2>
                <p class="description">.......
                </p>
                <a class="click" href="#">Get Started</a>
            </div>
            <div class="block">
                <img class="first" src="...">
                <h2 class="heading">.....</h2>
                <p class="description">......
                </p>
                <a class="click" href="#">....</a>
            </div>
            <div class="block">
                <img class="first" src="..">
                <h2 class="heading">....</h2>
                <p class="description">....
                </p>
                <a class="click" href="#">...</a>
            </div>
            <div class="block">
                <img class="first" src="https://i.postimg.cc/jSZcBY9X/icon-business.png">
                <h2 class="heading">....</h2>
                <p class="description">.....
                </p>
                <a class="click" href="#">...</a>
            </div>
        </div>
        <footer>
            <div class="line">
                <img class="logo footer-logo" src="...">
                <button class="footer-right">....</button>
            </div>
```
```css
#grid {
    display: flex;
    flex-direction: column;
    align-items: center;
    justify-content: center;
}
```

### Continued development

Use this section to outline areas that you want to continue focusing on in future projects. These could be concepts you're still not completely comfortable with or techniques you found useful that you want to refine and perfect.

**Note: Delete this note and the content within this section and replace with your own plans for continued development.**

### Useful resources

- [Browse Fonts](./fonts.google.com) - Using different font size with this web is easy
- [Figma](./figma.com) - Main page for website tools size and design


## Author

- Website - [Ekaterine Laevi](no-web)
- Twitter - [@ektaerinelaevi](https://www.twitter.com/ekaterinelaevi)


## Acknowledgments

For beginners: Use display flex, and make flex wrap for grid div and it opens in right way on desktop every size(mobile, tablet, desktop).
and make sure when you make a div which on other destop size looks different include other div which are next come together on row.
