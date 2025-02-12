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

To run the tests for the project, run the following command:

```bash
npm test
```

## Accessibility Lab Answers
COLOR CONTRAST: 
The current color scheme uses green as a background a black/gray as the foreground.
This gives you a contrast ratio of 2.79:1 which is well below the recommended 4.5:1
or 3:1 for larger text.  To fix this I will make the background white which much
improves it to 14.35:1.

SEMANTIC HTML: 
1.The content is still not very accessible — report on what happens when you try to navigate it using a keyboard.
It is very difficult to navigate using a keyboard only.  You can tab around and get to things, but its not that 
accessible.

2.Can you update the article text to make it easier for screen reader users to navigate?
Yes.  If you take the fonts out and replace them with h1, h2, h3, p it makes it a lot easier for a screen reader.

3.The navigation menu part of the site (wrapped in <div class="nav"></div>) could be made more accessible by putting it in a proper HTML semantic element. Which one should it be updated to? Make the update.
I changed div to "nav" which makes it more accessible.  

The Images
The images are currently inaccessible to screen reader users. Can you fix this?
Yes I had to fix the file path and also added a description for the screen reader.

The Audio Player
The <audio> player isn't accessible to hearing impaired (deaf) people — can you add some kind of accessible alternative for these users?
I added a transcription of the audio file for deaf users.

The <audio> player isn't accessible to those using older browsers that don't support HTML audio. How can you allow them to still access the audio?
I added a download feature so they can download it and listen.

The Show/Hide Comment Control
The show/hide comment control button is not currently keyboard-accessible. Can you make it keyboard-accessible, both in terms of focusing it using the tab key and activating it using the return key?
Yes I updated js and html to make it lock in with tab and also able to show or not show comments.

The Table
The data table is not currently very accessible — it is hard for screen reader users to associate data rows and columns together, and the table also has no kind of summary to make it clear what it shows. Can you add some features to your HTML to fix this problem?
Yes I added scope="col" to make it so the table is more accessible. 

Other Considerations?
Can you list two more ideas for improvements that would make the website more accessible?
I would look into if it can take audio for writing comments, but that might be a little high end.  
I would also leave more comments for the screen reader if I had more time.