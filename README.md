# system.css-boilerplate

[francoisromain.github.io/system.css-boilerplate/](http://francoisromain.github.io/system.css-boilerplate)

A minimal CSS boilerplate based on:

- [normalize.css](https://necolas.github.io/normalize.css/)
- [cssnext](http://cssnext.io)
- [system.css](http://francoisromain.github.io/system.css)

* * * 

## Installation

#### Clone this repo

    $ git clone https://github.com/francoisromain/system.css-boilerplate.git

#### Install dependencies

    $ npm install

* * * 

## Usage

#### Compile CSS

    $ npm run build

#### Watch, compile and livereload

    $ npm start

#### Lint

    $ npm test

* * * 

## Content

#### Settings

[cssnext](http://cssnext.io) is a bundle of PostCSS plugins which brings _css variables_, _calc()_, _autoprefixer_ and many other goodies. To use variables for example, set them in `settings.css`, within the `:root` declaration and they are available accross all your CSS files. 

- [settings](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/settings.css)

#### Reset

Consistent styling accross browsers, basic @print reset and corrects broken and missing styles. 

- [normalize](https://github.com/necolas/normalize.css/blob/gh-pages/src/normalize.css)
- [print](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/print.css)
- [reset](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/reset.css)

#### Helper classes

Consistent vertical rhythm, ready to use helper classes and more. Inspect elements on the [demo page](http://francoisromain.github.io/system.css-boilerplate/) to get the class names.

- [typography](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/typography.css). See [postcss-typescale](https://github.com/francoisromain/postcss-typescale#usage) for documentation.
- [lists](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/lists.css)
- [buttons](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/buttons.css). See [postcss-button](https://github.com/francoisromain/postcss-button#usage) for documentation.
- [forms](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/forms.css)
- [tables](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/tables.css)
- [utils](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/utils.css)

#### Grids

- [grid-system](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/grid-system.css). See [postcss-grid-system](https://github.com/francoisromain/postcss-grid-system#usage) for documentation.
- [grid-fluid](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/grid-fluid.css). See [postcss-grid-fluid](https://github.com/francoisromain/postcss-grid-fluid#usage) for documentation.
- [margins](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/margins.css)

#### Ui

- [paddings](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/paddings.css)
- [colors](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/colors.css)
- [ui](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/ui.css)

#### Tools

Classes to add to the main `html` element (`grid`: display baseline grid / `debug`: add a background color to every DOM elements)

- [tools](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/tools.css)

* * * 

## todo

- [ ] feat: add media object
- [ ] feat: add code and pre styles
- [ ] fix: indent list in list
- [ ] fix: tooltip position
- [ ] feat: add more ui components