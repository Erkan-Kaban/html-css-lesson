# HTML
## 11.8.22
### What we are going through today
- WHAT IS HTML
- DOCUMENT STRUCTURE
- BASICAL HTML TAGS
- ABSOLUTE AND RELATIVE PATH
- LINK DIFFERENT PAGES
- SEMANTIC TAGS

HTML a Hyper Text Markup Language
- it is not a programming language
- is a markup language
- tells the browser how and where to display content on a web page
- Tags are the way we markup our content
- tags tell the browser how the structure is shown
- `!DOCTYPE>` declaraction starts with that and have to input html it assumes the latest type according to the standard
- element is the opening tag and closing tag
- `<head>` is the metadata
- HTML merely presents data

# DOCTYPE
- Headings `<h1>Hello</h1>`
- Paragraphs `<p>Hello<p>`
- Line Break `<br>`
- Image `<img src="weblink">`
- Anchor `<a href="weblink">Google</a>`
- List `<ol>hello</ol>`

-`!` typing this hot key is a shortcut to building a html shortcut.
- meta tags to give the browser some extra information
- absolute path: is a complete path, could entire local path
- relative path: points to another file location depending on the location eg img/kitty.jpg
- `target="_blank"` attribute in `<a>` tag makes the link open in a new tab
  
  ## Semantic Element
- A semantic element clearly describes its meaning to both the browser and the developer. like form table and article
- The word semantic means to have meaning
- **non-semantic** are div and span, tags that don't have any meaning

# CSS

- What is CSS
  
  - Cascading Style Sheets describes the style of a HTML document.
  - style sheet language, to style different html elements
  - helps developers seperate the style from content
  - defined once and applied everywhere
  - cascading implies, the latest style overrides the previous definition

- Style tag
   - goes into HTML as a `<style> </style>` its the same as css
  
- Selectors
  - ids, classes
  - selector example ` h1 { color:blue }` h1 would be the selector, attribute would be color followed by a colon : and the color choice we have.
  - class selector: start with a dot and can be used multiple times
  - id selector: starts with a #
  - pseudo classes: a:hover < hover is a pseudo class.
  - class selector: when selected you can select multiple at a time with a space eg `p class="bold-red big"` p class of bold-red and big is selected simultaneously.

# Specificity
- inline style - 1000 points
- id - 100 points
- class and pseduo class - 10 points
- element - 1 point

# Types of style sheets
- Inline Styling
- Internal Stylesheet
- External Stylesheet
  
## linking css
  - `<link rel="stylesheet" href="stylesheet.css">`
    - rel is relationship to let know the browser what you're linking in this case a css. and href is a literal link into css.  
