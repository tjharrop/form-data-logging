# Form Data Logging
This is a demonstration of an easy way in which you can pass data between pages of a multi-screen form using local storage.

This repository is a demo, and acts as hosting for the js file. The blog post it comes from is available at [Passing data between screens in a prototype - @fightfortheuser](https://medium.com/@fightfortheuser/passing-data-between-screens-in-a-prototype-a8efe003ea8e)

The demo is available at [https://store-form-data.herokuapp.com/](https://store-form-data.herokuapp.com/)

## Getting Started
For more detailed instructions use the medium link above. Here's the TLDR version:

#### You will need:
- _Some_ HTML knowledge

#### 1. Include jQuery
`<script src=”https://ajax.googleapis.com/ajax/libs/jquery/2.1.4/jquery.min.js"></script>`

#### 2. Include the JS from this repo:
`<script type=”text/javascript” src=”http://tjharrop.github.io/form-data-logging/scripts/form.storage.js”></script>`

#### 3. Give your <input> elements names
The name should be unique.
    `<input type=”text” name=”customer-name”>`

#### 4. Displaying the data on a later page
Use a data-playback indicator and the content of the element will be replaced.
    `<div data-playback=”customer-name”></div>`
