## normalize-stylus

A port to [Stylus](https://github.com/learnboost/stylus) of [normalize.css](https://github.com/necolas/normalize.css).

## Installing

via [Bower](https://github.com/bower/bower):

```
$ bower install normalize-stylus
```

via [Component](https://github.com/component/component):

```
$ component install skw/normalize.stylus
```

## A note on mixins

Normalize-stylus utilizes a simple stylus box-sizing mixin:

```
box-sizing($boxmodel)
  -webkit-box-sizing $boxmodel
  -moz-box-sizing $boxmodel
  box-sizing $boxmodel
```

which can be found in `lib/mixins.styl`. Alternatively you can utilize [nib](https://github.com/visionmedia/nib) and comment out the `@import lib/mixins.styl` in `normalize.styl` (line 9).

## Contributing

Pull requests are welcome.

## Acknowledgements

Normalize.css is a project by [Nicolas Gallagher](https://github.com/necolas),
co-created with [Jonathan Neal](https://github.com/jonathantneal).