# web-dev-starter

This project covers the beginning of accessibility in web development. Topics covered include making websites accessible to those who are blind (need screen readers), deaf people, and people who have to use the Tab and enter keys to navigate websites.

## Getting Started

To get started, clone this repository and run the following commands:

## Development

If using VSCode, install the Live Server extension. This will allow you to view the changes to your code and
project in real-time when running the ">Live Preview: Start Server" command in VSCode. This will open up a
separate window displaying your webpage in real-time as you work on the project. 

To see how your designed webpage will look in an actual browser, you can simply copy the web address from
the opened window and paste it into your browser's search bar. This will display the full webpage and will
also update in real-time as you work on the project.

It's recommended to test your website when implementing accessibility functionality. Things to test for are using the keyboard for navigation, screen readers, etc.

## Testing

No test class was used for this project. To test if the webpage itself works, use the Live Server extension
to start the server using the command ">Live Preview: Start Server". Once started, a preview window will
appear displaying the webpage. You can copy the web address and paste it into your browser to see the full
display of the webpage.

Use test using the keyboard, screen readers, etc. to see if accessibility functionality works as intended.

## Accessibility Lab Answers

   ## Color
   1. I did a color contrast test with the text/background using the WebAIM Contrast Picker webtool. The test returned a Foreground/Background contrast ratio of 2.79:1. I fixed the issue by sliding the color of the Background Lightness slider to the right until I got the color white and the WCAG AA and WCAG AAA tests passed.

   ## Semantic HTML
   1. When trying to navigate the webpage using the keyboard using the Tab and Enter keys, it functions properly just like the examples in the readings and module intro video.

   2. I updated the article text to make it easier for screen reader users to navigate by removing all the font="" and '<br>' elements, replacing them with header elements (h1, h2, and h3) and updating the article text to be inside paragraph '<p>' elements.

   3. The HTML semantic element that could be used to make the navigation menu more accessible is to remove the '<div>' element and update it with the '<nav>' element.

   ## The Images
   1. I made the images more accessible to screen readers by adding alt text and title names to each of the images.

   ## The Audio Player
   1. To make the audio more accessible to deaf users, I added a text-transcript of the audio below the audio bar.

   2. To make the audio more accessible to those using older browsers that don't support HTML audio, I gave the option to download the audio file.

   ## The Forms
   1. I added an aria-label tag that defines what the search bar will do for screen readers.

   2. I unambiguously associated form's '<input>' elements text labels in the Comments section by replacing the '<p>' elements with '<label>' elements and adding a for="" to the labels.

   ## The Show/Hide Comment Control
   1. To make the data table more accessible, I added a '<caption>' element and some '<th scope="row">' '</th>' and '<th scope="col">' '</th>' elements to better distinguish the table's contents.

   ## Other Considerations
   1. One idea for improvement that could make the site more accessible would be to add a show/hide button for the transcript for the audio. It would be more valuable especially if the transcript was much longer than it currently is.

   2. Another idea for improvement that could make the site more accessible would be adding 'aria-labelledby' elements to the images to instead of 'alt' and 'title' like I did. It might make it easier and simpler for screen readers to read.

## References

Downloading an audio file found at "How do I add a download button to my audio file?" on Stack Overflow at https://stackoverflow.com/questions/76741783/how-do-i-add-a-download-button-to-my-audio-file

Styling "Show comments" button for button-press animation found using Google AI overview.

Found using 'for=""' in a '<label>' element on ChatGPT.

Making a table more accessible found using ChatGPT.