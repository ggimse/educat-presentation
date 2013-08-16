## What this is.

This the source for my short and very general presentation on using Northern Michigan University's EduCat CMS in a Composition I classroom.

## What's included.

I have included versions in [pandoc](http://johnmacfarlane.net/pandoc/) and general markdown as well as the index and markdown file I used with the [reveal.js](http://lab.hakim.se/reveal-js/) presentation software.

The included pdf was generated from pandoc using:

```shell
pandoc -t beamer educat_present.md -V theme:CambridgeUS -V colortheme:beaver -o educat.pdf
```

## License

Honestly, I'm assuming the re-usability of this is rather small considering the small audience and relative lack of detail. If you do use something and distribute it, though, make sure to give me a small nod.

For practical purposes, let say it falls under [Creative Commons Attribution 3.0 United States License](http://creativecommons.org/licenses/by/3.0/us/deed.en_US).
