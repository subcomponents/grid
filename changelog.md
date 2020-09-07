# changelog

## 3.1.0

- set default gap to 0
- use css variables for flex items variations
- improve gap rules
- remove units for zero values
- add `with-auto`, `width-min` classes
- add `with-auto`, `width-min` to docs
- remove `width-content` in favor of `width-auto`, `width-min`

## 3.0.0

- update dependencies
- refactor flexbox and grid
- refactor class names

## 2.0.0

- switch media queries from `px` to `ems`
- change naming convention: now using flex/grid for containers, width/height for items
- remove autoprefixer
- remove anchorjs
- add breakpoint as variables
- move -xs to the end as suffix

## 1.9.0

- add grid to demo
- use size declaration as suffix `col-xs-1` => `col-1-xs`
- add declarations without size suffix `col-1-xs` + `col-1`
- rename align properties `align-xs-middle` => `align-y-center-xs`

## 1.8.0

- add base column class aliases

## 1.7.0

- add css grid
- remove `.col`, `.column`
- add `.col-xs-auto`
- add `--grid-gap` variable
- add `--column-min-width` variable
- use flex shorthand
- add version number to dist files

## 1.6.0

- switch to postcss
