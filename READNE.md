# Before You Start

- [Course Materials and Instructions on Github](https://github.com/jonasschmedtmann/advanced-css-course)
- [Jonas Resources Page](http://codingheroes.io/resources/)
- [Free Videos for your Website](https://coverr.co/)

# Natours Project

- [Icons used on Natours Project](https://linea.io/)
- For Reference: /linea_complete_1.0/\_basic/\_ICONFONT/icons-reference.html

# How CSS works behind the scenes

### Three Main Pilars on HTML and CSS

1. Responsive Design
2. Maintainable and Scalable Code
3. Web Performance

### What happens to CSS when we load up a webpage ?

1. Load HTML
2. Parse HTML -->
   - (DOM: Document Object Model)
3. Load CSS --> Parse CSS
   - Resolve conflicting CSS declarations (cascade)
   - Process final CSS values
4. CSS Object Model (CSSOM)
5. DOM + CSSOM = Render Tree
6. Website rendering: The visual formatting model
7. Final rendered website

### How CSS is Parsed ?

- Watch 3.6 How CSS is Parsed, Part 2 Value Processing
- Value Processing
- ## Inheritance

# Introduction to SASS and NPM

- [SASS example in CodePen Variables and Nesting](https://codepen.io/hudson21/pen/xxVVBgq?editors=1100)

### Command Line

- live-server: To reload your project when there are new changes

### Basic Responsive Design Principles

1. Fluids Grids and Layouts: To allow content to easily adapt to the current viewport width used to browse the website. Uses `%` rather than `px` for all layout-related lengths.
2. Flexible/Responsive Images: Images behave differently than text content, and so we need to ensure that they also adapt nicely to the current viewport.
3. Media Queries: To change styles on certain viewport widths (breakpoints), allowing us to create different version of our website for different widths.
