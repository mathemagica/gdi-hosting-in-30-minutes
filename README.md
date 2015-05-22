GDI Hosting in 30 Minutes
======================

This course is intended to be an addendum to the official Girl Develop It Intro to HTML/CSS course. Material here was developed by Ann Lewis, with some slides borrowed from the Core Intro Web Concepts course. 

## Suggested course description is below:

*So, you just built your first website in Intro to HTML/CSS class! Now, how can you make this website accessible to other people?*

In this class, we will walk through the basics of hosting: what it means, how to do it, and the options and tradeoffs associated with different hosting providers. At the very end of the class, we'll walk you through uploading your html and css files to dropbox.

## Theme customization

You can change theme colors by changing the theme css to any of the following options:
```html
  <link rel="stylesheet" href="css/theme/gdidefault.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdilight.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdisunny.css" id="theme">
  <link rel="stylesheet" href="css/theme/gdicool.css" id="theme">
```
You can change the text editor theme by changing the highlight.js css to the following options:
```html
  <link rel="stylesheet" href="lib/css/dark.css">
  <link rel="stylesheet" href="lib/css/light.css">
```
You can change transition by changing the reveal transition property in Reveal.initialize
```javascript
  Reveal.initialize({
  				transition:  'default', // default/cube/page/concave/zoom/linear/none
  			});