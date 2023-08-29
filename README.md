# Frontend Mentor - Four card feature section solution

This is a solution to the [Four card feature section challenge on Frontend Mentor](https://www.frontendmentor.io/challenges/four-card-feature-section-weK1eFYK). Frontend Mentor challenges help you improve your coding skills by building realistic projects.

## Overview

### The challenge

Users should be able to:

- View the optimal layout for the site depending on their device's screen size

### Links

- Solution URL: [https://github.com/yosephwinata/four-card-feature-section](https://github.com/yosephwinata/four-card-feature-section)
- Live Site URL: [https://four-card-feature-section-ten-dusky.vercel.app/](https://four-card-feature-section-ten-dusky.vercel.app/)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Use CSS variables to avoid literals:

```css
.parent {
  --shared-padding: 3.2rem;
  padding: var(--shared-padding);
}

.child {
  right: var(--shared-padding);
  bottom: var(--shared-padding);
}
```

Formula to calculate unitless line height:<br/>
Line height (unitless) = Line height (px) / font-size (px)
