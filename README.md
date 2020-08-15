# [Bulma](https://bulma.io)

Befly is a **modern CSS framework** based on [Flexbox](https://developer.mozilla.org/en-US/docs/Web/CSS/CSS_Flexible_Box_Layout/Using_CSS_flexible_boxes). Strongly inspired and initially forked from [Bulma](https://github.com/jgthms/bulma).

## Quick install

Befly is constantly in development and will be published as soon as possible.

## CSS only

Befly is a **CSS** framework. As such, the sole output is a single CSS file: [befly.css](https://github.com/dualstackio/befly/blob/master/css/befly.css)

You can either use that file, "out of the box", or download the Sass source files to customize the (bulma) [variables](https://bulma.io/documentation/overview/variables/).

There is **no** JavaScript included. People generally want to use their own JS implementation (and usually already have one). Befly can be similar to Bulma considered "environment agnostic": it's just the style layer on top of the logic.

## Browser Support

Befly uses [autoprefixer](https://github.com/postcss/autoprefixer) to make (most) Flexbox features compatible with earlier browser versions. According to [Can I use](https://caniuse.com/#feat=flexbox), Befly is compatible with **recent** versions of:

- Chrome
- Edge
- Firefox
- Opera
- Safari

Internet Explorer (10+) is only partially supported.

## Documentation

The documentation resides in the [docs](docs) directory, and is built with the Ruby-based [Jekyll](https://jekyllrb.com/) tool.

Browse the [online documentation here.](https://bulma.io/documentation/overview/start/) (bulma)

## Copyright and license ![Github](https://img.shields.io/github/license/jgthms/bulma?logo=Github)

Code copyright 2020 Timo Zacherl. Code released under [the MIT license](https://github.com/jgthms/bulma/blob/master/LICENSE).
