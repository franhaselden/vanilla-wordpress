# Vanilla Wordpress
A vanilla wordpress set-up. Based on the Starkers theme. Responsive grid, basic set up.

##The concept

To create a framework for Wordpress that is bare-bones, but ready to go with a grid system.

##The grid

In order to keep the grid super-lightweight, there are limited columns. The naming convention for the columns works in plain english. There are up to 5 different columns named by fractions. E.g:

```css
.grid.one-fifth{}
.grid.four-fifths{}

.grid.half{}

.grid.one-third{}
.grid.two-thirds{}
```

This highly readable grid system is easy to write as it doesn't require working out specific numbers of columns. If you want the grid to be half a page each, simply use `.grid.half`
