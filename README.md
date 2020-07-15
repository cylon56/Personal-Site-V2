---
layout: home
cover: true
image: /assets/img/blog/hydejack-9.jpg
description: >
  Hydejack is a boutique Jekyll theme for hackers, nerds, and academics,
  with a focus on personal sites that are meant to impress.
hide_description: true
selected_projects:
  - /showcase/shawn-yeager/
  - _projects/lazyren.md
projects_page: showcase.md
selected_posts:
  - hydejack/_posts/2020-07-03-introducing-hydejack-9.md
  - /blog/hydejack/2018-09-01-introducing-dark-mode/
  - hydejack/_posts/2018-06-30-introducing-hydejack-8.md
  - hydejack/_posts/2018-06-01-example-content-iii.md
posts_page: /posts/
no_third_column: true
---

# Hydejack

A boutique Jekyll theme for hackers, nerds, and academics.  
{:.lead}

1. this list will be replaced by the toc
{:toc .large-only}

![Screenshot](assets/img/blog/hydejack-9.jpg){:.lead width="1920" height="1080" loading="lazy"}

Hydejack's cover page on a variety of screen sizes.
{:.figcaption}


**Hydejack** is a boutique Jekyll theme for hackers, nerds, and academics, with a focus on personal sites that are meant to impress. 

It includes a blog that is suitable for both prose and technical documentation, a portfolio to showcase your projects, and a resume template that looks amazing on the web and in print.

> Your complete presence on the web — A [blog], [portfolio], and [resume].
{:.lead}


## A Personal Site That Won't Disappear

**Hydejack** is 100% built on Open Source software, and is Open Source itself, save for parts of the PRO version. The PRO version is a one-time payment that gives you the right to use it forever.

Hydejack is all static sites. _HTML_. All you need is a web server --- any web server --- to have a professional web presence that lasts a lifetime.

## Download

{% include table.md %}


## A Free Blogging Theme
**Hydejack** started out as a free blogging theme for Jekyll — and continues to be so.

<!--posts-->


## An Impressive Portfolio
A portfolio that's guaranteed to be impressive — no matter what you put into it.

<!--projects-->


## A Printable Resume
Get a resume that's consistent across the board — whether it's on the web, mobile, print, or [PDF](assets/Resume.pdf).

[![Resume PDF](assets/img/blog/resume.png){:.lead width="884" height="632" loading="lazy"}][resume]{:.no-hover}

Front and center page of a print resume generated by Hydejack.
{:.figcaption}


## Just Markdown
Write all content with Markdown. __Hydejack__ gives you [additional CSS classes](docs/writing.md) to stylize your content, without losing compatibility with other Jekyll themes.


## Just Markup
**Hydejack** boasts a plethora of modern JavaScript, but make no mistake: It's still a _plain old web page_ at its core. It works without JavaScript and you can even view it in a text-based browser like `w3m`:

![w3m Screenshot](assets/img/blog/w3m.png){:width="1920" height="1260" loading="lazy"}

The Hydejack blog, as seen by the text browser `w3m`.
{:.figcaption}


## Syntax Highlighting
**Hydejack** features syntax highlighting, powered by [Rouge].

```js
// file: `example.js`
document.querySelector("hy-push-state").addEventListener("hy-push-state-load", () => {
  const supportsCodeHighlights = true; //!!
});
```

Code blocks can have a filename and a caption.
{:.figcaption}


## Beautiful Math
They say math is beautiful — and with **Hydejack**'s [math support][math] it's guaranteed to also look beautiful:

$$
\begin{aligned}
  \phi(x,y) &= \phi \left(\sum_{i=1}^n x_ie_i, \sum_{j=1}^n y_je_j \right) \\[2em]
            &= \sum_{i=1}^n \sum_{j=1}^n x_i y_j \phi(e_i, e_j)            \\[2em]
            &= (x_1, \ldots, x_n)
               \left(\begin{array}{ccc}
                 \phi(e_1, e_1)  & \cdots & \phi(e_1, e_n) \\
                 \vdots          & \ddots & \vdots         \\
                 \phi(e_n, e_1)  & \cdots & \phi(e_n, e_n)
               \end{array}\right)
               \left(\begin{array}{c}
                 y_1    \\
                 \vdots \\
                 y_n
               \end{array}\right)
\end{aligned}
$$

Hydejack uses KaTeX to efficiently render math.
{:.figcaption}


## Build an Audience
The PRO version has built-in support for customizable [Tinyletter] newsletter subscription boxes.

If you are using a different service like MailChimp, you can build a custom newsletter subscription box using [Custom Forms][forms].

{% include pro/newsletter.html %}


## Features

{% include features.md %}


## Comparison

{% include table.md %}


## Get It Now

Use the the form below to purchase Hydejack PRO:

<div class="gumroad-product-embed" data-gumroad-product-id="nuOluY"><a href="https://gumroad.com/l/nuOluY">Loading…</a></div>


[blog]: /blog/
[portfolio]: showcase.md
[resume]: resume.md
[download]: download.md
[welcome]: README.md
[forms]: forms-by-example.md

[features]: #features
[news]: README.md#build-an-audience
[syntax]: README.md#syntax-highlighting
[latex]: #beautiful-math
[dark]: hydejack/_posts/2018-09-01-introducing-dark-mode.md
[search]: #_search-input
[grid]: _featured_categories/hydejack.md

[lic]: LICENSE.md
[pro]: licenses/PRO.md
[docs]: docs/README.md
[ofln]: docs/advanced.md#enabling-offline-support
[math]: docs/writing.md#adding-math

[kit]: https://github.com/hydecorp/hydejack-starter-kit/archive/v9.0.4.zip
[src]: https://github.com/hydecorp/hydejack
[gem]: https://rubygems.org/gems/jekyll-theme-hydejack
[buy]: https://gum.co/nuOluY

[gpss]: https://developers.google.com/speed/pagespeed/insights/?url=https%3A%2F%2Fhydejack.com%2Fdocs%2F
[rouge]: http://rouge.jneen.net
[katex]: https://khan.github.io/KaTeX/
[mathjax]: https://www.mathjax.org/
[tinyletter]: https://tinyletter.com/
