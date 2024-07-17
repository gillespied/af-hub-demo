---
# Feel free to add content and custom Front Matter to this file.
# To modify the layout, see https://jekyllrb.com/docs/themes/#overriding-theme-defaults
layout: default
title: Welcome to the CDDO Analysis Hub.
---

Here you'll find all of the data that blah blah blah...

# Analysis categories

<div class="catergoriescontainer">
<div class="categories">
    {% for category in site.categories %}
    <div class="category">
        <a href="{{site.baseurl}}{{ category.permalink }}"><i class="fas fa-arrow-right"></i> {{ category.title }}</a>
        <p>{{ category.short }}</p>
    </div>
    {% endfor %}
</div>
</div>


---

# Other Resources

Here they will go.