---
layout: page
title: Shopping
permalink: /elements/
image: '/images/shopping.jpg'
---

## Before You Shop – Let’s Chat First!

Check out my "Artwork" section! Spotted a piece you love? 
<br>Shoot me an email at [hello@liljen.design](mailto:hello@liljen.design) with the one that caught your eye and where you'd like it shipped!

Every ceramic piece is handmade with love: whether it’s slab-built, wheel-thrown, or pinched, no two are exactly alike. Glazes have a mind of their own, creating beautiful surprises like crackles, pools, and tiny crystals. 
That’s the magic of handmade! These unique variations make each piece special and are not considered flaws or reasons for exchange. 
However, most important to me is that you are happy with your purchase, so let’s talk if you're not!
<br><br>I hope you’ll adore your new art piece as much as I loved making it! 

 ***

<!-- begin blog -->
<section class="blog section">

  <div class="container">
    <div class="row">
      <div class="col col-12">
        <div class="section__info">
          <div class="section__head">
            <h2 class="section__title">You </h2>
            <a class="section__link" href="{{ '/blog' | relative_url }}">Artwork</a>
          </div>
        </div>
      </div>
    </div>
  </div>

  <div class="container">
    <div class="row">
      {% if site.posts.size > 0 %}
        {% for post in site.posts offset:0 limit:3 %}
          {% include article.html %}
        {% endfor %}
      {% endif %}
    </div>
  </div>
Not done shopping yet? <br>Dive into my artwork and discover more pieces you’ll love!
</section>
<!-- end blog -->

{% comment %} ## Have questions? I’m here to help!

 
  <em>Gallery / <a href="https://unsplash.com/" target="_blank">Unsplash</a></em>
</div>

![Minimalism]({{site.baseurl}}/images/04.jpg)
*Photo by [Kimon Maritz](https://unsplash.com/photos/mQiZnKwGXW0) on [Unsplash](https://unsplash.com/)*



# H1 Default styles for headings
## H2 Default styles for headings
### H3 Default styles for headings
#### H4 Default styles for headings
###### H6 Default styles for headings

***
***

## Lists

### Ordered list example:

1. Poutine drinking vinegar bitters.
2. Coloring book distillery fanny pack.
3. Venmo biodiesel gentrify enamel pin meditation.
4. Jean shorts shaman listicle pickled portland.
5. Salvia mumblecore brunch iPhone migas.

***

### Unordered list example:

* Bitters semiotics vice thundercats synth.
* Literally cred narwhal bitters wayfarers.
* Kale chips chartreuse paleo tbh street art marfa.
* Mlkshk polaroid sriracha brooklyn.
* Pug you probably haven't heard of them air plant man bun.

***

## Table

<div class="table-container">
  <table>
    <tr><th>Header 1</th><th>Header 2</th><th>Header 3</th><th>Header 4</th><th>Header 5</th></tr>
    <tr><td>Row:1 Cell:1</td><td>Row:1 Cell:2</td><td>Row:1 Cell:3</td><td>Row:1 Cell:4</td><td>Row:1 Cell:5</td></tr>
    <tr><td>Row:2 Cell:1</td><td>Row:2 Cell:2</td><td>Row:2 Cell:3</td><td>Row:2 Cell:4</td><td>Row:2 Cell:5</td></tr>
    <tr><td>Row:3 Cell:1</td><td>Row:3 Cell:2</td><td>Row:3 Cell:3</td><td>Row:3 Cell:4</td><td>Row:3 Cell:5</td></tr>
    <tr><td>Row:4 Cell:1</td><td>Row:4 Cell:2</td><td>Row:4 Cell:3</td><td>Row:4 Cell:4</td><td>Row:4 Cell:5</td></tr>
    <tr><td>Row:5 Cell:1</td><td>Row:5 Cell:2</td><td>Row:5 Cell:3</td><td>Row:5 Cell:4</td><td>Row:5 Cell:5</td></tr>
    <tr><td>Row:6 Cell:1</td><td>Row:6 Cell:2</td><td>Row:6 Cell:3</td><td>Row:6 Cell:4</td><td>Row:6 Cell:5</td></tr>
  </table>
</div>

***

## Quotes

#### A quote looks like this:

> The longer I live, the more I realize that I am never wrong about anything, and that all the pains I have so humbly taken to verify my notions have only wasted my time!
>
> <cite>George Bernard Shaw</cite>

***



## Syntax Highlighter

{% highlight css %}
body {
  margin: 0;
  display: flex;
  justify-content: center;
  align-items: center;
  height: 100vh;
  width: 100vw;
  background-color: #1c2021;
}

li {
  width: 200px;
  min-height: 250px;
  border: 1px solid #000;
  display: inline-block;
  vertical-align: top;
  margin: 5px;
}
{% endhighlight %}

{% highlight js %}
  $('.top').click(function () {
    $('html, body').stop().animate({ scrollTop: 0 }, 'slow', 'swing');
  });
  $(window).scroll(function () {
    if ($(this).scrollTop() > $(window).height()) {
      $('.top').addClass("top-active");
    } else {
      $('.top').removeClass("top-active");
    };
  });
{% endhighlight %}


***

## Youtube Embed

<p><iframe src="https://www.youtube.com/embed/hRXd0MMsixI" frameborder="0" allowfullscreen></iframe></p>

***

## Vimeo Embed

<p><iframe src="https://player.vimeo.com/video/147264547?title=0&byline=0" width="640" height="360" frameborder="0" allowfullscreen></iframe></p>
{% endcomment %}
***