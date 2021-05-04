# Introduction
Hi we are team D and in this project we will have some C code and do some github action for that. Later we will promote the repo to the Internet.

# Code

# Contributors

{% for _stu in site._stu %}
<p>![]({{ _stu.image }})<a href="https://github.com/{{ _stu.user }}">@{{ _stu.user }}</a>({{ _stu.name }})<p>
    <p>{{ _stu.content | markdownify }}</p>
{% endfor %}
