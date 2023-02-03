# councilsofthefuture.org
Source code for [councilsofthefuture.org](https://www.councilsofthefuture.org/), based on [esculate/hugo-split-theme](https://github.com/escalate/hugo-split-theme).

The underlying tech of this website uses the static site generator [Hugo](https://gohugo.io/).

## TODO
- content/posts: investigate splitting posts by year, or make sure it keeps listing irrespective of year.
- posts/list.html:

  * separate date and title classes, so former doesn't get underlined. see ewen.io for inspiration. also may need a separate css style.
  * add tags to the bottom of the article.
- posts/single.html: create params for sub title and consistent image rendering and resizing (350px for width)