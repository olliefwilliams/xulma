# Xulma.scss
A minimal, configurable flexbox column framework based heavily on the excellent [Bulma](https://github.com/jgthms/bulma).

This framework makes no presumptions about the user's existing layout or media queries, and by configuring the variables at the top of the SCSS file, allows much more freedom and responsiveness than Bulma's flexbox column implementation. It does this whilst following the same straightforward, easy-to-understand "class syntax" as Bulma.

## Key changes

1. Modifiers defined in bulma's column framework are now accessible to "turn on and off" at any breakpoint (e.g. `is-vcentered` and `is-not-vcentered` can be appended with a media query name to turn vcentering on and off)
2. Column sizes in fractions (e.g. `is-one-fifth`) are no longer available, only the 12 column system (`is-1` through to `is-12`) is in place.
