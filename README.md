
# My Name is Habibur Rahaman


Currently, I am doing my Masters in the Department of Computer Science and Engineering from the Indian Institute of Technology, Kharagpur. My research interest focuses on VLSI test research-related topics such as FSM based Testing and Scan and Non-Scan based Testing using machine learning.
I'm also working as a DFT Intern at Intel Corporation, Bangalore.

(https://www.linkedin.com/in/habibur-rahaman-00a37117a/)

# Features
- Fully responsive
- [Disqus](https://disqus.com/) integration for comments.
- Google Analytics integration.
- Syntax Highlighter (using [highlight.js](https://highlightjs.org/)).
- Support for categories.
- Font-Awesome Icons.
- Optimized for SEO.
- Coolest [404 page ever](http://kronik3r.github.io/daktilo/404.html).

# How to use it
Start by cloning the repository, then check the `_config.yml` file and change it accordingly.
Note that the `title` property is what will be displayed as logo.

Finally execute `jekyll serve --watch` and head to [localhost:4000](http://127.0.0.1:4000) to see the result.

# Using categories
Categories are little bit tricky. Please make sure to do the following for each category:

- Create a file within `categories` folder with the name of your category
For example let's say that we have a category called `An Awesome Category` you will need to add an `an-awesome-category.html` file with this content:

``` html
---
layout: category
category: an-awesome-category
permalink: /categories/an-awesome-category/
---

```

- Create an entry inside `_data/categories.yml`

``` html
- slug: an-awesome-category
  name: An Awesome Category
```

- Then you will see it in the footer in the `Explore` section.

# License

The contents of this repository is licensed under [The MIT License.](https://opensource.org/licenses/MIT)
