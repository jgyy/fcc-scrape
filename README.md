# fcc-scrape

A test repository to try scraping a website out. First repository for year 2021.

## Convert md to html using pandoc

```sh
pandoc 0.md -f markdown -t html -s -o .\0\0\0.html; rm 0.md;
```

The filename `test1.md` tells pandoc which file to convert. The `-s` option says to create a “standalone” file, with a header and footer, not just a fragment. And the `-o 0.html` says to put the output in the file `0.html`. Note that we could have omitted `-f markdown` and `-t html`, since the default is to convert from markdown to HTML, but it doesn’t hurt to include them.
