# ENGO-lab0

URL: https://wongsitu.github.io/ENGO-lab0/index.html

## How to run the project
The project was built using VSCode. To run the project download the "Live Server" extension. Once that's done, at the right bottom corner of your editor there should be a "Go Live" button. Click on it and it should work.

## Requirements

- [x] Your website must contain at least four different .html pages, and it should be possible to get from any page on your website to any other page by following one or more hyperlinks.
- [x] Your website must include at least one list (ordered or unordered), at least one table, and at least one image.
- [x] Your website must have at least one stylesheet file.
- [x] Your stylesheet(s) must use at least five different CSS properties, and at least five different types of CSS selectors. You must use the #id selector at least once, and the .class selector at least once.
- [x] Your stylesheet(s) must include at least one mobile-responsive @media query, such that something about the styling changes for smaller screens
- [x] You must use Bootstrap 4 on your website, taking advantage of at least one Bootstrap component, and using at least two Bootstrap columns for layout purposes using Bootstrap’s grid model.
- [x] Your stylesheets must use at least one SCSS variable, at least one example of SCSS nesting, and at least one use of SCSS inheritance.
- [x] In README.md, include a short writeup describing your project, what’s contained in each file, and (optionally) any other additional information the staff should know about your project.

## Description
- The following project is a personal website. It contains 4 html files: ```index.html```,```about.html```,```portfolio.html``` and ```contact.html```

- For the SCSS requirements, browsers cannot read natively those files. These need to be compiled first. To do that I used the "Live Sass Compiler" extension

- Media queries were included using a media attribute in each of the stylesheets link tags. For exmaple
```html
<link rel="stylesheet" href="./css/iphone.css" type="text/css" />
<link rel="stylesheet" media="only screen and (min-device-width: 480px)" href="./css/ipad.css" type="text/css" />
```
In this case, if the viewport is larger than 480px, the ```/css/ipad.css``` stylesheet will take over.