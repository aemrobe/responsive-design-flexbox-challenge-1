responisve layout challenge 3

## Table of contents

- [The challenge](#the-challenge)
  - [Screenshot](#screenshot)
  - [Links](#links)
- [My process](#my-process)
  - [Built with](#built-with)
  - [What I learned](#what-i-learned)
  - [Continued development](#continued-development)
  - [Useful resources](#useful-resources)
- [Author](#author)

### The challenge

this challene have two section the upper and lower section.
the upper section is a page which i have done in the responsive desing challenge-2 so,
after you have done responsive design layout challenge-2

try to make your elements below the upper seciton close to the design which is found in this link: https://s3.us-east-1.amazonaws.com/product-content.podia.com/14hvxecayshytcthax2fkc9q6wpb?response-content-disposition=attachment%3B%20filename%3D%2202-03-challenge-layout.pdf%22%3B%20filename%2A%3DUTF-8%27%2702-03-challenge-layout.pdf&response-content-type=application%2Fpdf&X-Amz-Algorithm=AWS4-HMAC-SHA256&X-Amz-Credential=AKIAS4DOQ376LOGFEVUO%2F20220228%2Fus-east-1%2Fs3%2Faws4_request&X-Amz-Date=20220228T153057Z&X-Amz-Expires=3600&X-Amz-SignedHeaders=host&X-Amz-Signature=2ac232b8c338a1b21b863e075db8061837ca963e98559f084ac0f55d1dab2135

![](./screenshot.jpg)

file path for the screenshot of my solution:
solution image/flexbox challenge-1.png

### Links

- Live Site URL: [Add live site URL here](https://your-live-site-url.com)

## My process

I have done the upper-section in the responsive design layout challenge-3 repository so
this process only explain how I have done the page below the upper section which is the flexbox one.

when I do this challenge , I start with div which have class of row and row-1. it have three child elements (three of them have a class of col).

```
HTML
     <div class=" row row-1">
          <div class="col">
               <h2>Cheap</h2>
               <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
                        dolore magna aliqua. Ut enim ad minim veniam.
                </p>
          </div>

          <div class="col">
              <h2>Quick</h2>
              <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
                        dolore magna aliqua. Ut enim ad minim veniam.
              </p>
          </div>

          <div class="col">
               <h2>Affordable</h2>
               <p>Lorem ipsum dolor sit amet, consectetur adipiscing elit, sed do eiusmod tempor incididunt ut labore et
                        dolore magna aliqua. Ut enim ad minim veniam.
              </p>
          </div>
      </div>
```

I add display: flex to the row and all these three child elments with a class of col align themself with a singe row. and I add a property of gap 20px to class of row to add space with these three child elements.

```
css
.row {
 display: flex;
 gap: 20px;
}
```

I also add padding to the row element and it will add space at the top and bottom .

```
css
.row {
display: flex;
gap: 20px;
padding: 80px 0;
}
```

### Built with

- Semantic HTML5 markup
- CSS 3

### What I learned

in this section I learn about that width and height doesn't affect inline elements such as a link .

### Continued development

i want to focus on responsive design,flexbox , grid.

## Author

- frontendmentor - [@aemrobe](https://www.frontendmentor.io/profile/yourusername)
- Twitter - [@Aemro112](https://www.twitter.com/yourusername)
- freecodecamp - [@aemro11](https://www.freecodecamp.org/fcca3ca9e2b-f172-41a6-a671-68f137231a2d)
