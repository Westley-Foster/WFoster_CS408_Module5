# web-dev-starter

This is a starter project for web development with no frameworks and minimal
dependencies. It is intended to be a starting point for web development projects
that are written in plain HTML, CSS, and JavaScript.

## Getting Started

To get started, clone this repository and run the following commands:

```bash
npm install
```
This will install the necessary dependencies for the project.

## Development

It is recommended to use the VSCode Live Server extension to run the project
locally. This will allow you to see changes in real-time as you make them. There
is no need to run a build process or refresh the page manually. Additionally,
you do not need to setup a local server to run the project.

## Testing

To run the tests for the project, run the following command
## Accessibility Lab Answers

   ## Color
   1. I did a color contrast test with the text/background using the WebAIM Contrast Picker webtool. The test returned a Foreground/Background contrast ratio of 2.79:1. I fixed the issue by sliding the color of the Background Lightness slider to the right until I got the color white and the WCAG AA and WCAG AAA tests passed.

   ## Semantic HTML
   1. When trying to navigate the webpage using the keyboard using the Tab and Enter keys, it functions properly just like the examples in the readings and module intro video.

   2. I updated the article text to make it easier for screen reader users to navigate by removing all the font="" and <br> elements, replacing them with header elements (h1, h2, and h3) and updating the article text to be inside paragraph <p> elements.

   3. The HTML semantic element that could be used to make the navigation menu more accessible is the <nav> element.

   ## The Images
   1. I made the images more accessible to screen readers by adding alt text and title names to each of the images.

   ## The Audio Player
   1. 

```bash
npm test
```
