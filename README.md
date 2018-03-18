# Solarized Light Bold Nature Syntax theme

This is a modification of the default [Solarized Light Atom syntax theme](https://atom.io/themes/solarized-light-syntax), especially targeted towards PHP. The default [solarized](http://ethanschoonover.com/solarized) colors are nice for viewing, but I feel like they don't provide enough visual contrast between elements.

I chose the colors, weights, and styles to provide a little more "pop" between the elements while retaining a color scheme heavy on green/blue/gray with orange and purple accents; hence the name "Bold Nature".

## Known Issues
* No color differentiation between **public**, **protected**, and **private**. Ideally, I'd make **public** green, **protected** yellow, and **private** red, but Atom's parser(?) doesn't seem to provide any way to differentiate between them.
* Single-line SQL statements have syntax highlighting while multi-line ones do not. This seems to be the intended behavior from the parent project, but it's very odd-looking, at least in this color scheme.
* Regular expressions also have syntax highlighting, which also looks weird to me.
