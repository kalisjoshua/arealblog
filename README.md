# Joshua T Kalis - Articles

Here is how I generate my personal website.


## How To Generate Pages

``` bash
npm run pages
```

This will generate all content pages from the `content` folder.

``` bash
npm run watch
```

Will watch for file changes and re-run the static generation process.


## TODO

  - Create automated publishing pipeline (Travis, etc.)
  - Add unit tests: highlighter, sanguine
  - Classify DRAFT articles (no published date)
  - Add Sass for easier style writing (variables, nesting, minification)
  - Add JS compiling/transpiling (future features, bundling, minification)
