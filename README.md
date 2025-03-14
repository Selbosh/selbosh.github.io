# Tea & Stats

https://selbydavid.com

This web site is written using the [`blogdown`](https://github.com/rstudio/bookdown) package by Yihui Xie and rendered using the [Hugo](http://gohugo.io/) static web site generator.

It is deployed to GitHub Pages using [GitHub Actions](https://github.com/features/actions).
This means the (R) Markdown files are rendered into HTML by a cloud server, rather than having to generate them locally and then push them online.
Thus, I can write and edit blog posts from anywhere without any special software installed.

The blog theme is called [Hugo Tea](https://github.com/Selbosh/hugo-tea) and you can download it for yourself if you like.

## Development 
The theme is a git submodule, so when you clone the blog repository for the first time, you may find yourself with an empty `themes` folder and the web site not rendering locally.
Include the theme as well as the blog itself with:
```bash
git clone git@github.com:Selbosh/selbosh.github.io.git
git submodule init
git submodule update
```

Or as a one-liner:
```bash
git clone --recurse-submodules git@github.com:Selbosh/selbosh.github.io.git
```
