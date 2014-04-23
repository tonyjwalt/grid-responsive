# grid-responsive

A basic fluid responsive grid written in SCSS with support for column and gutter variables.

## File Structure
+ *_css* - The base scss files that the grid is written from.
  + *_global-grid.scss* - variables and mixins for the grid
  + *_rspGrid-x.scss* - base code for the grid
  + *example.scss* - styles specific to the example grid index page
  + *main.scss* - manifest scss file that pulls in all needed css files
+ *dist* - folder containing compiled grid css file

## Create a Build
+ Terminal into base folder *grid-responsive*
+ Run: *sass --watch _css:dist*

## To Do
+ further automate class creation based on sizes object
+ add back in equal height options - it's own module
+ add back in background color option - it's own module
+ add row reorder - it's own module
+ better structure for grid example background fills (using a background instead of cols)
+ support for various size gutters depending upon size

## Known Issues
+ Potential rounding errors in browsers that don't support percents with decimal values.

### License
The MIT License (MIT)