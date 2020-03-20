---
title:             "title"
subtitle:          "subtitle"
permalink:         "/home.html"
carousel:          default
breadcrumb:        #true false
alert:             #default #data file
heading:           true #true false
jumbotron:         #default
tiles:             default
images:            default
collection:        code
---

{% if page.tiles %} {% include default/tiles.html %} {% endif %}
{% if page.images %} {% include default/images.html %} {% endif %}
{% include default/spacer.html %}
{% include default/portfolio.html collection = code type = "list" width = 33 show-button = false show-subtitle = true limit = 4 %}
{% include default/spacer.html %}
{% include default/portfolio.html collection = code type = "list" width = 33 show-button = false show-subtitle = true limit = 4 %}
{% include default/spacer.html %}