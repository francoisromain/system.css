# system.css-boilerplate

[francoisromain.github.io/system.css-boilerplate/](http://francoisromain.github.io/system.css-boilerplate)

A minimal CSS boilerplate based on:

- [normalize.css](https://necolas.github.io/normalize.css/)
- [cssnext](http://cssnext.io)
- [system.css](http://francoisromain.github.io/system.css)

* * * 

## Installation

Clone this repo

    $ git clone https://github.com/francoisromain/system.css-boilerplate.git

Install dependencies

    $ npm install

* * * 

### Automations

Compile css

    $ npm run build

Watch, compile and livereload

    $ npm start

Lint

    $ npm test

* * * 

## Usage

### Settings

- [settings](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/settings.css)

[cssnext](http://cssnext.io) brings _css variables_, _calc()_, _autoprefixer_ and many other goodies. In your `settings.css`, set the variables in the `:root` declaration and they are available inside your CSS.

### Reset

- [normalize](https://github.com/necolas/normalize.css/blob/gh-pages/src/normalize.css)
- [print](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/print.css)
- [reset](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/reset.css)

Consistent styling accross browsers, basic @print reset and consistent vertical rhythm. 


### Helper classes

- [typography](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/typography.css). See [postcss-typescale](https://github.com/francoisromain/postcss-typescale#usage) for documentation.
- [lists](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/lists.css)
- [buttons](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/buttons.css). See [postcss-button](https://github.com/francoisromain/postcss-button#usage) for documentation.
- [forms](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/forms.css)
- [tables](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/tables.css)
- [utils](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/utils.css)

Ready to use helper classes. Inspect elements on the [demo page](http://francoisromain.github.io/system.css/) to get the class names.

### Grids
- [grid-system](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/grid-system.css). See [postcss-grid-system](https://github.com/francoisromain/postcss-grid-system#usage) for documentation.
- [grid-fluid](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/grid-fluid.css). See [postcss-grid-fluid](https://github.com/francoisromain/postcss-grid-fluid#usage) for documentation.
- [margins](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/margins.css)

### Ui

- [paddings](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/paddings.css)
- [colors](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/colors.css)
- [ui](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/ui.css)

### Tools

- [tools](https://github.com/francoisromain/system.css-boilerplate/blob/gh-pages/src/tools.css)

Add classes to the main `html` element: 

- `grid`: display baseline grid
- `debug`: add a background color to every blocs

* * * 

## todo

- [ ] feat: add media object
- [ ] feat: add code and pre styles
- [ ] fix: indent list in list
- [ ] fix: tooltip position
- [ ] feat: add more ui components