# BASIC

BASIC is a lightweight and mobile first framework for front end development.

Designed to be lightweight and style agnostic, It's built to be flexible and modular. It is an [OOCSS](http://www.smashingmagazine.com/2011/12/12/an-introduction-to-object-oriented-css-oocss-2/)(object oriented CSS) framework. It uses [BEM](http://www.smashingmagazine.com/2012/04/16/a-new-front-end-methodology-bem-2/)(block, element, modifier) naming convention. BASIC is CSS preprocessor(SASS or LESS) based so making modifications is easy. 

BASIC isn't supposed to be a finished product. It's a starting point that you can adapt to any project you're working on and make it your own.

**BASIC is intended for developers who**

* Needs a boilerplate framework with objects and abstractions.
* Needs DRY scalability and reusable CSS.
* Are confident and competent with CSS preprocessor.
* Understand and appreciate the value of object oriented CSS.
* Are familiar with OO principles in general.

**BASIC is not intended for developer who**

* Never heard of CSS preprocessor, BEM, OOCSS, or SMACSS
* Needs a framework that supplies design. You should look into [Foundation](http://foundation.zurb.com/), [Bootstrap](http://getbootstrap.com), or [Semantic UI](http://semantic-ui.com/)

## Getting Started

Download the [latest release](https://github.com/kanikarphan/basic/master.zip) or clone the repo, `git clone git://github.com/kanikarphan/basic.git`.

## File Structure

In the ZIP file you will find all CSS, LESS, SASS, and font files ready to use for your project.

```
basic/
|--- css/
|    |--- basic.css
|    |--- basic.min.css
|--- fonts/
|    |--- Basic Icons Webfont
|    |--- OpenSans Webfont
|--- index.html
|--- less/
|    |--- basic.less
|    |--- generic/
|    |    |--- _align.less
|    |    |--- _brand.less
|    |    |--- _clearfix.less
|    |    |--- _column.less
|    |    |--- _float.less
|    |    |--- _font.less
|    |    |--- _heading.less
|    |    |--- _image.less
|    |    |--- _margin.less
|    |    |--- _mixins.less
|    |    |--- _normalize.less
|    |    |--- _padding.less
|    |    |--- _print.less
|    |    |--- _restart.less
|    |    |--- _row.less
|    |    |--- _scaffolding.less
|    |    |--- _text.less
|    |    |--- _variables.less
|    |    |--- _visibility.less
|    |--- objects/
|    |    |--- _button.less
|    |    |--- _caption.less
|    |    |--- _form.less
|    |    |--- _icons.less
|    |    |--- _list.less
|    |    |--- _media.less
|    |    |--- _modal.less
|    |    |--- _progress.less
|    |    |--- _table.less
|--- README.md
|--- sass/
|    |--- basic.scss
|    |--- generic/
|    |    |--- _align.scss
|    |    |--- _brand.scss
|    |    |--- _clearfix.scss
|    |    |--- _column.scss
|    |    |--- _float.scss
|    |    |--- _font.scss
|    |    |--- _heading.scss
|    |    |--- _image.scss
|    |    |--- _margin.scss
|    |    |--- _mixins.scss
|    |    |--- _normalize.scss
|    |    |--- _padding.scss
|    |    |--- _print.scss
|    |    |--- _restart.scss
|    |    |--- _row.scss
|    |    |--- _scaffolding.scss
|    |    |--- _text.scss
|    |    |--- _variables.scss
|    |    |--- _visibility.scss
|    |--- objects/
|    |    |--- _button.scss
|    |    |--- _caption.scss
|    |    |--- _form.scss
|    |    |--- _icons.scss
|    |    |--- _list.scss
|    |    |--- _media.scss
|    |    |--- _modal.scss
|    |    |--- _progress.scss
|    |    |--- _table.scss
```

## The BASIC Way

**Mobile First**

BASIC is built mobile first. The term "mobile first", is the idea of starting with mobile styles and layer on styles optimized for larger screens only as needed. In other words, your mobile styles become the default and you no longer have to override them later. It's much simpler and less code!

**Object Oriented CSS**

BASIC takes an OOCSS approach to web development. It works in 'layers'. There are base styles and modifying styles. For example, `.button` sets the default button styles and behavior, while `.button--alpha` changes the color and `.button--big` changes the size.

## Browser Support

BASIC is a modern framework for modern browsers. It is not intended for **IE8** and lower. 

## Credits

BASIC was only possible because of the following people.

* **[Alexis Sellier](https://twitter.com/cloudhead)** for his creation of LESS
* **[Hampton Catlin](https://twitter.com/hcatlin)** for his creation of SASS
* **[Harry Roberts](https://twitter.com/csswizardry)** for his work on inuit.css
* **[Jonathan Snook](https://twitter.com/snookca)** for his work on SMACSS
* **[Nicole Sullivan](https://twitter.com/stubbornella)** for her work on OOCSS


## TODO
* Add documentation
* Add automate preprocessing of build