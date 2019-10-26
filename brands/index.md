---
# layout: page
# title: Brands
# class: page-template
layout: default
current: home
class: 'home-template'
logo: 'assets/images/blog-cover.jpg'
subclass: 'post page'
navigation: True
header: light
order: 3
hyphens: true
---

<!-- < default -->
<!-- <header class="site-header outer {% if page.cover or site.cover %}" style="background-image:  url({{ site.baseurl }}{% if page.cover %}{{ page.cover }}{% elsif site.cover %}{{ site.cover }}{% endif %}) {% else %}no-cover{% endif %}"> -->

<header>
    <div class="outer">
        {% include site-nav.html %}
    </div>
    <div class="inner">
        <div>
            <div class="site-home__content">
                <h1>Brands</h1>
                <h5 class="site-description-home">A Paper trail on a highly experimental entrepreneurial journey</h5>
                
                <div class="site-home__social">
                    <ul>
                        <li><a target="_blank" class="intro-social-link" href="https://github.com/{{ site.github }}">{% include github.html %}</a></li>
                        <li><a target="_blank" class="intro-social-link isl-size" href="https://facebook.com/{{ site.facebook }}">{% include facebook.html%}</a></li>
                        <li><a target="_blank" class="intro-social-link isl-size" href="https://twitter.com/{{ site.twitter }}">{% include twitter.html %}</a></li>
                        <li><a target="_blank" class="intro-social-link" href="https://linkedin.com/in/{{ site.linkedin }}">{% include linkedin.html %}</a></li>
                        <li><a target="_blank" class="intro-social-link" href="https://instagram.com/{{ site.instagram }}">{% include instagram.html %}</a></li>
                        <li><a target="_blank" class="intro-social-link" href="https://medium.com/@{{ site.medium }}">{% include medium.html %}</a></li>
                    </ul>
                </div>
            </div>
        </div>
    </div>
</header>