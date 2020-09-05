# Landing page for the Merely Useful projects

Uses [Hugo Lithium theme](https://github.com/jrutheiser/hugo-lithium-theme).

## Contributing

Easiest way to add stuff is in the `content/_index.md` file.
The site has to be built manually into the `docs/` folder
in order for GitHub Pages to build it.

One approach to building the website is with the R package 
[hugodown](https://github.com/r-lib/hugodown). Install it with:

```r
remotes::install_github("r-lib/hugodown")
```

And then to preview the site use:

```r
hugodown::hugo_start()
```

And to build the site to `docs/`

```r
hugodown::hugo_build(dest = "docs")
```


Any changes to the website layout needs to be done in the HTML files
in `layout` and with the CSS in the `static/main.css` file.
