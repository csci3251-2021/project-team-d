# Introduction
Hi we are team D and in this project we will have some C code and do some github action for that. Later we will promote the repo to the Internet.

# Code

# Contributors

{% for stu in site.stu %}
<p>![]({{ stu.image }})<a href="https://github.com/{{ stu.user }}">@{{ stu.user }}</a>({{ stu.name }})<p>
    <p>{{ stu.content | markdownify }}</p>
{% endfor %}
