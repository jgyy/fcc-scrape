# fcc-scrape

A test repository to try scraping a website out. First repository for year 2021.

## Convert md to html using pandoc

```sh
pandoc placeholder.md -f markdown -t html -s -o .\03-front-end-libraries\react-and-redux\part-001.html; git add .; git commit -am "part-001.html"; git push origin main;
```

The filename `test1.md` tells pandoc which file to convert. The `-s` option says to create a “standalone” file, with a header and footer, not just a fragment. And the `-o 0.html` says to put the output in the file `0.html`. Note that we could have omitted `-f markdown` and `-t html`, since the default is to convert from markdown to HTML, but it doesn’t hurt to include them.

The shell command will be updated from time to time.

https://teams.microsoft.com/l/meetup-join/19%3ameeting_NzEzZjUzNjYtZjA5MC00MDM3LTlmMDgtOTViNzA4Yjk5ZWM1%40thread.v2/0?context=%7b%22Tid%22%3a%227e586855-d882-4339-9a56-032d0aa10991%22%2c%22Oid%22%3a%2217b9038f-fa40-4e37-af03-99541ab95a6e%22%7d
