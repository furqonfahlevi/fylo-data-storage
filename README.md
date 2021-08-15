# Frontend Mentor - Fylo data storage component solution

This is a solution to the [Fylo data storage component challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/fylo-data-storage-component-1dZPRbV5n). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Table of contents

- [The challenge](#the-challenge)
- [Built with](#built-with)
- [What I learnt](#what-i-learned)
- [Useful resources](#useful-resources)
- [Author](#author)
- [Acknowledgments](#acknowledgments)

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Built with

- Non-Semantic HTML5 markup
- CSS custom properties
- Flexbox

### What I learnt

While working through this project, I've learnt something new.

Something new, see below:

```css
.storage-left {
  width: 180px;
  height: 80px;
  background: white;
  border-radius: 10px 10px 0 10px;
  position: absolute;
  z-index: 99;
  right: 0;
  top: -85px;
  display: flex;
  justify-content: center;
  align-items: center;
  gap: 0.5rem;
}

.storage-left::after {
  content: " ";
  position: absolute;
  width: 0;
  height: 0;
  left: auto;
  right: 0px;
  bottom: -20px;
  border: 12px solid;
  border-color: white white transparent transparent;
}

.storage-used {
  line-height: 16px;
  word-spacing: 1px;
}

.storage-size p {
  font-weight: 700;
}
```

If you want more help with writing markdown, we'd recommend checking out [The Markdown Guide](https://www.markdownguide.org/) to learn more.

### Useful resources

- [Text Bubble CSS](https://codepen.io/Founts/pen/gmhcl) - This helped me for create text bubble (storage-left) in CSS using pseudo-elements.
- [Illustration of the code](https://www.frontendmentor.io/solutions/fylo-data-storage-with-sass-t_aq6n-Kk) - This solution give me the illustration of the HTML and CSS. I learnt a lot of new things from this solution.

## Author

- Frontend Mentor - [@furqonfahlevi](https://www.frontendmentor.io/profile/furqonfahlevi)

## Acknowledgments

These are the person who helped me out through this project:

- [Aang/Gluekol] (https://github.com/milhamm)
- [Ditya/Duduh] (https://github.com/Dityath)
