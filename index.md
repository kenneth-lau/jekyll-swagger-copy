---
layout: page
title: Swagger API doc within jekyll
---

# *jekyll-swagger* layout test
These two pages demonstrate how the Swagger API documentation are output using *jekyll-swagger*. 

- [Petstore API](/jekyll-swagger-copy/example-1.html) 
- [Uber API](/jekyll-swagger-copy/example-2.html)

## Issues

- No API console/explorer ("Try it out")
- Doesn't show full spec file
  - No authentication/security
  - No descriptions
  - Only shows the endpoints
  - Doesn't show schema



# *Original Site Test*

_jekyll-swagger_ is a [Jekyll](http://jekyllrb.com/) layout that allow you to
include a [Swagger](http://swagger.io/) API documentation directly in a page.
Checkout examples to see how it renders!

**Bonus:** _jekyll-swagger_ works with GitHub pages!


## Usage instruction

 1. Download
 [jekyll-swagger](https://github.com/jexhson/jekyll-swagger/zipball/master)
 (you can also clone it).
 2. Copy `_layouts/swagger.html` and `_saas/_swagger.scss` into your jekyll site.
 3. Add import `swagger` in `css/main.scss` (like [here](https://github.com/jexhson/jekyll-swagger/blob/gh-pages/css/main.scss#L51))
 4. You can now create pages with the swagger layout (`layout: swagger`).

Swagger API doc can be either [within the page](https://raw.githubusercontent.com/jexhson/jekyll-swagger/gh-pages/example-1.md)
or in a [separate file](https://raw.githubusercontent.com/jexhson/jekyll-swagger/gh-pages/_data/fruits.yml)
and specified in your page with `data` front matter (like [here](https://raw.githubusercontent.com/jexhson/jekyll-swagger/gh-pages/example-2.md#L4)).

## License

jekyll-swagger is released under the MIT License. See [LICENSE][1] file for
details.

## Links

The official site for the library is at <http://jexhson.github.io/jekyll-swagger/>.


[1]: https://github.com/jexhson/jekyll-swagger/blob/master/LICENSE
