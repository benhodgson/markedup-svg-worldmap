# Marked-Up SVG World Map

An SVG world map marked-up with [ISO 3166 country codes](http://www.iso.org/iso/home/standards/country_codes.htm).
Path (`path`) and group (`g`) elements are annotated with `cc` attributes
containing their country codes.

For example, to colour Canada red, you might use the following JavaScript:

```javascript
// 'map' should contain a reference to the embedded SVG element
map.getSVGDocument().querySelector("[cc=ca]").style.fill = "red";
```

A full example is included in the `example.html` file.

## Acknowledgements

Adapted from Al MacDonald's [Low Resolution World Map](http://en.wikipedia.org/wiki/File:World_map_-_low_resolution.svg).

## Author

Original [Low Resolution World Map](http://en.wikipedia.org/wiki/File:World_map_-_low_resolution.svg)
by Al MacDonald. This derivative work has been pruned and marked-up with
[ISO 3166 country codes](http://www.iso.org/iso/home/standards/country_codes.htm)
by [Ben Hodgson](http://benhodgson.com/).

Thanks to [Marco Vettorello](https://github.com/markov00) and [Denis Hovart](https://github.com/dhovart) for contributing fixes.

## License

This work is made available under a [Creative Commons Attribution-ShareAlike 3.0 Unported](http://creativecommons.org/licenses/by-sa/3.0/)
license. For the full license, see the `LICENSE` file.
