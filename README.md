The GitHub Matrix Sceensaver
====================

<blockquote>The latest commits from GitHub visualized in a Matrix-style animation.</blockquote>

<img src="http://winterbe.com/image/matrix-has-you.gif">

The GitHub Matrix Screensaver for Mac OSX shows a constant stream of recent commits from GitHub. It's based on my [GitHub Matrix](https://github.com/winterbe/github-matrix) webapp project and on Tom Robinsons [WebSaver](https://github.com/tlrobinson/WebSaver) project (kudos).

### http://winterbe.com/projects/github-matrix/

<img src="http://winterbe.com/image/matrix.png">

For more infos about the GitHub Matrix see this repository:

### https://github.com/winterbe/github-matrix

## Install (Mac OSX only)

* Fork or clone this project, then double click the file `Web.saver` in the project folder.
* Open the Mac OSX preferences, choose Screensaver and activate `Matrix`

## Uninstall

Open the Mac OSX preferences, choose Screensaver, right click on `Matrix` and choose delete.

## Contribute

Feel free to [fork](https://github.com/winterbe/github-matrix-screensaver/fork) this project and send me pull requests. You can also send me feedback via [Twitter](https://twitter.com/benontherun) or by [opening an issue](https://github.com/winterbe/github-matrix-screensaver/issues).

## Development

After making changes to the html, css and js files in Web.saver/Contents/Resources/ to see your changes, you need to:

1. Uninstall the screensaver (as described above)

2. Clear the cache

    rm -rf ~/Library/Caches/com.apple.systempreferences/

3. Re-install the screensaver

4. Sometimes you may also need to add a cache-busting query string to
   the css and js URL's in index.html for instance, the `?v3` in:

    * `<script src="matrix.js?v3"></script>`, or
    * `<link rel="stylesheet" href="matrix.css?v3">`

    But you shouldn't need commit these, I've just found that they  may just help during the iterative development process

## Font face and font size changes

This fork customizes the font from Courier New to Google's [Oxygen Mono](https://fonts.google.com/specimen/Oxygen+Mono) (which more closely resembles the Menlo font I use when coding on the Mac) and increases the font size to 28px from the default 14px (which looks quite tiny to me on a large retina display :))


## Binary License

See: https://github.com/tlrobinson/WebSaver

<blockquote>
Copyright (c) 2013, Thomas Robinson http://tlrobinson.net

Copyright (c) 2012, Senseg Ltd http://www.senseg.com

All rights reserved.
</blockquote>
