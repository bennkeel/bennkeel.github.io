---
title: Fire Recovery in Philadelphia, PA
subtitle: An analysis of the social impacts of structure fires to support the Philadelphia Fire Department.
date: 2023-05-13 00:00:00
description: Analysis of the Fire Department's incident-level data and Philadelphia's permit, sales, and vacancy data revealed that structure fires are associated with an increase in all three outcomes. Our team then built model for to predict every property's future after a potential fire and assembled a tool to explore the forecast.
featured_image: /projects/philafire/demo.jpg
accent_color: '#4C60E6'
gallery_images:
  - demo.jpg
  - demo.jpg
  - demo.jpg
---

Project at the University of Pennsylvania, Spring 2023

By Myself, Myron Banez, Kendra Hills, supervised by professors Michael Fichman and Matt Harris. 

In collaboration with and support of Kathy Matheson, Andrew Newell, and Commissioner Adam Thiel of the Philadelphia Fire Department.

[Link to Forecast Site](https://bennkeel.github.io/MUSA_Practicum/site/index.html)

[Link to R Markdown](https://bennkeel.github.io/MUSA_Practicum/Phila_Fire_rmd_final.html) with in-depth data analysis and R code chunks.

### Abstract

![](/images/demo.jpg)

You can create lists:

* Simple bulleted lists
* Like this one
* Are cool

And:

1. Numbered lists
2. Like this other one
3. Are great too

You can also add blockquotes, which are shown at a larger width to help break up the layout and draw attention to key parts of your content:

> “Simple can be harder than complex: You have to work hard to get your thinking clean to make it simple. But it’s worth it in the end because once you get there, you can move mountains.”

The theme also supports markdown tables:

| Item                 | Author        | Supports tables? | Price |
|----------------------|---------------|------------------|-------|
| Duet Jekyll Theme    | Jekyll Themes | Yes              | $49   |
| Index Jekyll Theme   | Jekyll Themes | Yes              | $49   |
| Journal Jekyll Theme | Jekyll Themes | Yes              | $49   |

And footnotes[^1], which link to explanations[^2] at the bottom of the page[^3].

[^1]: Beautiful modern, minimal theme design.
[^2]: Powerful features to show off your work.
[^3]: Maintained and supported by the theme developer.

You can throw in some horizontal rules too:

---

#### Image galleries

Here's a really neat custom feature we added – galleries:

{% include post-components/gallery.html
	columns = 2
	full_width = true
	images = "/images/demo.jpg,/images/demo.jpg,/images/demo.jpg,/images/demo.jpg,
	"
%}

Inspired by the Galleries feature from WordPress, we've made it easy to create grid layouts for your images. Just use a simple Liquid snippet in your post to create a masonry grid image layout:

{% raw %}
```liquid
{% include post-components/gallery.html
	columns = 2
	full_width = true
	images = "/images/demo.jpg,/images/demo.jpg,/images/demo.jpg,/images/demo.jpg,
	"
%}
```
{% endraw %}

*See what we did there? Code and syntax highlighting is built-in too!*

Change the number inside the 'columns' setting to create different types of gallery for all kinds of purposes. You can even click on each image to seamlessly enlarge it on the page.


#### Image carousels

Here's another gallery with only one column, which creates a carousel slide-show instead.

A nice little feature: the carousel only advances when it is in view, so your visitors won't scroll down to find it half way through your images.

{% include post-components/gallery.html
	columns = 1
	full_width = true
	images = "/images/demo.jpg,/images/demo.jpg,/images/demo.jpg
	"
%}

### Pretty cool, huh?

We've packed this theme with powerful features to show off your work.
Why not put them to use on your new website?

<a href="https://jekyllthemes.io/theme/made-portfolio-jekyll-theme" class="button--fill">Get This Theme</a>