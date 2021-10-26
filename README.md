
# TinDog

## Table of contents

- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
- [Author](#author)

## My process

### Built with

- HTML5
- CSS3
- Bootstrap
- Bootstrap Grid

### What I learned

A website created with HTML, CSS, and Bootstrap. My first time dabbling in Bootstrap. Created as a course assignment. I learned how to use Bootstrap grid to get the layout that I desired, as well as making that layout responsive when it came to a mobile viewport.

The part I enjoyed building the most were the pricing plan cards, made much easier using the Bootstrap pre-built component. Customizing through Bootstrap is also a breeze.

The more challenging aspects I faced while building this website included optimizing the layout for mobile view (made possible by Bootstrap grid classes) and positioning the iPhone image that I used in the header section (made possible through absolute positioning).

Below are some examples of code that I'm proud of in this project:

```html
<div class="pricing-card col-sm-12 col-md-12 col-lg-4">
  <div class="card">
    <div class="card-header">
      <h3 class="pricing-plan">Mastiff</h3>
    </div>
    <div class="card-body">
      <h2 class="pricing-text">$99 / mo</h2>
      <p>Pirority Listing</p>
      <p>Unlimited Matches</p>
      <p>Unlimited Messages</p>
      <p>Unlimited App Usage</p>
      <div class="d-grid"></div>
    </div>
  </div>
</div>
```

This is the HMTL for the pricing card components used to map out the varying "Plan Purchases".

```css
.iphone {
  transform: rotate(25deg);
  width: 22%;
  padding-left: 0;
  position: absolute;
  right: 23%;
}
@media (max-width: 991px) {
  .iphone {
    width: 60%;
    position: static;
    transform: rotate(0deg);
  }
}
```

This is the CSS used to layout the responsive iPhone image in the header.

### Continued development

This project was a fun and efficient introduction into the world of Bootstrap. I hope to continue useing Bootstrap and perfecting my methods with it as I grow on my journey as a developer.

## Author

- Website - [Elyse Chambers](https://www.diaryofelyse.com)
- Frontend Mentor - [Elyseeloo](https://www.frontendmentor.io/profile/Elyseeloo)
- Twitter - [@Elyseeloo\_](https://www.twitter.com/elyseeloo_)
