# system.css

[francoisromain.github.io/system.css/](http://francoisromain.github.io/system.css)

A minimal CSS boilerplate based on:

- [normalize.css](https://necolas.github.io/normalize.css/)
- [cssnext](http://cssnext.io)
- [postcss-grid-system](http://francoisromain.github.io/postcss-grid-system)
- [postcss-grid-fluid](http://francoisromain.github.io/postcss-grid-fluid)
- [postcss-typescale](http://francoisromain.github.io/postcss-typescale)
- [postcss-button](http://francoisromain.github.io/postcss-button)

* * * 

## Installation

#### Clone this repo

    $ git clone https://github.com/francoisromain/system.css.git

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

- [settings](https://github.com/francoisromain/system.css/blob/master/src/settings.css)

#### Reset

Consistent styling accross browsers, basic @print reset and corrects broken and missing styles. 

- [normalize](https://github.com/necolas/normalize.css/blob/master/src/normalize.css)
- [print](https://github.com/francoisromain/system.css/blob/master/src/print.css)
- [reset](https://github.com/francoisromain/system.css/blob/master/src/reset.css)

#### Elements

- [typography](https://github.com/francoisromain/system.css/blob/master/src/typography.css). See [postcss-typescale](https://github.com/francoisromain/postcss-typescale#usage) for documentation.
- [lists](https://github.com/francoisromain/system.css/blob/master/src/lists.css)
- [buttons](https://github.com/francoisromain/system.css/blob/master/src/buttons.css). See [postcss-button](https://github.com/francoisromain/postcss-button#usage) for documentation.
- [forms](https://github.com/francoisromain/system.css/blob/master/src/forms.css)
- [tables](https://github.com/francoisromain/system.css/blob/master/src/tables.css)

#### Layout

- [utils](https://github.com/francoisromain/system.css/blob/master/src/utils.css)
- [grid-system](https://github.com/francoisromain/system.css/blob/master/src/grid-postcss-structure). See [postcss-grid-system](https://github.com/francoisromain/postcss-grid-system#usage) for documentation.
- [grid-fluid](https://github.com/francoisromain/system.css/blob/master/src/grid-fluid.css). See [postcss-grid-fluid](https://github.com/francoisromain/postcss-grid-fluid#usage) for documentation.
- [margins](https://github.com/francoisromain/system.css/blob/master/src/margins.css)
- [paddings](https://github.com/francoisromain/system.css/blob/master/src/paddings.css)
- [sticky-footer](https://github.com/francoisromain/system.css/blob/master/src/sticky-footer.css)

#### Ui

- [colors](https://github.com/francoisromain/system.css/blob/master/src/colors.css)
- [ui](https://github.com/francoisromain/system.css/blob/master/src/ui.css)

#### Tools

Classes to add to the main `html` element (`grid`: display baseline grid / `debug`: add a background color to every DOM elements)

- [tools](https://github.com/francoisromain/system.css/blob/master/src/tools.css)
