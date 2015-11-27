# LM Webfonts

This repository contains fonts and css files to be able to use the
'Latin Modern' font family on a modern web browser. These were created
by [GUST][1] by working on the foundation of the [Computer Modern][2] by
Donald Knuth.

## Use
First, you need to load the font on your webpage, you do this by using
one or more of the `.css` files in `style/`.

For example, adding the following if you wanted to use the font 'Lucida
Modern Mono'. The families are defined in those files.

```html
<link rel="stylesheet" href="style/latinmodern-mono.css" type="text/css" charset="utf-8" />
```

After doing that, you can safely use something like the following to
style the elements of your pages.

```css
pre, kbd {
    font-family: 'Latin Modern Mono', 'Courier New', Courier, monospace;
}
```

## Origin
This repository contains the fonts of the `Latin Mono` font family,
repackaged to be used on webpages and able to be displayed on modern web
browsers.

The font files in their current formats were downloaded from [Font
Squirrel][3]. The files were split into three different "Webfont Kit"
downloads as follows:

- [Latin Modern Mono][4]: Typewriter Type face
- [Latin Modern Roman][5]: Serif Type face
- [Latin Modern Sans][6]: Sans Serif Type face

## License
The files in the directory `font/` are covered by the `GUST Font License`
as explained in the `LICENSE.md` file in this directory.

All other files in this directory (i.e. not in the `font/` directory)
are covered under a `BSD 2-Clause License (FreeBSD/Simplified)`, also
explained in `LICENSE.md`.

[1]: http://www.gust.org.pl
[2]: https://en.wikipedia.org/wiki/Computer_Modern
[3]: http://www.fontsquirrel.com/
[4]: http://www.fontsquirrel.com/fonts/Latin-Modern-Mono
[5]: http://www.fontsquirrel.com/fonts/Latin-Modern-Roman
[6]: http://www.fontsquirrel.com/fonts/Latin-Modern-Sans
