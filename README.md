# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

**Note: Delete this note and update the table of contents based on what sections you keep.**

## Overview
 It's the first project I developed from https://www.frontendmentor.io/ challenges. 
It's been a while since I began learning web development but been in and out of it.
Hopefully, through these challenges, I'll make a streak of evolving my skills and climbing up that mountain.
I've been looking to do a challenge from the website for 
about two years and I finally got my feet wet.

### Links

- Solution URL: [https://github.com/brunomoleta/bug-free-carnival]
- Live Site URL: [https://brunomoleta.github.io/bug-free-carnival/]

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

There's a big difference between developing an exercise following along an instructor and doing it on your own.
The difficulties I went about were:
          1: to centralize the QR code card in the Y-axis;
          2: removing the vertical scroll bar;
          3: to put the text closer do the QR code, inside the card;


Use this section to recap over some of your major learnings while working through this project. Writing these out and providing code samples of areas you want to highlight is a great way to reinforce your own knowledge.

To see how you can add code snippets, see below:

1 & 2:
```html
<body>
    <div id="central">
      <div class="card">
        <figure>
          <img>
        </figure>
        <div id="tex">
          <h1>
          <p>
        </div>
      </div>
    </div>
```
```css
#central {
  display: flex;
  flex-direction: column;
  align-items: center;
  justify-content: center;
  /* Taking away the vertical scroll bar. There's probably a better solution to that. */
  min-height: 98vh;
}
```

3 (to put the text closer do the QR code, inside the card):
```css
.card{
  /* parent */
  position: relative;
}
#text {
  position: absolute;
  bottom: 0;
}
/* Beyond that, the 'QR code image' CSS box had a padding inside that made it farther from the text.
To remove it I did the following: */
img {
  display: flex;
  justify-content: center;
}
```

### Continued development

=> To explain the process of coding, such as its happening through this document.;
=> To have a better control over the layout using flexbox;


### Useful resources

- [Jad Joubran's HTML/CSS course](https://learnhtmlcss.online/app.html?id=3021) - Much of what I know about CSS comes from this course right here. It's beginner friendly and it has a fair price tag.


## Author

- Website - [Bruno Moleta's Github](https://github.com/brunomoleta)
- Frontend Mentor - [@brunomoleta](https://www.frontendmentor.io/profile/brunomoleta)