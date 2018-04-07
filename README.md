# chromeExtensionExample

This a basic example to create a chrome Extension. This simple chrome extension will put a blue background and show an alert when you click in a button.

## Introduction

The first step to create a chrome extension is create a `manifest.json` file. In this file we will include some config data like extension name, description or version. Also we need include the scripts that we want to execute and images related to the extension.

## CSS File

In our extension we will change the background color. In this case we only need to add a rule in our `styles.css` file to do this change. We can include all css code that we want and do all changes that we want in the current page that we are executing the chrome extension.

## JS File

Also we will have a Javascript file in this case `content.js`. Here we can include all JS code that we want execute inside the page that we are working. In our case we will show an alert when we click in a button.