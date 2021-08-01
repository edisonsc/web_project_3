# Project 3: From Portland to Portland

### Overview
* Intro
* Project Brief - Figma
* GitHub Pages Link
* Responsive Design
* Using Figma

**Intro**

This is a project about traveling across the US. It was built using HTML5, CSS, BEM methodoloy, Flexbox, Grid and responsive web practices. 

**Figma**

* [Link to the project on Figma](https://www.figma.com/file/AtbNbstbxWPcMqvF061V0R/Sprint-3%3A-From-Portland-to-Portland-%7C-desktop-%2B-mobile?node-id=0%3A1)

**GitHub Pages**

* View the finished project on [GitHub Pages](https://edisonsc.github.io/web_project_3/index.html)

**Responsive Design**

This project tested my knowledge of responsive design. I used grid layout and flexbox to achieve the layout of the page. I learned how to use the calc() function with media queries to keep elements consistent with the design at various breaks. 

```
@media screen and (max-width: 1024px) {
  .header {
    width: calc(100% - 96px);
  }
}

```

I used a grid layout for the photo-grid section and the places section. I decided to use the grid-template-area below to style the place block. 

```
.place {
  display: grid;
  grid-template-columns: 49fr 51fr;
  grid-column-gap: 40px;
  grid-row-gap: 48px;
  grid-template-areas:
    "title link-area"
    "image text";
  margin: 0 auto;
  max-width: 984px;
}
```

**Using Figma**

This is my first project using Figma. I downloaded images from the file and copied text and CSS as needed. One of the more difficult parts of this project was knowing when and how to use the dimensions provided in Figma. 
