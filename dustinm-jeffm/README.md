![CF](https://camo.githubusercontent.com/70edab54bba80edb7493cad3135e9606781cbb6b/687474703a2f2f692e696d6775722e636f6d2f377635415363382e706e67) Lab 04: HTML Templating w/HandlebarsJS
===

## Submission Instructions
Follow the submission instructions from Lab 01.

## Resources  
[Handlebars Docs](http://handlebarsjs.com/)

[Arrow Functions MDN](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)

## Configuration
_Your repository must include:_

```
04-templating
├── .eslintrc.json
├── .gitignore
├── LICENSE
├── README.md
├── index.html
├── scripts
│   ├── article.js
│   ├── articleView.js
│   └── blogArticles.js
├── styles
│   ├── base.css
│   ├── fonts
│   │   ├── icomoon.eot
│   │   ├── icomoon.svg
│   │   ├── icomoon.ttf
│   │   └── icomoon.woff
│   ├── icons.css
│   ├── layout.css
│   └── modules.css
└── vendor
    └── styles
        └── normalize.css
```

## User Stories and Feature Tasks

- Continue styling the app using SMACSS practices. Take a few minutes for code review of your partner's CSS and decide how to incorporate it into your paired lab. You can choose one partner's CSS structure, or you can combine them as you see fit. Seek to optimize and organize your CSS as much as possible!

*As a user, I want my app to render articles with consistent formatting so that I can visit the site often and have the same experience each time.*

- Include the Handlebars.js CDN in your project to replace the `$.clone()` template.

*As a developer, I want to utilize the Handlebars library to dynamically render the articles using a template so that I can easily edit the way articles are rendered.*

- Convert your existing HTML template into a Handlebars template.
- Update the `Article.prototype.toHtml()` method to utilize the Handlebars template.

*As a developer, I want to utilize modern JavaScript features so that my code is up to date with industry standards.*

- Refactor the functions and methods in articleView.js to use ES6 arrow functions.

### Stretch Goal
*As a developer, I want to use Handlebars to build my filters so that my code is more DRY.*

- Look at all that duplicated markup inside your `#filter` list items! Looks like a good opportunity to use a template. Make a small template for each filter, and re-render the list once you have data to populate it.

## Documentation
_Your README.md must include:_

```md
# Project Name

**Author**: Jeff Martinez and Dustin Mundy
**Version**: 1.0.4

## Overview
<!-- Provide a high level overview of what this application is and why you are building it, beyond the fact that it's an assignment for a Code Fellows 301 class. (i.e. What's your problem domain?) -->
This application is designed to present curated content to an audience via the web.

## Getting Started
<!-- What are the steps that a user must take in order to build this app on their own machine and get it running? -->
1. Create a structured webpage with a template article or two. Style CSS to make it look and act the way you want.
2. Create a container array for your articles in javascript. Each article should include all data to be displayed in the page.
3. Create code to iterate your article array and print articles to your DOM.
4. Adjust the user experience to your hearts content. Our page allows users to expand content or filter articles by author or catagory.

## Architecture
<!-- Provide a detailed description of the application design. What technologies (languages, libraries, etc) you're using, and any other relevant design information. -->
Our webapp uses Handlebars and JQuery libraries. It is written in HTML, CSS and JavaScript. CSS was provided for this iteration by Kat Cosgrove.

## Change Log
<!-- Use this are to document the iterative changes made to your application as each feature is successfully implemented. Use time stamps. Here's an examples:

01-01-2001 4:59pm - Application now has a fully-functional express server, with GET and POST routes for the book resource. -->
* 10/27/2017 0905 - Replaced relevant HTML with JS handlebars code.
* 10/27/2017 0925 - Replaced clone() jQuery code with handlebars code.
* 10/27/2017 1030 - Refactored code in articleView to use ES6 Fat Arrow syntax.

## Credits and Collaborations
<!-- Give credit (and a link) to other people or resources that helped you build this application. -->
CSS by Kat Cosgrove           http://github.com/Katcosgrove/
jQuery by the jQuery team           https://jquery.org/team/
handlebars by the handlebars team   http://handlebarsjs.com/
...
