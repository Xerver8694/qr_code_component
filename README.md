# Frontend Mentor - QR code component solution

This is a solution to the [QR code component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/qr-code-component-iux_sIO_H). Frontend Mentor challenges help you improve your coding skills by building realistic projects. 

## Table of contents

- [Overview](#overview)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

## Overview

A basic project to reinforce my learning of HTML and CSS and get some experience with actually building and managing webpages. 

### Screenshot

![Screenshot 2024-11-08 at 06-37-25 QR Code Component](https://github.com/user-attachments/assets/67449506-fc61-4782-8aa7-44b32ac3a0a3)


### Links

- Solution URL: (https://github.com/Xerver8694/qr_code_component)
- Live Site URL: (https://xerver8694.github.io/qr_code_component/)

## My process

Adding the Boilerplate HTML for the basics of the webpage
Creating a div element for the qr code componenet
Importing the images to add the QR Code
Using CSS Flexbox to style the page and make it responsive to the size of the window

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learned

I had to review a lot about CSS flexbox and styling elements. Flexbox is something I sort of struggle grasping, but the research I had to do helped reinforce the concepts I needed.

```css
.qr_code {
    display: flex;
    flex-direction: column;
    align-items: center;
    background-color: hsl(212, 45%, 89%);
    padding: 20px;
    border-radius: 10px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.2); 
    max-width: 300px; 
    text-align: center;
}

```
### Useful resources

- [w3 Schools](https://www.w3schools.com/css/css3_flexbox.asp) - Helped me relearn a lot about the flexbox model for this project. 

- [Learn CSS Flexbox in 8 minutes](https://www.youtube.com/watch?v=phWxA89Dy94) - This video explained how to use Flexbox in a very simple way that helped me utilize it in this project.


## Author

- Frontend Mentor - [@Xerver8694](https://www.frontendmentor.io/profile/Xerver8694)
