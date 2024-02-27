Description for Meme Generator Project:

The Meme Generator project is a web application that allows users to generate random wholesome memes with just a click of a button. The project is built using HTML, CSS, and JavaScript, leveraging an external API to fetch random memes.

HTML Structure:
The HTML file defines the structure of the web page. It consists of a container element with the class "meme-generator". Inside this container, there is a button labeled "Generate Meme", a heading element for displaying the meme title, an image element for displaying the meme itself, and a div for showing the meme author.

CSS Styling:
The CSS file provides styles for the meme generator interface. It sets the font family, aligns text to the center, and defines styles for the meme image, generate button, and hover effects for the button.

JavaScript Functionality:
The JavaScript file contains the functionality for fetching random memes from an external API and updating the meme details on the web page. It selects the necessary DOM elements using querySelector and attaches an event listener to the "Generate Meme" button. When the button is clicked, it triggers a function to fetch a random meme using the fetch API. Once the response is received, the meme details (URL, title, and author) are extracted from the JSON data and displayed on the web page using the updateDetails function.

Overall, the Meme Generator project provides a simple and fun way for users to discover and enjoy wholesome memes with ease. Users can click the "Generate Meme" button to see a new meme each time, adding an element of randomness and surprise to the meme browsing experience.
