---
title: JonLuca's Blog
is_home: true
header-img: "/images/mini-profile.png"
---
<ul class="list pa0" id="blog-posts">
    {% for post in site.posts %}
    <li class="mt2">
        <a class="db link-text pv1 link blue hover-mid-gray" href="{{ site.url }}{{ post.url }}">
            <time class="time fr silver ttu">{{ post.date | date_to_string }}</time>
            {{ post.title }}
        </a>
    </li>
    {% endfor %}
</ul>