# housing-and-reproduction

*Jekyll website for the Trying to Stay Put: Reproductive and Housing Justice During the 2008 Financial Crisis Project @ [Boston College](https://bc.edu)*

By Meghan McCoy

## About

This project covers many purposes. On one hand, this website is my attempt to understand, albeit from a scholarly perspective, the 2008 financial crisis and why it was so devastating for lower-middle income families like my own. At its core, however, this project also combines my research interests of reproductive justice and how it intersects with and shapes other fields including housing and economic justice.

In the pages that follow, I will argue that unlike popular representations of the 2008 financial crash as the "Great Recession," a term that implies a one-off crisis that was overshadowed only by the Great Depression, the roots of this socio-economic disaster stretched back far longer than the handful of years unethical subprime lenders had been operating. Instead, I begin my narrative in the late 1980s, when "welfare reform" proposals amassed astounding levels of social and political support and made reproductive and housing security for single mothers, single women, and low-middle income families all the more precarious.

## Local Development

* Follow [this guide](https://jekyllrb.com/docs/installation/) to install Ruby and Jekyll
* Install [Node](https://nodejs.org/en)
* `git clone` this repo and then `cd` inside the directory
* Comment out the `url` and `baseurl` lines of `_config.yml` when working locally
* Install Ruby dependencies by running `bundle install`
* Install Node dependencies by running `npm install`
* Run the server with `bundle exec jekyll serve`

## How to Make Changes

**To set attribution**

``` bash
README.md # this file, make sure to change with your name in the credits
CITATION.cff # the citation file, make sure to include your project name and author(s) names. Use OrcIDs if you have them
package.json # the npm package file, include the project title and author information (again)
_config.yml # the Jekyll config file, which controls how the page is put together, include project name, author names, project locations, and footer messages
```

**To change the theme**

``` bash
_sass/theme-settings.scss # edit this file to change theme colors, fonts, and the sizes of the headers/footers
_sass/custom-style.scss # edit this file to add your CSS (or SCSS) to the site. CSS here will override other files
_sass/theme.scss # advanced, contains the code for the theme itself, edit to customize the theme directly
```

**To change the site structure (the nav menu)**

```bash
_config.yml # the Jekyll config file, edit the section titled nav-menu. Note that you can nest menus using a submenu attribute
_pages/ # where you create individual site pages (either .html or .md). As you change the _config.yml you should create new files here, or rename/delete existing ones, to match _config.yml
```

**To use built-in TailwindCSS**

```bash
https://tailwindcss.com/docs # tailwind is already installed, consult the docs to look up how to use it for things like flex layout, margins, alignment, and more
```

``` html
<!-- example of a tailwindcss element that goes to width 100% and also centers the text inside-->
<div class="w-full text-center">Some text</div>
```

## Acknowledgements

Jekyll & Tailwind Setup based on [TailPages](https://github.com/harrywang/tailpages) by [Harry Wang](https://harrywang.me/) (Chinese: 王建楠)