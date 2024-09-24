Text2Speech
This project enables speech-to-text functionality, allowing you to speak and convert it to text using the browser APIs. We then copy the text generated from speech to clipboard and create a text annotations from this text in clipboard.

Prerequisites
Node.js (version 14 or later)
npm (version 6 or later)
Getting Started
Clone the repository:

git clone https://github.com/Narashiman-K/Speech2Text.git
cd Speech2Text

Open a terminal and navigate to the project directory.
Install the project dependencies: "npm install"

Copy the PSPDFKit for Web library assets to the public directory by running:
`cp -R ./node_modules/pspdfkit/dist/pspdfkit-lib public/pspdfkit-lib`

You should now be able to run the project locally by executing `npm run dev`

Now click on the "start speech to Text" button and make sure you allow the microphone on the web browser.
click on the button and start talking, once you stop the text annotation will be placed on the PDF. 

Building for Production
To create a production build of the app and serve it: sh npm run build npm run preview 

Open your browser and navigate to http://localhost:4173 to see the application in action.

License
This project is licensed under the BSD license. See the LICENSE file for more details.

Contributing
Please ensure you have signed our CLA so that we can accept your contributions.

Support, Issues and License Questions
PSPDFKit offers support for customers with an active SDK license via PSPDFKit Support.

Are you evaluating our SDK? That's great, we're happy to help out! To make sure this is fast, please use a work email and have someone from your company fill out our sales form.

About
This project allows speech to text synthesis, creating the text annotation, and even support the manual copy paste feature (using Ctrl + V).

Author
Narashiman Krishnamurthy