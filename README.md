### The challenge

Users should be able to:

- View the optimal layout for the interface depending on their device's screen size
- See hover and focus states for all interactive elements on the page

### Screenshot
[](./design/desktop-design.jpg)

### Links

- Solution URL: [Solution URL](https://www.frontendmentor.io/solutions/summarycomponent-using-media-query-css-grid-and-flexbox-e07pGvp6kT)

## My process

### Built with

- Semantic HTML5 markup
- CSS custom properties
- Flexbox
- CSS Grid

### What I learned

Media query for responsive layout and combine css grid with flexbox

```css
@media (max-width: 1508px){
  .grid-container { 
    display: flex; 
    flex-wrap: wrap; 
    justify-content: center; } 

  .box-1, .box-2 { 
    margin-top: 0; 
    margin-bottom: 0;
  } 
}


```
### Continued development

Definitely continue to use media query and more css grid.

### Useful resources

- [Using media queries](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_media_queries/Using_media_queries) - This helped me to understand a little about media queries and ot's a very helpful resource.
- [A complete guide to css grid](https://css-tricks.com/snippets/css/complete-guide-grid/) - I was struggling to understand the grids of css and this site helped a lot.


## Author

- Website - [Isaele Araújo](https://www.your-site.com)
- Frontend Mentor - [@IsaeleAraujo](https://www.frontendmentor.io/profile/IsaeleAraujo)
