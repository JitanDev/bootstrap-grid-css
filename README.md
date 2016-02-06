# bootstrap.grid.css

**Version:** 4.0.0-alpha.2

**License:** MIT ([https://github.com/twbs/bootstrap/blob/master/LICENSE](https://github.com/twbs/bootstrap/blob/master/LICENSE))

**Contents Copyright:** (c) 2011-2016 Twitter, Inc.

## Purpose

There are times when you only want to use the excellent Bootstrap grid functionality but don't want the extra classes and typography changes included. With Bootstrap 4, extracting the grid functionality is easy.

### Included Features

* Grid framework (flex enabled)
* Responsive Utilities

## Usage

I have already taken the liberty of extracting the grid and responsive utilities mixins (for those who don't know how or don't want to bother keeping it updated), which can be found in `dist/css/bootstrap-grid.css`. I also wrapped the classes with the `.bootstrap-wrapper' class to avoid conflicts with other classes that may already be used in a project.

Simply download the appropriate CSS file and include it in your HTML header (you only need one):
* `bootstrap-grid.css` - The expanded version
* `bootstrap-grid.min.css` - The minified version
* `bootstrap-grid-noflex.min.css` - The minified version with flex support disabled

Documentation for the [grid framework](http://v4-alpha.getbootstrap.com/layout/grid/) and [responsive utilities](http://v4-alpha.getbootstrap.com/layout/responsive-utilities/) may be found on the [Bootstrap 4 web site](http://v4-alpha.getbootstrap.com/).

### Basic Example

	<div class="bootstrap-wrapper">
		<div class="container">
			<div class="row">
				<div class="col-md-4">.col-md-4</div>
				<div class="col-md-4">.col-md-4</div>
				<div class="col-md-4">.col-md-4</div>
			</div>
			<div class="row hidden-sm-down"> <!-- Hidden on small screens -->
				<div class="col-md-6">.col-md-6</div>
				<div class="col-md-6">.col-md-6</div>
			</div>
		</div>
	</div>

## Custom Build Tutorial

*Coming soon...*

## Credits

* [Bootstrap](http://getbootstrap.com)
