# Gluon-CSS
WIP: Minimalistic collection of css utility and helper classes

## Scheme
Gluon follows the following scheme for creating minimalistic classes:

`prefix*`-`property`-`modifer`-`breakpoint*`-`value`

- prefix*: optionally prefixes all the generates classes with a a namespace to avoid
- property: margin, padding, text,
- modifier: left, right, bottom, center, top, etc...
- breakpoint*: optional, the shorthand name of the media breakpoint (xs, sm, md)
- value: the value set on the css property. (auto, 5, 10, left, etc...)
- separator: (-) the separator can be set individually

## Building
`npm run build`