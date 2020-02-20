# Bootstrap CSS Grid Only

## Purpose

There are times when you only want to use the excellent Bootstrap grid functionality but don't want the extra classes and typography changes included, often when asked to work on existing client sites that do not include any responsive frameworks and you just want to get the changes done quickly and responsively. With Bootstrap 4, extracting the grid functionality is easy.

### Included Features

-  Grid framework
-  Responsive Utilities (ported from alpha)
-  `.img-fluid` class (formerly `.img-responsive` in Bootstrap 3)
-  `clearfix` utility

## Installation

### NPM

```bash
npm install bootstrap-css-grid-only --save
```

<!-- ### Bower Installation

```bash
bower install bootstrap-css-grid-only
``` -->

## Usage

Unlike traditional Bootstrapped, the grid must be wrapped with the `.rllyhz-wrapper` class in an attempt to minimize potential conflicts with other libraries.

Simply download the appropriate CSS file and include it in your HTML header (you only need one):

-  `app.css` - The expanded version
-  `app.min.css` - The minified version

Documentation for the [grid system](https://getbootstrap.com/docs/4.1/layout/grid/) may be found on the [Bootstrap web site](https://getbootstrap.com/).

### Linking Stylesheets

Add the following to the head of your web page:

```html
<link rel="stylesheet" href="rllyhz/css/app.min.css" />
```

### Basic Usage Example

```html
<div class="rllyhz-wrapper">
   <div class="container">
      <div class="row">
         <div class="col-md-4">.col-md-4</div>
         <div class="col-md-4">.col-md-4</div>
         <div class="col-md-4">.col-md-4</div>
      </div>
      <div class="row hidden-sm-down">
         <!-- Hidden on small screens -->
         <div class="col-md-6">.col-md-6</div>
         <div class="col-md-6">.col-md-6</div>
      </div>
   </div>
</div>
```

Thanks.
