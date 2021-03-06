[![BrowserStack Status](https://www.browserstack.com/automate/badge.svg?badge_key=VU1CUkFDYUh0QmN1UDdtOXJQSVdVbEViMnlyUm96czNGeFJqWnB2VXZhWT0tLWZ1OU9TZENGN1prc3pWZGh3c2x1Y2c9PQ==--b6177e3b1e1ef8275a81f4f0ea363336a5ac309c)](https://www.browserstack.com/automate/public-build/VU1CUkFDYUh0QmN1UDdtOXJQSVdVbEViMnlyUm96czNGeFJqWnB2VXZhWT0tLWZ1OU9TZENGN1prc3pWZGh3c2x1Y2c9PQ==--b6177e3b1e1ef8275a81f4f0ea363336a5ac309c)
[![Build Status](https://travis-ci.org/rudywaltz/custom-element-workshop.svg?branch=master)](https://travis-ci.org/rudywaltz/custom-element-workshop)

Workshop for Custom Element

1. `nvm use`
2. `npm install --only=prod` you don't need devDependency for a workshop
3. `npm start`


You can find the description of practice in each folder.

http://localhost:8000/


# What are web components?

> Web components are a set of web platform APIs that allow you to create new custom, reusable, encapsulated HTML tags to use in web pages and web apps. Custom components and widgets build on the Web Component standards, will work across modern browsers, and can be used with any JavaScript library or framework that works with HTML.
>
> Web components are based on existing web standards. Features to support web components are currently being added to the HTML and DOM specs, letting web developers easily extend HTML with new elements with encapsulated styling and custom behavior.

https://www.webcomponents.org/introduction

## Specification

### Shadow DOM
Encapsulate the style and markup.

<img src="./img/shadowDOM_1.png" width="700px">

developer tools -> Settigs -> Show user agent shadow DOM

<img src="./img/shadowDOM_2.png" width="700px">

### HTML Template
Declare fragments of markup that go unused at page load, but can be instantiated later on at runtime.

### ES Modules
The specification defines the inclusion and reuse of JS documents in a standards based, modular, performant way.

### Custom Elements
Designing and using new types of DOM elements.


### Tests
You can use <a href="https://www.browserstack.com" target="_blank">BrowserStack</a> for a live or automated test for any kind of browser.

<img src="./img/browserstack.svg" width="300px">
