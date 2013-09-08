# Clearfix [![Build Status](https://secure.travis-ci.org/css-recipes/clearfix.png?branch=master)](http://travis-ci.org/css-recipes/clearfix)

> A popular way to contain floats without resorting to using presentational markup.

## Getting Started

If you haven't used [css-recipes](http://css-recipes.putaindecode.io/) before, be sure to check out the [Getting Started](http://css-recipes.putaindecode.io/getting-started) guide, as it explains consume the recipes using Bower. Once you're familiar with that process, you may install this recipe with this command:

```shell
bower install css-recipe-clearfix --save
```

Once the recipe has been installed (& assuming `bower_components` folder is in your Sass import paths), it may be enabled inside your Sass file with this line:

```scss
@import "css-recipe-clearfix/index"
```

Read more below to find alternative way to use this recipe.


## Component purpose

This recipe is available as CSS & Sass (scss).
It's advised to use this one with Sass placeholder.

This component is just the famous "micro clearfix" by @necolas that you can find here http://nicolasgallagher.com/micro-clearfix-hack/

## Browser support

Should work everywhere, even on IE 6.

## CSS classes

### `crp-Clearfix`

Use this class to trigger clearfix.

## Sass placeholder(s)

Same as classes.

## Sass mixin(s)

### `crp-Clearfix()`

Generate the clearfix.

### Usage examples

#### CSS use

```html
<div class="crp-Clearfix"></div>
```

#### Sass use

_This recipes requires Sass `~3.2.0` or libsass `~0.?`_

##### Generating classes

Before importing the file, you can eventually enable css classes like this:

```sass
$crp--output: true
@import "css-recipe-clearfix/index";
```

Just remember that placeholders should be available as well.

##### Mixins use

```sass
.org-Component {
    @include crp-Clearfix(...);
}
```

## Release History

 * 2013-09-09   v0.1.0   First release from Compass Recipes.

---

Recipe submitted by ["MoOx" Maxime Thirouin](http://moox.io)