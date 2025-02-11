# Simple CSS Framework

A **lightweight**, **minimalist**, and **customizable** CSS framework designed to help developers build modern web designs quickly.

## Installation
To install the framework, you can:

1. Download the `simple.css` file from the [repository](https://github.com/liu00635/simple-css-framework).
2. Include it in your HTML file.
 ```html
   <link rel="stylesheet" href="css/simple.css">
```

## Usage
Once installed, you can use the CSS classes to style your HTML elements. Here are some examples:
```html
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Simple CSS Framework</title>
    <link rel="stylesheet" href="css/simple.css">
</head>
<body>

    <header class="container">
        <h1 class="text-center">Welcome to Simple CSS</h1>
    </header>

    <section class="container">
        <button class="btn btn-primary">Click Me</button>
    </section>

</body>
</html>

```

## Customization
You can easily customize the framework by overriding default variables in your own CSS file.

1. Copy the _variables.scss file into your own custom stylesheet.
```scss
$primary-color: #ff5733;
$secondary-color: #3498db;
$font-size-base: 16px;
$spacing-md: 20px;

```
2. Include your custom styles after the framework.
```html
<link rel="stylesheet" href="css/simple.css">
<link rel="stylesheet" href="css/custom.css">

```
## Utility Classes
Simple CSS Framework provides a variety of utility classes for quick styling.
Flexbox Utilities
```html
<div class="flex justify-center align-center">
    <div class="box">Item 1</div>
    <div class="box">Item 2</div>
</div>
```
* .d-flex → Enables flexbox
* .justify-center → Centers content horizontally
* .align-center → Centers content vertically

## Spacing Utilities
```html
<div class="p-4 m-2">Content</div>
```
* .p-4 → Adds padding
* .m-2 → Adds margin

## Typography Utilities
```html
<h1 class="text-primary">Hello World</h1>
<p class="text-bold">This is a paragraph.</p>
```
* .text-primary → Applies primary color
* .text-bold → Applies bold text

Thank you for tring our CSS framework! Enjoy!🚀😊



